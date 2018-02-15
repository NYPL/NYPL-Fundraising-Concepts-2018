
# Functional & Dimensional Specifications for Development 2018
2/15/2018 15:25 -5:00

## Meerkats

### User Centered Design Principles
* Do no harm
* Do not annoy
* Give users control
    - Closeable
    _ Session based
* Tell stories & be compelling

### Dimensions
* Responsive Design Principles
    - Mobile First approach
    - Do not consume more than 15% of the user's viewport
        * Browser chrome must be taken into account, especially on the smallest of devices (ex: iPhone SE)
    - Progressive enhancement if Javascript is disabled, basic content should be rendered.
    - Viewports should be considered as small / medium / large rather than a fixed pixel width or height
    
### Accessibility
* Module(s) should be written in semantically correct HTML
* Progressively Enhanced
    - Should function if Javascript is disabled
* Should be keyboard operable
* Should close on ESC key press

### Buttons
* Should be unique to the module itself and not be repeat of other buttons found in the global header
    - This should reduce button "fatigue"
    - This will allow for more perceived targeting towards a specific campaign or cause within the library 

### Colors
* A11Y combinations should come from the [Design Tool Kit's Color Accessibility Table](https://nypl.github.io/design-toolkit/sections/color-a11y.html)

### Functions
* Should behave as expected
* Close buttons should close for that session
    - session cookie set to remember action
* Links are visually treated as buttons

### Images and Graphics
* Should be used sparingly and only as an enhancement
* Compressed, in-line SVGs for vector graphics

### Type faces
* System Type should be used
* Keivit only if absolutely compelled by a senior manager
* Type should never be an image
* Type will be set in `rem`s and be based on a default of 16px. 
    - If type _must be_ smaller 0.75rem or 12px is smallest acceptable size 

### Animation
* Should be used sparingly
* Depending on context should only run once
* Only when modules load to the screen or are closed by the user
