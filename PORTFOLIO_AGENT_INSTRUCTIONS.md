# Google Jules Instructions: Personal Portfolio Website Implementation

## Objective

You are Google Jules, executing directly inside an already initialized repository. Your task is to generate, structure, and prepare the deployment of a modern, high-performance personal brand and portfolio website for **Kamal Decadova Bramwell (Kam)** hosted on **GitHub Pages** with the custom domain **kamalbramwell.com**.

---

## 1\. Context & Profile Information

- **Name**: Kamal Decadova Bramwell (Kam)  
- **Professional Title**: Software Architect & Senior Mobile Engineer  
- **Core Specialties**:  
- **Email**: peaks\_barques0c@icloud.com  
  - Kotlin Multiplatform (KMP) & Compose Multiplatform (CMP)  
  - Android (Jetpack Compose, Kotlin, Coroutines/Flow)  
  - iOS (Swift, SwiftUI, Native Interop)  
  - Clean Architecture, Test-Driven Development (TDD with manual test doubles), Trunk-Based Development  
  - End-to-End Encryption (E2EE), Cryptographic Protocol Design (X3DH, Double Ratchet)  
- **Featured Projects**:  
  1. **Spaces (2026)**: Community-focused social networking application built with Kotlin Multiplatform, Jetpack Compose, SQLDelight, and Firebase Firestore (Live on iOS App Store & Google Play).  
  2. Personalities (2026): Mobile application calculating and visualizing personality blends based on MBTI assessments and astrological inputs, featuring brutalist UI design (Compose Multiplatform).  
  3. NADA \- Not Another Dating App (2023): Jetpack Compose and TDD exploration using mock data; architectural foundation for Spaces.  
  4. Fyeo (2019/2026): Privacy-first messaging application featuring clean-room End-to-End Encryption and modern Material 3 Jetpack Compose architecture.  
- **Online Profiles & Links**:  
  - GitHub: https://github.com/kdbramwell  
  - Threads (Optional): @kam.palmer.876  
  - Domain: kamalbramwell.com

---

## 2\. Technical Stack & Constraints

- **Architecture**: Single-page static website (JAMstack).  
- **Styling**: Strictly semantic HTML5 and Tailwind CSS (via official Tailwind CDN script) with clean typography, modern dark/light contrast, and subtle micro-interactions.  
- **Icons**: Lucide Icons or Heroicons (via CDN / inline SVG).  
- **Zero-Dependency Runtime**: Ensure fast loading with no bloated framework runtime requirements.  
- **Hosting**: GitHub Pages (main branch root deployment).

---

## 3\. Step-by-Step Agent Execution Plan

### Step 1: Create and Populate Project Files

1. Within the root of the existing repository, create the following structure and files:  
     
   ├── index.html  
     
   ├── CNAME  
     
   ├── assets/  
     
   │   ├── css/ (optional custom styles)  
     
   │   ├── img/ (project screenshots / avatar placeholder)  
     
   │   └── favicon.svg  
     
2. Populate CNAME with the apex custom domain:  
3. Create and populate DEPLOYMENT.md with the DNS and GitHub Pages configuration details provided in Section 4\.  
     
   kamalbramwell.com

### Step 2: Implement index.html Structure

Generate semantic, fully accessible HTML5 markup containing the following sections:

1. **\<head\> Setup & SEO Metadata**:  
     
   - Title: Kamal Bramwell | Software Architect & Senior Mobile Engineer  
   - Responsive viewport, meta description, and keywords (Kotlin Multiplatform, Android, iOS, Software Architecture).  
   - Open Graph (OG) tags (og:title, og:description, og:url, og:type=website, og:image).  
   - Tailwind CSS CDN and Google Fonts (Inter / JetBrains Mono).

   

2. **Navigation Bar**:  
     
   - Clean header with name logo (Kamal Bramwell / KB) and smooth-scroll anchors:  
     - About  
     - Projects  
     - Skills & Philosophy  
     - Contact  
   - Optional dark mode toggle or refined dark-slate palette by default.

   

3. **Hero Section**:  
     
   - Prominent headline: Software Architect & Senior Mobile Engineer specializing in Kotlin Multiplatform and cross-platform native experiences.  
   - Concise value proposition: Building high-performance mobile apps, clean-room architectures, and developer-first products.  
   - Primary Call-to-Actions (CTAs):  
     - View Projects (anchor link to \#projects)  
     - Get in Touch (mailto or anchor to \#contact)

   

4. **Featured Projects Section (\#projects)**:  
     
   - Render structured project cards with badges, architecture highlights, and links:  
     - **Spaces \- Gated Communities (2026)**: A community-based structure combining Reddit-like discussions with gender-gated topics. Built with Kotlin and Compose Multiplatform for Android and iOS, backed by Firebase (Auth, Firestore, Crashlytics, Remote Config). Links: Google Play (Spaces for Android), Apple App Store (Spaces for iOS). Reference screenshot assets.  
     - Personalities (2026): Compose Multiplatform application calculating and visualizing personality blends combining MBTI archetypes with astrological zodiac inputs, using a brutalist design system.  
     - NADA \- Not Another Dating App (2023): An early dive into Jetpack Compose and Test-Driven Development (TDD) using mock data, whose architectural foundation and components were imported into the Spaces project. Link: android-dating GitHub repository.  
     - Fyeo \- Confidential Instant Messaging (2019 / Modernized 2026): Privacy-first messenger preventing screenshots, offering full media control, and pioneering blurred message previews. Modernized with clean-room E2EE architecture (X3DH, Double Ratchet) and Jetpack Compose. Link: Google Play.

   

5. **Technical Skills & Engineering Philosophy (\#skills)**:  
     
   - Grouped skill chips:  
     - *Mobile & Platforms*: Kotlin Multiplatform, Android (Jetpack Compose), iOS (SwiftUI), Compose Multiplatform.  
     - *Architecture & Security*: Clean Architecture, E2EE Cryptography, State Machines, SQLDelight, Firebase.  
     - *Practices & Tooling*: Trunk-Based Development, TDD / Manual Fakes, CI/CD GitHub Actions, Jules / Antigravity Agentic Workflows.

   

6. **About & Background (\#about)**:  
     
   - Concise bio summarizing architectural expertise, solo product shipping cadence, and passion for elegant cross-platform engineering.

   

7. **Footer & Contact Section (\#contact)**:  
     
   - Direct email contact button (mailto:peaks\_barques0c@icloud.com).  
   - Social links with clean SVGs: GitHub, Threads, LinkedIn.  
   - Copyright notice (© 2026 Kamal Bramwell. All rights reserved.).

---

## 4\. DNS & GitHub Pages Deployment Guide

1. **DNS Apex (@) Configuration**: Create 4 A records for kamalbramwell.com:  
     
   - 185.199.108.153  
   - 185.199.109.153  
   - 185.199.110.153  
   - 185.199.111.153

   

2. **Subdomain (www) Configuration**: Create a CNAME record for www:  
     
   - Name: www  
   - Target: kdbramwell.github.io

   

3. **GitHub Repository Settings**:  
     
   - Navigate to **Settings** → **Pages**.  
   - Source: Deploy from a branch → Branch: main → Folder: / (root).  
   - Custom Domain: kamalbramwell.com.  
   - Ensure **Enforce HTTPS** is enabled after DNS validation.

---

## 5\. Verification Checklist

Before completing the task, the agent must verify:

- [ ] index.html is valid HTML5 and renders cleanly across mobile, tablet, and desktop viewports.  
- [ ] CNAME file exists in the root directory and contains kamalbramwell.com.  
- [ ] All internal navigation links (\#about, \#projects, \#skills, \#contact) scroll smoothly to target IDs.  
- [ ] Meta tags (title, description, OG tags) are properly configured for social previews.  
- [ ] No broken asset links or external script console errors.

