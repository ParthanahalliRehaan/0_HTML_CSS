CSS Index: Basic -> Intermediate

BASIC SECTION

1. CSS Fundamentals
   What is CSS? (Cascading Style Sheets)
   How CSS Works (browser rendering pipeline)
   Three Ways to Add CSS
      Inline: style attribute
      Internal: <style> tag
      External: .css file + <link>
   CSS Syntax: Selector + Declaration Block
   CSS Comments /* */
   Cascade, Specificity, and Inheritance

2. Selectors
   Element Selector: div
   Class Selector: .class
   ID Selector: #id
   Universal Selector: *
   Grouping Selectors: h1, h2, p
   Descendant Selector: div p
   Child Selector: div > p
   Adjacent Sibling: h1 + p
   General Sibling: h1 ~ p
   Attribute Selectors
      [attr], [attr=value], [attr^=value], [attr$=value], [attr*=value]

3. Colors & Backgrounds
   Color Values
      Named colors: red, blue
      Hex: #ff0000, #f00
      RGB / RGBA: rgb(255, 0, 0), rgba(255, 0, 0, 0.5)
      HSL / HSLA: hsl(0, 100%, 50%)
   background-color
   background-image
   background-repeat
   background-position
   background-size (cover, contain)
   background-attachment (fixed, scroll)
   background shorthand

4. Text & Fonts
   color
   font-family (fallback stacks, web-safe fonts)
   font-size (px, em, rem, %)
   font-weight (normal, bold, 100-900)
   font-style (normal, italic, oblique)
   font-variant
   line-height
   text-align (left, right, center, justify)
   text-decoration (none, underline, line-through)
   text-transform (uppercase, lowercase, capitalize)
   letter-spacing & word-spacing
   text-indent
   white-space (normal, nowrap, pre)
   text-shadow

5. Box Model
   Content Box
   padding (top, right, bottom, left shorthand)
   border
      border-width, border-style, border-color
      border-radius
   margin (collapse behavior)
   box-sizing: content-box vs border-box
   outline (vs border)
   box-shadow

6. Display & Visibility
   display
      block
      inline
      inline-block
      none
   visibility: hidden vs display: none
   opacity

7. Sizing & Units
   Absolute Units: px, pt, cm, in
   Relative Units
      em (parent relative)
      rem (root relative)
      % (container relative)
      vw / vh (viewport relative)
      vmin / vmax
   width, height, min-width, max-width, min-height, max-height
   overflow (visible, hidden, scroll, auto)

8. Positioning
   static (default)
   relative
   absolute
   fixed
   sticky
   z-index (stacking context)
   top, right, bottom, left

9. Float & Clear
   float (left, right, none)
   clear (left, right, both)
   Clearfix hack (legacy)
   overflow: auto clearfix

10. Basic Layouts
    Centering Techniques
       Horizontal: margin: 0 auto
       Text: text-align: center
    Simple Two-Column Layout (float-based)
    Horizontal Navigation Bar
    Basic Card Component


INTERMEDIATE SECTION

11. Flexbox
    display: flex
    Flex Container Properties
       flex-direction (row, column, row-reverse, column-reverse)
       flex-wrap (nowrap, wrap, wrap-reverse)
       flex-flow (shorthand)
       justify-content (flex-start, center, space-between, space-around, space-evenly)
       align-items (stretch, flex-start, center, flex-end, baseline)
       align-content (multi-line alignment)
       gap, row-gap, column-gap
    Flex Item Properties
       order
       flex-grow
       flex-shrink
       flex-basis
       flex (shorthand)
       align-self

12. CSS Grid
    display: grid
    Grid Container Properties
       grid-template-columns
       grid-template-rows
       grid-template-areas
       grid-template (shorthand)
       gap, row-gap, column-gap
       justify-items, align-items
       justify-content, align-content
       place-items, place-content
    Grid Item Properties
       grid-column-start / grid-column-end
       grid-row-start / grid-row-end
       grid-column, grid-row (shorthand)
       grid-area
       justify-self, align-self, place-self
    repeat(), minmax(), fr unit
    auto-fit vs auto-fill
    Named Grid Lines
    Subgrid (intro)

13. Responsive Design
    Viewport Meta Tag
    Media Queries
       @media screen and (min-width: ...)
       @media screen and (max-width: ...)
       @media screen and (min-width: ...) and (max-width: ...)
       @media (orientation: portrait/landscape)
       @media (prefers-color-scheme: dark)
    Mobile-First vs Desktop-First Approach
    Breakpoints Strategy
    Responsive Images
       max-width: 100%
       object-fit (cover, contain, fill, none, scale-down)
       object-position
    Responsive Typography
       clamp() function

14. CSS Transitions
    transition-property
    transition-duration
    transition-timing-function
       ease, linear, ease-in, ease-out, ease-in-out
       cubic-bezier()
    transition-delay
    transition shorthand
    Transformable Properties (what can transition)

15. CSS Transforms
    transform property
    2D Transforms
       translate(x, y), translateX(), translateY()
       scale(x, y), scaleX(), scaleY()
       rotate(angle)
       skew(x-angle, y-angle)
    transform-origin
    transform-box
    3D Transforms (intro)
       perspective
       rotateX(), rotateY(), rotateZ()
       translateZ(), scaleZ()

16. CSS Animations
    @keyframes rule
    Animation Properties
       animation-name
       animation-duration
       animation-timing-function
       animation-delay
       animation-iteration-count
       animation-direction (normal, reverse, alternate)
       animation-fill-mode (forwards, backwards, both)
       animation-play-state (running, paused)
    animation shorthand
    Multiple Animations

17. Pseudo-Classes & Pseudo-Elements
    Pseudo-Classes
       :hover, :active, :focus
       :first-child, :last-child, :nth-child(), :nth-of-type()
       :not()
       :is(), :where()
       :has() (parent selector)
       :target, :checked, :disabled, :required, :valid, :invalid
    Pseudo-Elements
       ::before, ::after (content generation)
       ::first-line, ::first-letter
       ::selection
       ::placeholder
       ::marker

18. CSS Variables (Custom Properties)
    --variable-name declaration
    var() function
    Scope: Global (:root) vs Local
    Fallback Values: var(--color, blue)
    Dynamic Theming with Variables
    calc() with Variables

19. Advanced Typography
    @font-face (custom fonts)
    Google Fonts / Adobe Fonts integration
    font-display (swap, block, fallback, optional)
    Variable Fonts (intro)
    font-feature-settings
    text-overflow: ellipsis
    hyphens (auto hyphenation)
    writing-mode (vertical text)
    direction (RTL support)

20. Advanced Selectors & Combinators
    :is() and :where() (specificity control)
    :has() (relational pseudo-class)
    Complex attribute selectors
    Selector specificity calculation
    !important (when to use / avoid)

21. CSS Architecture & Methodologies
    BEM (Block, Element, Modifier)
    SMACSS (Scalable Modular Architecture)
    OOCSS (Object-Oriented CSS)
    Utility-First CSS (Tailwind philosophy)
    CSS-in-JS (intro concept)
    Component-Based CSS

22. Modern CSS Features
    clamp(), min(), max() functions
    aspect-ratio
    container queries (@container)
    contain property
    isolation: isolate
    backdrop-filter (glassmorphism)
    clip-path
    mask-image
    shape-outside (text wrapping)
    CSS Nesting (native)
    @layer (cascade layers)
    @property (registered custom properties)

23. CSS for Print & Accessibility
    @media print
    page-break-before, page-break-after
    print-color-adjust
    prefers-reduced-motion
    prefers-contrast
    prefers-reduced-transparency
    Focus Visible: :focus-visible
    outline for focus indicators

24. CSS Performance
    Critical CSS (above-the-fold)
    CSS Containment (contain)
    will-change (GPU acceleration hint)
    Avoid @import (use <link>)
    Minification
    Unused CSS removal
    Render blocking and <link rel="preload">


RESOURCES & REFERENCES

MDN CSS Reference: https://developer.mozilla.org/en-US/docs/Web/CSS
CSS-Tricks: https://css-tricks.com/
Can I Use: https://caniuse.com/
CSS Specs - W3C: https://www.w3.org/Style/CSS/specs.en.html
Flexbox Froggy: https://flexboxfroggy.com/
Grid Garden: https://cssgridgarden.com/