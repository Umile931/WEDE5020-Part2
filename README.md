# WEDE5020 Part 1 - Cape Town Coffee Co Website

Student Number: ST10524342
GitHub Repo: https://github.com/Umile931/WEDE5020-Part1.git

## 1\. Project Overview

Cape Town Coffee Co is a fictional artisan coffee brand based in Long Street, Cape Town. This website was created for WEDE5020 POE Part 1 to establish an online presence and increase customer enquiries (Figma, 2024).

The website consists of 5 pages: Home, About, Menu (products), Order (enquiry) and Contact.

## 2\. Website Goals

* Increase brand visibility in Cape Town CBD
* Generate online orders via enquiry form
* Provide menu, pricing and location information
* Improve user experience with clear navigation

## 3\. Sitemap and Folder Structure

WEDE5020\_Part1\_ST10524342/
│
├── index.html
├── about.html
├── products.html
├── enquiry.html
├── contact.html
├── README.md
├── css/
│ └── style.css
├── js/
│ └── script.js
└── images/
└── (3x coffee images from Pexels, 2024)

## 4\. Design Choices and Tools Used

Wireframes were created using Balsamiq (Balsamiq, 2024) to plan the layout before coding. This helped define the header, navigation, hero section and footer.

High-fidelity mockups were designed in Figma (Figma, 2024) to test colour scheme and typography.

Stock images for the hero and products were sourced from Pexels (Pexels, 2024) under free license.

HTML5 semantic structure was validated using documentation from W3Schools (W3Schools, 2024).

Version control and hosting was managed via GitHub (GitHub, 2024) with descriptive commits.

## 5\. Features Implemented (Part 1)

* Semantic HTML5: header, nav, main, footer
* Navigation links using correct.html extensions (not.html.txt)
* Responsive meta viewport tag
* Contact form with required fields
* External links to CSS and JS

## 6\. AI Usage Disclosure

The initial boilerplate for header and navigation was generated with AI assistance (OpenAI, 2024). The code was then manually edited to add comments, content depth and fix file extensions. Screenshots of prompts are included in Annexe D of the proposal document.

## 7\. GitHub Commit History

This shows how I committed more often as per feedback:

* feat: create initial file structure with index.html
* feat: add header and navigation with comments
* feat: add about page with company story and team
* feat: add products page with menu pricing
* feat: add enquiry form and contact page with map
* fix: correct file extensions from.html.txt to.html
* docs: update README to match proposal with Harvard referencing
* docs: add AI disclosure with in-text citations
* feat: add content depth to all pages

## 8\. How to Run

1. Extract ZIP
2. Double-click index.html
3. It will open in browser (Chrome/Edge) as a proper HTML Document, not Text Document
4. Click navigation to test all 5 pages

## 9\. References - Harvard Style (All cited in-text above)

Balsamiq. (2024). Balsamiq Wireframes. \[online] Available at: https://balsamiq.com \[Accessed 1 Sep 2026].

Figma. (2024). Figma Design Tool. \[online] Available at: https://www.figma.com \[Accessed 1 Sep 2026].

GitHub. (2024). GitHub Documentation. \[online] Available at: https://docs.github.com \[Accessed 1 Sep 2026].

OpenAI. (2024). ChatGPT. \[online] Available at: https://chat.openai.com \[Accessed 1 Sep 2026].

Pexels. (2024). Free Stock Photos. \[online] Available at: https://www.pexels.com \[Accessed 1 Sep 2026].

W3Schools. (2024). HTML Tutorial. \[online] Available at: https://www.w3schools.com/html/ \[Accessed 1 Sep 2026].

## 10\. Screenshots Evidence

* Wireframes: See Proposal Document pages 4-6
* File extensions: Screenshot of folder showing Type = HTML Document
* GitHub commits: Screenshot of GitHub commit history with descriptive messages



\---

\## WEDE5020 Part 2 - 18 Sept 2026 - ST10524342



\### 1. Changelog (What changed from Part 1 feedback)

\- Added alt text to all images

\- Fixed navigation links

\- Created external style.css

\- Linked style.css to all 5 pages: index.html, about.html, products.html, enquiry.html, contact.html



\### 2.1 External Stylesheet

style.css created in root folder, linked with <link rel="stylesheet" href="style.css">



\### 2.2 Base

\* {margin:0 padding:0 box-sizing:border-box} body background #faf6f1



\### 2.3 Typography

h1 2.5rem weight 700, h2 2rem, p 1rem line-height 1.6, font Arial sans-serif



\### 2.4 Layout

nav uses display:flex gap:2rem, main uses display:grid grid-template-columns:2fr 1fr



\### 2.5 Visual

nav bg #3b2112, hover #f5c16c, button shadow 0 2px 4px, border-radius 6px, img max-width 100%



\### 3.1 Media Queries

@media max-width 1024px grid becomes 1fr, @media max-width 768px nav column h1 1.8rem



\### 3.2 Relative Units

Used rem, %, fr - not px for layout



\### 3.3 Responsive Images

img max-width:100% height:auto



\### 3.4 Testing

Tested on Chrome DevTools: Desktop 1200px, Tablet 768px, Mobile 360px - Screenshots in folder



\### 4. References

W3Schools CSS, MDN Web Docs







