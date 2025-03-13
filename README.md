# Emily’s 101 Travels Agent Site

A modern, responsive web application for planning magical Disney vacations. This project empowers users to explore travel packages, submit booking forms, and interact with travel agents. It’s built with a focus on performance, accessibility, and maintainability. The codebase serves as both a business solution and a technical reference for best practices in modern web development.

---

## Table of Contents

- [Emily’s 101 Travels Agent Site](#emilys-101-travels-agent-site)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
    - [MVP](#mvp)
    - [Post-MVP Enhancements](#post-mvp-enhancements)
  - [Tech Stack](#tech-stack)

---

## Features

### MVP

- **Landing Page:** Engaging, Disney-themed entry point.
- **Gallery:** Image gallery with low-resolution placeholders and lazy-loading of high-resolution images.
- **Testimonials & About:** Display customer testimonials and detailed travel agent information.
- **Booking Form:** User-friendly form (powered by Google Forms) for trip inquiries, capturing contact details, vacation dates, budget, and preferences.
- **Contact Page:** Direct contact via email (integrated with Gmail or mailto links).
- **Responsive Design:** Fully optimized for desktop and mobile experiences.

### Post-MVP Enhancements

- Individual agent dashboards and profile pages.
- Integration with external APIs (YouTube, ThemeParks, Weather, Disney).
- Automated PDF itinerary generation with Disney branding.
- Enhanced reporting and analytics.
- User authentication with Auth0.
- Agent dashboard for managing multiple bookings.
- Itinerary builder incorporating Disney attraction information.
- Review and rating system for customer feedback.

---

## Tech Stack

- **Frontend:**  
  - HTML, CSS, TypeScript, React, and Vite  
- **Styling & Design:**  
  - CSS
- **Testing:**  
  - Playwright (for end-to-end testing)  
  - Jest and React Testing Library (for unit and integration tests)  
- **Linting & Code Quality:**  
  - ESLint with an extended configuration for React and TypeScript  
- **Deployment:**  
  - Netlify or Vercel for continuous deployment from GitHub  
- **APIs & Integrations:**  
  - Google Forms for booking submissions  
  - External APIs for weather, YouTube, Disney info, etc.  
- **Backend (Future):**  
  - Node.js (or a serverless solution) with Express/NestJS  
  - PostgreSQL (with Prisma ORM) for managing agents, clients, and assignments

---

