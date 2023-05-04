# Template inclusions
This FHIR template adds the following specific styling elements:

## 1. ./includes
### a) `/_append.fragment-header.html`
To the header, add:
* Australian Digital Health Agency logo (`content/assets/images/adha-logo-dark.svg`)
* the image has the alt text of "Visit the Australian Digital Health Website"
* the image has an associated hyperlink to the Agency home page

### b) `/_append.fragment-footer.html`
After the existing core template footer, add the following:
* an empty line
* a line with "Publisher: [Australian Digital Health Agency](https://www.digitalhealth.gov.au) ABN 84 425 496 912, Level 25, 175 Liverpool Street, Sydney, NSW 2000"
* a line with "Telephone 1300 901 001 or email [help@digitalhealth.gov.au](mailto:help@digitalhealth.gov.au)"
* a line with the ADHA website: "https://www.digitalhealth.gov.au"
* a line with "[Privacy policy](https://www.digitalhealth.gov.au/about-us/policies-privacy-and-reporting/privacy-policy) | [Terms of Use](https://www.digitalhealth.gov.au/about-us/policies-privacy-and-reporting/terms-of-use)"

### c) `/_append.fragment-css.html`
The Agency CSS is introduced (`content/assets/css/ADHA.css`)

See below for the specific styling localisations.

## 2. ./layouts
No layouts have been introduced in this template

## 3. ./scripts
No scripts have been introduced in this template

## 4. CSS Styling
The CSS file `content/assets/css/ADHA.css` includes the following styling localisations:

### a) Navigation bar - background colour
* setting: `.navbar-inverse. background-color`
* set to the Agency required [`#1E6DB6`](https://www.color-hex.com/color/1e6db6)

### b) Navigation bar - 'on-hover' colour of the menu headings
* setting: `.navbar-inverse .navbar-nav > li > a:hover`
* set to black [`#000000`](https://www.color-hex.com/color/000000)

### c) Navigation bar stripe (thin bar across the page in line with the top of the navigation bar) - colour
* setting: `#stripe background`
* set to the Agency required [`#1E6DB6`](https://www.color-hex.com/color/1e6db6)

### d) abc - tbd

### e) abc - tbd
