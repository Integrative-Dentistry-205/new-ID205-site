# Integrative Dentistry Website

A modern, responsive, and free-flowing custom website for Integrative Dentistry, a holistic dental practice located in Seattle, WA.

## Overview

This repository contains the front-end codebase for the practice's redesigned web presence. The site was built from scratch to replace the previous template, prioritizing a smooth, interactive user experience with custom animations and specialized section scrolling to ensure a clean, uncluttered interface.

## Tech Stack

*   **HTML5:** Semantic structure, including the updated "About Us" and service pages.
*   **CSS3:** Custom styling, responsive layouts, and animations. Features customized overflow handling to ensure content remains cleanly bounded within sections without visible scrollbars.
*   **JavaScript:** Interactive elements, layout manipulation, and dynamic user experience enhancements.

## Key Features

*   **Modern UI/UX:** A free-flowing layout designed to present holistic dentistry services in a welcoming, highly polished format.
*   **Custom Scrolling & Animations:** Tailored section behaviors that keep longer content contained perfectly within section borders while hiding native browser scrollbars.
*   **Fully Responsive:** Optimized across desktop, tablet, and mobile devices.

## Getting Started

To view the site locally:
1. Clone this repository to your local machine.
2. Open `index.html` in your preferred web browser.
3. No build tools or package managers are required for this static front-end setup.

## Deployment

This codebase consists of static files (HTML, CSS, JavaScript) and does not require a backend server or database environment. It can be deployed to almost any web host.

**Option A: Standard Web Hosting (cPanel, standard hosts, etc.)**
1. Access your web host's File Manager or connect via FTP.
2. Upload the contents of this repository directly into the `public_html` (or equivalent root) folder for `integrativedentistry.com`.

**Option B: GitHub Pages**
Since this repository is hosted on GitHub, you can deploy it for free directly from the repository:
1. Navigate to the repository **Settings** on GitHub.
2. Select **Pages** from the left-hand sidebar.
3. Under the **Build and deployment** source, select `Deploy from a branch`.
4. Choose the main branch and save. 

## Maintenance Notes

When updating section content, ensure that any new text blocks do not break the custom section borders. The CSS is configured to manage overflow silently, so preview lengthy content additions locally to ensure the layout remains intact.
