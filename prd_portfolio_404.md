# Product Requirements Document (PRD)
## Personal Portfolio & Dynamic Profile: The "404 Not Found" Edition

---

### 1. Document Metadata & Overview
* **Product Name:** Personal Portfolio & Dynamic Profile (Error 404 / Human Resource Theme)
* **Product Vision:** To build a uniquely memorable, highly personal web page that subverts traditional corporate portfolio tropes. By framing the landing experience as a "404 Error — Resource Not Found," the site cleverly pivots to reveal that the visitor has actually found *you*—a hybrid thinker blending rigorous Industrial Engineering systems logic with heavy enterprise Mainframe COBOL execution.
* **Target Audience:** 
  * Tech recruiters and engineering managers looking for robust technical reliability.
  * Business, banking, and operations leaders looking for process optimization and systems thinking.
  * Peers, mentors, and future leaders in people development.

---

### 2. Conceptual & Aesthetic Theme
* **The Concept:** 
  * **Hero Header:** Mimics a classic terminal or system error: `< ERROR 404 // RESOURCE NOT FOUND >`
  * **The Twist Subtitle:** `"The page you are looking for cannot be found... because, technically, you're already looking at it."`
* **Aesthetic Direction:**
  * **Typography:** Monospaced fonts (Courier New, JetBrains Mono, or Fira Code) combined with clean technical sans-serif borders.
  * **Color Palette:** Terminal black/dark charcoal background with crisp white and muted amber/terminal-green accent text, giving it an authentic developer aesthetic while remaining polished and legible.
  * **Layout:** Brutalist yet minimalist structural lines, bracketed metadata (`[ ABOUT ]`, `[ CREDENTIALS ]`, `[ CONTACT ]`), and a raw, human portrait slot.

---

### 3. Core Architecture & Tech Stack
* **Frontend:** Next.js (React) or Astro (ensuring lightning-fast static generation and optimal SEO).
* **Styling:** Tailwind CSS with custom monospace configurations and utility classes for retro-terminal styling.
* **Backend, Database & Auth:** Supabase or Firebase (handling secure admin authentication and dynamic data tables).
* **Hosting:** Vercel (seamless deployment and edge performance).

---

### 4. Detailed Functional Requirements

#### A. Public-Facing Visitor Experience (The "404" Interface)
* **F1.1: The Terminal Hero Section**
  * Displays the satirical 404 error text transitioning smoothly into your introduction.
  * Brief biographical punchline: Mainframe COBOL developer by trade, Industrial Engineer by training, exploring futures in banking, business operations, and people development.
* **F1.2: Dynamic Bio & Profile Slot**
  * Clean frame housing a professional or candid photo styled with subtle retro scanlines or minimalist borders.
* **F1.3: Bracketed Sections (CRUD-Linked)**
  * **`[ ABOUT ]`**: Summary of your 4-year Industrial Engineering background and your current enterprise work.
  * **`[ CREDENTIALS & WORKLOAD LOGS ]`**: Tab or list showing certifications, technical stack (COBOL, JCL, DB2), and IE methodologies.
  * **`[ CONTACT ]`**: Direct terminal-style links to LinkedIn, Email, and a resume download link (`[ GET RESUME.LOG ]`).

#### B. Admin / Owner Experience
* **F2.1: Protected Admin Route (`/admin`)**
  * Secure password authentication wall restricting content edits to the site owner.
* **F2.2: Simple CRUD Dashboard**
  * Clean form interface to add, edit, or delete portfolio logs, certifications, and profile copy without modifying code repositories.

---

### 5. Phased Implementation Roadmap
* **Phase 1: Static MVP & Theme Implementation**
  * Build the HTML/CSS/React structure focusing heavily on the 404 terminal styling and typography.
  * Hardcode initial portfolio items and bio copy to test layout responsiveness.
* **Phase 2: Database & Admin Integration**
  * Connect Supabase for data persistence.
  * Build the backend authentication and input forms for dynamic updates.
* **Phase 3: Launch & Refinement**
  * Deploy via Vercel with a custom domain, ensuring optimal performance and mobile responsiveness.
