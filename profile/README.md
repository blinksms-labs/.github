
# 📱 Instafication - Smart Booking Notifications

[![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)](https://kit.svelte.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)](https://prisma.io/)

Instafication is a smart notification service that monitors booking systems and instantly alerts you via SMS or email when new appointment slots become available. Never miss a booking opportunity again!

## ✨ Features

- 🔔 **Real-time Notifications** - Get instant SMS/email alerts when bookings become available
- 🏠 **Multi-Service Support** - Monitor laundry, parking, rental bookings and more
- 🌍 **Internationalization** - Available in multiple languages (Swedish, English)
- 💳 **Flexible Pricing** - Pay-per-use or monthly subscription options
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile
- 🔐 **Secure Authentication** - Google OAuth and email/password login
- ⚡ **High-Performance Scraping** - Efficient monitoring with configurable intervals
- 🎯 **Smart Filtering** - Get notifications only for your preferred areas and timeframes


### Tech Stack

- **Frontend**: SvelteKit with TypeScript
- **Styling**: Tailwind CSS + Flowbite components
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: Supabase Auth
- **API**: tRPC for type-safe APIs
- **Payments**: Stripe integration
- **Deployment**: Vercel, Cloudflare Workers support
- **Email**: Sendinblue integration


## 🔧 Configuration

### Service Configuration

Users can configure:
- Notification method (SMS/Email)
- Notification timing (1 hour, 1 day, 2 days in advance)
- Service areas (e.g., specific housing areas)
- Service types (laundry, parking, rentals)


### Scraper Configuration

Administrators can configure:
- Scraping frequency (minutes)
- Target companies/services
- Service parameters
- Monitoring areas


## 🌐 Supported Services

Currently supports:
- **Stockholms Studentbostäder (SSSB)** - Laundry booking monitoring
- More services coming soon!


## 📄 License

This project is licensed under MIT license.
