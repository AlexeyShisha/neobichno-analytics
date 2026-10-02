# Neobichno Analytics

Public website for the Neobichno Analytics TikTok analytics service.

## Configuration

- Frontend: static HTML hosted with GitHub Pages.
- TikTok authentication: TikTok Login Kit via Supabase Edge Functions.
- Backend: Supabase project `Neobichno Analytics`.
- TikTok callback: `https://sbieydlttplfkwjobzts.supabase.co/functions/v1/tiktok-callback`.
- Login endpoint: `https://sbieydlttplfkwjobzts.supabase.co/functions/v1/neobichno-site/login`.
- Requested TikTok scopes: `user.info.basic`, `user.info.stats`, `video.list`.
- The TikTok client secret is stored only in Supabase Secrets and must never be committed to this repository.

## Deployment

The site is intended to be published from the `main` branch root with GitHub Pages.

Expected project URL:
`https://alexeyshisha.github.io/neobichno-analytics/`

## TikTok review

The website provides a public description of the service, visible Privacy Policy and Terms of Service links, and a TikTok authorization entry point. The TikTok verification signature file is included at the repository root.

Never put OAuth secrets, access tokens, refresh tokens, or Supabase service-role keys in this repository.
