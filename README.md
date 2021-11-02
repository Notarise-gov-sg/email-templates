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
<br/><br/>

### View Certificate

![View Certificate](/screenshots/view-certificate.png)

> **Reminder**: Update the `href` link according to the payload returned by the `api-notarise-healthcerts` endpoint.

File: [view-certificate.html](view-certificate.html)
<br/><br/>

### Pre-Departure Test QR Codes

 ![PDT QR Codes (Mobile)](/screenshots/pdt-qr-codes-mobile.png) 


File: [pdt-qr-codes.html](pdt-qr-codes.html)

<br/><br/>

### Google Pay COVID Card

![Google Pay COVID Card](/screenshots/gpay-covid-card.png)

> **Reminder**: Update the `href` link according to the payload returned by the `api-notarise-healthcerts` endpoint.

File: [gpay-covid-card.html](gpay-covid-card.html)

<br/><br/>

### Vaccination QR Codes

![VAC QR Codes (Mobile)](/screenshots/vac-qr-codes-mobile.png) 


File: [vac-qr-codes.html](vac-qr-codes.html)
