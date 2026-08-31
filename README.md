# Examinate Marketing Website

This repository contains the marketing and advertising website for **Examinate**, an enterprise-grade Exam Development Platform. 

The site is built on WordPress and utilizes a fully containerized local development environment powered by Docker (OrbStack) to ensure consistency and isolate dependencies.

## Local Development Setup

To run this website locally, you do not need to install PHP or MySQL on your machine. You simply need Docker (or [OrbStack](https://orbstack.dev) if on macOS).

### 1. Start the Environment
Run the following command from the root of this repository to start the WordPress and MariaDB containers:
```bash
docker-compose up -d
```

### 2. Access the Site
Once the containers are running, you can view the site and log in to the admin dashboard:
- **Public Site:** [http://localhost:8000](http://localhost:8000)
- **Admin Dashboard:** [http://localhost:8000/wp-admin](http://localhost:8000/wp-admin)

### 3. Stop the Environment
To stop the local servers when you are done working, run:
```bash
docker-compose down
```

## Built-In SEO Configuration
This site is pre-configured with Google SEO best practices using a 100% free stack:
- **Site Kit by Google:** Native integration with Search Console and Google Analytics.
- **Yoast SEO:** Manages XML sitemaps, meta tags, and Open Graph data.
- **W3 Total Cache:** Caching for optimal Core Web Vitals (LCP) performance.
