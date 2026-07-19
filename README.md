# Michael Angelo Yoga

A personal website for yoga instructor Michael Angelo.

## Structure

- `index.html` — Home page
- `about.html` — Instructor bio
- `classes.html` — Class schedule and offerings
- `personal-training.html` — Personal training and private sessions
- `yoga.html` — About the yoga practice
- `testimonials.html` — Student testimonials
- `contact.html` — Contact form and information
- `css/style.css` — Shared styles
- `js/main.js` — Mobile navigation and contact form handling

## Deployment

This site is designed for **Cloudflare Pages**. Connect this repository in the Cloudflare dashboard and use the default static site settings:

- **Build command:** (none)
- **Build output directory:** `/` (root)

## Local Preview

Open any HTML file directly in a browser, or serve the folder with a simple static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Contact Form

The contact form currently displays a success message without sending email. To make it functional, connect the form action to a service such as Formspree, Netlify Forms, or a Cloudflare Worker.

## License

All rights reserved.
