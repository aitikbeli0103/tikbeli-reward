repo: aitikbeli0103/tikbeli-reward
branch: main

## Last sync

date: 2026-09-20T07:12:40Z

### Updated in this project

- Codex migration complete — eight screens now live in this project
- Added Login, Claim Beauty Gift and Waiting List from the local source
- `aitikbeli0103/TikBeli` holds only a README; the admin UI is not on GitHub
- Admin UI source is the local folder `tikbeli-login-preview-fix`, attached as `uploads/tikbeli-ui`

## Screen map

| Project screen | Source files |
| --- | --- |
| Rewards Club — Home / Gifts / Club / Rewards / Contact | tikbeli-reward: index.html, girl-3d.png |
| Login | uploads/tikbeli-ui: app/login/page.tsx, login-form.tsx, login.module.css, brand/login-approved-canva.png |
| TikBeli Admin — Dashboard | uploads/tikbeli-ui: app/dashboard-preview/page.tsx, dashboard-preview.module.css, app/admin/admin-dashboard.tsx |
| TikBeli Admin — sidebar | uploads/tikbeli-ui: app/admin/admin-sidebar.tsx |
| TikBeli Admin — Appointments | uploads/tikbeli-ui: app/admin/appointments/appointments-view.tsx, appointments.module.css |
| TikBeli Admin — Referral | uploads/tikbeli-ui: app/admin/referral/referral-view.tsx, referral/dashboard/hq-referral-data.ts |
| Waiting List | uploads/tikbeli-ui: app/admin/appointments/waiting-list/waiting-list-view.tsx, waiting-list.module.css, waiting-list-data.ts |
| Claim Beauty Gift | uploads/tikbeli-ui: app/refer/[code]/page.tsx, claim-form.tsx, refer.module.css |
| Staff Dashboard | TikBeli HR app: project_specs.md (spec only — no UI existed) |
| Operations Dashboard + Daily Closing | TikBeli HR app: project_specs.md (spec only — no UI existed) |

## Not ported

- `app/admin/appointments/card-preview` — a wrapper around the appointment card already built into the Appointments screen
- Marketing pages (`about`, `features`, `contact`, `privacy`, `terms`)
- Role stubs (`staff`, `manager`, `hr`, `admin`, `customer` in the TikBeli HR app) — all four-line placeholders

## Sync history

- 2026-09-20T04:47:22Z — admin UI rebuilt on the real design tokens and brand artwork
- 2026-09-20T04:19:55Z — Beauty Rewards Club ported from tikbeli-reward
