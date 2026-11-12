# Save Contact

A static, client-side page that builds a vCard (`.vcf`) contact file. Nothing is uploaded; everything runs in the browser.

- Standard contact fields: name parts, nickname, phonetic names, company, department, title, multiple phones, emails, addresses, websites, social profiles, instant messaging, birthday, anniversary and notes.
- Photo: pick any image, crop to a 1:1 square (drag, zoom, rotate), choose output resolution and JPEG quality with sliders, and see the resulting size. The photo is converted to JPEG and embedded as base64 (`PHOTO;ENCODING=b;TYPE=JPEG`).
- Import: open an existing `.vcf` (vCard 2.1, 3.0 or 4.0, including embedded photos) to edit and re-export it.
- Output is vCard 3.0 with proper escaping and 75-octet line folding, which imports on iPhone, Android and desktop contacts apps.

Hosted with GitHub Pages from the repository root (`index.html`).
