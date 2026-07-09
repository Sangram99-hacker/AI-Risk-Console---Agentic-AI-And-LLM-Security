========================================================
 AI RISK CONSOLE
 OWASP Top 10 for LLMs & MAESTRO Agentic Threat Modeling
========================================================

WHAT THIS IS
------------
A single-file, interactive web app for learning AI/LLM and
agentic AI security. It covers:

  1. OWASP Top 10 for LLM Applications (2025 edition)
  2. MAESTRO - the Cloud Security Alliance's 7-layer threat
     modeling framework for agentic AI systems
  3. 8 common agentic architecture patterns and their
     signature threats
  4. A hands-on "Threat Modeling Workbench" that generates
     a live threat report based on your own system's
     architecture and in-scope MAESTRO layers

No login, no backend, no data collection. Everything runs
entirely in the browser on your own device.


FILE
----
index.html   <- open this file, that's it.


HOW TO USE IT
-------------
1. Double-click index.html (or open it from
   your browser's File > Open menu). No server or install
   needed.
2. Use the top navigation (or the hamburger menu on mobile)
   to move between: Overview, OWASP Top 10, MAESTRO Layers,
   Agent Patterns, and Threat Workbench.
3. Click any risk / layer / pattern card to expand it, then
   click "Reveal mitigation plan" to see the fix.
4. In the Workbench tab, describe your system (name,
   architecture pattern, which MAESTRO layers apply) and
   click "Generate threat model" for a report you can copy
   as plain text.


TECHNOLOGIES / PROGRAMMING LANGUAGES USED
------------------------------------------
- HTML5            Page structure and semantic markup
- CSS3              All styling, layout, responsive design,
                     animations and transitions (plain CSS,
                     using CSS custom properties/variables
                     for theming - no CSS framework used)
- JavaScript (ES6+)  All interactivity: rendering the content
                     from data, expand/collapse behavior, tab
                     navigation, filters, and the Threat
                     Workbench report generator (vanilla JS -
                     no external JS framework or library)

External resources:
- Google Fonts (Space Grotesk, IBM Plex Mono, Inter) loaded
  via a <link> tag for typography. Requires internet access
  the first time fonts are fetched; the rest of the app
  works fully offline.

No build tools, package managers, or servers are required.
It is a single static .html file that bundles its own CSS
and JavaScript inline.


BROWSER SUPPORT
----------------
Any modern browser: Chrome, Edge, Firefox, Safari (desktop
or mobile). Responsive down to small mobile screens.


CONTENT SOURCES
----------------
Content is adapted from and should be cross-checked against
the primary sources for anything used in a real assessment:

- OWASP GenAI Security Project - Top 10 for LLM Applications
  https://genai.owasp.org/llm-top-10/

- Cloud Security Alliance - Agentic AI Threat Modeling
  Framework: MAESTRO (Ken Huang)
  https://cloudsecurityalliance.org/blog/2025/02/06/agentic-ai-threat-modeling-framework-maestro


DISCLAIMER
----------
This is an educational reference tool built for learning and
awareness. It is not a substitute for a formal security
assessment, a certified threat-modeling engagement, or the
official OWASP / CSA publications.
