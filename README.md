# SnabbWebb Website

**SnabbWebb** is a professional, full-stack web presence for a Swedish web-design service. The project pairs clear service messaging with reusable Django architecture and interactive client examples, demonstrating the ability to build a polished website that supports a real business goal.

## Overview

The site presents affordable, professional website services for small businesses. It guides visitors from service discovery to concrete portfolio examples and contact information, with focused pages for service tiers, maintenance, and projects.

## Features

- **Business-focused homepage** — explains SnabbWebb’s offering and provides direct contact details.
- **Service presentation** — communicates basic website packages, premium custom solutions, and technical maintenance.
- **Project showcase** — offers client-style examples that demonstrate possible website directions.
- **Interactive examples** — includes tailored templates for a pizzeria, hair salon, and construction company.
- **Structured navigation** — separates services, projects, and contact content through dedicated Django routes.
- **Reusable page system** — applies shared layouts and template inheritance for a consistent visual experience.
- **Static asset management** — organizes branding, images, styling, and visual content through Django’s static-file system.

## Technical Highlights

| Area | Implementation |
| --- | --- |
| Framework | Django 5 |
| Language | Python |
| Front end | HTML, CSS, Django templates, and responsive components |
| Database | SQLite |
| Site architecture | Dedicated Django apps for the main website and project examples |
| Content delivery | Template inheritance, URL routing, and Django static files |
| Deployment tooling | Gunicorn and WhiteNoise included in project dependencies |

## What This Project Demonstrates

- Building a public-facing digital product with a clear commercial purpose
- Translating a business service offering into a focused user journey
- Designing reusable server-rendered templates with Django
- Structuring a multi-page application with clean route separation
- Creating portfolio examples that make an abstract service tangible
- Organizing front-end assets and content within a maintainable Django project
- Balancing visual presentation with practical business communication

## Project Structure

```text
snabbwebb-website/
├── main/                 # Core site pages, templates, and static assets
├── project_examples/     # Portfolio example routes, templates, and assets
├── snabbwebb/            # Django project configuration
├── db.sqlite3            # Local SQLite database
├── manage.py             # Django command-line entry point
└── requirements.txt      # Python dependencies
```

## Getting Started

1. Clone the repository and enter the project folder.
2. Create and activate a Python virtual environment.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. Run the development server:

   ```bash
   python manage.py runserver
   ```

6. Visit `http://127.0.0.1:8000` in your browser.

## Author

Developed by **Arian Bartholovich** as a business-oriented Django project that combines full-stack web development with strong product presentation and client-focused design.
