# OrderTrack — WhatsApp Order Manager

A simple, mobile-friendly order management dashboard for small businesses that take orders via WhatsApp.

## Features
- Log and track orders (New → Confirmed → Shipped → Done)
- One-tap WhatsApp message with pre-filled order details
- Orders saved permanently in browser (localStorage)
- Works offline — no backend needed
- Mobile-first design

## Deploy to Vercel (free)

### Option 1 — Vercel CLI (fastest)
```bash
npm i -g vercel
vercel
```
Follow the prompts. Your site will be live at a URL like `ordertrack-xyz.vercel.app`.

### Option 2 — GitHub + Vercel dashboard
1. Create a GitHub account at github.com
2. Create a new repository, upload these two files (index.html + vercel.json)
3. Go to vercel.com → Sign up with GitHub → "Add New Project"
4. Select your repository → click Deploy
5. Done — live in 60 seconds

### Option 3 — Drag and drop (easiest)
1. Go to vercel.com and sign up
2. On your dashboard, drag the entire project folder onto the page
3. Vercel deploys it instantly

## Custom domain (optional)
After deploying, go to your Vercel project → Settings → Domains → add your domain (e.g. orders.yourbusiness.com)

## Give it to a client
1. Deploy once
2. Share the URL with the business owner
3. They open it on their phone and tap "Add to Home Screen"
4. It looks and works like an app

## Notes
- Orders are saved in the browser's localStorage — they persist between sessions on the same device
- If the owner uses multiple devices, each device has its own order list
- For multi-device sync, the next step is connecting to Supabase (a free database)
