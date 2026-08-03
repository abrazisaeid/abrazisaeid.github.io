# Saeid Safari Abrazi — Portfolio

Professional GitHub Pages portfolio for Embedded Systems, FPGA/SoC, IEC 61850, and IEEE 1588 work.

## Deploy
Upload all files in this folder to the repository root of `abrazisaeid.github.io` and commit them to `main`.

## Add a new article
Edit `articles.json` and add the newest item at the top:

```json
{
  "title": "Article title",
  "date": "2026-08-03",
  "category": "IEC 61850",
  "summary": "One or two concise sentences.",
  "url": "https://www.linkedin.com/pulse/..."
}
```

The website automatically sorts articles by date. Direct automatic LinkedIn synchronization is intentionally not used because LinkedIn does not offer a stable public feed/API for this use case.
