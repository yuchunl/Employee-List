# Employee-List


This is a functional component that explores a list of emplyees.

It is build based on Angular JS framework. 

This demo can be visited at [Demo](http://yuchunl.github.io/employeelist/).

### Functionalities: 

1. Each item has an employee name and bio content.
2. By default, the bio conent of each item is hidden.
3. By clicking on the employee name, it expands/collapses the item's bio content. 
4. Only on item can be expanded at a time (expanding one will collapse the others).
5. Additionally by clidking on the bio content, an action occurs -- popping up an alert dialog with certain message. 


### Test unit:
- Click the first item "Employee A", it should expand the bio content of A. 
- Click the second item "Employee B", it should expand the bio content of B, while collapse that of A. 
- Click the second item "Employee B" again, it should collapse the bio content of B.
- Click the third item "Employee C", it should expand the bio content of C.
- Click the bio of C, it should pop up an alert dialog with item data of C; click anywhere outside the dialog to close the alert message.
