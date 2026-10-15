# My First Site: Jaipur Engineering College

A static, multi-page website about Jaipur Engineering College (JEC), built with
semantic HTML from Lectures 1–5. One tiny `style.css` only makes the tables readable.

This is a student project, not the official college website. Facts, seats and
contact details were copied from https://www.jeckukas.org.in/ in October 2026.
Fees, calendar dates and notices are sample data.

The campus photos in `images/` are from the Jaipur Engineering College website and are
used here for classwork only. The logo is Technoledge's.

## Pages
- index.html: Home (hero image, campus photos, notices, calendar table, four kinds of links)
- about.html: History, quick-facts table, facilities with photos
- courses.html: Course, seat and fee tables
- admission.html: Admission form
- contact.html: Address, office table, enquiry form
- thank-you.html: Shown after a form is submitted

## Folders
```
jec-kukas-site/
├── index.html
├── about.html
├── courses.html
├── admission.html
├── contact.html
├── thank-you.html
├── style.css
├── images/
│   ├── logo.png
│   ├── building.jpg
│   ├── library.jpg
│   ├── hostel.jpg
│   └── sports.jpg
└── README.md
```

## How to open
Open index.html with Live Server.

## Where to find each topic
| Topic | Lecture | Look in |
| --- | --- | --- |
| Skeleton: DOCTYPE, html, head, title, body | 1, 2 | every page |
| Headings as an outline, p, strong, comments | 2 | every page |
| ul and ol | 2 | about.html |
| Absolute, relative, same-page, mailto and tel links | 2 | index.html "Useful links" |
| img with src, alt, width, height | 3 | index.html, about.html |
| Image as a link | 3 | logo in the header |
| Relative paths and one images/ folder | 3 | every page |
| Shared nav | 3 | every page |
| Simple table: caption, thead, tbody, th, td | 3 | index.html |
| Row headers only | 3 | about.html |
| tfoot and colspan | 3 | courses.html, B.Tech table |
| rowspan | 3 | courses.html, postgraduate table |
| Two-level header | 3 | courses.html, fees table |
| Links inside table cells | 3 | contact.html |
| form, label for/id, input types, select, textarea, button | 4 | admission.html, contact.html |
| required, minlength, min, max, pattern | 4 | admission.html |
| header, nav, main, section, article, footer | 4 | index.html |
| aria-label on nav | 4 | every page |

## Definition of done
- [ ] Every page validates at validator.w3.org with zero errors
- [ ] The nav works from every page
- [ ] Every image has alt text
- [ ] One h1 per page, headings in order
- [ ] Every form can be filled in with the keyboard only
