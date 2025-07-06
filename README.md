# TMS Global Agents Demo

An AI-powered multi-agent system for Team Management Systems (TMS) that provides intelligent onboarding and debrief experiences for team managers and members.

## Overview

This project demonstrates a sophisticated multi-agent orchestration system featuring:

- **Triage Agent**: Routes requests to appropriate specialist agents
- **Onboarding Agent**: Guides new Team Managers through optimal curriculum selection
- **TMP Debrief Agent**: Provides comprehensive walkthroughs of Team Management Profile reports

## Tech Stack

- **Frontend**: Next.js 14+, TypeScript, Tailwind CSS, Shadcn UI, Framer Motion
- **Backend**: Next.js API Routes, Prisma ORM, Edge Functions
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Clerk
- **AI**: OpenAI GPT-4
- **Deployment**: Vercel
- **UI Components**: Shadcn UI, Lucide Icons
- **Notifications**: Sonner Toast
- **Payments**: Stripe (future integration)

## Features

- Split-screen interface showing customer chat and agent internals
- Real-time agent handoffs with context preservation
- TMS brand-compliant design
- Assessment integration (TMP, Team Signals, QO2, WoWV)
- Personalized journey recommendations
- Magic link authentication

## Getting Started

```bash
# Clone the repository
git clone https://github.com/[your-username]/tms-global-agents-demo.git
cd tms-global-agents-demo

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run development server
npm run dev
```

## Project Structure

```
tms-global-agents-demo/
├── app/              # Next.js app directory
├── components/       # React components
├── lib/             # Utility functions and configurations
├── prisma/          # Database schema and migrations
├── public/          # Static assets
├── styles/          # Global styles
└── types/           # TypeScript type definitions
```

## License

Proprietary - Team Management Systems

## Contact

For questions about this demo, please contact Team Management Systems.