# YETAF HOLDING PLC

A modern corporate website built with Next.js, featuring a dynamic hero section, business segments showcase, news updates, and comprehensive company information.

## Features

- **Dynamic Hero Section** - Auto-rotating carousel with company highlights and initiatives
- **Business Segments** - Showcase of different business areas and operations
- **News & Updates** - Latest company news and announcements
- **Multi-page Structure** - Dedicated sections for careers, community, investors, sustainability, and more
- **Responsive Design** - Built with Tailwind CSS and Radix UI components
- **Modern UI/UX** - Clean, professional design with smooth animations

## Tech Stack

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS with custom animations
- **UI Components**: Radix UI primitives
- **Icons**: Lucide React
- **TypeScript**: Full type safety
- **Theme**: Next Themes for dark/light mode support

## Getting Started

1. Install dependencies:
```bash
pnpm install
```

2. Run the development server:
```bash
pnpm dev
```

3. Open [http://localhost:3000](http://localhost:3000) to view the site

## Project Structure

```
├── app/                    # Next.js app router pages
│   ├── careers/           # Careers section
│   ├── contact/            # Community initiatives
│   ├── community/         # Community initiatives
│   ├── newsroom/          # News and press releases
│   ├── companies/         # 
│   ├── what-we-do/       # Business operations
│   └── who-we-are/       # Company information
├── components/            # Reusable UI components
│   ├── ui/               # Base UI components
│   ├── header.tsx        # Site navigation
│   ├── hero-section.tsx  # Dynamic hero carousel
│   ├── business-segments.tsx
│   ├── news-section.tsx
│   └── footer.tsx
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
└── public/               # Static assets
```

## Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint
