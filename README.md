# sangcnt.online

Personal portfolio for Sang, a senior full-stack engineer based in Ho Chi Minh City.

## Local development

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
```

The production site is generated in `dist/` and served locally on port `5013`.
Cloudflare Tunnel routes `sangcnt.online` to that local service.

## Content

- Main page: `src/pages/index.astro`
- Global styles: `src/styles/global.css`
- Social preview: `public/og.png`
- Local service definition: `deployment/com.sangcnt.portfolio.plist`
