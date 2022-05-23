# Testing 

Test release: [QA Release V1.0.0](https://github.com/ibuttimer/hockey-history/releases/tag/v1.0.0-qa)

The site was tested using the following methods:

## Manual 
The site was manually tested in the following browsers:

|   | Browser | OS | 
|---|---------|----|
| 1 | Google Chrome, Version 101.0.4951.64 | Windows 11 Pro Version 21H2 |
| 2 | Mozilla Firefox, Version 100.0 (64-bit) | Windows 11 Pro Version 21H2 |
| 3 | Opera, Version:86.0.4363.59 | Windows 11 Pro Version 21H2 |
| 4 | Google Chrome, Version 101.0.4951.41 (protrait and landscape mode)| Android 10 |

Testing undertaken:

| Feature | Expected | Action | Related | Result | 
|---------|----------|--------|---------|--------|
| Navbar `Logo` | Clicking opens Home page | Click `Logo` button | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Navbar `Home` | Clicking opens Home page | Click `Home` button | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Navbar `Ireland` | Clicking opens Ireland page | Click `Ireland` button | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Navbar `Resources` | Clicking opens Resources page | Click `Resources` button | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Navbar hamburger | On small screens, navbar is replaced with hamburger menu | View page on small screen | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Footer `Built With` | Clicking opens Built With page | Click `Built With` icon | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Footer social media icons | Clicking opens correct social media site in a new tab; `Facebook`, `Twitter`, `Instagram`, `TikTok` & `YouTube` | Click each social media icon | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Hero image - animation effects on | Hero image rotates on page load | Reload page | Home, Ireland & Resources pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Hero image - animation effects off | Hero image fades in   on page load | Reload page | Home, Ireland & Resources pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| External site links (identified by ![](../media/external_link.jpg)) | Clicking opens correct external site in a new tab | Click each external site link | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Sources links | Clicking opens correct sources list | Click sources link | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |
| YouTube video does not start before being click and plays correctly | Clicking opens correct external site in a new tab | Click YouTube video  | Home page | ![pass](https://badgen.net/badge/checks/Pass/green) |
| Page content | All page content correct | Reload page | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |

## Responsiveness Testing

Responsiveness testing was done using [Screenfly](https://screenfly.org/#u=https%3A//ibuttimer.github.io/hockey-history/&w=1024&h=600&s=1) and Google Chrome Developer Tools Device Mode.

Testing undertaken:

| Feature | Expected | Action | Related | Result | 
|---------|----------|--------|---------|--------|
| Page responsiveness | Page content realigns/resizes when page resized  | Resize page | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |

## Lighthouse

Lighthouse testing was carried out in an Incognito window using Lighthouse (Version 9.5.0) from Chrome Developer Tools.


| Page | Test | Result |  |  |  | Report |
|-|-|-|-|-|-|-|
| Main | Mobile | ![Performance 91](https://img.shields.io/badge/Performance-91-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[home-mobile](https://ibuttimer.github.io/hockey-history/test/lighthouse/home-mobile.html) |
|     | Desktop | ![Performance 86](https://img.shields.io/badge/Performance-86-orange) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[home-desktop](https://ibuttimer.github.io/hockey-history/test/lighthouse/home-desktop.html) |
| Ireland | Mobile | ![Performance 87](https://img.shields.io/badge/Performance-87-orange) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[ireland-mobile](https://ibuttimer.github.io/hockey-history/test/lighthouse/ireland-mobile.html) |
|     | Desktop | ![Performance 95](https://img.shields.io/badge/Performance-95-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[ireland-desktop](https://ibuttimer.github.io/hockey-history/test/lighthouse/ireland-desktop.html) |
| Resources | Mobile | ![Performance 93](https://img.shields.io/badge/Performance-93-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[resources-mobile](https://ibuttimer.github.io/hockey-history/test/lighthouse/resources-mobile.html) |
|     | Desktop | ![Performance 99](https://img.shields.io/badge/Performance-99-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[resources-desktop](https://ibuttimer.github.io/hockey-history/test/lighthouse/resources-desktop.html) |
| Pitch | Mobile | ![Performance 93](https://img.shields.io/badge/Performance-93-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[pitch-mobile](https://ibuttimer.github.io/hockey-history/test/lighthouse/pitch-mobile.html) |
|     | Desktop | ![Performance 100](https://img.shields.io/badge/Performance-100-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[pitch-desktop](https://ibuttimer.github.io/hockey-history/test/lighthouse/pitch-desktop.html) |
| Built With | Mobile | ![Performance 81](https://img.shields.io/badge/Performance-81-orange) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[builtwith-mobile](https://ibuttimer.github.io/hockey-history/test/lighthouse/builtwith-mobile.html) |
|     | Desktop | ![Performance 99](https://img.shields.io/badge/Performance-99-brightgreen) | ![Accessibility 100](https://img.shields.io/badge/Accessibility-100-brightgreen) | ![Best Practises 100](https://img.shields.io/badge/Best%20Practises-100-brightgreen) |![SEO 100](https://img.shields.io/badge/SEO-100-brightgreen) |[builtwith-desktop](https://ibuttimer.github.io/hockey-history/test/lighthouse/builtwith-desktop.html) |

The report JSON files in [test/lighthouse](https://github.com/ibuttimer/hockey-history/tree/main/test/lighthouse) may be viewed in [Lighthouse Report Viewer](https://googlechrome.github.io/lighthouse/viewer/).

## Accessibility
Accessibility testing was carried out using the [NVDA](https://www.nvaccess.org/) and [ChromeVox](https://chrome.google.com/webstore/detail/screen-reader/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en) screen readers.

Testing undertaken:

| Feature | Expected | Action | Related | Result | 
|---------|----------|--------|---------|--------|
| Audio commentary | Audio commentary provided for important page elements | Process page using screen reader | All pages | ![pass](https://badgen.net/badge/checks/Pass/green) |


## User
User testing was carried out and feedback was captured via a [Google Forms survey](https://docs.google.com/forms/d/e/1FAIpQLSeZoQm6RPCzz0rOybJ4WLT3x8OV0hXDFhMVdZbwiNV5HOahlQ/viewanalytics).


## Validator Testing 

The [W3C Nu Html Checker](https://validator.w3.org/nu/) was utilised to check the HTML validity, while the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was utilised to check the CSS validity with respect to [CSS level 3 + SVG](https://www.w3.org/Style/CSS/current-work.html.)

| Page | Home | Ireland | Resources | Built With | Pitch |
|------|------|---------|-----------|------------|-------|
| HTML | [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Findex.html) | [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fireland.html) | [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fresources.html) | [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fbuiltwith.html) | [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fpitch.html) |
| Result | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) |
| CSS | [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fireland.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fresources.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fbuiltwith.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fibuttimer.github.io%2Fhockey-history%2Fpitch.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) |
| Result | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) | ![pass](https://badgen.net/badge/checks/Pass/green) |


## Issues

Issues were logged in [GitHub Issues](https://github.com/ibuttimer/hockey-history/issues).

### Unfixed Issues

There are currently no issues outstanding. 

