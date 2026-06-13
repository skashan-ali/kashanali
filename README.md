# Kashan Ali CV Portfolio

This repository contains a small static website for showcasing three professional CV profiles:

- DevOps Specialist
- Solution Architect
- CloudOps Specialist

## Project structure

- index.html — landing page with links to the three CV profiles
- cv-devops.html — DevOps-focused curriculum vitae
- cv-cloud-architect.html — cloud architecture and solution design profile
- cv-cloudops.html — cloud operations and platform reliability profile
- noc-logo.png — branding asset used by the site

## Preview locally

Because this is a simple static site, you can preview it by opening the HTML files directly in a browser, or by serving the folder with a local web server.

Example with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Notes

The site uses Tailwind CSS via CDN for styling and is designed to be easy to host on any static hosting platform such as GitHub Pages, Azure Static Web Apps, or Netlify.
