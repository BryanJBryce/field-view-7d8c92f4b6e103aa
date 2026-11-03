# Craig Bloomfield proposal website

Prepared November 3, 2026. Implementation handoff for Opus 5.5. Revised November 3, 2026 to lead with outcomes (see “Revision: outcomes first”).

## Brief and boundaries

Build one static proposal page for Craig Bloomfield, from Bryan Bryce / Bryce Labs LLC. Craig should understand the proposed result, see an example, understand the cost, and know how to reply. This is a visual proposal before the agreement, not a working financial dashboard or a contract acceptance flow.

Content authority: `../phase1-scope.md`, with Bryan's latest corrections in this conversation taking precedence. Heritage Homestead's Clover connection uses a private, read-only Clover OAuth app. Address approval directly to Craig as ‘you’; Clover stays exactly as you run it. Use first-person singular for Bryan at Bryce Labs. OAuth is an implementation detail, not headline copy. Bryan will buy and set up a media computer for the office TV. On-site work is invoiced separately (in the agreement, not on the page). Use the blue/white palette from https://www.velocity.builders/ and generic TV wording throughout.

Use only the supplied client-facing scope and this brief. Do not consult additional commercial source material. All displayed balances, sales and receivables below are invented examples. Do not add real financial information, credentials, account identifiers, testimonials, or claims of measured savings.

### Revision: outcomes first

Bryan's direction: “Focus on what he gets, not on contractual edge cases.” This overrides the earlier requirement to keep limits explicit on the page.

- Lead with what Craig sees and uses: connected books, bank balances together, answers on his phone, the office TV dashboard, sample questions and the 12-week plan. Each gets its own section with a visual.
- Every heading names something Craig gets. The only exceptions are “What I need from you” and “Let’s talk.”
- Contract detail moves to the written agreement, not this page: on-site rate, hours and terms; the initial term, cancellation and maintenance option; AI usage allowance; the “Not included” list; and open items such as the specific Bloomfield Property Group source, the media computer choice and conditional wording on Thirty Acres rent.
- Price appears as one line, “$3,000 / month”, with one plain sentence about what continues each month.
- “What I need from you” is a short, friendly list of access steps with no conditions.
- No internal details on the page: percentages, hours, other clients or prior vendors.

The sections below supply final visible wording. Layout instructions and technical notes are for the implementer and must not appear as page copy.

## Information architecture and final copy

Use this order. Anchor links are optional navigation aids, not separate pages. Header: text wordmark “Bryce Labs” and a single “Let’s talk” link to `#next-step`. No menu drawer or sticky action bar. Sections alternate white and pale blue backgrounds so each outcome reads as its own scene.

### 1. Hero — `#proposal`

**Small identification:** “Prepared for Craig Bloomfield”

**H1:** “All your companies’ numbers in one place.”

**Body:** “I’ll connect the systems you already use, so you can ask a question from your phone and see the same numbers on your office TV.”

**Primary link:** “See what you get” → `#what-you-get`

**Byline:** “Bryan Bryce · Bryce Labs LLC”

Pair the copy with a small phone and TV composition using the example cash figure from section 7, labeled “Example data.”

### 2. Overview — `#what-you-get`

**H2:** “What you get”

Six linked cards, numbered 1–6, each jumping to its section. Three columns on wide screens, two on tablets, one on phones. Card H3s end with a decorative arrow.

| # | H3 | Line | Links to |
| --- | --- | --- | --- |
| 1 | “Your books, connected” | “QuickBooks and Clover feed one place, for all your companies.” | `#one-place` |
| 2 | “Your bank balances together” | “Up to 6 bank accounts in one total, read-only.” | `#banks` |
| 3 | “Answers on your phone” | “Type or speak a question. Get a straight answer.” | `#phone` |
| 4 | “Questions you can ask” | “Cash, bills, sales, profit, the farm store and rent.” | `#questions` |
| 5 | “Your office TV dashboard” | “Your companies on the wall, kept up to date.” | `#tv-example` |
| 6 | “Your 12-week plan” | “First answers in week 2. Everything checked by week 12.” | `#timeline` |

### 3. Books connected — `#one-place`

**H2:** “Your books, connected”

**Intro:** “You keep using QuickBooks, Clover and your banks the way you do today. I connect them to one assistant that you can ask from your phone and see on your office TV.”

Use the diagram specification later in this plan.

**Below the diagram:** “You approve a read-only Clover connection, and Clover stays exactly as you run it.”

### 4. Bank balances — `#banks`

**H2:** “Your bank balances together”

Two columns on wide screens: a white card with the example balances, and the benefit copy beside it.

**Card:** “Example data” tag, label “Cash in connected bank accounts”, total “$186,400”, then one horizontal bar per company, sorted largest first, each scaled to the largest balance:

| Company | Value |
| --- | --- |
| Velocity Builders | $94,200 |
| Tiago LLC | $38,100 |
| Heritage Homestead LLC | $29,400 |
| Dirt Kings | $24,700 |

Bars are decorative (`aria-hidden`); names and values are text.

**Intro:** “One number for all your cash, and the balance for each company underneath it. No more logging in to each bank.”

**Points (tick icons):**

- “**Up to 6 bank accounts** in one view.”
- “**Read-only.** Nothing can move money.”
- “**Your password stays yours.** I never see or store it.”

### 5. Answers on your phone — `#phone`

**H2:** “Answers on your phone”

Benefit copy beside a CSS phone mockup with a static conversation. No input field or chat controls.

**Intro:** “Ask the way you’d ask your bookkeeper. Type it or say it, and get an answer from your connected numbers, wherever you are.”

**Points:**

- “**Plain English.** No reports to run or menus to learn.”
- “**All your companies at once,** or one at a time.”
- “**The same numbers** you see on the office TV.”

**Phone mockup** (tag “Example data”; values must match the TV example):

| You ask | Answer |
| --- | --- |
| “How much cash is in my connected bank accounts?” | “$186,400 across four companies. Velocity Builders has the most, at $94,200.” |
| “How much is past due for Velocity?” | “$12,800 in past-due invoices.” |
| “How did the farm store do this week?” | “$8,420 in sales at Heritage Homestead.” |

### 6. Questions — `#questions`

**H2:** “Questions you can ask”

**Intro:** “Here are the kinds of questions I’ll set up first. We’ll pick your starter list together, and I’ll check every answer before you rely on it.”

Four grouped cards (two columns on wide screens), each question with a small decorative speech-bubble marker. All ten visible.

- **Cash:** “How much cash is in my connected bank accounts?” · “What’s the cash balance for each company?” · “What money moved between my connected accounts this week?”
- **Money owed:** “Who owes Velocity, Tiago and Dirt Kings money, and how much is past due?” · “What bills do my companies owe in the next 30 days?”
- **Sales and results:** “What did Velocity Builders do in sales this month?” · “What did each company make or lose this month and year to date?” · “What were the biggest expenses across the companies this month?”
- **Farm store and rent:** “How did the farm store do this week: sales, top sellers and anything running low?” · “Did both Thirty Acres tenants pay rent this month?”

The transfer question asks about recorded activity; it must never look like a command to move money.

### 7. TV example — `#tv-example`

**H2:** “Your office TV dashboard”

**Intro:** “Your companies on the wall, so you and your team can see where things stand without asking.”

**Visible label, inside the mock TV:** “Example data, not your accounts”

Build a landscape TV silhouette using HTML/CSS, with a restrained dark bezel. Its content is live HTML text, not a screenshot. Show this exact static example:

| Area | Label | Value |
| --- | --- | --- |
| Main total | Cash in connected bank accounts | $186,400 |
| Velocity Builders panel | Bank cash | $94,200 |
| Velocity Builders panel | Past-due invoices | $12,800 |
| Tiago LLC panel | Bank cash | $38,100 |
| Dirt Kings panel | Bank cash | $24,700 |
| Heritage Homestead LLC panel | Bank cash | $29,400 |
| Heritage Homestead LLC panel | Farm store sales this week | $8,420 |

**Inside the TV, beneath the total:** “Four companies shown in this example.”

**Below the TV, three points:**

- “**I set it up for you.** I buy and set up the computer that runs your TV.”
- “**It grows with you.** Start with 2 company panels and grow to 4 or more.”
- “**You choose what’s on it.** Cash, money owed, sales, whatever you check most.”

The four bank cash values sum to $186,400. Receivables and Clover sales are separate measures and are not added to cash. No fake timestamp or connection status. On narrow screens, let the bezel stretch vertically and stack the panels.

### 8. Timeline — `#timeline`

**H2:** “Your 12-week plan”

**Intro:** “Week 1 starts as soon as I have access to your accounts. You’ll see working answers early and more every few weeks.”

Three phases side by side on desktop, stacked on phones. Each H3 carries a small week range above the phase name, and each phase ends with a pale “You’ll have” box.

| Phase | Week | Copy |
| --- | --- | --- |
| Connect (Weeks 1–4) | 1 | “Kickoff, access and your starter questions.” |
| | 2 | “Connect all 3 QuickBooks accounts. First answers on your phone.” |
| | 3 | “Connect bank accounts and Clover.” |
| | 4 | “Demo of your first 2 TV panels.” |
| | You’ll have | “answers on your phone and a first look at your TV.” |
| Answer (Weeks 5–8) | 5 | “Set up the TV in your office.” |
| | 6 | “Farm store weekly summary and Thirty Acres rent tracking.” |
| | 7 | “Check the starter questions and fix any wrong answers.” |
| | 8 | “Grow the dashboard to 4 or more company panels.” |
| | You’ll have | “the TV running in your office with all your main companies.” |
| Prove (Weeks 9–12) | 9–10 | “Use it day to day. I fix and polish.” |
| | 11 | “Check your questions against live data.” |
| | 12 | “Handoff, a short how-to sheet and what comes next.” |
| | You’ll have | “checked answers you can trust, on your phone and the TV.” |

### 9. Price — `#monthly`

**H2:** “One simple monthly price”

**Price:** “$3,000 / month”

**Beside it:** “You get a weekly update or short demo, and I keep your connections working.”

Nothing else. Term, on-site work, maintenance option and usage allowance belong in the agreement.

### 10. What comes next — `#next-project`

**H2:** “What we can build next”

**Intro:** “Once this is running, you pick what we work on next. Two ideas for later:”

- **“Email triage”** — “Help staying on top of your inbox.”
- **“Construction pipeline”** — “Homes under construction, spec homes and days on market.”

### 11. Client inputs — `#from-you`

**H2:** “What I need from you”

**Intro:** “Just access to get started. I’ll walk you through each step.”

Simple list with small decorative check-outline icons. No checkboxes, no conditions, no requests for passwords on the page.

- “QuickBooks invites for Velocity Builders, Tiago LLC and Dirt Kings.”
- “Your OK on the read-only Clover connection.”
- “A short session together to connect your bank accounts.”
- “The Thirty Acres rent sheet or account.”
- “Your questions and what you want on the TV. Notes or a voice memo are fine.”

### 12. Next step — `#next-step`

**H2:** “Let’s talk.”

**Body:** “Reply to the message I sent with this link and we’ll set up a call. After that, I’ll put everything in writing for you to look over.”

**Footer:** “Prepared for Craig Bloomfield by Bryan Bryce · Bryce Labs LLC”

No form, invented email, embedded scheduler or contract-acceptance behavior. If Bryan's PM supplies a verified email or scheduling URL, it may become a real link.

## Visual direction

Construction-friendly through legibility and sturdy typography. Match Velocity Builders’ blue-and-white palette: primary blue, deep navy, pale blue surfaces and white space. The colors below were verified in the live reference site's styles on November 3, 2026; its blues include primary #2F5F99, navy #1C375A, accent #1B75BA and pale blue #D7EAFF. [Color reference](https://www.velocity.builders/). Avoid construction clip art, fake blueprints, stock workers, neon effects and dashboard chrome unrelated to the proposal.

Suggested tokens, subject to measured contrast:

| Role | Color |
| --- | --- |
| Page | `#FFFFFF` |
| Text | `#1C375A` |
| Primary / button | `#2F5F99` |
| Main surface | `#FFFFFF` |
| Subtle surface | `#D7EAFF` |
| Muted text | `#375579` |
| Accent / conditional connector | `#1B75BA` |
| TV background | `#1C375A` |

Use a system sans-serif stack, strong weights and tabular numerals for money. No downloaded fonts. One H1; section H2s; H3 only for phase names, deliverables or true subsections. Body 18px minimum on phones; no tiny labels. Hero title approximately `clamp(2.4rem, 6vw, 5rem)`. Main content max-width around 1280px, with paragraphs limited to about 65 characters per line. TV numbers scale above surrounding body text.

Phone gutters 20px; desktop gutters 32–48px. Section spacing around 56px on phones and 88px on wide screens. Prefer whitespace and subtle dividers to a card around every sentence. Use 8–12px corners on cards and controls, slightly larger on the TV bezel. Give each outcome section its own visual (diagram, balance bars, phone conversation, question cards, TV, phase boxes) so the page reads as things Craig gets, not a list of terms.

At 1920×1080, the diagram and dashboard must be readable at normal browser zoom with no fine print; each can occupy its own scroll position during a TV presentation. This remains a scrolling page, not a slide deck. Do not use fixed-height sections. At 320–430px widths, stack content and preserve all names, qualifiers, prices and questions without horizontal page scrolling.

Default to no animation and no JavaScript. Native anchor links are sufficient. No parallax, auto-scrolling, loading screens, hover-only explanations or fake chat input. If a small enhancement is added, the whole proposal and CTA still work without it and with reduced motion enabled.

Aim for WCAG 2.2 AA: semantic landmarks, skip link, meaningful headings, visible keyboard focus, at least 4.5:1 normal-text contrast and 3:1 large-text/non-text control contrast. Use 44×44 CSS-pixel comfortable link targets where relevant. Test reflow at 400% zoom and text enlargement at 200%. Decorative graphics stay out of the accessibility tree.

## Diagram specification

Render the labels as real HTML in a figure, using CSS grid and decorative CSS or inline SVG connectors. No diagram library, remote image or tiny rasterized labels. Keep the same logical reading order on all viewports: companies and sources, banks, assistant, outputs. An ordered relationship in the markup must explain the flow without relying on arrows. Expose one concise accessible description and readable node text, without announcing every decorative connector.

### Sources: exact labels and connections

| Company node | Source text |
| --- | --- |
| Velocity Builders | QuickBooks Online |
| Tiago LLC | QuickBooks Online |
| Dirt Kings | QuickBooks Online |
| Heritage Homestead LLC | Clover · read-only |
| Thirty Acres LLC | Rent and expenses |
| Bloomfield Property Group | Company records |

All connectors are solid. There is no dashed “to confirm” style and no line key. Bloomfield Property Group shows the generic label “Company records”; the specific source is settled in the agreement.

Separate shared source beneath the company group:

**“Your banks”** / **“Up to 6 accounts · read-only”**

Connect that shared source to the assistant once. Do not draw one bank account per company or name specific banks.

**Center node:** “Your assistant”

**Output nodes:** “Your phone” / “Type or speak a question” and “Your office TV” / “See the same numbers”

**Accessible description:** “QuickBooks for Velocity Builders, Tiago LLC and Dirt Kings, Clover for Heritage Homestead, Thirty Acres rent and expenses, Bloomfield Property Group’s company records, and up to six bank accounts feed one assistant. You get the answers on your phone and the office TV.”

On desktop, use sources at left, assistant in the middle, phone and TV at right. Stack the company nodes in one column within the source area. Connectors point toward the assistant; arrows then point outward to phone and TV. They indicate the proposed flow, not current operational status.

On phones, use the company/source rows, the shared banks row, one downward connector to the assistant, then the two outputs below. No sideways pan, overlapping lines or duplicate visible diagram. Small device outlines are decoration; labels carry the meaning.

## File structure and technical requirements

Recommended implementation structure:

```text
proposal-site/
  PLAN.md                 # this handoff; not linked from the page
  README.md               # local viewing and Pages instructions; client-safe
  .gitignore              # editor/OS artifacts and local QA output
  docs/                   # Pages publishing folder
    .nojekyll             # publish plain files without a Jekyll build
    index.html            # all proposal content and semantic diagram markup
    styles.css            # responsive page, diagram and mockup styles
```

Use `/docs` as the publishing folder to keep handoff and QA files outside the served site. They would still be visible if committed to a public repository. Do not copy source documents into this repo. No package manager, framework, backend, API calls, authentication, financial-system connections or build step for this page. Do not add a JS file unless an approved interaction actually needs it. Use relative asset paths such as `./styles.css` so project Pages URLs work. Do not add a `CNAME` or use the account's root Pages repository.

In the document head include UTF-8, `lang="en"` on the root element, viewport metadata, title “Craig Bloomfield — Phase 1 proposal | Bryce Labs”, a concise description drawn from the hero, and exactly:

```html
<meta name="robots" content="noindex,nofollow">
```

No trackers, analytics, cookies, third-party fonts, embeds, external image loads, service worker or storage. No real account data is necessary. Keep the initial page and its local assets below roughly 200 KB uncompressed. Native HTML/CSS should make that easy. Proposal instructions must never imply the published page itself connects to the client's books or banks.

## GitHub Pages deployment checklist — for later, not this planning task

Recommended repository: **`BryanJBryce/field-view-7d8c92f4b6e103aa`**.

Expected default URL: `https://bryanjbryce.github.io/field-view-7d8c92f4b6e103aa/`. Verify the actual URL returned by Pages; an existing account-wide custom domain can change it. The suffix is a suggested opaque identifier, not a password. No separate hidden subpath is needed.

**Visibility tradeoff for Bryan:** GitHub Free requires a public repository for Pages. Both the published page and committed source/history are publicly readable. An opaque name and `noindex,nofollow` reduce casual discovery; they do not restrict access or guarantee removal from search. Only the client-safe proposal belongs here. If public visibility is unacceptable, choose access-controlled hosting instead before publication. Do not call this link private. [GitHub Pages visibility and setup](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

Execute only during a later authorized deployment. Do not create a repository, commit, push or enable Pages as part of writing this plan.

- [ ] Finish implementation and the local acceptance review below. Resolve any real contact link only from information supplied by Bryan or his PM; the reply-to-message CTA already works without one.
- [ ] Confirm `gh auth status` is authorized for BryanJBryce. Check `git status`, `git branch --show-current` and `git remote -v` in `/Users/bryan/bloomfield/proposal-site`. This folder already contains an initialized repository on `main` with no commits at planning time. Preserve unexpected existing work/remotes and reconcile them before running creation commands.
- [ ] Confirm the proposed repository name is available; if occupied, choose a fresh opaque suffix rather than touching that repository.
- [ ] Inspect every file to be committed and the staged diff. Stage explicit files, never the parent folder. Confirm the full history is suitable for a public repo; do not copy private source material, local QA captures or financial records into it.
- [ ] Create the initial commit, then the public repository and push. The following assumes the initial state described above and the required implementation files are present:

  ```sh
  cd /Users/bryan/bloomfield/proposal-site
  git add PLAN.md README.md .gitignore docs/index.html docs/styles.css docs/.nojekyll
  git diff --cached
  git commit -m "Add Bloomfield proposal page"
  gh repo create BryanJBryce/field-view-7d8c92f4b6e103aa --public --source=. --remote=origin
  git push -u origin main
  ```

  `gh repo create --source` associates the existing checkout; keeping the push separate makes the stages explicit. [GitHub CLI repository creation](https://cli.github.com/manual/gh_repo_create).

- [ ] Enable Pages from `main`, `/docs`. CLI option:

  ```sh
  gh api --method POST repos/BryanJBryce/field-view-7d8c92f4b6e103aa/pages \
    -f 'source[branch]=main' \
    -f 'source[path]=/docs'
  gh api repos/BryanJBryce/field-view-7d8c92f4b6e103aa/pages \
    --jq '{status, html_url, source, https_enforced}'
  ```

  This requires repository administration / Pages settings permission. If Pages is already enabled, inspect the existing configuration before changing it. Do not repeatedly POST. [Pages API](https://docs.github.com/en/rest/pages/pages).

- [ ] Alternatively enable it in GitHub: repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /docs → Save**. Use either CLI or UI, not both. `.nojekyll` keeps this a plain-file deployment. [Publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
- [ ] Verify the Pages deployment reaches successful completion, HTTPS works, the reported URL serves the final page, relative CSS loads, and the robots meta is in the delivered HTML. A configured source or successful push alone is not proof of deployment.
- [ ] Repeat the mobile, wide-screen, keyboard, CTA and network checks on the actual project URL. Share the verified URL with Bryan for delivery to Craig; do not send it to Craig automatically.

## Acceptance checklist for the later review

Review the implementation against this checklist before any publication. Repeat deployment-dependent checks after publishing. Record the commit reviewed, widths/browser tested, defects and fixes, and any untested items. Do not describe source-only inspection as a completed visual or accessibility review.

### Content and scope

- [ ] All 12 sections appear in the specified order with final wording. Every H2 names something Craig gets, except “What I need from you” and “Let’s talk.”
- [ ] No contract detail on the page: no on-site rate or hours, initial term, cancellation, maintenance option, AI allowance, “Not included” list, “to confirm” or “if practical” caveats.
- [ ] Price appears once, as “$3,000 / month”, with one plain sentence.
- [ ] Exactly three QuickBooks connections (Velocity Builders, Tiago LLC, Dirt Kings), read-only Clover for Heritage Homestead, Thirty Acres rent and expenses, Bloomfield Property Group company records, and up to 6 read-only bank accounts. No money movement is implied.
- [ ] Hero, bank card, phone mockup and TV all say example data; the TV says “not your accounts.” Values match this plan, four cash balances total $186,400, and the phone answers match the TV.
- [ ] Bryan buys and sets up the computer for the office TV; it starts with 2 panels and grows to 4 or more. No TV brand names.
- [ ] All ten questions are visible in four groups.
- [ ] Each timeline phase ends with a “You’ll have” outcome.
- [ ] “What I need from you” is five short access items with no conditions and no request for passwords on the page.
- [ ] CTA gives a reply path without a form, invented email, dummy button, embedded scheduler or contract-acceptance behavior.
- [ ] First-person singular for Bryan; Craig is “you.” No percentages, hours, other clients or prior vendors. No em-dash-heavy or slogan copy.

### Visual and interaction review

- [ ] Inspect rendered views at 320, 390, 768, 1440 and 1920 CSS pixels wide; include a 1920×1080 TV-like view. Save representative mobile and wide screenshots outside the public repo. If actual TV viewing is unavailable, state that limitation.
- [ ] On a phone, the hero action is easy to reach; all source labels wrap; diagram flows downward; TV panels stack and remain readable; timeline remains in order. No horizontal page overflow, clipped prices or overlapping arrows.
- [ ] On the wide view, diagram and dashboard communicate without zooming. Read the company names, amounts, example label and conditional notes at normal zoom; flag a real room-distance check as pending if untested.
- [ ] Arrows correctly flow sources → assistant → phone/TV. The shared bank node does not imply six accounts for every company.
- [ ] Keyboard navigation reaches skip link, header and hero links, the six overview cards, and any supplied contact link in a sensible order, with visible focus and no traps or obscured destinations.
- [ ] Check heading/landmark structure and accessible diagram meaning in the accessibility tree. Spot-check reading order with a screen reader where available; record limitations.
- [ ] Measure rendered text and control contrast. Check 200% text enlargement, 400% reflow, reduced motion and forced-color presentation; content and links remain usable.
- [ ] All content and native links work with JavaScript disabled. No hover-only detail or unnecessary motion. All anchors lead to the intended visible section.

### Static site and publication

- [ ] Plain HTML/CSS only, with any minimal JS justified. No install or build needed: `python3 -m http.server 8000 --directory docs` previews the completed page locally.
- [ ] Correct title, language, viewport, description and exact `noindex,nofollow` meta. No trackers, third-party resource requests, cookies, storage, forms, credentials, backend or financial API calls. Inspect network traffic, not only source.
- [ ] Styles and any local assets resolve under a repository subpath; no root-relative asset assumptions or broken console/network requests. Initial page/assets stay around the 200 KB target or less.
- [ ] Only intended client-safe files are committed. `/docs` contains `.nojekyll` and the site; PLAN and QA output are not linked or served from that publishing folder. Public-source visibility is understood by Bryan.
- [ ] After authorized deployment, successful Pages run, actual URL, HTTPS, metadata, styling and CTA verified on the published page. Record actual results rather than marking deployment complete from commands alone.

## Handoff

Planning ends with this file. Bryan's PM hands it to Opus 5.5 for implementation and returns the result here for review against the checklist. Do not launch agents, implement the site, create the GitHub repository or deploy during this planning task.
