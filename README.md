# ResizablePanelsReact

A simple react component to create resizable panels :D

Props:

- **bkcolor**: set a background color
- **displayDirection**: its like flex direction, you can choose "row" for horizontal resizing or "column" for vertical resizing
- **width**: set a width for you component
- **height**: set a height for you component
- **panelsSize**: a array to set your panels sizes, if you have 2 panels
- **sizeUnitMeasure**: unit used to calculate the amount to resize (px or %)
- **resizerColor**: change resizer color
- **resizerSize**: change resizer size
- **minPanelSize**: (number) min width a panel can have in %
- **onResizeStart**: callback function that will be called when the user starts resizing (mousedown)
- **onResize**: callback function that will be called during resize (mousemove). Array of panel sizes is sent as parameter
- **onResizeEnd**: callback function that will be called when the user stops resizing (mouseup). Array of panel sizes is sent as parameter

Code sample on CodeSandBox: https://codesandbox.io/embed/8l8lpp5nk9?fontsize=14
