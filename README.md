## Testdome React Interview Questions

### 1. Focus
The TextInput component renders an input element in the DOM and accepts a ref that is forwarded to that input element. Finish the FocusableInput component:

+ The component should accept a focused prop.
+ When the focused prop is changed from false to true, and the input is not focused, it should receive the focus.
+ If on mounting the focused prop is true, the input should receive the focus.

### 2. Todo List
Write a TodoList component that expects an items prop, and a list of objects, each with text and done properties.

TodoList also accepts an onItemClick function prop, which should be called when a user clicks an item in the list, if the item is not marked as done. Otherwise, the onItemClick should not be called and the click event itself should not be propagated further. The function should be called the item object from the items list as the first parameter and the event as the second parameter.

### 3. Grocery App
You have a GroceryApp class, which receives a list of products, each one with name and votes. The app should render an unordered list, with a list item for each product. Products can be upvoted or downvoted.

By appropriately using React state and props, implement the upvote/downvote logic. Keep the state in the topmost component, while the Product component should accept props.