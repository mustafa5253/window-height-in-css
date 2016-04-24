# Set an Element’s Height Equal to the Window’s Height
apply window height in body to make body 100% height

Within the function JavaScript queries the DOM for body and sets the CSS min-height property to the innerHeight() of the browser window. In most cases it’s probably best to specify min-height, so the elements height can increase when needed, that way nothing gets cut-off if the content extends past the viewport.
Just replace body with the class or id of the element you wish to target.
