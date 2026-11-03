# Craig Bloomfield proposal website

Prepared November 3, 2026. Implementation handoff for Opus 5.5.

## Brief and boundaries

Build one static proposal page for Craig Bloomfield, from Bryan Bryce / Bryce Labs LLC. Craig should understand the proposed result, see an example, understand the cost, and know how to reply. This is a visual proposal before the agreement, not a working financial dashboard or a contract acceptance flow.

Content authority: `../phase1-scope.md`, with Bryan's latest corrections in this conversation taking precedence. Heritage Homestead's Clover connection uses a private, read-only Clover OAuth app. Address approval directly to Craig as ‘you’; Clover stays exactly as you run it. Use first-person singular for Bryan at Bryce Labs. OAuth is an implementation detail, not headline copy. Bryan will buy and set up a media computer for the office TV. On-site work is invoiced separately. Use the blue/white palette from https://www.velocity.builders/ and generic TV wording throughout.

Use only the supplied client-facing scope and this brief. Do not consult additional commercial source material. All displayed balances, sales and receivables below are invented examples. Do not add real financial information, credentials, account identifiers, testimonials, or claims of measured savings.

Three limits must remain explicit:

- Bloomfield Property Group belongs in the six-company picture, but its data source is not assigned in the scope. Show “Source to confirm.” Do not invent a fourth QuickBooks connection or an additional deliverable.
- Thirty Acres rent tracking is conditional on a practical bank feed or simple sheet. Keep that condition beside each promise about rent.
- The media computer choice, question pack and access timing remain to be agreed. Twelve weeks is the planned sequence after access, not a guaranteed calendar deadline.

The sections below supply final visible wording. Layout instructions and technical notes are for the implementer and must not appear as page copy.

## Information architecture and final copy

Use this order. Anchor links are optional navigation aids, not separate pages. Header: text wordmark “Bryce Labs” and a single “Let’s talk” link to `#next-step`. No menu drawer or sticky action bar.

### 1. Hero — `#proposal`

**Small identification:** “Prepared for Craig Bloomfield”

**H1:** “Your companies. One clear view.”

**Body:** “Ask a question from your phone. See the same numbers on your office TV. I connect the systems you already use.”

**Primary link:** “See how it connects” → `#one-place`

**Byline:** “Bryan Bryce · Bryce Labs LLC”

Pair the copy with a small phone and TV composition using the example cash figure from section 4. Include the visible label “Example data” within this composition. Keep the title and primary link visible on a typical phone without an oversized empty hero. The full company diagram follows immediately; do not repeat it here.

### 2. Diagram — `#one-place`

**H2:** “One place to see your money”

Use the diagram specification later in this plan. Its exact node labels are final page copy.

**Below the diagram:** “Your bank connection is read-only. No money moves. You approve the read-only Clover connection, and Clover stays exactly as you run it.”

Keep this reassurance adjacent to the connections. Do not bury the conditional sources in a footer.

### 3. Deliverables — `#what-you-get`

**H2:** “What you get”

Present these six items as a compact two-column list on wide screens and a single list on phones. Each item has one short title and one sentence; no extra badge or subtitle.

1. **“Your books, connected”** — “QuickBooks Online for Velocity Builders, Tiago LLC and Dirt Kings, plus a read-only Clover connection for Heritage Homestead.”
2. **“Your bank balances together”** — “Connect up to 6 bank accounts through Plaid, with read-only access.”
3. **“Answers on your phone”** — “Type or speak a question and get an answer from your connected numbers.”
4. **“Your office TV dashboard”** — “I’ll buy and set up a media computer for your office TV. Start with 2 company panels and grow to 4 or more.”
5. **“Thirty Acres rent, if practical”** — “Track rent from both tenants and the few expenses using a bank feed or simple sheet, if practical.”
6. **“A checked set of answers”** — “I’ll agree on about 10 starter questions with you, check the answers, and leave you a short how-to sheet.”

### 4. TV example — `#tv-example`

**H2:** “A look at your office TV”

**Visible label, inside the mock TV:** “Example data — not your accounts”

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

**Below the mockup:** “The first dashboard starts with 2 company panels, then grows to 4 or more. You choose what you want to see.”

The four bank cash values sum to $186,400. Receivables and Clover sales are separate measures and are not added to cash. Do not add a fake current timestamp, fake connection status, sample tenant names, or unsupported projections. This is an illustration of the proposed result, not a claim that accounts are already connected. Thirty Acres and Bloomfield Property Group appear in the main diagram; do not fabricate balances for them here.

On narrow screens, let the bezel stretch vertically and stack the company panels. Do not shrink a fixed 16:9 image until its text is unreadable. The wide version should still feel like a TV dashboard.

### 5. Questions — `#questions`

**H2:** “Ask it in plain English”

Use a readable list of questions, not interactive chat controls. All ten are visible; no carousel or hidden tabs.

1. “How much cash is in my connected bank accounts?”
2. “What’s the cash balance for each company?”
3. “What did Velocity Builders do in sales this month?”
4. “Who owes Velocity, Tiago and Dirt Kings money, and how much is past due?”
5. “What bills do my companies owe in the next 30 days?”
6. “What did each company make or lose this month and year to date?”
7. “How did the farm store do this week: sales, top sellers and anything running low?”
8. “Did both Thirty Acres tenants pay rent this month?” — adjacent visible note: “If rent tracking is included.”
9. “What were the biggest expenses across the companies this month?”
10. “What money moved between my connected accounts this week?”

**Below the list:** “I’ll agree on the final questions with you, based on the data I connect.”

The transfer question asks about recorded activity; it must never look like a command to move money. Do not promise a profit-and-loss answer from a bank balance alone. The final question pack must match the available company records.

### 6. Timeline — `#timeline`

**H2:** “12 weeks: connect, answer, prove”

**Timing note:** “Week 1 starts when access is ready. If access comes later, the dates move with it.”

Three adjacent phases on desktop; a vertical sequence on phones. Use these exact milestones:

| Phase | Week | Copy |
| --- | --- | --- |
| Connect | 1 | “Kickoff, access and your starter questions.” |
| Connect | 2 | “Connect all 3 QuickBooks accounts. First answers on your phone.” |
| Connect | 3 | “Connect bank accounts and Clover.” |
| Connect | 4 | “Remote demo of the first 2 TV panels.” |
| Answer | 5 | “Set up the TV on-site, booked separately.” |
| Answer | 6 | “Farm store weekly summary. Thirty Acres rent tracking, if included.” |
| Answer | 7 | “Check the starter questions and fix wrong answers.” |
| Answer | 8 | “Grow the dashboard to 4 or more company panels.” |
| Prove | 9–10 | “Use it day to day. Fix and polish.” |
| Prove | 11 | “Check the agreed questions against live data.” |
| Prove | 12 | “Handoff, how-to sheet and what comes next.” |

**Completion line:** “Phase 1 is done when the assistant answers the agreed questions correctly, from live data, on your phone and the TV.”

The week-5 milestone does not include its separate fee in the monthly price. Link “booked separately” to `#on-site`.

### 7. Monthly arrangement — `#monthly`

**H2:** “What’s included monthly”

**Primary price:** “$3,000 / month”

**Term:** “3 months to start. Then month to month.”

**Initial commitment:** “$9,000 over the first 3 months. On-site work is invoiced separately.”

**Included list:**

- “One active build project, worked on remotely.”
- “A weekly update or short demo.”
- “2 remote sessions a month, 60–90 minutes each.”
- “Monitoring, working connections, fixes and security.”
- “Up to $150 a month in AI usage for the assistant. If you go over, I’ll talk with you before anything changes.”

**Cancellation:** “After the first 3 months, either of us can stop with 30 days’ notice.”

**Secondary option:** “Maintenance only: $750 / month”

**Secondary option body:** “After the first 3 months, you can switch to maintenance only. That keeps everything running and fixed, with no new features.”

Use one primary price block and a quieter maintenance row below it. No artificial tier comparison, discount, countdown, checkout, or “most popular” tag. Do not imply maintenance includes continued feature development or promise additional usage terms absent from the scope.

### 8. On-site work — `#on-site`

**H2:** “On-site setup”

**Rate:** “$200 / hour, prepaid”

**Estimate:** “TV setup: about 3 hours / about $600, if your crew mounts the hardware and runs the cables. I handle setup and testing.”

**Terms:** “On-site or dedicated time is invoiced separately. I’ll book the visit once the remote side is working. If it looks like I’ll run over, I’ll stop and check with you first. Unused prepaid hours stay as credit for 12 months.”

**Open details:** “I’ll buy and set up the media computer for your TV. I’ll confirm the computer with you before I buy it.”

Do not describe $600 as a fixed quote or an all-in hardware price. No hardware model or purchase price has been agreed.

### 9. Boundaries and later work — `#next-project`

**H2:** “What comes next”

Give these two future items modest visual emphasis:

- **“Email triage”** — “A possible next project after Phase 1.”
- **“Construction pipeline”** — “Homes under construction, spec homes and days on market.”

**Next-project terms:** “Once Phase 1 is accepted, you choose the next project under the same monthly fee. If you want a second project running at the same time, I’ll quote it first.”

**Subheading:** “Not included in Phase 1”

- “Bookkeeping or replacing your bookkeeper.”
- “Email triage, texting or iMessage.”
- “Construction pipeline tracking.”
- “A dedicated TV app.”
- “Work on existing custom software.”
- “Replacing Clover or QuickBooks.”
- “Equipment and property tracking, inter-company leases or moving money.”
- “Investment accounts or market alerts.”

Show the boundaries as a compact open list; do not hide them behind a disclosure. The “same monthly fee” means the active $3,000 build arrangement, not the $750 maintenance option. This section offers later discussion, not a promise that every listed system or feature is feasible without scoping.

### 10. Client inputs — `#from-you`

**H2:** “What I need from you”

Use a simple list with small decorative check-outline icons. Do not create checkboxes that imply anything has already been provided.

- “QuickBooks Online invites for Velocity Builders, Tiago LLC and Dirt Kings.”
- “Your approval of the private, read-only Clover connection for Heritage Homestead.”
- “A session with you to connect up to 6 bank accounts through Plaid. I never see or store your bank password.”
- “The Thirty Acres rent sheet or account, if rent tracking is included.”
- “Your questions and what you want on the TV. A photo, notes or a voice memo is fine.”
- “A spot near the TV for the media computer, with power and internet.”
- “Your best email and phone for updates, and one other main contact if you want.”
- “The legal company name that will sign the agreement.”
- “Which records should represent Bloomfield Property Group.”

The final item resolves the diagram's open mapping; it does not add a promised integration. Do not ask Craig to submit access details or passwords on this proposal page.

### 11. Next step — `#next-step`

**H2:** “Let’s talk.”

**Prominent call to action:** “Reply to Bryan to schedule a call.”

**Body:** “Reply to the message I sent with this link. I’ll settle the open details with you, then put the agreed scope in writing.”

**Footer:** “Prepared for Craig Bloomfield by Bryan Bryce · Bryce Labs LLC”

Default to these reply instructions because the scope supplies no verified sender email or scheduling URL. The prominent call to action is text, not an inert button. The header link scrolls here. If Bryan's PM supplies a verified email, turn “Reply to Bryan” into a real `mailto:` link, keep the reply instructions as a fallback, and display the address. A supplied scheduling URL may instead be a plain external link. Do not invent either destination, embed a scheduler, add a form, or make a link that accepts the proposal.

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

Phone gutters 20px; desktop gutters 32–48px. Section spacing around 56px on phones and 88px on wide screens. Prefer whitespace and subtle dividers to a card around every sentence. Use 8–12px corners on cards and controls, slightly larger on the TV bezel. Keep the price, deliverables and timeline visually distinct without adding unrequested headings or promotional copy.

At 1920×1080, the diagram and dashboard must be readable at normal browser zoom with no fine print; each can occupy its own scroll position during a TV presentation. This remains a scrolling page, not a slide deck. Do not use fixed-height sections. At 320–430px widths, stack content and preserve all names, qualifiers, prices and questions without horizontal page scrolling.

Default to no animation and no JavaScript. Native anchor links are sufficient. No parallax, auto-scrolling, loading screens, hover-only explanations or fake chat input. If a small enhancement is added, the whole proposal and CTA still work without it and with reduced motion enabled.

Aim for WCAG 2.2 AA: semantic landmarks, skip link, meaningful headings, visible keyboard focus, at least 4.5:1 normal-text contrast and 3:1 large-text/non-text control contrast. Use 44×44 CSS-pixel comfortable link targets where relevant. Test reflow at 400% zoom and text enlargement at 200%. Source status must be conveyed in words as well as line style/color. Decorative graphics stay out of the accessibility tree.

## Diagram specification

Render the labels as real HTML in a figure, using CSS grid and decorative CSS or inline SVG connectors. No diagram library, remote image or tiny rasterized labels. Keep the same logical reading order on all viewports: companies and sources, banks, assistant, outputs. An ordered relationship in the markup must explain the flow without relying on arrows. Expose one concise accessible description and readable node text, without announcing every decorative connector.

### Sources: exact labels and connections

| Company node | Source text | Connector to assistant |
| --- | --- | --- |
| Velocity Builders | QuickBooks Online | Solid |
| Tiago LLC | QuickBooks Online | Solid |
| Dirt Kings | QuickBooks Online | Solid |
| Heritage Homestead LLC | Clover · read-only | Solid |
| Thirty Acres LLC | Rent · bank feed or simple sheet, if practical | Dashed; condition visible |
| Bloomfield Property Group | Source to confirm | Dashed; uncertainty visible |

Separate shared source beneath the company group:

**“Banks through Plaid”** / **“Up to 6 accounts · read-only”**

Connect that shared source to the assistant once. Do not draw one bank account for each company, imply six accounts per company, assign specific banks, or make QuickBooks and Clover balances look like additional cash on top of bank balances. The shared bank node applies to the accounts Craig selects; company ownership is confirmed during setup.

**Center node:** “Your assistant”

**Output nodes:** “Your phone” / “Type or speak a question” and “Your office TV” / “See the same numbers”

**Visible line key:** “Solid: planned connection. Dashed: to confirm.”

**Accessible description:** “QuickBooks for Velocity Builders, Tiago LLC and Dirt Kings, Clover for Heritage Homestead, and up to six bank accounts through Plaid feed one assistant. Thirty Acres rent depends on a practical bank feed or sheet. Bloomfield Property Group’s source is still to confirm. The assistant supplies answers on your phone and the office TV.”

On desktop, use sources at left, assistant in the middle, phone and TV at right. Give the six companies a two-column grid within the source area if needed. Do not put six tiny source columns across the page. Solid and dashed connectors point toward the assistant; arrows then point outward to phone and TV. They indicate the proposed flow, not current operational status.

On phones, use the six company/source rows, the shared banks row, one downward connector to the assistant, then the two outputs below. Make each conditional row's meaning readable even where a shared connector replaces individual paths. No sideways pan, overlapping lines or duplicate visible diagram. Small device outlines are decoration; labels carry the meaning.

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

- [ ] All 11 sections appear in the specified order with final wording or a clearly documented, scope-preserving copy correction. Craig and Bryan / Bryce Labs LLC are identified correctly.
- [ ] All six company names appear in the diagram; exactly three QuickBooks connections are assigned to Velocity Builders, Tiago LLC and Dirt Kings.
- [ ] Clover is a private read-only OAuth app in the implementation brief; visible copy says ‘you’ approve the read-only connection and Clover stays exactly as you run it. No request for a Clover login or generic Clover invite replaces this approval.
- [ ] Up to 6 bank accounts total, through Plaid, read-only; no money movement. Bank ownership is not invented. Cash does not double-count bookkeeping or sales data.
- [ ] Thirty Acres is conditional beside diagram, deliverable, sample question and timeline. Bloomfield Property Group says “Source to confirm” and has no invented integration or balance.
- [ ] The static mockup and hero preview visibly say example data; the TV says “not your accounts.” Values match this plan and four cash balances total $186,400. No real records or live-status implication appears.
- [ ] Bryan explicitly buys and sets up a media computer for the office TV; it starts with 2 panels and grows to 4 or more. No dedicated TV app is promised. No TV brand names appear in visible or accessible copy.
- [ ] All ten draft questions are visible; the final pack is agreed together and matched to connected data. Completion means correct answers from live data on phone and TV.
- [ ] Connect / Answer / Prove cover weeks 1–12 with access dependency and separately billed week-5 on-site work explicit.
- [ ] $3,000/month; 3-month start; $9,000 initial monthly-fee total; month-to-month after; 30 days' notice; $750 maintenance-only afterward with no new features.
- [ ] One active remote project, weekly update/demo, two 60–90 minute sessions, maintenance/security and $150/month AI allowance all appear. No automatic usage overage price is invented.
- [ ] On-site/dedicated time is explicitly invoiced separately, prepaid at $200/hour; about 3 hours/$600 depends on Craig's crew mounting hardware and running cables. Runover check, 12-month credit and media computer choice remain clear.
- [ ] All exclusions are present. Email triage and construction pipeline are future projects after acceptance; the $750 option does not include them.
- [ ] Inputs include correct access/approval steps, bank session, rent source if included, TV/power/internet, questions, contact details, signing entity and Bloomfield Property Group source confirmation.
- [ ] CTA gives an actual reply path without a form, invented email, dummy button, embedded scheduler or contract-acceptance behavior. No unsupported commercial claims or private source material appears in page, repo files or history.

- [ ] All provider voice uses first-person singular (I / my); client-facing approval says you. The palette matches the verified Velocity Builders blues and white, with rendered contrast rechecked.

### Visual and interaction review

- [ ] Inspect rendered views at 320, 390, 768, 1440 and 1920 CSS pixels wide; include a 1920×1080 TV-like view. Save representative mobile and wide screenshots outside the public repo. If actual TV viewing is unavailable, state that limitation.
- [ ] On a phone, the hero action is easy to reach; all source labels wrap; diagram flows downward; TV panels stack and remain readable; timeline remains in order. No horizontal page overflow, clipped prices or overlapping arrows.
- [ ] On the wide view, diagram and dashboard communicate without zooming. Read the company names, amounts, example label and conditional notes at normal zoom; flag a real room-distance check as pending if untested.
- [ ] Arrows correctly flow sources → assistant → phone/TV. Dashed connections have visible textual qualifiers. The shared bank node does not imply six accounts for every company.
- [ ] Keyboard navigation reaches skip link, header and hero links, timeline cross-link, and any supplied contact link in a sensible order, with visible focus and no traps or obscured destinations.
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
