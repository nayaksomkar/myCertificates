# myCerificates

A simple collection of certificate files and metadata.

## Contents

- `certificates.json` — list of certificates with titles, image paths, PDF paths, and Udemy links.
- `CertificateJPG/` — certificate image files.
- `CertificatePDF/` — certificate PDF files.

## Notes

This repository is intended for storing and organizing certificate records in a lightweight format.

## Certificate entry format

Each certificate entry in `certificates.json` uses this structure:

```json
"certificate_XX": {
  "Title": "Certificate title",
  "pathJPG": "CertificateJPG/filename.jpg",
  "pathPDF": "CertificatePDF/filename.pdf",
  "udemyURL": "https://www.udemy.com/certificate/..."
}
```

Use this as the reference format when adding new certificates.
