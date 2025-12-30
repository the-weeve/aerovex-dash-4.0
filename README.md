# Aerovex Dashboard

A business intelligence dashboard for tracking revenue, ad campaigns, and performance metrics.

## 🚀 Quick Deploy

### 1. Create GitHub Repository
```
https://github.com/new
```
- Repository name: `aerovex-dashboard-v2` (or whatever you want)
- Public or Private (your choice)
- **DON'T** add README, .gitignore, or license
- Click "Create repository"

### 2. Upload Files
- Click "uploading an existing file"
- Drag ALL files from this folder into GitHub
- Commit changes

### 3. Deploy to Netlify
```
https://app.netlify.com
```
- Click "Add new site" → "Import an existing project"
- Choose "Deploy with GitHub"
- Select your repository
- Leave all settings default
- Click "Deploy site"

### 4. Add API Key (Optional - for AI chat)
In Netlify:
- Site settings → Environment variables
- Add variable:
  - **Key**: `ANTHROPIC_API_KEY`
  - **Value**: Your Anthropic API key
- Trigger redeploy

## ✅ What Works

- ✅ 24 months of business data (2025-2026)
- ✅ 8 campaigns (4 Meta + 4 Google)
- ✅ Business Overview with revenue trends
- ✅ Ad Campaign Performance comparison
- ✅ Revenue Breakdown by channel
- ✅ Monthly Trends analysis
- ✅ Executive Summary
- ✅ Dark mode
- ✅ AI chat assistant (if API key added)

## 📝 Updating Data

Data is hardcoded in `index.html` (lines ~1909-1944).

To update:
1. Open `index.html` in text editor
2. Find `HARDCODED_BUSINESS_DATA` and `HARDCODED_CAMPAIGNS`
3. Edit the numbers/names
4. Save and upload to GitHub
5. Netlify auto-redeploys

## 🎯 Files Included

```
aerovex-fresh-start/
├── index.html           # Complete dashboard
├── logo.png            # Aerovex logo
├── netlify.toml        # Deployment config
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── netlify/
    └── functions/
        └── chat.js     # AI chat backend
```

## 🔧 Troubleshooting

**Dashboard not loading?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Try Incognito mode

**AI chat not working?**
- Check that `ANTHROPIC_API_KEY` is set in Netlify
- Redeploy after adding the key

**Still having issues?**
- Open F12 (Developer Tools)
- Check Console tab for errors
- Should see: "Initializing dashboard with hardcoded data..."

## 📊 Sample Data

The dashboard includes sample data showing realistic business growth:
- Revenue: $45k-$68k/month
- Ad spend: $7k-$12k/month
- ROAS: Varies by campaign
- 8 active campaigns with performance metrics

Replace this with your actual data after deployment.

## 🎨 Features

- Real-time ROAS calculations
- Profit margin analysis (adjustable 30%-70%)
- Campaign performance rankings
- Break-even indicators
- Dark mode support
- Responsive design
- AI-powered insights

---

Need help? Check the Console (F12) for debug messages.
