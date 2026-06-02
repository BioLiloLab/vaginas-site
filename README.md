# Artist's Vaginas

**Artist's Vaginas** is an archival website originally created in 2019 to document an artistic experiment developed by **BioLiloLab** around microbiology, collaboration, and intimate bodily ecologies.

The project emerged from a meeting/workshop on **microbiology for artists**, where a group of participants — all women — gathered to learn and experiment with basic microbiology techniques. During the encounter, one of the participants was experiencing a *Candida albicans* infection. Moved by curiosity, opportunity, and collaboration, the group decided to collect vaginal secretion and cultivate it in a Petri dish, observing how this invisible intimate microbiota would grow, express itself, and become visually present.

From this process, the project **Artist's Vaginas** took shape: not as a medical investigation, but as an artistic and collective experiment in making visible the microorganisms that inhabit the body. The work invited women artists to access, cultivate, and observe their own intimate microbiota through simple scientific tools, shifting the body from an object of representation into a living site of inquiry.

The project was exhibited as part of the **MIT Bio Summit** in 2019.

This website is kept online as a historical archive and documentation of BioLiloLab's visual identity, artistic research, and bioart practice at that time.

## About this repository

This repository contains the restored Jekyll website for **Artist's Vaginas**.

The site is preserved as a historical/artistic archive. The goal of this restoration is not to redesign the project, but to keep the original 2019 website accessible online.

## Routes

* English version: `/en`
* Portuguese version: `/pt`
* Root `/` redirects to `/en`

## Local development

Run the site locally with:

```bash
jekyll serve --baseurl "/vaginas-site" --port 4447
```

Then open:

```text
http://127.0.0.1:4447/vaginas-site/en
http://127.0.0.1:4447/vaginas-site/pt
```

For local root testing, you can also run:

```bash
jekyll serve --baseurl "" --port 4447
```

## Deployment

The site is configured for GitHub Pages as a project page:

```yaml
url: "https://biolilolab.github.io"
baseurl: "/vaginas-site"
```

Production URLs:

```text
https://biolilolab.github.io/vaginas-site/
https://biolilolab.github.io/vaginas-site/en
https://biolilolab.github.io/vaginas-site/pt
```

## Restoration note

This repository was lightly restored to make the original Jekyll website work again on GitHub Pages. The restoration focused on path handling, language routing, and small navigation fixes while preserving the original content, layout, images, and 2019 BioLiloLab visual identity.
