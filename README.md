# Hidden Div Bug in HTML
This repository demonstrates a common, yet easily overlooked, bug in HTML where a div element is hidden using JavaScript's `display: none`, but no mechanism is provided to make it visible again.  This leads to a permanently hidden element.

## Bug Description:
The `bug.html` file shows a simple HTML page with a div and a button.  Clicking the button hides the div.  There's no way to un-hide it after that.  This is a subtle bug because it might not be immediately apparent, especially in more complex applications.

## Solution:
The `solution.html` file presents a corrected version. It includes a way to show or hide the div element, making it user interactive.