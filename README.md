
# ShopIn : Sprint 17

ShopIn is a full-stack ecommerce application built with Next.js, Express, MongoDB, and Redux Toolkit.

For Sprint 17, the focus was on preparing the application for production deployment, securing environment variables, and setting up a production-ready backend with PM2, NGINX, and HTTPS.

## Included

* Responsive ecommerce UI
* Login and registration
* Product listing and product management
* Shopping cart and orders
* Admin dashboard
* AI-generated product descriptions using Gemini
* Redux Toolkit and RTK Query
* Helmet security headers and Content Security Policy
* DOMPurify-based server-side input sanitization
* JWT authentication and role-based access
* Docker Compose with MongoDB, backend instances, frontend, and NGINX
* Production frontend deployment
* PM2 process management for the backend
* NGINX reverse proxy
* HTTPS with SSL/TLS

## Tech Stack

**Frontend:** Next.js, React, Redux Toolkit, RTK Query

**Backend:** Node.js, Express, MongoDB, Mongoose, JWT

**Security:** Helmet, CSP, DOMPurify, environment variables

**AI:** Google Gemini API

**Deployment:** Docker, NGINX, PM2, Vercel, VPS, Certbot

## Running locally

```bash
git clone <your-repository-url>
cd Sprint_17_ShopIn
docker compose up --build
```
