frontend/
├── app/
│ ├── layout.tsx
│ ├── globals.css
│ ├── (auth)/
│ │ ├── login/
│ │ │ └── page.tsx
│ │ └── register/
│ │ └── page.tsx
│ ├── (main)/
│ │ ├── browse/
│ │ │ └── page.tsx
│ │ ├── recommendations/
│ │ │ └── page.tsx
│ │ └── profile/
│ │ ├── page.tsx ← main profile info
│ │ └── favorites/
│ │ └── page.tsx ← nested route inside profile
│ └── page.tsx ← optional homepage or redirect
│
├── components/
│ ├── ui/
│ │ ├── Button.tsx
│ │ ├── Input.tsx
│ │ ├── Card.tsx
│ │ └── Avatar.tsx
│ ├── layout/
│ │ ├── Navbar.tsx
│ │ └── Footer.tsx
│ └── books/
│ ├── BookCard.tsx
│ └── BookList.tsx
│
├── lib/
│ ├── api.ts
│ ├── auth.ts
│ └── types.ts
│
├── store/
│ └── useUserStore.ts
│
├── public/
│ └── (book covers, icons, etc.)
│
├── tailwind.config.ts
├── tsconfig.json
├── package.json
└── next.config.ts
