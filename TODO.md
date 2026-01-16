# TODO: Upgrade BMK Fruits Website with Moroccan Luxe Features

## Tasks
- [x] Update supabase_schema.sql: Add origin and tags columns to products table
- [x] Update types.ts: Add stock_quantity, origin, tags to Product interface
- [x] Enhance App.tsx: Integrate framer-motion animations, react-hot-toast notifications, improve smart search, add floating cart enhancements
- [x] Update ProductCard.tsx: Add quick view modal, stock bar indicator, freshness countdown/badge
- [ ] Update Header.tsx: Make it premium with dynamic features, better styling
- [ ] Update Footer.tsx: Modernize with new design
- [x] Add new components: QuickView modal, MiniCart for floating cart
- [ ] Test build and functionality

## Dependent Files
- supabase_schema.sql
- types.ts
- App.tsx
- components/ProductCard.tsx
- components/Header.tsx
- components/Footer.tsx
- New: components/QuickView.tsx, components/MiniCart.tsx

## Followup Steps
- [ ] Verify schema updates in Supabase
- [ ] Test animations, notifications, quick view, etc.
- [ ] Ensure responsive design and RTL support
