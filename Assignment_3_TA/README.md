# Dialog Box

Dialogue is similar to a div with a purpose. Its purpose is to pop up into the user's screen as various of different things like: dismissible alerts, inspectors or subwindows.

## Simple Example

Simple example of using the dialog method. This is also the way to set it up for commands. 

```html
   <dialog open>

        <p>Hello World</p>
        <form action="dialog">
            <button>OK</button>
        </form>
    </dialog>    
```
#

## Open and close the Dialog box
```javascript
'use strict';

const dialog = document.querySelector("dialog");

//Use this only if the dialog doesnt have the open in it's element tag.
window.onload = function(){
    dialog.show();
}

//To close it after it being open.
window.onload = function(){
    dialog.close();
}

```
You can further customize your dialog box by adding loops and event listeners.

#

## Conclusion
These code snippets will alows you to customize your website further

#
### References
- [The Dialog element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog)

- [Introducing the dialog element](https://webkit.org/blog/12209/introducing-the-dialog-element/)
