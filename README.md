# Adkins Elloz — MoonLight Art Gallery

This repository hosts the official website for **Adkins Elloz**, an artist working through reduction, constraint, and direct gesture.

The site is published using **GitHub Pages** and is intentionally simple.  
No frameworks. No build steps. No decoration.

Live site  
https://xbosch.github.io/adkins_elloz/

---

## About the Work

Adkins Elloz develops images through constraint.

Forms are reduced to what cannot be removed.  
Color is used as structure, not decoration.  
Gesture is direct. Revision is minimal.

There is no narrative.  
There is no symbolism offered as guidance.

The work does not explain itself.  
It establishes presence.

Each series operates as a closed system.  
Repetition is not variation.  
It is insistence.

---

## Website Structure

The site is entirely static and organized as follows:

/
├── index.html Home
├── about.html Artist information
├── contact.html Contact and inquiries
├── css/
│ └── style.css Global styles
├── gallery/
│ ├── index.html Gallery overview
│ ├── olives.html Olives series
│ ├── faces.html Faces series
│ └── symbols.html Symbols series
└── images/
├── olives/
├── faces/
└── symbols/


Each series page introduces the work as a sequence.  
Each artwork page is self contained and intentionally sparse.

---

## Design Principles

- Static HTML and CSS only
- No JavaScript
- No tracking
- No analytics
- No animations
- Neutral background
- Text as structure
- Images treated as physical objects

The site is designed to hold space rather than occupy it.

---

## Deployment

The site is deployed using **GitHub Pages** from the `main` branch.

Any push to `main` updates the live site automatically.

Typical workflow:

```bash
git add .
git commit -m "Update site content"
git push 
```

After pushing, GitHub Pages typically updates the site within a few seconds to a minute.

## Notes

The repository root is used as the publishing source
The home page must be named index.html
All paths are relative and must remain consistent
There is no local server requirement for deployment
The simplicity of this workflow is intentional.