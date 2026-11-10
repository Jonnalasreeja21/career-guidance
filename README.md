# Career Guidance

A static, multi-page career guidance prototype for students exploring technology and cybersecurity roles. The project uses HTML, CSS, JavaScript, and Bootstrap to present a landing page, a simple sign-in flow, interest choices, and career information pages.

> This is a front-end learning project. The sign-in screen only sets a browser `sessionStorage` flag; it does not authenticate users or protect content. The contact form is visual only and does not submit to a service.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Landing page with overview and contact form layout |
| `login.html` | Demo sign-in screen |
| `intereste.html` | Career interest cards |
| `tech.html` | Technology and IT career descriptions |
| `cyber.html` | Cybersecurity career descriptions and roadmap |

The interest page also links to `data.html`, `design.html`, `business.html`, and `science.html`; those pages are not present in the current repository.

## Run locally

No build step or package installation is required. Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/Jonnalasreeja21/career-guidance.git
cd career-guidance
```

You can also serve the files over HTTP with Python:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). Select **Sign In**, enter any values, and submit to view the interest page. The demo does not validate the entered credentials.

Bootstrap and Google Fonts are loaded from external CDNs, so those assets require an internet connection.

## Built with

- HTML
- CSS
- JavaScript
- Bootstrap 4.3.1

## Project structure

```text
career-guidance/
├── index.html
├── login.html
├── intereste.html
├── tech.html
├── cyber.html
└── README.md
```

## Current scope

This repository is a static prototype. It has no backend, database, real authentication, personalized recommendation engine, or working contact submission. The career descriptions are informational examples and should not be treated as individualized career advice.

## License

No license file is currently included. Contact the repository owner before reusing or redistributing this project.
