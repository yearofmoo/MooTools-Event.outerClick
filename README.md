# MooTools - Event.outerClick

This piece of code is by no means my own, however, I grew tired of having to download, copy and paste this library between my projects. Thus I'm hosting it on my Github account :)

Event.outerClick listens on *click events that are fired outside of the given element which belong to the same parent as the element*. In other words when you click outside the element and the element that you clicked on isn't that element or a child of that element then the event is fired. Think of it as unfocusing off an element simply by clicking elsewhere. 

## Usage

All that is required is to add the event to the given element:

```javascript
$('element').addEvent('outerClick',function() {
  //The user has clicked (outside) of the given element
});
```
