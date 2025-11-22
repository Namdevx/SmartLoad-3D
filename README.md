# 🚚 SmartLoad 3D

SmartLoad 3D is a small React + Vite TypeScript app for visualizing and configuring 3D truck loading and capacity. It provides interactive UI for placing boxes, configuring truck dimensions, and quick persistence via Supabase helper.

## ✨ Highlights / Features
- 3D truck visualization
- Custom Truck Capacity Manager
- Box Management Dashboard
- Pop-Up Toasts
- Generate Delivery Report


## 🛠 Tech stack
- Framework: React + TypeScript
- Bundler/dev server: Vite — see [vite.config.ts](vite.config.ts)
- Styling: Tailwind CSS — see [tailwind.config.ts](tailwind.config.ts) and [postcss.config.js](postcss.config.js)
- Linting: ESLint — see [eslint.config.js](eslint.config.js)
- Optional backend helper: Supabase — see [`supabase`](src/lib/supabase.ts)
- Entry point: [`src/main.tsx`](src/main.tsx), main app [`src/App.tsx`](src/App.tsx)

## 📁 Folder structure (key files)
- [index.html](index.html)  
- [package.json](package.json)  
- [vite.config.ts](vite.config.ts)  
- [tsconfig.json](tsconfig.json)  
- [.env](.env) (environment variables for Supabase and other secrets)

src/
- [src/main.tsx](src/main.tsx) — app bootstrap  
- [src/App.tsx](src/App.tsx) — main app  
- [src/index.css](src/index.css), [src/App.css](src/App.css) — styles  
- components/
  - [src/components/Navigation.tsx](src/components/Navigation.tsx) — `Navigation`  
  - [src/components/TruckVisualization.tsx](src/components/TruckVisualization.tsx) — `TruckVisualization`  
  - [src/components/TruckCapacityConfig.tsx](src/components/TruckCapacityConfig.tsx) — `TruckCapacityConfig`  
  - [src/components/ui/](src/components/ui/) — shared UI primitives
- pages/
  - [src/pages/AddBox.tsx](src/pages/AddBox.tsx) — `AddBox`
  - ... other pages in [src/pages/](src/pages/)
- data/
  - [src/data/dummyData.ts](src/data/dummyData.ts) — sample/demo data
- hooks/
  - [src/hooks/use-mobile.tsx](src/hooks/use-mobile.tsx) — `useMobile`
  - [src/hooks/use-toast.tsx](src/hooks/use-toast.tsx) — `useToast`
- lib/
  - [src/lib/supabase.ts](src/lib/supabase.ts) — `supabase`
  - [src/lib/utils.ts](src/lib/utils.ts) — helper utilities
- vite-env.d.ts: [src/vite-env.d.ts](src/vite-env.d.ts)

public/
- [public/placeholder.svg](public/placeholder.svg)  
- [public/robots.txt](public/robots.txt)

Other config files:
- [postcss.config.js](postcss.config.js)  
- [tailwind.config.ts](tailwind.config.ts)  
- [eslint.config.js](eslint.config.js)

## ▶️ How to run (local)
1. Install dependencies
```sh
npm install
