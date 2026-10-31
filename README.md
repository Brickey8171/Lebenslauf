<div align="center">

# 📄 Lebenslauf-Ersteller

### CV & cover letter maker – one HTML file, no server, no account.

Build a clean CV and a matching cover letter in minutes.
Your data never leaves your browser.

![Single file](https://img.shields.io/badge/single%20file-HTML-e34f26?style=for-the-badge)
![No dependencies](https://img.shields.io/badge/dependencies-none-2ea44f?style=for-the-badge)
![Offline](https://img.shields.io/badge/works-offline-0969da?style=for-the-badge)
![Languages](https://img.shields.io/badge/DE%20·%20EN%20·%20HU-8957e5?style=for-the-badge)

**[🚀 Open the app](https://brickey8171.github.io/Lebenslauf)** · **[✨ Features](#-features)** · **[📦 Use it](#-getting-started)** · **[🔒 Privacy](#-privacy)**

</div>

---

## ✨ Features

### 📋 CV (Lebenslauf)
- **114 templates** – classic, modern, sidebar, creative
- Free choice of **colours, fonts, spacing** and page structure
- **Photo upload with cropping** and a built-in editor
- Guided **3-step flow**: personal data → experience & skills → design & export
- **Several CVs** side by side – ideal for different job applications
- Phrase suggestions for job descriptions and skills

### ✉️ Cover letter (Bewerbungsschreiben)
- **Generator** that builds the letter from your CV data
- Choose between a **formal** or a **modern & personal** tone – every paragraph changes
- **9 layouts** to pick from
- Text stays **fully editable**; regenerate any time
- Each CV keeps its **own cover letter**

### ✍️ Signature
- **Draw** it with finger or mouse, or **upload a photo** of your signature
- Background is removed automatically
- Stays readable on **dark layouts** (automatic light variant)

### 🌍 Languages
- **German, English and Hungarian** – CV text *and* the whole interface switch together
- Language-specific salutations, closing phrases and date formats

### 📥 Export
- **Direct PDF download** with a **searchable text layer** (works on phones too)
- Print-friendly output
- **Backup & restore** all CVs as a single file

---

## 🚀 Getting started

**Option 1 – Online:** open the hosted page and start.

**Option 2 – Offline:**

1. Download [`lebenslauf-ersteller.html`](lebenslauf-ersteller.html)
2. Double-click it – it opens in any modern browser
3. No installation, no build step

**Option 3 – Host it yourself:**

1. Fork or clone this repository
2. *Settings → Pages →* deploy from the `main` branch
3. Your app is live at `https://<your-name>.github.io/<repo>`

---

## 🧭 How it works

```
 Main menu
 ├── 📋 Lebenslauf            ① Personal  →  ② Content  →  ③ Design & PDF
 ├── ✉️ Bewerbungsschreiben   Job · company · tone · layout · signature → PDF
 └── ⚙️ (gear)                Manage CVs · language · backup
```

1. Pick **Lebenslauf** or **Bewerbungsschreiben** from the main menu.
2. Fill in your details – the live preview updates as you type.
3. Choose a template or layout, colours and fonts.
4. Download the **PDF**.

> 💡 Use the **sample** button to load example data and explore every feature first.

---

## 🔒 Privacy

- **No server, no tracking, no cookies, no account**
- Everything is stored in your browser's `localStorage`
- Photos and signatures are processed locally
- PDFs are generated on your device
- Use the **backup file** to move your data to another device

> ⚠️ Clearing your browser data deletes your saved CVs. Export a backup now and then.

---

## 🛠️ Tech

| | |
|---|---|
| **Stack** | Plain HTML, CSS and JavaScript – no framework, no build tools |
| **PDF** | Rendered in-browser to pages with an invisible text layer (searchable, selectable) |
| **Storage** | `localStorage` |
| **Size** | ~260 KB, everything included |
| **Browsers** | Current Chrome, Edge, Firefox, Safari (desktop & mobile) |

---

## ⚠️ Good to know

- The cover letter is a **template-based generator**, not AI. Your own entries are inserted as written, so check grammar and endings before sending.
- Template names are in German in all interface languages.
- Signature photos with ruled paper lines may leave a faint line – draw it for the cleanest result.

---

## 🗺️ Ideas

- [ ] Match the cover letter automatically to the CV template
- [ ] Job-ad keyword helper
- [ ] Download CV + letter as one bundle
- [ ] Running header on page 2 of long letters
- [ ] Installable app (PWA)
- [ ] Application tracker

Suggestions and pull requests are welcome.

---

<div align="center">

Made with ☕ in Austria · Your data stays yours

</div>
