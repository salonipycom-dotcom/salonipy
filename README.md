# Salonipy — Windows downloads

This repository exists to host the **Salonipy for Windows** installer.

**→ [Download the latest version](https://github.com/salonipycom-dotcom/salonipy/releases/latest)**

Most people should use the [download page](https://salonipy.com/download)
instead, which also offers the Android app and the browser version.

## What Salonipy is

Salon management software — appointments, sales and invoices, expenses,
clients, staff and WhatsApp reminders. One account, synced across every device.

- 🌐 Web app — <https://salonipy.com/app/> (works on any browser, including iPhone)
- 🤖 Android — <https://salonipy.com/download>
- 🖥️ Windows — the releases in this repository

## Why the installer lives here and not on salonipy.com

The installer is around 90 MB. On shared hosting a file that size is not just
bandwidth: a single download holds a connection and the disk for a minute or
two, and the dozen at once that follows a launch post makes every other page on
the same server crawl. GitHub serves release binaries for free and was built
for it.

## Verifying a download

Each release includes `SHA256SUMS.txt`. To check the installer arrived intact,
open Command Prompt in your Downloads folder and run:

```
certutil -hashfile Salonipy-Setup-1.0.0.exe SHA256
```

The result should match the line in that file.

`latest.yml` and the `.blockmap` are not for downloading by hand — the installed
app reads them to update itself.

## Support

- WhatsApp — <https://wa.me/923471835667>
- Email — hello@salonipy.com

© Codipy Labs
