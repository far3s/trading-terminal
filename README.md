# Trading Terminal — Plus500

AI-powered trading analysis terminal. Built for Plus500 CFD traders.

---

## Deploy to Vercel (Free) — Step by Step

### What you need
- A free GitHub account → https://github.com
- A free Vercel account → https://vercel.com
- Your Anthropic API key → https://console.anthropic.com

---

### Step 1 — Upload to GitHub

1. Go to https://github.com and sign in
2. Click the **+** button (top right) → **New repository**
3. Name it `trading-terminal`
4. Click **Create repository**
5. On the next page, click **uploading an existing file**
6. Upload ALL files from this folder keeping the same folder structure:
   - `api/analyze.js`
   - `public/index.html`
   - `vercel.json`
   - `package.json`
7. Click **Commit changes**

---

### Step 2 — Deploy on Vercel

1. Go to https://vercel.com and sign in (use your GitHub account)
2. Click **Add New Project**
3. Find your `trading-terminal` repo and click **Import**
4. Leave all settings as default
5. Click **Deploy**
6. Wait ~1 minute — Vercel will build and deploy your app

---

### Step 3 — Add your Anthropic API Key

1. In Vercel, go to your project dashboard
2. Click **Settings** → **Environment Variables**
3. Click **Add New**
4. Name: `ANTHROPIC_API_KEY`
5. Value: paste your API key (starts with `sk-ant-...`)
6. Click **Save**
7. Go to **Deployments** → click the 3 dots on your latest deployment → **Redeploy**

---

### Step 4 — Open your app

1. Go back to your project in Vercel
2. Click the URL shown (e.g. `trading-terminal-xyz.vercel.app`)
3. Your trading terminal is live!

---

## How to get your Anthropic API Key

1. Go to https://console.anthropic.com
2. Sign in or create a free account
3. Click **API Keys** in the left menu
4. Click **Create Key**
5. Copy the key (starts with `sk-ant-...`)
6. Paste it in Vercel as shown in Step 3 above

---

## Usage

- Select a market tab (Stocks / Crypto / Forex / Commodities)
- Click any symbol
- Read the AI signal: BUY / SELL / HOLD
- Enter your account balance and risk %
- Get your exact Stop Loss and Take Profit levels
- Open Plus500, find the symbol, and enter the levels

⚠️ Not financial advice. CFDs carry high risk. Always verify prices on Plus500.
