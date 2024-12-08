## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

#### Initial

---

| Page | Screenshot | Notes |
| --- | --- | --- |
| Home | ![screenshot](documentation/validation/html-index-validation-1.png) | use of 'li' element inside a 'div'. Fix: replace div with menu element|
| Home | ![screenshot](documentation/validation/html-index-validation-2.png) | Button element must not be a descendant of 'a' element |
| Home | ![screenshot](documentation/validation/html-index-validation-3.png) | Section lacks header h2-h6 warning |
| Portfolio | ![screenshot](documentation/validation/html-portfolio-validation-1.png) | use of 'li' element inside a 'div'. Fix: replace div with menu element|
| Contact Success | ![screenshot](documentation/validation/html-contact-success-validation-1.png) | Section lacks header h2-h6 warning |


- I carried the majority of error fixes that arose out of html validation for the home page across all pages. 

#### Final State 

| Page | Screenshot | Notes |
| --- | --- | --- |
| Home | ![screenshot](documentation/validation/html-index-validation-4.png) | Pass: No Errors |
| Portfolio | ![screenshot](documentation/validation/html-portfolio-validation-2.png) | Pass: No Errors |
| Contact | ![screenshot](documentation/validation/html-contact-validation-1.png) | Pass: No Errors |
| Contact Success | ![screenshot](documentation/validation/html-contact-success-validation-2.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/) to validate the CSS file for this project.

| Page | Screenshot | Notes |
| --- | --- | --- |
| style.css | ![screenshot](documentation/validation/css-validation.png) | Pass: No Errors |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsiveness/mobile.png) | Works correctly |
| Tablet (DevTools) | ![screenshot](documentation/responsiveness/tablet.png) | Works correctly  |
| Desktop (DevTools) | ![screenshot](documentation/responsiveness/desktop.png) | Works correctly  |
| Desktop large (DevTools) | ![screenshot](documentation/responsiveness/desktop-large.png) | Works correctly  |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/lighthouse/lighthouse-home-mobile.png) | Some warnings,  Slower response time due to large images |
| Home | Desktop | ![screenshot](documentation/lighthouse/lighthouse-home-desktop.png) | Some warnings,  Slower response time due to large images |
| Portfolio | Mobile | ![screenshot](documentation/lighthouse/lighthouse-portfolio-mobile.png) | Some warnings,  Slower response time due to large images |
| Portfolio | Desktop | ![screenshot](documentation/lighthouse/lighthouse-portfolio-desktop.png) | Some warnings,  Slower response time due to large images |
| Contact | Mobile | ![screenshot](documentation/lighthouse/lighthouse-contact-mobile.png) | Some warnings,  Slower response time due to large images |
| Contact | Desktop | ![screenshot](documentation/lighthouse/lighthouse-contact-desktop.png) | Some warnings,  Slower response time due to large images |
| Contact Success | Mobile | ![screenshot](documentation/lighthouse/lighthouse-contact-success-mobile.png) | Some warnings,  Slower response time due to large images |
| Contact Success | Desktop | ![screenshot](documentation/lighthouse/lighthouse-contact-success-desktop.png) | Some warnings,  Slower response time due to large images |

- Some of the lighthouse tests where slower due to the size of images in the carousel. I tested reducing the image size however, as you can see this has caused a degredation of quality.
