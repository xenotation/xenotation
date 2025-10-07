# 🧩 Nikola Stoyanov — Artist, Developer, and Infrastructure Theorist

**Contemporary artist + technologist from Bulgaria** working across visual culture, cloud architecture, and digital infrastructures.  
This GitHub space hosts my ongoing experiments in **web-based exhibitions**, **art–tech platforms**, and **critical software infrastructures**.

---

## 🧠 About Me

I’m **Nikola Stoyanov**, a **Bulgarian artist, philosopher, and FinTech analyst** based between Varna and Sofia.  
My work bridges the fields of **contemporary art**, **critical theory**, and **software infrastructure**, focusing on how technical systems shape cultural production.

My current interests include:
- Cloud automation & data visualization in artistic contexts  
- Static-site architectures (**Hugo**, **Netlify**, **Cloudflare**)  
- Integrating **Decap CMS**, **GitHub Actions**, and **Stream APIs** for hybrid film-art platforms  
- The aesthetics of **infrastructure**, **scrap materiality**, and **automation**  

---

## ⚙️ Active Projects on GitHub

### 🎬 [Plankton](https://plankton.bg)
A curated film platform for independent cinema in Bulgaria.  
- Built with **Hugo**, **Cloudflare Stream**, and **Decap CMS**  
- Features **secure tokenized video playback**, **geo-blocking**, and **editorial workflows**  
- Source includes **custom Hugo shortcodes**, **responsive layouts**, and **Cloudflare API automation**

### 🧱 [New Degeneration](https://newdegeneration.xyz)
My digital portfolio and philosophical research node.  
- Minimalist front-end using **Hugo**, **pure CSS grid layouts**, and **typographic systems**  
- JSON-LD metadata for **Person**, **ExhibitionEvent**, and **Movie** schema  
- Automated deployment with **Netlify** + **Cloudflare DNS**

### ☁️ Azure Learning Resources
A set of long-form technical lessons based on **Tek Experts** and **Microsoft Azure** training materials.  
- Topics: Durable Functions, App Service internals, Docker on Linux, VNet integration, and Managed Identity  
- Each module written in **plain text**, optimized for **live teaching and translation**

---

## 🧩 Tech Stack

| Category | Tools / Frameworks |
|-----------|--------------------|
| **Frontend / Static Sites** | Hugo, Vanilla CSS, HTML5 |
| **CMS & Content** | Decap CMS (Netlify CMS), Cloudflare Stream API |
| **Deployment / CI** | Netlify, GitHub Actions |
| **Cloud & Infrastructure** | Microsoft Azure (App Service, ACR, Functions) |
| **Video Delivery** | Cloudflare Stream, HLS playback via Video.js |
| **SEO / Metadata** | JSON-LD, Open Graph, canonical tags |
| **Languages** | HTML, CSS, JavaScript, Markdown, YAML, TOML |

---

## 🧰 Example: Hugo + Cloudflare + CMS Workflow

```mermaid
graph TD
  A[Author post in Decap CMS] --> B[Commit to GitHub main branch]
  B --> C[GitHub Actions: Refresh Cloudflare Stream token]
  C --> D[Hugo Build & Minify]
  D --> E[Netlify Deploy + Cloudflare CDN]
