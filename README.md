### Jquery-Playing-with-Classes

```
What's happening here is that for all the 3 input buttons we have given the same class 
name because the class name can be the same(just not the id)..
```
```
The class name for all 3 input buttons is 'btn_class'..so when any of the 3 buttons is clicked, divId stores
the data-id attr. of the button that has been clicked cos of the 'this' used..
```
```
And the value of data-id of buttons is same as the normal div id (same name used- one,two,three)..so 
then the div is toggled
```
