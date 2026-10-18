# WebPDF Studio PRO — Official Downloads

**Zero-upload, client-side PDF & Office suite for Windows.**
None of your PDF/Office files ever leave your computer.

👉 **To download the installers, go to the [Releases](../../releases/latest) section on the right.**

---

## ⬇️ Download

| File | When to use it |
|---|---|
| **WebPDF-Studio-Pro-Setup-x.y.z.exe** | Standard installation. Creates Start Menu + desktop shortcuts and includes an uninstaller. |
| **WebPDF-Studio-Pro-Portable-x.y.z.exe** | Single file for anyone who does not want an installation. It even runs from a USB stick. |

### Windows SmartScreen warning — this is expected

Because the app is not signed with a commercial EV code-signing certificate,
Windows may show the following warning on first launch:

> *"Windows protected your PC — Windows Defender SmartScreen prevented an unrecognized app from starting."*

To continue: **More info → Run anyway**.
This warning does not mean the file is malicious; it only means the publisher is
not yet recognized by Microsoft. A signed build will be added in the future.

### Verify the file is intact

Compare it with the `SHA-256` value published on the release page:

```powershell
Get-FileHash .\WebPDF-Studio-Pro-Setup-2.4.2.exe -Algorithm SHA256
```

---

## 🔒 Why is there no source code in this repository?

- This repository hosts **compiled installers only**.
- The source code is kept in a **private** repository; copying or redistributing
  it is prohibited under the license.
- The application runs **fully offline**: it contains no external AI/LLM service,
  no OCR cloud, and no file-upload endpoint.

## 💳 License

Commercial Lifetime — **€29** · [mavvi.online](https://mavvi.online)

After purchase, the license key is entered in the **License** screen inside the
app; it is verified once and then cached on the device as a signed token.

## 🐞 Bug reports

For installation or runtime problems you can open an **Issue** in this repository.
Please include the version number, your Windows version, and a screenshot.

---

*Copyright © 2026 mavvi.online / smnlcm — All rights reserved.*
*Source code is not published. Redistribution is prohibited.*
