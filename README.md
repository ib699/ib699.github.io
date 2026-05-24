# Ibrahim Sedighi Portfolio

A personal portfolio website for Ibrahim Sedighi, focused on backend engineering, distributed systems, Linux infrastructure, cloud-native security, and systems programming.

The site is built as a lightweight static page and is suitable for hosting on GitHub Pages.

## Overview

This portfolio highlights:

- Backend engineering experience with Go, Gin, PostgreSQL, GORM, RBAC/ABAC, and Open Policy Agent
- Distributed systems work with DDS, eProsima Fast DDS, and real-time communication pipelines
- Infrastructure experience with Kubernetes, Docker, Traefik, NGINX, Linux, QEMU, and KVM
- Featured projects in security, IoT, real-time AI, and Linux environment engineering
- Contact links for email, GitHub, and LinkedIn

## Tech Stack

- HTML5
- CSS3
- Google Fonts
- GitHub Pages

The project currently uses a single `index.html` file with embedded styles, so no build step or package manager is required.

## Project Structure

```text
.
|-- index.html
`-- README.md
```

## Running Locally

Open `index.html` directly in a browser:

```text
index.html
```

You can also serve the folder with any static file server, for example:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This repository can be deployed with GitHub Pages.

1. Push the repository to GitHub.
2. Open the repository settings.
3. Go to **Pages**.
4. Set the source branch to `main` or `master`.
5. Select the root folder.
6. Save the configuration.

For a user or organization site named `ib699.github.io`, GitHub Pages will publish it at:

```text
https://ib699.github.io
```

## Customization

Update `index.html` to change:

- Personal bio and headline
- Project descriptions
- Technical skills
- Email address
- GitHub and LinkedIn links
- Colors and visual styling in the embedded CSS

## License

No license has been specified yet. Add a license file if you want to define how others may use or modify this project.
