# Microrbit• EFB — Electronic Form Builder

A fully client-side, single-file electronic form builder web application. No backend, no dependencies to install, no build step. Open the HTML file and start building.

---

## Features

- **Drag-and-drop form builder** — 12 field types including text, email, date, dropdown, radio, checkbox, file upload, phone, signature, and section headings
- **Live form preview** — render your form as a working interactive form and simulate submission
- **Dashboard** — real-time submission stats, activity charts, and recent submission log
- **My Forms** — manage multiple forms, view submission counts, duplicate or delete forms
- **Analytics** — submission trends, outcome breakdowns, validation error tracking
- **Submissions log** — track every submission with reference numbers and status badges
- **Settings** — configure form behaviour, approval routing, AI features, notifications, and accessibility options
- **Dark / Light mode** — toggle with the moon/sun button in the top-right corner
- **Accent colour picker** — customize the brand colour from Settings
- **Form templates** — start from blank, Access Request, or Onboarding templates
- **Platform selector** — tag each form as Web Form, Power Apps, Microsoft Forms, or AEM Forms

---

## Getting Started

### Option 1 — Open locally

```bash
git clone https://github.com/YOUR_USERNAME/microrbit-efb.git
cd microrbit-efb
open index.html        # macOS
start index.html       # Windows
xdg-open index.html   # Linux
```

No server required. Everything runs in the browser.

---

### Option 2 — Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app will be live at `https://YOUR_USERNAME.github.io/microrbit-efb/`

> Make sure `microrbit-efb.html` is renamed to `index.html` before pushing if you want it to load at the root URL.

---

### Option 3 — Deploy to Netlify (drag & drop)

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `index.html` file onto the page
3. Live in seconds — no account required

---

## File Structure

```
microrbit-efb/
├── index.html        # The entire application — one self-contained file
└── README.md         # This file
```

All CSS, JavaScript, and HTML are contained in a single file. No external CDN calls, no frameworks, no build tools.

---

## How to Use the Builder

### Creating a form

1. Click **+ New Form** in the top-right or nav bar
2. Choose a **platform type** (Web Form, Power Apps, Microsoft Forms, AEM Forms)
3. Enter a **form name** and description
4. Choose a **template** (blank, Access Request, or Onboarding) or start from scratch
5. Click **Create Form →**

### Adding fields

- Click any **field type** in the left panel to add it to the canvas
- Click a field on the canvas to **select it** and edit its properties in the right panel
- Use the **↑ ↓** arrows on each field to reorder
- Use the **✕** button to delete a field
- Edit the **form title and description** by clicking directly on them in the canvas

### Field types available

| Field | Description |
|-------|-------------|
| Text | Single-line text input |
| Email | Email with format validation |
| Number | Numeric input |
| Date | Date picker (YYYY-MM-DD) |
| Dropdown | Select from a list of options |
| Radio | Single-choice radio group |
| Checkbox | Multi-choice checkbox group |
| Long Text | Multi-line textarea |
| File Upload | File attachment (PDF, DOCX, PNG) |
| Phone | Phone number input |
| Section | Section heading / divider |
| Signature | Signature capture area |

### Previewing and submitting

- Click **Preview Form** in the top-right to open a live interactive preview
- Fill in the fields and click **Submit Request** to simulate a submission
- A unique reference number (`REF-2025-XXXX`) is generated on submission

---

## Configuration

All settings are accessible from the **Settings** page:

| Category | Options |
|----------|---------|
| Appearance | Theme, accent colour, border radius |
| Form behaviour | Save & resume, duplicate detection, AI suggestions, printable summary |
| Approval routing | Auto-escalation timeout, IT review for owner access, parallel approval |
| Notifications | Email on submission, approval reminders, weekly digest |
| Accessibility | WCAG target level, high contrast mode, focus ring style |

---

## Accessibility

This application is designed with WCAG 2.1 AA guidelines in mind:

- All interactive elements are keyboard accessible
- Form fields use associated labels
- Error states are communicated via text, not colour alone
- Colour contrast ratios meet minimum 4.5:1 for body text
- Focus indicators are visible and clearly styled

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✓ Full |
| Firefox 88+ | ✓ Full |
| Safari 14+ | ✓ Full |
| Edge 90+ | ✓ Full |

---

## Disclaimer

This is a demonstration application. All form submissions, analytics data, and submission records shown are sample/mock data for UI demonstration purposes only. No data is transmitted, stored externally, or retained between sessions. All state resets on page refresh.

---

## License

MIT — free to use, modify, and distribute.

---

*Built with Microrbit• EFB — Electronic Form Builder*
