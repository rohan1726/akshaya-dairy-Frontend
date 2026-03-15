# Akshaya Dairy – Driver / Center Panel

React + Vite app for drivers and dairy centers (milk collection, payments).

## Run locally

1. **Backend must be running** at `http://localhost:3000` (see backend repo).
2. **Run app**
   ```bash
   npm install
   npm run dev
   ```
   Opens at http://localhost:3002. Set `VITE_API_URL` in `.env` to `http://localhost:3000` if needed (default uses `http://localhost:3000/api`).

## Build

```bash
npm run build
```

Output is in `dist/`. Preview with:

```bash
npm run preview
```

## Deploy to Vercel

1. Import this repo in Vercel (Root Directory: leave empty).
2. **Build & Development Settings**
   - Framework Preset: **Vite**
   - Build Command: `npm run build`
   - Output Directory: `dist`
3. **Environment variable:** `VITE_API_URL` = your backend API URL (no trailing slash), e.g. `https://your-backend.vercel.app`
4. Deploy.

## About

Driver and center panel for Akshaya Dairy (milk collection, duty status, payments).
