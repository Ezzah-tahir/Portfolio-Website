# Vision and Scope Document

### Personal Portfolio Website



 **Prepared by** : Ezza 
 **Role** : BS Information Technology, 7th Semester — International Islamic University Islamabad (IIUI) 
 **Document version** : 1.0 
 **Status** : Draft 

---

## 1. Executive Summary

This document defines the vision, scope, and boundaries for the design and development of a personal portfolio website. The site will serve as a single, professional online reference point that presents the owner's academic background, technical skill set, and project work to potential employers, academic evaluators, and professional contacts. It will be built as a lightweight, primarily front-end web application, prioritizing fast load times, clear presentation of project work, and ease of long-term maintenance.

## 2. Problem Statement

As a final-semester BS Information Technology student, project work, coursework, and technical skills currently exist in scattered forms: individual GitHub repositories, CV documents, and academic project reports. There is no single, easily shareable destination that presents this work coherently. Recruiters, potential clients, and academic evaluators currently have no fast way to review this body of work in one place, which weakens the impression of technical capability and professionalism during job applications, internship search, and freelance opportunities.

## 3. Vision Statement

For a final-year IT student seeking employment, internships, and freelance opportunities, the portfolio website is a personal branding platform that consolidates academic background, technical skills, and project work into a single professional online presence. Unlike scattered GitHub repositories, static CV files, or social profiles, this product presents each project as a readable case study with context, technology used, and outcomes, and remains fast, responsive, and easy to keep up to date as new projects and skills are added.

## 4. Project Scope

### 4.1 In Scope (Release 1)

- Home / hero section with name, current role, and a short professional tagline
- About section covering academic background (IIUI, BS IT, current semester), interests, and a brief personal narrative
- Projects section featuring completed work, each with a short description, tech stack tags, and links to source code or demo where available
- Case-study style detail view for 2–3 flagship projects (e.g. the Final Year Project and one full-stack project), covering problem, approach, tech stack, and outcome
- Skills section grouped by category: languages, frameworks/libraries, databases, and tools
- Certifications section for completed courses (e.g. Cisco Networking Academy cybersecurity course)
- Resume section with an in-browser viewable and downloadable PDF resume
- Contact section with email, LinkedIn, and GitHub links, plus a working contact form via a static-form service (no custom backend)
- Fully responsive layout across mobile, tablet, and desktop breakpoints
- Light/dark mode toggle
- Deployment to a free static hosting platform (e.g. GitHub Pages, Netlify, or Vercel)

### 4.2 Out of Scope (Release 1)

- User authentication or visitor accounts
- A custom backend server or database for content management
- A blogging platform or CMS-driven content
- Real-time features (chat, live notifications)
- Multi-language / localization support
- Paid hosting, custom analytics backend, or e-commerce functionality

### 4.3 Future Considerations

- Blog section for technical write-ups, added once there is a regular need to publish longer-form content
- Admin panel or lightweight CMS integration for updating projects without editing code directly
- Visitor analytics dashboard beyond a basic third-party script

## 5. Stakeholders

| Stakeholder | Interest |
|---|---|
| Site owner (Ezza) | Primary user and maintainer; needs the site to accurately represent skills and be easy to update |
| Recruiters / hiring managers | Need to quickly assess skills, projects, and suitability for a role |
| Academic evaluators / supervisors | May reference the site alongside the Final Year Project submission |
| Potential freelance clients | Need evidence of prior delivered work (e.g. the tourism website project) |

## 6. Success Criteria

- Site loads in under 2–3 seconds on a typical broadband or mobile connection
- All project links, resume download, and contact form function correctly across major browsers
- Layout renders correctly on common mobile, tablet, and desktop screen sizes
- At least 3–4 projects are presented with enough detail (tech stack, description, links) to be independently understandable
- Site is live on a public URL and included in job/internship applications within the target timeframe

## 7. Assumptions and Constraints

### 7.1 Assumptions

- Project screenshots, demo videos/GIFs, and a finalized resume PDF will be available before content population begins
- No dedicated design budget; visual design will be created directly in code using established design/UI conventions
- Content (project descriptions, bios) will primarily be written by the site owner

### 7.2 Constraints

- Must be deployable on free-tier hosting (no recurring cost)
- Should be maintainable by a single developer without a dedicated backend team
- Timeline is constrained by final semester academic workload (FYP, coursework)

## 8. Technology Overview

The site will be implemented as a static, primarily front-end application, consistent with the scope defined above. The following stack is proposed based on existing familiarity and project requirements:

| Layer | Technology |
|---|---|
| Structure & styling | HTML5, CSS3, Bootstrap |
| Interactivity | JavaScript (optionally React, if a component-based build is preferred) |
| Contact form | Formspree, Getform, or EmailJS (static-friendly, no custom backend) |
| Hosting / deployment | GitHub Pages, Netlify, or Vercel |
| Version control | Git / GitHub |

## 9. High-Level Milestones

| Milestone | Deliverable |
|---|---|
| Content & structure | Finalized project list, bios, resume PDF, and information architecture |
| Visual design | Wireframe / layout and color-typography system for all sections |
| Core build | Home, About, Skills, Projects, Contact sections implemented and responsive |
| Case studies | Detailed write-ups for flagship projects (e.g. Final Year Project) |
| QA & polish | Cross-browser and cross-device testing, performance check, dark/light mode |
| Launch | Deployed to public hosting and linked from CV/LinkedIn/GitHub profile |

## 10. Risks

- Scope creep — adding blog/CMS/backend features mid-build, delaying launch
- Time constraints from concurrent Final Year Project and coursework in the final semester
- Content readiness — project descriptions or resume not finalized in time for the build phase
