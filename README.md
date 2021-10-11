# HTML Email Templates

Recommended HTML templates and guidelines for Notarise-related emails.

> **Note**: This repository only contains the respective HTML code for each specific section (e.g. QR codes, GPay COVID Card, etc.).

## Getting Started

### Responsive Base HTML Boilerplate

As a starting point, clinics/providers should look into a responsive base HTML boilerplate/template.

A good reference: <https://github.com/leemunroe/responsive-html-email-template>

### Images

Please remember to host any images that appear in the email from a trusted source. Alternatively, you may also make use of CID (Content-ID).

Read more: <https://mailtrap.io/blog/embedding-images-in-html-email-have-the-rules-changed/>

## Respective Sections

For each section of the email, please refer to the respective HTML files:

### View Certificate

![View Certificate](/screenshots/view-certificate.png)

File: [view-certificate.html](view-certificate.html)

### Pre-Departure Test QR Codes

| Desktop                                                          | Mobile                                                         |
| ---------------------------------------------------------------- | -------------------------------------------------------------- |
| ![PDT QR Codes (Desktop)](/screenshots/pdt-qr-codes-desktop.png) | ![PDT QR Codes (Mobile)](/screenshots/pdt-qr-codes-mobile.png) |

> **Important**: The online QR section is semantically defined in a reverse column order (when viewed on a large viewport). When viewing in a smaller viewport, the order of the column will be reverted to follow the same order as the offline QR section.

> **Media Query Required**: The table columns in the offline QR section requires a `@media` query for the columns be responsive. Remember to place it in the `<head></head>` of the HTML.

File: [pdt-qr-codes.html](pdt-qr-codes.html)

### Vaccination QR Codes

| Desktop                                                          | Mobile                                                         |
| ---------------------------------------------------------------- | -------------------------------------------------------------- |
| ![VAC QR Codes (Desktop)](/screenshots/vac-qr-codes-desktop.png) | ![VAC QR Codes (Mobile)](/screenshots/vac-qr-codes-mobile.png) |

> **Media Query Required**: The table columns in the offline QR section requires a `@media` query for the columns be responsive. Remember to place it in the `<head></head>` of the HTML.

File: [vac-qr-codes.html](vac-qr-codes.html)

### Google Pay COVID Card

![Google Pay COVID Card](/screenshots/gpay-covid-card.png)

File: [gpay-covid-card.html](gpay-covid-card.html)
