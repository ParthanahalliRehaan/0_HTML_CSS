HTML Index: Basic -> Intermediate

BASIC SECTION

1. HTML Fundamentals
   What is HTML? (HyperText Markup Language)
   How Browsers Render HTML
   HTML Document Structure
      <!DOCTYPE html>
      <html> (lang attribute)
      <head>
         <meta charset="UTF-8">
         <meta name="viewport">
         <title>
         <link rel="stylesheet">
      <body>
   HTML Comments <!-- -->
   HTML is NOT Case-Sensitive (but lowercase is standard)

2. Core Elements & Tags
   Headings: <h1> to <h6>
   Paragraphs: <p>
   Line Break: <br>
   Horizontal Rule: <hr>
   Text Formatting
      <strong> / <b>
      <em> / <i>
      <mark>
      <small>
      <del> / <ins>
      <sub> / <sup>
      <pre> / <code>
   Links: <a> (href, target, rel, absolute vs relative)
   Images: <img> (src, alt, width, height, loading="lazy")
   Block vs Inline Elements

3. Lists
   Unordered Lists: <ul> + <li>
      list-style-type (disc, circle, square, none)
   Ordered Lists: <ol> + <li>
      type, start, reversed attributes
   Description/Definition Lists: <dl>, <dt>, <dd>

4. Tables
   <table> structure
      <thead>, <tbody>, <tfoot>
      <tr> (table row)
      <th> (table header)
      <td> (table data)
   Table Attributes
      colspan & rowspan
      border, cellpadding, cellspacing (legacy vs CSS)
   Accessible Tables (scope, captions)

5. Forms (The Essentials)
   <form> (action, method: GET vs POST)
   Input Types
      text, password, email, number
      checkbox, radio
      submit, reset, button
      file, hidden
   Other Form Elements
      <textarea>
      <select> + <option> + <optgroup>
      <label> (proper for attribute)
   Form Attributes
      name, value, placeholder, required
      readonly, disabled
      maxlength, min, max, step, pattern
   Basic Form Validation (HTML5)

6. Semantic HTML (Basic)
   <div> vs <span>
   <header>
   <footer>
   <nav>
   <main>
   <section> vs <article> (intro)

7. Media Basics
   <audio> (controls, src, autoplay, loop, muted)
   <video> (controls, width, height, poster, preload)
   <source> for multiple formats


INTERMEDIATE SECTION

8. Advanced Semantic HTML
   <article> (independent content)
   <aside> (tangential content)
   <figure> + <figcaption>
   <time> (datetime attribute)
   <address>
   <details> + <summary> (native accordion)
   <dialog> (native modal)
   <mark> (semantic highlighting)
   <template> (inert DOM fragments)
   <slot> (Web Components intro)
   <data> (machine-readable data)
   <wbr> (word break opportunity)
   <bdi> + <bdo> (bidirectional text)
   Semantic HTML for Accessibility (screen readers)

9. Forms Deep Dive
   New HTML5 Input Types
      date, time, datetime-local, month, week
      color, range, search, tel, url
      pattern attribute with regex
   Form Validation API
      required, minlength, maxlength
      min, max, step
      novalidate attribute
      Custom validation messages
   Datalist: <datalist> (autocomplete suggestions)
   Output: <output> (calculation results)
   Progress & Meter
      <progress> (task completion)
      <meter> (gauge/value in range)
   Form Attributes
      formaction, formmethod, formtarget
      formnovalidate, formenctype
      autocomplete (on/off + values)
   Multiple file uploads + accept attribute

10. Embedded Content
    <iframe> (sandbox, allow, loading, srcdoc)
    <embed> & <object> (legacy plugins)
    <canvas> (2D drawing intro - JS ties here)
    <svg> inline vs external
    MathML <math> (basic equations)
    <map> + <area> (image maps)
    <picture> (responsive images)
       <source> (media, srcset, sizes)
       art direction use cases

11. Document Metadata & SEO
    <meta> tags deep dive
       charset, viewport
       description, keywords (legacy)
       author, generator
       theme-color
       Open Graph (og:title, og:image, etc.)
    <link> relations
       canonical
       icon / shortcut icon
       manifest (PWA)
       preload, prefetch, preconnect
       stylesheet, alternate stylesheet
    <base> tag
    Favicon standards (ICO, PNG, SVG, mask-icon)
    Twitter Cards
    Structured Data / JSON-LD (intro)
    Robots meta tag

12. Accessibility (A11y) in HTML
    ARIA when HTML is not enough
       role attributes (complementary, navigation, etc.)
       aria-label, aria-labelledby, aria-describedby
       aria-hidden, aria-live
       aria-expanded, aria-pressed
       aria-current
    Skip Links
    Focus Management
    Landmarks (complementary to semantic tags)
    Language attributes (lang, xml:lang, hreflang)
    Accessibility Tree basics

13. HTML APIs (Browser-native, no JS lib needed)
    Content Editable
       contenteditable attribute
    Drag and Drop API (HTML attributes)
       draggable
       dropzone
    Spellcheck
       spellcheck attribute
    Translate
       translate attribute
    Custom Data Attributes
       data-* attributes
    <menu> + <menuitem> (deprecated but know history)

14. Performance & Best Practices
    Lazy Loading
       loading="lazy" for images
       loading="eager"
    Resource Hints
       <link rel="preload">
       <link rel="prefetch">
       <link rel="preconnect">
       <link rel="dns-prefetch">
    Defer & Async (script loading)
    Minification concepts
    Critical CSS inline
    Base64 inline images (data URIs)
    HTML Compression (gzip/brotli)

15. Modern HTML Patterns
    Web Components Architecture
       Custom Elements
       Shadow DOM
       HTML Templates
       Slots
    Progressive Web App (PWA) HTML
       Service Worker registration
       Web App Manifest link
       Theme color meta
    Dark Mode Support
       color-scheme meta tag
    View Transitions API (meta tags)


RESOURCES & REFERENCES

MDN HTML Reference: https://developer.mozilla.org/en-US/docs/Web/HTML
HTML Living Standard: https://html.spec.whatwg.org/
W3C HTML Validator: https://validator.w3.org/
A11y Project Checklist: https://www.a11yproject.com/checklist/