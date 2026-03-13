# 🌐 CF9 Web — Web Development Projects

> Εκπαιδευτικά projects HTML5, CSS3, Bootstrap & Tailwind CSS που δημιουργήθηκαν στο πλαίσιο του **[Coding Factory](https://codingfactory.aueb.gr/)** — Οικονομικό Πανεπιστήμιο Αθηνών (AUEB).

---

## 📖 Περιγραφή

Το repository περιέχει πρακτικά παραδείγματα και ασκήσεις‑challenges που καλύπτουν τις βασικές τεχνολογίες front‑end web development. Ο κώδικας είναι οργανωμένος σε **6 κεφάλαια** (chapters) που ακολουθούν τη ροή του μαθήματος, καθώς και σε ένα φάκελο **challenges** με πιο σύνθετες ασκήσεις ανά κεφάλαιο.

---

## 🛠️ Τεχνολογίες

| Τεχνολογία | Έκδοση / CDN |
|---|---|
| HTML5 | — |
| CSS3 (Vanilla) | — |
| Bootstrap | 5.3.x (CDN) |
| Bootstrap Icons | 1.13.x (CDN) |
| Tailwind CSS | v4 (CDN — `@tailwindcss/browser@4`) |
| Font Awesome | 7.x (CDN) |
| Google Fonts | Διάφορα (π.χ. custom fonts) |

---

## 📂 Δομή Repository

```
cf9web/
├── ch1/                        # Κεφάλαιο 1 – Εισαγωγή στην HTML5
├── ch2/                        # Κεφάλαιο 2 – CSS3 Styling
│   └── css/                    # Εξωτερικά CSS αρχεία
├── ch3-layout/                 # Κεφάλαιο 3 – CSS Layouts
│   └── css/                    # Εξωτερικά CSS αρχεία
├── ch4-responsive/             # Κεφάλαιο 4 – Responsive Design
│   ├── css/                    # Εξωτερικά CSS αρχεία
│   └── app-gov-gr/             # 🏛️ Mini‑project: Gov.gr App Mockup
├── ch5-bootstrap/              # Κεφάλαιο 5 – Bootstrap 5
│   └── Corfu-Bootstrap/        # 🏝️ Mini‑project: Corfu Guide
├── ch6-tailwind/               # Κεφάλαιο 6 – Tailwind CSS
├── challenges/                 # Ασκήσεις & Challenges
│   ├── chapter1/               #   HTML challenges
│   ├── chapter2/               #   CSS challenges
│   ├── chapter3/               #   Layout challenges
│   └── chapter4/               #   Responsive challenges
├── img/                        # Κοινές εικόνες (logos, photos)
└── README.md
```

---

## 📚 Κεφάλαια

### Κεφάλαιο 1 — HTML5 Basics (`ch1/`)

Εισαγωγή στα βασικά στοιχεία της HTML5:

- Δομή σελίδας, headings & παράγραφοι
- Λίστες (ordered / unordered / nested)
- Πίνακες (tables) με `colspan` & `rowspan`
- Σύνδεσμοι (anchors) & εικόνες
- Φόρμες (text, email, radio, checkbox, select, textarea, fieldset)
- Ενσωμάτωση πολυμέσων (video / audio)

### Κεφάλαιο 2 — CSS3 Styling (`ch2/`)

Βασικά και ενδιάμεσα θέματα CSS:

- Σύνδεση εξωτερικών CSS αρχείων & κλάσεις
- Selectors, specificity & cascade
- Google Fonts integration
- Styling φορμών, πινάκων & λιστών
- Εικόνες & background images
- CSS Transitions & hover effects
- Overflow handling & viewport units (`vh`)
- CSS mockup (σχεδιασμός σελίδας Coding Factory)
- Navigation list menu

### Κεφάλαιο 3 — CSS Layouts (`ch3-layout/`)

Τεχνικές τοποθέτησης & layout:

- **Float** — Βασικό float layout & float around image
- **Box Model** — Margin, padding, border
- **Flexbox** — Alignment, menu, wrapping, order, sizing, grow/shrink
- **CSS Grid** — Grid template, grid areas, grid sizing, flexbox‑grid alignment
- **Positioning** — Relative, absolute, fixed, sticky
- **Dropdown menus** με CSS

### Κεφάλαιο 4 — Responsive Design (`ch4-responsive/`)

Responsive τεχνικές με CSS Media Queries:

- Βασικά responsive παραδείγματα με breakpoints
- Σύνθετο responsive mockup με header, nav, hero image, footer
- Hamburger menu toggle (JavaScript)
- Font Awesome icons integration

#### 🏛️ Mini‑project: Gov.gr App Mockup (`app-gov-gr/`)

Responsive κλώνος σελίδας κυβερνητικής εφαρμογής "Δήλωση Καθαρισμού Οικοπέδων" — πλήρες layout με header, main content, form links & footer.

### Κεφάλαιο 5 — Bootstrap 5 (`ch5-bootstrap/`)

Ανάπτυξη με Bootstrap 5:

- Bootstrap setup & βασική χρήση
- Grid system & responsive columns
- Typography & spacing utilities
- Tables (responsive, striped, hover)
- Login form layouts
- Responsive Navbar (collapsible, dark theme, icons)

#### 🏝️ Mini‑project: Corfu Guide (`Corfu-Bootstrap/`)

Πολυσέλιδο website τουριστικού οδηγού για την Κέρκυρα — responsive navbar με dropdowns, hero section, image cards, footer με social icons. Χρήση Bootstrap 5 + Bootstrap Icons.

### Κεφάλαιο 6 — Tailwind CSS v4 (`ch6-tailwind/`)

Ανάπτυξη με Tailwind CSS:

- Εγκατάσταση & βασική χρήση (CDN browser build)
- Utility‑first typography & spacing
- Responsive design με Tailwind breakpoints
- Flex & Grid layouts
- Containers & columns
- Display utilities (show/hide)
- Styled tables & circular images
- Login form
- Responsive Navbar (JavaScript toggle, hover effects)

---

## 🎯 Challenges

Ασκήσεις-challenges ανά κεφάλαιο με αυξανόμενη δυσκολία:

| Challenge | Περιγραφή |
|---|---|
| **Chapter 1** | Βιογραφικό (Resume) σε HTML, Registration form, Tables |
| **Chapter 2** | Styled Login form, Bio page CSS styling |
| **Chapter 3** | Gov.gr TaxisNet Login page clone (CSS Flexbox layout) |
| **Chapter 4** | Gov.gr "Ακαθάριστα Οικόπεδα" responsive landing page |

---

## 🚀 Πώς να τα τρέξετε

Τα αρχεία είναι **στατικά HTML/CSS** — δεν απαιτείται build process ή server.

1. **Clone** το repository:
   ```bash
   git clone https://github.com/blancberger/cf9-web.git
   ```
2. Ανοίξτε οποιοδήποτε `.html` αρχείο απευθείας στον browser σας, ή χρησιμοποιήστε ένα **Live Server** extension (π.χ. VS Code Live Server).

> **Σημείωση:** Τα παραδείγματα Bootstrap & Tailwind φορτώνουν τα CSS frameworks μέσω CDN, οπότε απαιτείται σύνδεση στο internet.

---

## 📸 Highlights

- ✅ HTML5 σημασιολογικά (semantic) elements
- ✅ CSS3 Flexbox & Grid layouts
- ✅ Πλήρως responsive σελίδες
- ✅ Bootstrap 5 components (navbar, cards, forms, tables)
- ✅ Tailwind CSS v4 utility‑first approach
- ✅ Real‑world mockups (Gov.gr, Corfu Guide)
- ✅ Accessible forms με `label`, `fieldset`, `aria` attributes

---

## 📄 Άδεια Χρήσης

Εκπαιδευτικό υλικό — [Coding Factory @ AUEB](https://codingfactory.aueb.gr/).

---

<p align="center">
  <sub>Made with ❤️ at <strong>Coding Factory</strong> — Athens University of Economics and Business</sub>
</p>