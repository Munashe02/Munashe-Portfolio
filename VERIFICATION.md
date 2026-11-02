# Verification — 2 November 2026

- `npm run build`: PASS. TypeScript checks and Vite production bundle completed. Final JS approximately 251 kB (77.7 kB gzip); CSS approximately 19.2 kB (5.4 kB gzip).
- `npm test`: PASS, 5 tests. Checks cover unique project/service identifiers, qualification of ARIPO contribution, development labels, evidence fields and empty unverified contact defaults.
- Production preview: rendered successfully in the in-app browser at desktop size and at 390px phone width.
- Browser interaction checks: work filter selected Product and displayed the Faith AI case; detail page rendered; contact form produced a copyable brief with an explicit not-sent state; phone menu expanded and closed on navigation; recruiter CTA preselected Recruiter and Role / collaboration.
- Desktop layout check: document width equals viewport width (1265px), with no horizontal overflow. Final route changes keep the header visible.
- No external messages, enquiries, repository pushes or deployments were performed. Existing portfolio untouched.

Environment limits: Vite's default esbuild configuration loader attempted to inspect a restricted ancestor directory. Build scripts use Vite's runner loader, and production builds pass. Live development dependency optimisation also encounters that directory restriction in this managed Windows environment; use `npm run build` followed by `npm run preview` here. Ordinary local development outside this restriction can use `npm run dev`.

Not verified: actual delivery to an email provider (none configured), production deployment, physical devices, assistive-technology audit, verified CV/contact details, project screenshots, exact individual ARIPO scope or product implementation details.

## Project and contact update — 2 November 2026

- Production build passed after adding all six case studies and an SEO service.
- All 6 content tests passed, including real screenshot paths, HTTPS project links, agency credit and the owner-confirmed contact destinations.
- All 6 screenshot images loaded in the browser. SEO filter displayed Hyundai and Motsatsi Media.
- Email and both telephone links matched the supplied details; WhatsApp and generated draft links targeted +263714651299. Drafts were inspected only, not sent.
- Updated work listing checked at phone width: viewport and document both 375px, no horizontal overflow.
- Public project pages reviewed and captured, including ARIPO anniversary site. Legacy capture is of its public sign-in page; no private account was accessed.
- Prior contact-pending and unverified-contribution notes above describe the initial version. The current data reflects the owner’s subsequent confirmation of primary development contributions, live website delivery and Legacy pilot status. Exact tools, feature-level contributions and SEO results remain undocumented.
