# **Landing Page Project**  
### _The Odin Project – Foundations Assignment_

---

This is a simple **landing page** built as part of [The Odin Project](https://www.theodinproject.com/) **Foundations** curriculum.  
The goal is to recreate a provided design layout using basic **HTML and CSS**, with freedom to customize:

 - Fonts  
 - Images  
 - Text content  
 - Color schemes  

> _"Style it your way!"_

---

## 📄 **Project Overview**

The landing page features:

- **Hero section** with a bold headline, subtext, image, and a CTA button  
- **Information section** with icons or images and descriptive text  
- **Driver quote section** with a testimonial-style layout  
- **Final call-to-action**  
- **Footer**

---

## 🧠 **Skills Demonstrated**

- Semantic HTML  
- CSS styling and layout  
- Flexbox for responsive structure  
- Git version control (commit early, commit often!)  
- Using `@media` queries for basic responsiveness  

---

## 📌 **Assignment Guidelines**

> **Tip**: Work one section at a time.  
> 1. Structure HTML first  
> 2. Style with CSS (single stylesheet is enough)  
> 3. Be creative – just credit any copyrighted material you use

---

## 🧱 **How I'm Building This Project**

I’m following a **section-by-section** development style — from the **top** (header/hero) to the **bottom** (footer), and I aim to complete each section before moving on to the next.

### Section Workflow:

1. **Top Section (Hero area)**  
   - Build HTML structure first (logo, navigation, heading, subtext, image, CTA button)  
   - Add basic CSS styling  
   - Refine layout with Flexbox  
   - Polish styling (spacing, font size, colors)  
   - **→ Made the image responsive using `@media`** 👇 _(see details below)_

2. ~~**Information Section**~~ → **About Section**  
   - basicly it means the same but made it to **"About" section** to match the header navlink  
   - This section includes a **background image**, section heading, subtext, and **three value cards**:
     - *Individual & Team*  
     - *Tradition & Innovation*  
     - *Passion & Achievement*  
   - Built and styled using Flexbox, with new image assets added to `/images`

3. **Driver Quote Section (Testimonial)**  
   - Labeled as "Driver" in the navigation bar  
   - Features a quote from Lewis Hamilton on joining Ferrari  
   - Image and quote styled side-by-side using Flexbox  
   - Carefully adjusted padding and margins for clean layout  
   - Added supporting image assets to the `/images` directory

4. **Call-To-Action (CTA) Section**  
5. **Footer**

---

## 🤔 **What I Struggled With (and Fixed!)**

### The Problem: Hero Image Wouldn’t Shrink

Even though the project is meant for desktop view, it was really bothering me that the image in the hero section didn’t resize when I shrank the browser window. It was overflowing and felt broken.

### The Fix: Media Queries

I found [this helpful Stack Overflow answer](https://stackoverflow.com/questions/66684482/using-media-for-entire-css) that explained how to use `@media` queries in regular CSS (not just Sass).  
With that, I:

- Set `width: 100%` and `max-width: 700px` for the image  
- Added a `@media (max-width: 768px)` query to:
  - Switch layout direction to column  
  - Center-align text and image  
  - Remove negative margins so the image centers properly

Now the image scales naturally while still looking great on desktop.  
It wasn’t required, but I’m proud of solving it anyway.

---

## 📤 **To-Do**
- [x] Setup project repo and file structure  
- [x] Add header and hero section HTML  
- [x] Style hero section  
- [x] Make image responsive with media queries  
- [x] Build ~~**info section**~~ about section  
- [x] Add testimonial quote (Driver section)  
- [ ] Build footer  
- [ ] Final polish  
- [ ] Push to GitHub  
- [ ] Share with the community!

---

## 🎨 Credits for Assets Used in This Project

I try to credit every asset I use. This section will be updated as I add more.

**Official sources:**
- [Ferrari Official Website](https://www.ferrari.com/)

**Image & content credits:**
- Lewis Hamilton Ferrari image: [Ferrari Store Replica Editorial](https://store.ferrari.com/en-ae/editorial-replica-scuderia-ferrari)  
- Charles Leclerc Monza 2024 selfie: Found via [F1 on X (Twitter)](https://x.com/F1/status/1830260240056717534) — originally shared by Leclerc on Instagram Story  

**Fonts used:**
- Ferro Rosso font: [Download on dafont.style](https://dafont.style/download/ferro-rosso-font.html)  
- Oswald font: [Google Fonts](https://fonts.google.com/specimen/Oswald?query=oswald)  
- Anton font: [Google Fonts](https://fonts.google.com/specimen/Anton)

**Other image references:**
- [Ferrari 125 F1 on Pinterest](https://id.pinterest.com/pin/18647785947355183/)

→ *More credits will be added as needed.*

---

## 📸 Reference Design

This is the landing page reference image provided by The Odin Project:

![Landing Page Preview](https://cdn.statically.io/gh/TheOdinProject/curriculum/81a5d553f4073e593d23a6ab00d50eef8620796d/foundations/html_css/project/imgs/01.png)

---

© The Odin Project 2021 | Made with ❤️ by Krisnaarji | © Scuderia Ferrari Hp F1 Team 2025
