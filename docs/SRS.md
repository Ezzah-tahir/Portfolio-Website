# Software Requirements Specification

### Portfolio Website — Ezza Tahir

| | |
|---|---|
| **Prepared by** | Ezza Tahir |
| **Document version** | 1.0 |
| **Status** | Draft |
| **Related document** | `docs/VisionScope.md` |

---

## 1. Introduction

### 1.1 Purpose

The purpose of this document is to specify the requirements for a personal portfolio website for Ezza Tahir. The website will showcase academic background, technical skills, and projects to potential recruiters, collaborators, and academic evaluators.

### 1.2 Scope

The portfolio website will include:

- Home page with introduction
- About page with education and skills
- Projects page with descriptions, tech stack tags, and links
- Case-study detail view for flagship projects (e.g. Final Year Project)
- Certifications section
- Resume section, viewable in-browser and downloadable as PDF
- Contact form for visitors to reach out
- Light/dark mode toggle
- Responsive design for desktop, tablet, and mobile

### 1.3 Definitions, Acronyms, Abbreviations

- **UI**: User Interface
- **DB**: Database
- **SRS**: Software Requirements Specification
- **FR**: Functional Requirement
- **NFR**: Non-Functional Requirement
- **FYP**: Final Year Project

### 1.4 References

- IEEE SRS standards
- HTML5, CSS3, JavaScript documentation
- `docs/VisionScope.md` (this repository)

## 2. Overall Description

### 2.1 Product Perspective

The portfolio website is a standalone, static front-end application hosted on GitHub Pages, Netlify, or Vercel. It has no custom backend or database. The contact form is handled entirely through a static-friendly third-party service (Formspree, Getform, or EmailJS) rather than a self-hosted API.

### 2.2 Product Features

- Showcase personal information and résumé (view + download)
- Display projects with descriptions, tech stack, and GitHub/demo links
- Detailed case-study view for 2–3 flagship projects
- Display certifications
- Contact form with validation
- Light/dark mode toggle
- Responsive layout

### 2.3 User Characteristics

- Recruiters, employers, academic evaluators, and peers accessing the site via web browsers
- Users are expected to have basic internet navigation skills; no technical setup required

### 2.4 Constraints

- Must be lightweight and fast-loading
- Should support modern browsers (Chrome, Edge, Firefox, Safari)
- Hosting limited to free platforms (GitHub Pages, Netlify, or Vercel)
- No custom backend or database, per project scope

## 3. Specific Requirements

### 3.1 Functional Requirements

- **FR1**: The system shall display a home page with a welcome message and short professional tagline.
- **FR2**: The system shall provide an About page with education (IIUI, BS IT), interests, and a brief personal narrative.
- **FR3**: The system shall provide a Skills section grouped by category: languages, frameworks/libraries, databases, and tools.
- **FR4**: The system shall provide a Certifications section listing completed courses (e.g. Cisco Networking Academy cybersecurity course).
- **FR5**: The system shall provide a Projects page with project cards, each linking to a GitHub repository and/or live demo where available.
- **FR6**: The system shall provide a detailed case-study view for at least two flagship projects, covering problem, approach, tech stack, and outcome.
- **FR7**: The system shall provide a Resume section with the résumé viewable in-browser and available as a downloadable PDF.
- **FR8**: The system shall provide a Contact form with fields: Name, Email, Message.
- **FR9**: The system shall validate contact form inputs (required fields, valid email format) before submission.
- **FR10**: The system shall submit contact form data through a static-form service (Formspree, Getform, or EmailJS) without a custom backend.
- **FR11**: The system shall provide a light/dark mode toggle, with the selected mode persisted across visits.

### 3.2 Non-Functional Requirements

- **NFR1**: The system shall be responsive across mobile, tablet, and desktop screen sizes.
- **NFR2**: The system shall load within 2–3 seconds on standard broadband.
- **NFR3**: The system shall ensure basic accessibility (semantic HTML, ARIA roles where needed, alt text on images).
- **NFR4**: The system shall use a secure (HTTPS) endpoint for handling contact form submissions.
- **NFR5**: The system shall be maintainable by a single developer without requiring backend infrastructure changes.
- **NFR6**: The system shall be deployable at no recurring cost (free-tier hosting only).

### 3.3 External Interface Requirements

- **UI**: Clean, minimal design with a persistent navigation bar and clear section anchors.
- **Hardware**: Any device with a modern web browser.
- **Software**: HTML5, CSS3, JavaScript (optionally React); no required backend runtime.

## 4. Appendices

### 4.1 Glossary

See Section 1.3.

### 4.2 Future Enhancements

*(Not part of Release 1 — see `docs/VisionScope.md`, Section 4.3)*

- Blog section for technical write-ups
- Admin panel / lightweight CMS integration for updating projects without editing code
- Visitor analytics dashboard beyond a basic third-party script
