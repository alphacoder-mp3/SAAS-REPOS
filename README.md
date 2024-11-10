# Notable Open Source Next.js SaaS Platforms

## Complete SaaS Boilerplates

1. **Nextjs-Subscription-Payments**

- GitHub: [vercel/nextjs-subscription-payments](https://github.com/vercel/nextjs-subscription-payments)
- Features:
  - Stripe subscription payments
  - User authentication
  - Database with Supabase
  - TypeScript support
  - Tailwind CSS styling

2. **SaaSguru**

- GitHub: [boxyhq/saas-starter-kit](https://github.com/boxyhq/saas-starter-kit)
- Features:
  - Multi-tenancy
  - SSO with SAML
  - Team management
  - Billing with Stripe
  - Email templates
  - PostgreSQL database

3. **Shipfast**

- GitHub: [wasp-lang/SaaS-Template-GPT](https://github.com/wasp-lang/SaaS-Template-GPT)
- Features:
  - AI integration ready
  - Authentication system
  - Stripe payments
  - Admin dashboard
  - Email notifications

4. **NextJS-SaaS-Boilerplate**

- GitHub: [Saas-Starter-Kit/Saas-Kit-prisma](https://github.com/Saas-Starter-Kit/Saas-Kit-prisma)
- Features:
  - Prisma ORM
  - Authentication with NextAuth
  - Stripe integration
  - Tailwind CSS
  - Email templates

## Specialized SaaS Applications

5. **Cal.com**

- GitHub: [calcom/cal.com](https://github.com/calcom/cal.com)
- Type: Scheduling platform
- Features:
  - Meeting scheduling
  - Team calendar management
  - Integration with popular calendar services
  - Customizable booking pages

6. **Papermark**

- GitHub: [mfts/papermark](https://github.com/mfts/papermark)
- Type: Document sharing and analytics
- Features:
  - Secure document sharing
  - View analytics
  - Link management
  - Team collaboration

7. **Formbricks**

- GitHub: [formbricks/formbricks](https://github.com/formbricks/formbricks)
- Type: Survey and feedback platform
- Features:
  - Form builder
  - Survey templates
  - Response analytics
  - API integration

8. **EmailEngine**

- GitHub: [shellscape/email-engine](https://github.com/shellscape/email-engine)
- Type: Email automation
- Features:
  - Email template management
  - Campaign tracking
  - Analytics dashboard
  - API endpoints

## Tech Stack Common Among These Platforms

- Frontend:

  - Next.js 13/14
  - TypeScript
  - Tailwind CSS
  - Shadcn UI / Radix UI

- Backend:

  - Prisma/Supabase
  - PostgreSQL
  - NextAuth.js
  - tRPC (in some cases)

- Infrastructure:
  - Vercel/Railway deployment
  - GitHub Actions
  - Docker support

## Getting Started Resources

- Most platforms include detailed documentation for local setup
- Required environment variables are typically documented in `.env.example` files
- Docker compose files are often provided for local development
- Installation typically follows the pattern:
  ```bash
  git clone [repository]
  npm install
  cp .env.example .env
  npm run dev
  ```
