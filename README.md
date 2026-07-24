app/
├── src/
│   ├── app/                    # Next.js App Router pages
│   │   ├── api/               # API routes
│   │   ├── admin/             # Admin pages
│   │   ├── vendor/            # Vendor pages
│   │   ├── user/              # User pages
│   │   ├── sign-up/           # Sign-up pages
│   │   ├── layout.tsx         # Root layout
│   │   ├── page.tsx           # Home/Landing page
│   │   └── globals.css        # Global styles
│   ├── components/            # Reusable components
│   ├── lib/                   # Utility functions
│   │   └── auth.ts           # Authentication utilities
│   └── store/                 # Zustand stores
│       └── authStore.ts      # Authentication store
├── prisma/
│   └── schema.prisma         # Database schema
├── package.json
├── tsconfig.json
├── next.config.ts
├── tailwind.config.ts
├── postcss.config.mjs
└── .env.local                 # Environment variables
