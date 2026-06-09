# BETWORLD 2026 🌍⚽

Premium SaaS platform dedicated to FIFA World Cup 2026 predictions, analytics, and real-time match data.

## 🎯 Vision

Become the international reference for:
- Football statistics
- AI analytics
- Predictions
- News & updates
- Player data
- Team data
- Tournament simulations
- Community competitions

## 🏗️ Tech Stack

### Frontend
- **Next.js 15** - React framework
- **TypeScript** - Type safety
- **TailwindCSS** - Styling
- **Shadcn UI** - Component library
- **Framer Motion** - Animations

### Backend
- **Node.js** - Runtime
- **PostgreSQL** - Database
- **Prisma ORM** - Database client
- **Supabase** - Auth & Real-time

### Services
- **Stripe** - Payments
- **Resend** - Emails
- **Firebase** - Notifications
- **Redis** - Caching
- **WebSockets** - Real-time updates

### Deployment
- **Vercel** - Frontend hosting

## 📦 Project Structure

```
betworld-2026/
├── app/                    # Next.js app directory
│   ├── (auth)/            # Authentication pages
│   ├── (dashboard)/       # Protected routes
│   ├── (marketing)/       # Public pages
│   ├── api/               # API routes
│   └── layout.tsx         # Root layout
├── components/            # React components
│   ├── ui/               # Shadcn UI components
│   ├── layouts/          # Layout components
│   ├── sections/         # Page sections
│   └── shared/           # Shared components
├── lib/                  # Utility functions
├── types/                # TypeScript types
├── hooks/                # React hooks
├── prisma/               # Database schema
├── public/               # Static assets
└── utils/                # Helper functions
```

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local

# Setup database
npx prisma migrate dev

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📋 Features

### Core
- ✅ Homepage with live matches
- ✅ Live Match Center with real-time updates
- ✅ AI-powered predictions
- ✅ Team & Player profiles
- ✅ News & articles
- ✅ Bracket Challenge
- ✅ Tournament simulator

### Premium
- ✅ Unlimited AI analyses
- ✅ Advanced predictions
- ✅ Notifications
- ✅ Favorite tracking

## 💳 Subscription Tiers

- **Free**: 3 analyses/day + news
- **Premium**: €19.90/month - unlimited access
- **Lifetime**: €50 - one-time payment

## 📊 Database Schema

See `prisma/schema.prisma` for the complete database schema.

## 🔐 Security

- Supabase Auth for authentication
- Row-level security (RLS)
- API rate limiting
- Input validation with Zod

## 📱 Responsive Design

- Mobile-first approach
- Desktop, tablet, and mobile optimized
- Dark mode & Light mode
- Premium UI with modern animations

## 🎨 Design System

- **Colors**: Blue (FIFA), Deep Black, White, Gold
- **Typography**: Inter font family
- **Animations**: Smooth transitions and interactions
- **Components**: Consistent with Shadcn UI

## 📈 Performance

- Image optimization
- Code splitting
- Lazy loading
- Caching strategy
- CDN integration

## 🔄 Real-time Updates

- WebSockets for live match data
- Supabase Realtime for database changes
- Push notifications
- Email alerts

## 📝 SEO

- Automatic sitemap generation
- Meta descriptions
- Schema.org markup
- Open Graph tags
- AMP pages
- 100,000+ indexable pages

## 📞 Support

For issues and feature requests, please open an issue on GitHub.

## 📄 License

Proprietary - All rights reserved

---

**Made with ⚽ for World Cup 2026**
