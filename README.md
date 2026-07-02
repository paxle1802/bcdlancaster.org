# bcdlancaster.org

Static landing page for **Bhutanese Community Development of Lancaster County Pennsylvania** (Lancaster, PA · EIN 27-4000473 · 501(c)(3)).
Single self-contained `index.html` (inline CSS, no build step). Style: modern minimal, airy, saffron + Himalayan teal, sans-serif, rounded cards.

## Deploy (GitHub Pages)
1. `git init && git add -A && git commit -m "feat: initial BCD Lancaster landing page"`
2. Create repo, push.
3. Repo Settings → Pages → deploy from `main` / root.
4. DNS (registrar Spaceship): apex A records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; `www` CNAME → `<user>.github.io`. `CNAME` file already set to `bcdlancaster.org`.
5. Enable HTTPS in Pages.

## Before applying to Claude for Nonprofits (build-guards)
- [ ] **Set MX** + create `info@bcdlancaster.org`.
- [ ] **Age domain 60 days** from registration before applying.
- [ ] Confirm current **board/officers** (Kamal Kafley = chairman per press; verify still current) + add real photos/bios → identity-verification.
- [ ] Add real contact **phone** if available.
- [ ] Wire **Support Our Work / donate** button to a real link.
- [ ] Apply as a **named officer** from an `@bcdlancaster.org` email.
- [ ] ⚠️ This org files **990-N** (micro tier). Before applying, have the org **file any overdue 990-N** (free, at IRS.gov) so IRS status is current — mirrors the mvsbca guard.

## Guard note
Secular resettlement/integration services are foregrounded; no religious framing. Keep it that way for Goodstack.
