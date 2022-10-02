
<b>Q1: Explain what the simple List component does.</b>

* It is used for displaying "items" which passed as props into List component.
* List functional component returns other component i.e. SingleListItem and pass some data as props into it.
* This internal "SingleListItem" component used for adding functionality to "items" i.e. change colour green and red on the basis of "isSelected" variable which is set        using useState hook and passed as prop into this internal component.

</br>

<b>Q2: What problems / warnings are there with code?</b>

Problem 1:  _propTypes.default.shapeOf is not a function.

Problem 2:  setSelectedIndex is not a function.

Problem 3:  Wrong dependency in useEffect hook

Problem 3:  items set to null i.e doesn't show anything on to the screen.

Problem 4:  automatically invokes the onClickHandler function without clicking on it.

Problem 5:  Each child in a list should have a unique "key" prop.

Problem 6:  Invalid prop 'isSelected' of type 'boolean' supplied to `WrappedSingleListItem`, expected 'number'.

</br>
<b>Q3: Please fix, optimize, and/or modify the component as much as you think is necessary.</b>

* removing dependecy "items" from useEffect hook.

* Inside useState hook setting the function i.e. setSelectedIndex correctly.

* Adding items i.e. "item1", "item2" that are passed further as props into the list component.

* putting "onClickHandler" function inside arrow function which invokes this function only by clicking on the items.

* Adding unique key prop to singleListItem component.

* Setting "isSelected" prop-type to number instead of boolean.



