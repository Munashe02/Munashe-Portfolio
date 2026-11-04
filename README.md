# Munashe L. Gwaze — Portfolio 2.0

A separate React + TypeScript + Vite + Tailwind project. It is deployed as its own GitHub Pages site; the earlier portfolio remains untouched.

## Run locally

Requires Node.js 22 and npm.

    npm ci
    npm run dev

Open the Local URL printed by Vite. Production check:

    npm run build
    npm run preview

## Edit the content

`src/content.ts` holds the profile, contact details, services and case studies. `src/styles.css` holds the dark navy / lime design system, `src/story.css` styles the story-led homepage, and `src/main.tsx` holds page composition and interactions.

Pages: `#/`, `#/services`, `#/work`, `#/work/aripo`, `#/work/legacy-faith-ai`, `#/work/business-operations`, `#/about`, `#/recruiters`, `#/contact`.

Hash routes deliberately work on static hosts and project subdirectories without rewrite configuration. They trade cleaner URLs and independently indexable case-study documents for straightforward static deployment. For a larger SEO campaign, migrate to prerendered routes.

Contact form: validates name, email and message, then generates a brief for copying or opening in an email or WhatsApp draft. The visitor sends the message from their own app; this website does not deliver email or store enquiries. Supplied email and both phone numbers are shown, with +263714651299 used for WhatsApp. Service enquiries include full-stack development, database management, data entry and analytics, and defensive cybersecurity support for authorized systems.

Set a case study's `screenshot` to an approved image path (for example `./screenshots/aripo.webp`) after adding the file under `public/screenshots/`. All six listed projects now use real public-page screenshots captured on 2 November 2026. See public/screenshots/SOURCES.md. Do not publish client material without permission.

## Content and launch review

See PROJECT-CONTEXT.md for the six updated case-study descriptions. Contact details were supplied by Munashe; test the email and WhatsApp drafts on your device before sharing. Website screenshots and public-page context have been added. Legacy remains a pilot. D7 TechNode is shown as a delivered public website based on the owner’s latest clarification. Specific stacks, dates, feature ownership, SEO tasks and results are still to be documented. No metrics, endorsements or sole-authorship claims are invented.

The original business operations platform entry remains in draftProjects in src/content.ts for future expansion and does not appear in selected work. A genuine CV can be linked through profile.resume.

## Deploy as a new site

Build with `npm ci` then `npm run build`. Publish only the contents of `dist/` to a NEW static site. For Netlify or similar static hosts, use build command `npm run build` and output `dist`. No environment variables or backend are required. The Vite base is relative, so asset links support subdirectories.

This project is deployed from the `Munashe02/Munashe-Portfolio` repository. In Settings > Pages, choose GitHub Actions as the source. The included workflow uploads only `dist`, which includes the built assets. The workflow is manually triggered from Actions > Deploy separate portfolio > Run workflow on `main`; subsequent source pushes do not deploy automatically.

The included workflow deploys on manual dispatch only. Run it after changes you want to publish. The separate repository and workflow leave the earlier portfolio untouched.

## Client acquisition roadmap

Today: test the contact links, confirm the services you can deliver now, and share the services page directly with warm prospects. Start enquiries around one specific problem and agree scope, price and timing before work. No public prices or response-time guarantees are invented here.

Next: replace one concept image with approved evidence and complete the corresponding contribution record. A concise verified case study is more useful than adding more unverified claims.

Then: add a real enquiry delivery service, CV and verified professional links. Introduce analytics only after choosing a provider and deciding what data is necessary.

## Verification

See `VERIFICATION.md` for checks completed in this environment and any limits. No credentials, testimonials, client metrics, employment history or certifications have been invented.
