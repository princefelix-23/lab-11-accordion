# Lab 11: Accessible Custom Components & widgets

## What is the keyboard interaction missing?

- The keyboard interaction is missing a visible focus style when navigating with the Tab key. It’s difficult for keyboard users to see where they are on the page and to move to the next element.

## What is the ARIA missing?

The ARIA attributes missing are:

- `aria-expanded`: True if Expanded or False if collapsed.
- `aria-controls`: Points to the ID of the panel which the header controls.
- `aria-labelledby`: Defines the accessible name for the region element.
- `region`: To create a landmark region that contains the currently expanded accordion panel.
