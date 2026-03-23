# CCMI Systems & Data Team Site

> Professional team dashboard integrating Power Apps, Power BI, documentation, and production system access.

[![HTML5](https://img.shields.io/badge/HTML5-Structure orange?style=flat square&logo=html5)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-Styling blue?style=flat square&logo=css3)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript Interactivity yellow?style=flat square&logo=javascript)](https://developer.mozilla.org/en US/docs/Web/JavaScript)

---

## Overview

The CCMI Systems & Data Team Site is a professional, custom built dashboard designed to consolidate team resources, tools, and workflows in a single integrated hub. Developed by Naadir D for the CCMI team, this application streamlines access to Power Apps, Power BI reports, documentation, code snippets, and production systems.

The site provides a centralized platform for team collaboration, reducing context switching and improving efficiency. It features embedded Microsoft Power Applications, responsive design, toggleable sidebar navigation, and quick links to critical production systems.

---

## Features

### Power Apps Integration
- Embedded internal CCMI Power Apps for team workflows
- One column and two column layout support
- Launch apps directly or in new tabs
- Developer versions available (restricted access)
- Interactive app selector dropdown

### Power BI Reports
- Real-time embedded Power BI reports and dashboards
- Expandable/collapsible report sections
- Key dashboards: Report/Dataflow Finder, CCMI Team Summary
- Interactive analytics and drill-down capabilities
- Full-screen viewing options

### Documentation & Resources
- Centralized access to CCMI documentation
- Curated code snippet library for common solutions
- Knowledge base for team reference
- Easy copy to clipboard functionality

### Additional Features
- CCMI Gen AI Assistant integration (requires API key)
- Quick links to production systems (Depot, MySAP, Success Factors, ServiceNow)
- Formatted date copy utility
- Responsive sidebar navigation
- Dark theme optimized UI
- Font Awesome icon library
- Professional branding with CCMI logo

---

## Screenshots

> Drop screenshots into `screens/` and reference them below.

![CCMI Team Site](images/demoscreen.jpg)

---

## Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge)
- Access to internal CCMI Power Apps and Power BI reports
- (Optional) Google Gemini API key for AI Assistant feature

### Installation

```bash
git clone https://github.com/Naadir-Dev-Portfolio/Website-ccmi-team-site.git
cd Website-ccmi-team-site
# Serve with a local web server
python -m http.server 8000
```

Navigate to `http://localhost:8000` in your browser.

### Configuration

1. Update embedded Power Apps iframes with your Power Apps URLs
2. Configure Power BI report URLs in the Power BI page sections
3. Customize quick links to your production systems
4. Update team logo and branding in the sidebar
5. Add your API key for the Gen AI Assistant (optional)

### Deployment

Deploy to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Azure Static Web Apps
- Corporate web server

---

## Tech Stack

- HTML5, Semantic markup and structure
- CSS3, Modular stylesheets (global, menu, hero, content, carousel, Power Apps, Power BI)
- Vanilla JavaScript (ES6), Dynamic interactions and iframe management
- Font Awesome, Icon library
- Microsoft Power Apps, Embedded applications
- Microsoft Power BI, Embedded reports
- Streamlit API, Gen AI Assistant integration

---

## Navigation

**Sidebar Menu:**
- Home, Main dashboard
- Power Apps, CCMI applications
- Power BI Reports, Analytics and dashboards
- Documentation, Knowledge base
- Code Snippets, Reusable solutions
- Gen AI Assistant, AI powered support
- Production Systems, Quick links to enterprise tools

---

## File Structure

```
Website-ccmi-team-site/
├── index.html
├── page_power_apps.html
├── page_power_bi.html
├── page_documents.html
├── page_snippets.html
├── css/
│   ├── global_styles.css
│   ├── additional_menu_styles.css
│   ├── additional_hero_styles.css
│   ├── main_content_styles.css
│   ├── additional_carousel.css
│   └── page_power_apps.css
├── images/
│   ├── teamlogo3.png
│   └── demoscreen.jpg
└── icons/
    ├── menu-icon-home.png
    ├── menu-icon-papp.png
    ├── menu-icon-pbi.png
    ├── menu-icon-doc.png
    ├── menu-icon-snippet.png
    └── menu-icon-ai.png
```

---

## Key Features

- **Responsive Design**, Adapts to desktop, tablet, and mobile
- **Modular CSS**, Component based stylesheets for maintainability
- **Dynamic JavaScript**, Menu toggles, iframe management, state persistence
- **Professional UI**, Clean, modern interface with consistent branding
- **Integration Hub**, Centralized access to all team tools
- **Quick Access**, Shortcut buttons to frequently used systems
- **Performance**, Lightweight, fast loading interface

---

## Related Projects

- [Streamlit AIQuizbot](https://github.com/Naadir Dev Portfolio/Streamlit AIQuizbot)
- [Streamlit ccmi genai](https://github.com/Naadir Dev Portfolio/Streamlit ccmi genai)
