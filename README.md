# HelioNote API Docs

**HelioNote API Docs** is an imaginary application that I created to showcase my **API documentation skills** using **DITA XML** and **Oxygen XML Editor**.  
The goal was to design a simple, structured, and professional API documentation set with minimal design effort — keeping the layout clean, consistent, and easy to read.  

---
## View the Live Site

You can view the live HTML version of this documentation at:

👉 **https://nenas97.github.io/HelioNote_API_Docs/**

The site is automatically generated from the contents of the `docs/` folder using GitHub Pages.

---
## DITA Elements Used

### Common Topic Elements
- `<topic>` - container for concept/reference/task topics  
- `<title>`- titles for all topics  
- `<shortdesc>` - short description after the title  
- `<p>` - paragraphs (used everywhere)  
- `<section>` - for structuring content inside topics  

### Task Topics (Quickstart, Endpoints)
- `<task>` - wrapper for task-based topics  
- `<taskbody>` - container for task content  
- `<prereq>`- prerequisites (optional)  
- `<context>`- background info before steps  
- `<steps>`- ordered steps block  
- `<step>`- single step  
- `<cmd>`- instruction inside a step  
- `<info>`- extra details within a step  
- `<codeblock>`- showing code inside steps  
- `<result>`- outcome after the steps  
- `<example>`- examples related to the task  

### Reference Topics (Errors, Keys, FAQs, Endpoints)
- `<reference>`- wrapper for structured reference topics  
- `<refbody>`- container for reference content  
- `<section>`- subdivisions inside reference body  
- `<table>`- tabular information (used in errors.dita)  
- `<tgroup>`- table column/row group  
- `<thead>`- table header row  
- `<tbody>`- table body rows  
- `<row>`- table row  
- `<entry>`- table cell  
- `<dl>`- definition list (suggested for FAQs)  
- `<dlentry>`- one Q&A pair  
- `<dt>`- question term  
- `<dd>`- answer definition  

### Reuse & Variables
- `<conref>`- content reuse (pointing to another topic or fragment)  
- `<keydef>`- key definition in the DITA map  
- `<ph keyref="">`- phrase that pulls value from a key  

### Other
- `<ol>` - ordered lists  
- `<ul>`- unordered lists  
- `<b>`- bold text (inline)  
- `<xref>`- cross-references between topics  
- `<image>`- API logo or screenshots  

---

## Custom CSS Styling

Since Oxygen’s default publishing templates had limitations, a **custom CSS override** was created to achieve the desired look and consistency.  
The design is intentionally **minimal** and clean.

### CSS Elements Used
- `body`- page layout (background, text, font)  
- `.home-button`- styled "Home" button for navigation  
- `main, #content, .body, .map, .topic, .reference, .task, .concept` - main content container styles  
- `table, th, td` - table formatting (borders, padding, alignment)  
- `pre` - code block background, padding, and scroll behavior  
- `.codeph` - inline code styling (highlighted monospace text)  
- `h1`- centered, bold titles  
- `h1 + p, h2 + p, h3 + p`- reduced spacing after headings  

---
