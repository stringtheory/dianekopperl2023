# Resume Readme

This file contains notes on the html structural notes resume markup. 

*Semantics:*

- Markup: HTML5 semantic tags
- Additional Semantics: http://schema.org 
https://schema.org/docs/gs.html

*CSS Class Naming:*

I used Brad Fronst's  Atomic Design principals, for CSS class naming.
Prefixes
- `l_name` Layout
- `a_name` Single Elements

## Contact Section Notes

### Container
I used the `<address>` element for my contact information. 

"The `address` element represents the contact information for its nearest article or `body` element ancestor. 
If that is the body element, then the contact information applies to the document as a whole." <sup>[1]</sup>

"The contact information provided by an <address> element's contents can take whatever form is 
appropriate for the context, and may include any type of contact information that is needed, 
such as a physical address, URL, email address, phone number, social media handle, geographic coordinates, 
and so forth." <sup>[2]</sup>

```
    <p>Professional Profiles and Code Examples:</p>
    <address>
      <a href="mailto:jim@rock.com">jim@rock.com</a>
      <a href="tel:+13115552368">(311) 555-2368</a>
    </address>
``` 
<sup>[2]</sup>

References:
1. [Specification](https://html.spec.whatwg.org/multipage/sections.html#the-address-element)
2. [Mozilla Developer Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address)
 

## Contact Link Code:

- *Visual:* I chose to use a visual icon (SVG) and short URL for visual purposes. 
- *Screen Readers':* I used an contextualy readable `aria-label` on the `<a>` element to override the text supplied within the link.

## TODO:

- [x] Create HTML, Readme, CSS
- [x] HTML Outline
- [ ] Content (HTML & Readme notes)
    - [ ] Section: Header
    - [ ] Main Section: Contact
    - [ ] Main Section: Skills
    - [ ] Main Section: Experience
    - [ ] Main Section: Foundational Experience
    - [ ] Main Section: Foundational Experience
    - [ ] Main Section: Foundational Experience
- [ ] Readme Outline
- [ ] CSS
    - [ ] Scaffold
    - [ ] Reset
    - [ ] Fonts
    - [ ] Layout
    - [ ] Atoms
    
    
Additional Questions: 

- Contact links in section & not header, check through schema.org validator
- Finalize current Best Practices for google font display
https://fonts.google.com/specimen/Hind
https://sia.codes/posts/making-google-fonts-faster/
https://font-display.glitch.me/
