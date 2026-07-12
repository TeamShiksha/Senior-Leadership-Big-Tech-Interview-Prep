# Interview Prep (Senior Leadership @ Big Tech)

A curated set of practical interview preparation notes for senior leadership roles at major technology companies.

## Live Site

This repository now includes a GitHub Pages-ready site that auto-discovers Markdown guides.

- Default GitHub Pages URL (after enabling Pages):
  - `https://teamshiksha.github.io/Interview-Prep-Senior-Leadership-Big-Tech/`
- Site entrypoint for branch-based Pages deploy:
  - `/docs/index.html`

## Repository Contents

- `google_interview_prep.md`
- `meta_interview_prep.md`
- `microsoft_interview_prep.md`
- `rippling_interview_prep.md`
- `INTERVIEW_PREP_TEMPLATE.md` (template for new company guides)

Each file is focused on one company and is designed for quick scanning before interviews.

## Pages Setup (GitHub)

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/docs`
3. Save and wait for deployment.
4. Open `https://teamshiksha.github.io/Interview-Prep-Senior-Leadership-Big-Tech/`.

### Custom Domain Setup (`senior-leadership-interviews.forbunnies.com`)

After Pages is live, configure:

1. In **Settings → Pages**, set custom domain to:
   - `senior-leadership-interviews.forbunnies.com`
2. In your DNS provider, add:
   - **Type**: `CNAME`
   - **Name/Host**: `senior-leadership-interviews`
   - **Target/Value**: `teamshiksha.github.io`
   - **TTL**: default (or 300 seconds)
3. Wait for DNS propagation, then enable **Enforce HTTPS** in Pages.

## How to Use This Repository

1. Start with the company file you need.
2. Read the sections in order once to build context.
3. Revisit and tailor the material to your own experience and examples.
4. Keep your own notes externally, then contribute improvements back here.

## How to Contribute (Safely)

To keep this repo useful and stable for everyone:

1. Create a branch for your change.
2. Make focused edits (small PRs are easier to review).
3. Preserve heading structure and existing section flow unless intentionally improving it.
4. Verify markdown renders correctly and that links/headings are not broken.
5. Avoid adding confidential interview content, proprietary details, or personal data.
6. Open a PR with a clear summary of what changed and why.

### Contribution Guidelines

- Prefer clarity over volume.
- Keep advice actionable and role-relevant.
- Avoid duplicate content across company files; cross-reference instead.
- If adding a new company guide, follow the same naming pattern: `<company>_interview_prep.md`.
- If creating a new guide from scratch, start with `INTERVIEW_PREP_TEMPLATE.md`.

## Contributors

Thanks to everyone helping improve this resource.

- [@sunnykgupta](https://github.com/sunnykgupta)

To add yourself, include your GitHub handle in this section as part of your PR.
