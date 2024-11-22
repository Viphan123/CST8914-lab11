# CST8914-lab11
## Questions:
### 1. What is the keyboard interaction missing?
The previous JS code does not provide much keyboard navigation. Specifically:
* Arrow Navigation: Users should be able to use the ArrowUp and ArrowDown keys to navigate between accordion buttons.
* Open/Close: When the user presses Enter or Space on a focused accordion button, it should toggle the open/close state.
* Focus Indicators: Users should be able to clearly see which accordion button is focused when navigating via the keyboard.
### 2. What is the ARIA missing?
*aria-expanded: This attribute should be used to indicate whether an accordion section is expanded or collapsed. It should toggle between true and false to represent the open/close state.
* aria-controls: This property should link the button (accordion header) to the content it controls (accordion body), establishing an association for screen readers.
* role="button": This should be explicitly set on the accordion button to ensure it's recognized as a button for screen readers.
* aria-labelledby (optional): If necessary, to ensure a more descriptive label for the content sections, particularly when content and controls are separated.
## Code
Please visit: https://viphan123.github.io/CST8914-lab11/accordion.html
