# Rumah Jahit Arkadara Landing Page

A premium landing page for Rumah Jahit Arkadara built with **Astro JS** and **Tailwind CSS**.

## 🚀 Key Features
- **Responsive Design**: Optimized for desktop and mobile devices.
- **WhatsApp Integration**: Direct consultation button to WhatsApp.
- **Tailwind CSS v4**: Built with the latest design standards for high performance.
- **Elegant Typography**: A combination of 'Playfair Display' and 'Lato' for a premium boutique feel.

## 🛠️ Local Development

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Run the development server:**
   ```sh
   npm run dev
   ```
   Open [http://localhost:4321](http://localhost:4321) in your browser.

## ☁️ Deployment to Cloudflare Pages

This site is optimized for deployment to **Cloudflare Pages**. You can follow these steps:

### Option 1: Git Integration (Recommended)
1. Push your code to a GitHub or GitLab repository.
2. Open the **Cloudflare Pages** dashboard.
3. Select **"Connect to Git"** and choose your repository.
4. Use the following build settings:
   - **Framework preset**: `Astro`
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`
5. Click **"Save and Deploy"**.

### Option 2: Using Wrangler CLI
1. Build the project locally:
   ```sh
   npm run build
   ```
2. Deploy using Wrangler:
   ```sh
   npx wrangler pages deploy dist
   ```

## 👀 Astro Documentation
To learn more about Astro, please visit the [official Astro documentation](https://docs.astro.build).
