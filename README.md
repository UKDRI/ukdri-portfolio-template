# Professional GitHub Portfolio – Quarto Template

This repository is a **template for creating a professional GitHub Pages site**
using **Quarto**. It is designed to help researchers present their work clearly,
build a narrative CV (“Résumé for Research”), and provide evidence of contributions
for job, fellowship, and funding applications.

The emphasis is on **clarity, structure, and evidence**, not web design.

---

## What this template is for

You can use this site as:
- a **personal research portfolio**
- a **Résumé for Research / narrative CV**
- a place to **show evidence of projects and contributions**
- a lightweight alternative to a traditional academic webpage


This template is intentionally simple and prompt-driven.

---

## Structure of the site

The site includes four main pages:

- **Home** (`index.qmd`)  
  Who you are, what you work on, and why it matters.

- **Projects** (`projects.qmd`)  
  Case studies describing problems, your role, approach, and evidence.

- **Résumé for Research** (`resume.qmd`)  
  A four-module narrative CV aligned with funder expectations:
  1. Contributions to the generation of knowledge  
  2. Contributions to the development of others  
  3. Contributions to the wider research community  
  4. Contributions to broader society  

- **Outputs** (`outputs.qmd`)  
  Publications, talks, software, datasets, and other outputs.

Each page contains **prompts** (HTML comments) to guide what to write.

---

## How to use this template

### 1. Fork the repository
Click **Fork** in the top-right corner of GitHub.

### 2. Edit the content
Open the `.qmd` files and replace the placeholder text.
You can delete the prompt comments once you are finished.

No web development experience is required.

### 3. Publish with GitHub Pages
This repository is configured to publish automatically using **GitHub Actions**.

To enable publishing:
1. Go to **Settings → Pages**
2. Under *Build and deployment*, set **Source** to **GitHub Actions**
3. Save

Your site will be published at:

```

https://<your-username>.github.io/<repository-name>/

````

---

## Local preview (optional)

If you have Quarto installed, you can preview the site locally:

```bash
quarto preview
````

Before pushing changes, it’s good practice to run:

```bash
quarto render
```

---

## Design & customisation

* The site uses a clean Bootstrap theme
* Colours and typography can be customised via `styles.css`
* Navigation tabs are defined in `_quarto.yml`

You can keep it minimal or build on it over time.

---

## License

This material is licensed under a
**Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license.

You are free to reuse and adapt this template, provided you:

* give appropriate credit
* indicate if changes were made
* share derivative works under the same license

---

## A note on intent

This template is designed to reduce friction and anxiety.
If you can answer the prompts, you can build a professional portfolio.


