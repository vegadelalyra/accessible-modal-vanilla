# Accessible Modal in JS Vanilla

An Accessible Modal Dialog with HTML, CSS, and JavaScript from https://levelup.gitconnected.com/an-accessible-modal-dialog-with-html-css-and-javascript-d885004d0b3a

## Credits to

(Giacomo Mariani)[https://levelup.gitconnected.com/an-accessible-modal-dialog-with-html-css-and-javascript-d885004d0b3a]

## ACCESIBILITY TEST FROM W3C WCAG

Implemented with HTML, CSS and JavaScript, that satisfies the tests set by the W3C WCAG working group:

# 1

Check that role=dialog is an attribute of the container (such as a div) that is used as the custom dialog.

# 2

Check that the container is inserted (or made visible) via JavaScript following a user interaction or some other event.

# 3

When the dialog is activated, check that focus is set to an element in the container.

# 4

When the dialog is active, check that focus is never set to an element that is not in the container.

# 5

When the dialog is deactivated, check that focus is set to the control that originally activated the dialog.

On top of these five points, the modal dialog also satisfy the following:

# 6

The modal dialog closes when the user clicks Escape.

# 7

The modal dialog closes when the user clicks outside its visible part.
