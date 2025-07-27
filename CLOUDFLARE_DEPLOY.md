# Cloudflare Pages Deployment Instructions

## Prerequisites
1. Update Node.js to version 20 or higher
   - Using nvm: `nvm install 20 && nvm use 20`
   - Using Homebrew: `brew install node@20`

## Deployment Commands
After updating Node.js, run:
```bash
npx wrangler deploy
```

## Configuration
The `wrangler.toml` file is already configured to deploy this static site.

## Alternative: Direct Upload
You can also deploy via Cloudflare Dashboard:
1. Go to https://dash.cloudflare.com
2. Click "Pages" > "Create a project"
3. Connect your GitHub repository
4. Use these build settings:
   - Build command: (leave empty)
   - Output directory: (leave empty or use ".")
   - Root directory: (leave empty)
