# XenopoulosGuard-Website
Paradox‑detection model for code; inspired by the Greek philosopher Epameinondas Xenopoulos.
# XenopoulosGuard-Website

XenopoulosGuard — marketing site για το ομώνυμο προϊόν/μοντέλο ανίχνευσης παραδοξολογικών συμπεριφορών στον κώδικα.

Important: the core algorithm and source code remain in private repositories and are not included in this public site.

---

## Short description / Σύντομη περιγραφή

EN  
XenopoulosGuard is a paradox‑detection model for code analysis, inspired by the Greek philosopher Epameinondas Xenopoulos. This public repository hosts a bilingual (EL/EN) static marketing site with product information, publications, pricing and contact.

EL  
Το XenopoulosGuard είναι ένα μοντέλο ανίχνευσης παραδοξολογικών συμπεριφορών σε κώδικα, εμπνευσμένο από τον Έλληνα φιλόσοφο Epameinondas Xenopoulos. Αυτό το δημόσιο repo φιλοξενεί μια διγλώσση (EL/EN) στατική σελίδα παρουσίασης (marketing) με πληροφορίες προϊόντος, εκδόσεις/βιβλιογραφία, τιμολόγηση και επαφή.

---

## What this repo contains / Τι περιέχει το repo

- `index.html` — διγλώσση (EL/EN) landing page scaffold (hero, features, publications, about, pricing, contact)  
- `thank-you.html` — simple post‑purchase / request page  
- `assets/` — εικόνες placeholder (portrait, cover, og image, orcid icon)  
- `README.md` — αυτό το αρχείο  
- `privacy.md` / `terms.md` — απλά templates για Privacy Policy & Terms  
- `LICENSE` — MIT (για το scaffold)  
- `NOTICE.txt` — εξαιρέσεις πνευματικών δικαιωμάτων για εικόνες/αποσπάσματα

---

## Key items to update / Σημαντικά προς αντικατάσταση μετά την αρχική ρύθμιση

1. Images  
   - `/assets/portrait-family.jpg` — αντικατάστησε με την τελική φωτογραφία (high‑res)  
   - `/assets/cover-epistemology.jpg` — αντικατάστησε με το εξώφυλλο σε υψηλή ανάλυση  
   - `/assets/og-image.png` — optimized social preview (1200×630)

2. PayPal  
   - Αντικατάστησε `YOUR_CLIENT_ID` στο `index.html` με το PayPal sandbox ή live client‑id όταν είσαι έτοιμη.

3. Contact & metadata  
   - Contact email: `katerinaxenopoulou@gmail.com` (μπορεί να αλλάξει στο `index.html`)  
   - Αν έχεις γραπτή άδεια (permission), ανέβασε `assets/permission.pdf` και θα γίνει link από τη σελίδα.

---

## License & Permissions / Άδειες & Δικαιώματα

- The site scaffold (HTML/CSS/JS) is licensed under the MIT License — see `LICENSE`.  
- Images and book excerpts displayed on this site are used with permission of the Epameinondas Xenopoulos family and are NOT covered by the repository license. They may not be reused, redistributed, or modified without written permission. See `NOTICE.txt` for details.  
- For permission or licensing requests contact: [katerinaxenopoulou@gmail.com](mailto:katerinaxenopoulou@gmail.com)

---

## ORCID & Structured data / ORCID & Δεδομένα δομημένα (JSON‑LD)

Author ORCID: [https://orcid.org/0009-0000-1736-8555](https://orcid.org/0009-0000-1736-8555)

The site includes JSON‑LD Person metadata with the ORCID identifier to improve indexing and author attribution.

---

## How to publish with GitHub Pages / Βήματα για ενεργοποίηση GitHub Pages

1. Repository → Settings → Pages → Source: Branch = `main`, Folder = `/ (root)` → Save.  
2. Περιμένετε λίγα λεπτά για να γίνει publish. Το site θα είναι διαθέσιμο στο:  
   `https://<yourusername>.github.io/XenopoulosGuard-Website/` (π.χ. `https://kxenopoulou.github.io/XenopoulosGuard-Website/`)

---

## SEO & Social / Βελτιστοποίηση για sharing

- Βελτιστοποίησε `meta description`, `og:image` και `twitter:card`.  
- Παρέχεται JSON‑LD για Person (με ORCID) και Product — όποια αλλαγή στα metadata να ενημερώνει και το JSON‑LD.

---

## Development / Συνεισφορά

Αυτό το repo προορίζεται ως public marketing site. Ο πηγαίος κώδικας του μοντέλου παραμένει private.

Για αλλαγές:
- Επεξεργασία στο GitHub Web UI: Add file → Upload files / Edit.  
- Ή τοπικά με git:
```bash
git clone git@github.com:kxenopoulou/XenopoulosGuard-Website.git
git checkout -b update-images
# κάνε αλλαγές
git add .
git commit -m "Update images / copy / payPal id"
git push origin update-images
```

---

## Suggested repository topics / Προτεινόμενα topics
- xenopoulos  
- paradox-detection  
- code-analysis  
- static-analysis  
- security  
- orcid  
- greek-philosophy  
- saas

---

## Initial commit message suggestion
Initial scaffold: bilingual marketing site (EL/EN) with placeholders, ORCID, PayPal placeholder, privacy & terms templates, MIT license.

---

## Contact / Επικοινωνία

[katerinaxenopoulou@gmail.com](mailto:katerinaxenopoulou@gmail.com)  

Used with permission of the Epameinondas Xenopoulos family.
