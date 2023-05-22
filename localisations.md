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

See below for the specific styling localisations in `ADHA.css`.

## 2. ./layouts
No layout localisations have been introduced in this template

## 3. ./scripts
No scripts have been introduced in this template

## 4. CSS Styling
The CSS file `content/assets/css/ADHA.css` includes the following styling localisations:

### a) ADHA Logo

#### ADHA logo placement (in `family-nav` div container)
* setting `#family-logo`
* float: left
* margin-top: 20px
* margin-left: 40px
* margin-bottom: 20px
* margin-right: 40px
* display: block

#### Placement of logo container (`family-nav` div)
* setting: `#family-nav`
* line-height: 70px;
* float: left;
* margin-top: 4px;
* margin-bottom: 4px;

### b) Styling of the Implementation Guide title
* setting: `#ig-status`
* line-height: 70px;
* margin-top: 40px;
* margin-left: 250px;
* color: #000000;
* text-align: center;
* height: 50px;

### c) Navigation bar

#### Background colour
* setting: `.navbar-inverse. background-color`
* set to the Agency required [`#1E6DB6`](https://www.color-hex.com/color/1e6db6)

#### Colour of the menu headings 'on-hover' 
* setting: `.navbar-inverse .navbar-nav > li > a:hover`
* set to black [`#000000`](https://www.color-hex.com/color/000000)

#### Colour of the navigation bar heading font
* setting: `.navbar-inverse .navbar-nav > li > a`
* font colour set to [`#FFFFFF`](https://www.color-hex.com/color/FFFFFF), for improved contrast (see below for compliance to WCAG)

#### Compliance to WCAG Level 2.1 re colour contrast
* for compliance to the Web Content Accessibility Guidelines [(WCAG) Level 2.1](https://www.w3.org/WAI/standards-guidelines/wcag/), regarding minimum contrast ratio, at level AA
* font colour set to [`#FFFFFF`](https://www.color-hex.com/color/FFFFFF), given the background is set to [`#1E6DB6`](https://www.color-hex.com/color/1E6DB6); contrast ratio is [5.35:1](https://webaim.org/resources/contrastchecker/?fcolor=FFFFFF&bcolor=1E6DB6)

### d) Menu bar stripe
This is the thin bar across the page in line with the top of the navigation bar

#### Colour
* setting: `#stripe background`
* set to the Agency required [`#1E6DB6`](https://www.color-hex.com/color/1e6db6)

### e) Publish box

#### Colour of the hyperlinks
* setting: `#publish-box a`
* font colour set to [`#0000FF`](https://www.color-hex.com/color/0000FF), for improved contrast (see below for compliance to WCAG)

#### Compliance to WCAG Level 2.1 re colour contrast
* for compliance to the Web Content Accessibility Guidelines [(WCAG) Level 2.1](https://www.w3.org/WAI/standards-guidelines/wcag/), regarding minimum contrast ratio, at level AA
* font colour set to [`#0000FF`](https://www.color-hex.com/color/0000FF), given the background is set to [`#FFEB7E`](https://www.color-hex.com/color/FFEB7E); contrast ratio is [7.13:1](https://webaim.org/resources/contrastchecker/?fcolor=0000FF&bcolor=FFEB7E)

### d) Main body of text

#### Colour of the hyperlinks
This includes hyperlinks in the yellow contents box
* setting: `#segment-content a`
* font colour set to [`#0000FF`](https://www.color-hex.com/color/0000FF), for improved contrast (see below for compliance to WCAG)

#### Compliance to WCAG Level 2.1 re colour contrast
* for compliance to the Web Content Accessibility Guidelines [(WCAG) Level 2.1](https://www.w3.org/WAI/standards-guidelines/wcag/), regarding minimum contrast ratio, at level AA
* font colour set to [`#0000FF`](https://www.color-hex.com/color/0000FF), given the background is set to [`#FFFFFF`](https://www.color-hex.com/color/FFFFFF); contrast ratio is [8.59:1](https://webaim.org/resources/contrastchecker/?fcolor=0000FF&bcolor=FFFFFF)

### e) Footer

#### Footer background colour
* setting: `#segment-footer > .container`
* set to the Agency required [`#707070`](https://www.color-hex.com/color/707070)

#### Footer hyperlink font colour
* setting: `:root --footer-hyperlink-text-color`
* font colour set to [`#F6F9C8`](https://www.color-hex.com/color/F6F9C8), for improved contrast (see below for compliance to WCAG)

#### Compliance to WCAG Level 2.1 re colour contrast
* for compliance to the Web Content Accessibility Guidelines [(WCAG) Level 2.1](https://www.w3.org/WAI/standards-guidelines/wcag/), regarding minimum contrast ratio, at level AA
* font colour set to [`#F6F9C8`](https://www.color-hex.com/color/F6F9C8), given the background is set to [`#707070`](https://www.color-hex.com/color/707070); contrast ratio is [4.55:1](https://webaim.org/resources/contrastchecker/?fcolor=F6F9C8&bcolor=707070)
