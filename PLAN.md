# Craig Bloomfield proposal website

Prepared November 3, 2026. Implementation handoff for Opus 5.5. Revised November 3, 2026 to lead with outcomes (see “Revision: outcomes first”).

## Brief and boundaries

Build one static proposal page for Craig Bloomfield, from Bryan Bryce / Bryce Labs LLC. Craig should understand the proposed result, see an example, understand the cost, and know how to reply. This is a visual proposal before the agreement, not a working financial dashboard or a contract acceptance flow.

Content authority: `../phase1-scope.md`, with Bryan's latest corrections in this conversation taking precedence. Heritage Homestead's Clover connection uses a private, read-only Clover OAuth app. Address approval directly to Craig as ‘you’; Clover stays exactly as you run it. Use first-person singular for Bryan at Bryce Labs. OAuth is an implementation detail, not headline copy. Bryan will buy and set up a media computer for the office TV. On-site work is invoiced separately (in the agreement, not on the page). Use the blue/white palette from https://www.velocity.builders/ and generic TV wording throughout.

Use only the supplied client-facing scope and this brief. Do not consult additional commercial source material. All displayed balances, sales and receivables below are invented examples. Do not add real financial information, credentials, account identifiers, testimonials, or claims of measured savings.

### Revision: outcomes first

Bryan's direction: “Focus on what he gets, not on contractual edge cases.” This overrides the earlier requirement to keep limits explicit on the page.

- Lead with what Craig sees and uses: connected books, answers on his phone, the office TV dashboard, sample questions and the monthly options. Each gets its own section with a visual.
- Every heading names something Craig gets. The only exceptions are “Next steps” and “Let’s talk.”
- Contract detail moves to the written agreement, not this page: on-site rate, hours and terms; the initial term and cancellation; the “Not included” list; and open items such as the specific Bloomfield Property Group source, the media computer choice and conditional wording on Thirty Acres rent.
- Pricing shows two plain options, active development and maintenance, with what each includes. No term, notice or allowance detail.
- No 12-week plan, no “what we can build next” section, and no talk of starting with a few TV panels and growing. The TV shows all six companies at once.
- “Next steps” opens with signing the master services agreement and statement of work, then a short, friendly list of access steps with no conditions.
- No internal details on the page: percentages, hours, other clients or prior vendors.

### Revision: Craig's own goals

Copy is framed around what Craig said he wants in the October 28 kickoff. The kickoff notes stay out of this repo. Echo these goals in plain words; never quote him, name a prior software vendor, or include anything private from the call (family, staff, other people, personal finances).

- Lead his companies without having to be there or check up on them.
- Know where each company stands, with every company's numbers in one place.
- Ask from anywhere (out on the property, in the truck, between meetings) by voice or text.
- One big office TV split by company, instead of a screen per company, so he and his operators look at the same numbers.
- Start with finances, then build on it.
- See what came in and went out of the bank accounts.
- A summary of each weekend at the farm store, which is open on weekends. Clover stays as the store runs it; it is connected, not replaced.

The sections below supply final visible wording. Layout instructions and technical notes are for the implementer and must not appear as page copy.

## Information architecture and final copy

Use this order. Anchor links are optional navigation aids, not separate pages. Header: text wordmark “Bryce Labs” and a single “Let’s talk” link to `#next-step`. No menu drawer or sticky action bar. Sections alternate white and pale blue backgrounds so each outcome reads as its own scene.

### 1. Hero — `#proposal`

**Small identification:** “Prepared for Craig Bloomfield”

**H1:** “Know how every company is doing, without being there.”

**Body:** “You want to spend your time leading your companies, not checking up on them. I’ll connect the systems you already use so the numbers come to you: on your phone wherever you are, and on the big TV in your office.”

**Primary link:** “See what you get” → `#what-you-get`

**Byline:** “Bryan Bryce · Bryce Labs LLC”

Pair the copy with a small phone and TV composition using the example cash figure from section 7, labeled “Example data.”

### 2. Overview — `#what-you-get`

**H2:** “What you get”

Five linked cards, numbered 1–5, each jumping to its section. Three columns on wide screens, two on tablets, one on phones. H3s end with a decorative arrow.

| # | H3 | Line | Links to |
| --- | --- | --- | --- |
| 1 | “Your books, connected” | “QuickBooks and Clover feed one assistant. No logging in to each system.” | `#one-place` |
| 2 | “Answers on your phone” | “Ask a question, or change what’s on the TV.” | `#phone` |
| 3 | “Questions you can ask” | “Cash, bills, sales, profit, the farm store and rent.” | `#questions` |
| 4 | “Your office TV dashboard” | “All six companies on one TV, with charts.” | `#tv-example` |
| 5 | “Your monthly options” | “Active building when you want new things. Upkeep when you don’t.” | `#monthly` |

### 3. Books connected — `#one-place`

**H2:** “Your books, connected”

**Intro:** “Right now each company’s numbers live in a different place. You keep using QuickBooks, Clover and your banks the way you do today. I connect them to one assistant, so the answers are in one spot.”

Use the diagram specification later in this plan.

### 4. Answers and TV controls on your phone — `#phone`

**H2:** “Answers and TV controls on your phone”

Benefit copy beside one phone mockup that is both the TV remote and the chat. Same command-center styling as the TV: dark screen, translucent cards, cyan selected chip, the assistant orb beside “Office TV”, and an orb-style microphone button. Static illustration: chips and composer are not real controls, and there is no real input field.

**Intro:** “Out on the property, in the truck or between meetings, just ask. The same app runs the office TV, so you can put up whatever you want to talk about before a meeting starts.”

**Points:**

- “**Pick what’s on the TV.** All six companies, one company, the farm store or your cash trend, with a tap.”
- “**Or just ask.** Say or type a question, or tell it what to put on the TV.”
- “**The same numbers** on your phone and on the wall.”

**Phone screen, top to bottom:**

1. Header “Office TV” / “Showing all six companies”, with an “Example data” tag.
2. A decorative miniature of the TV (navy band over six tiles).
3. “Show on TV” chips: “All six” (selected), “One company”, “Farm store”, “Cash trend”.
4. “Ask” conversation (example data, matching the TV):

| You say | Answer |
| --- | --- |
| “Put Velocity Builders on the TV.” | “Done. Velocity Builders is up: $94,200 in the bank and $12,800 past due.” |
| “How did the farm store do this weekend?” | “$8,420 in sales, up from $8,050 last weekend.” |
| “Show all six again.” | “All six companies are back on the TV.” |

5. A decorative composer bar, “Ask, or tell the TV what to show”, with a microphone button.

### 5. Questions — `#questions`

**H2:** “Questions you can ask”

**Intro:** “These are the kinds of things you said you want to know. We’ll pick your starter list together, and I’ll check every answer before you rely on it.”

Four grouped cards (two columns on wide screens), each question with a small decorative speech-bubble marker. All ten visible.

- **Cash:** “How much cash is in my connected bank accounts?” · “What’s the cash balance for each company?” · “What money moved between my connected accounts this week?”
- **Money owed:** “Who owes Velocity, Tiago and Dirt Kings money, and how much is past due?” · “What bills do my companies owe in the next 30 days?”
- **Sales and results:** “What did Velocity Builders do in sales this month?” · “What did each company make or lose this month and year to date?” · “What were the biggest expenses across the companies this month?”
- **Farm store and rent:** “How did the farm store do this weekend: sales, top sellers and anything running low?” · “Did both Thirty Acres tenants pay rent this month?”

The transfer question asks about recorded activity; it must never look like a command to move money.

### 6. TV example — `#tv-example`

**H2:** “Your office TV dashboard”

**Intro:** “All six companies on one screen, with your total cash across the top. When your operators come in to meet, you’re all looking at the same numbers.”

**Visible label, inside the mock TV:** “Example data, not your accounts”

Design: a restrained “business command center” look, with a little of an AI assistant’s presence but nothing theatrical. Dark screen (#050D19) with a faint grid and soft blue glow; translucent panels with thin hairlines and small cyan corner brackets; one cyan-blue data colour (#4CC3FF, latest period brightest, earlier periods dimmer) with a light glow on lines; monospace uppercase meta labels; large white numbers. A small glowing orb stands for the assistant. Live HTML text with inline SVG charts, no JS or chart library, no animation, and no live or connected indicators. No red or green; changes are written out in words. At ≥64em the screen is 16:9 with a 3×2 tile grid; two per row on tablets; stacked on phones. The same theme applies to both phones and the hero mockup.

**Summary band:** “Cash in connected bank accounts” $216,000, “Up $26,200 since June, across all six companies”, with a combined cash line chart (Jun to Now).

**Six tiles, largest cash first.** Each shows company name, bank cash, one small chart with a caption, and one footer fact:

| Company | Bank cash | Chart | Footer |
| --- | --- | --- | --- |
| Velocity Builders | $94,200 | Sales by month (Oct $121,800) | Past-due invoices $12,800 |
| Tiago LLC | $38,100 | Cash, June to now | Up $4,300 |
| Heritage Homestead LLC | $29,400 | Farm store sales, last 8 weekends | Farm store this weekend $8,420 |
| Dirt Kings | $24,700 | Cash, June to now | Down $3,200 |
| Thirty Acres LLC | $18,600 | Cash, June to now | Rent this month: 2 of 2 tenants paid |
| Bloomfield Property Group | $11,000 | Cash, June to now | Up $1,400 |

Invented example series (month-end cash Jun, Jul, Aug, Sep, Oct, now). Each line ends at the current balance, and the monthly values add up to the combined line:

- Velocity Builders 81,500 / 86,900 / 90,300 / 88,100 / 91,700 / 94,200
- Tiago LLC 33,800 / 35,200 / 34,100 / 36,500 / 37,200 / 38,100
- Dirt Kings 27,900 / 26,400 / 28,100 / 25,300 / 23,800 / 24,700
- Heritage Homestead LLC 21,800 / 24,600 / 27,300 / 28,900 / 30,100 / 29,400
- Thirty Acres LLC 15,200 / 15,900 / 16,700 / 17,200 / 17,900 / 18,600
- Bloomfield Property Group 9,600 / 10,200 / 10,800 / 10,400 / 11,300 / 11,000
- Combined 189,800 / 199,200 / 207,300 / 206,400 / 212,000 / 216,000
- Velocity Builders sales May to Oct: 96,400 / 108,700 / 102,300 / 117,900 / 112,600 / 121,800
- Farm store sales, last 8 weekends: 6,180 / 7,040 / 6,620 / 7,350 / 8,910 / 7,780 / 8,050 / 8,420

**Assistant briefing** along the bottom of the TV, with the orb: “Assistant: Cash is up $26,200 since June. Velocity Builders has $12,800 past due, and both Thirty Acres tenants have paid.”

Sales and receivables are never added into cash. Every chart is `aria-hidden` and has a hidden text sentence listing its values. No fake timestamp, live or connected status, or TV brand names.

**Below the TV, three points:**

- “**I set it up for you.** I buy and set up the computer that runs your TV.”
- “**All six companies at once.** Each one gets its own spot, with its cash and a chart.”
- “**You choose what’s on it.** Cash, money owed, sales, whatever you want your team to see.”

**Second example, below the points: “Ask, and the TV changes”** (H3)

**Intro:** “Before a meeting or on a Monday morning, ask your phone for what you want to see. The TV switches to it.”

A phone (left) beside a second TV (right) on screens 80em and wider; stacked phone-then-TV below that, so the TV keeps its 16:9 shape. Same styling as the main TV and the phone section. Static illustration.

- **Phone:** “Office TV” / “Showing farm store top sellers”, “Farm store” chip selected. You ask: “Show the farm store’s top sellers from this weekend on the TV.” Answer: “Done. Whole milk led with $1,640, then eggs at $1,260. Butter and eggs are running low.”
- **TV band:** “Heritage Homestead farm store, this weekend” $8,420, “Up $370 from last weekend”, with “Example data, not your accounts.”
- **Top sellers this weekend** (Top 5: $4,686): a ranked horizontal bar chart, not a pie. Thick bars on a shared $0–$1,750 scale with gridlines and a $0 / $500 / $1,000 / $1,500 axis; names in a left column, the dollar value at each bar’s end (inside the bar for the leader), units sold in a right column (hidden on narrow screens). The leader is the brightest bar.

| # | Item | Sold | Sales |
| --- | --- | --- | --- |
| 1 | Whole milk, gallon | 164 sold | $1,640 |
| 2 | Eggs, dozen | 210 sold | $1,260 |
| 3 | Tomatoes, lb | 180 lb | $630 |
| 4 | Butter, lb | 58 sold | $580 |
| 5 | Sweet corn, dozen | 72 sold | $576 |

- **Running low:** Butter, 6 lb left · Eggs, 12 dozen left · Whole milk, 9 gallons left.
- **Sales, last 8 weekends:** the same series as the main TV, ending at $8,420 (last weekend $8,050).
- **Assistant briefing:** “Milk and eggs led again. Butter is down to 6 lb, so it’s worth restocking before Saturday.”

### 7. Monthly options — `#monthly`

**H2:** “Your monthly options”

**Intro:** “We start with active development. When you have what you need and don’t want new features for a while, you can drop to maintenance.”

Two cards side by side on wide screens, stacked on phones. Active development is the primary card (blue border, larger); maintenance is quieter. Tick lists, no tier comparison table, discount or “most popular” tag.

**Active development — “$3,000 / month”**

- “I’m building for you every week: new connections, new views and the changes you ask for.”
- “A weekly update or short demo.”
- “Text or email me an idea any time, and we’ll fit it in.”
- “Everything in maintenance, too.”

**Maintenance — “$750 / month”**

- “Everything keeps running and stays connected.”
- “Security updates and fixes.”
- “No new features. Switch back to active development when you’re ready for more.”

**Below both cards, a navy “all inclusive” panel:**

**H3:** “Both options are all inclusive” — “No separate bills for the pieces it runs on.”

- **“Computer hardware”** — “The computer that runs your office TV, plus the KVM.”
- **“Cloud servers”** — “Private cloud networks (VPCs) and the compute your assistant runs on.”
- **“AI usage”** — “Up to $200 a month for the assistant.”

**Below the all-inclusive panel, a quiet tax note** (light card with a blue left border, like the documents list in next steps):

**H3 (small):** “A possible tax benefit”

“Your fees for active development are a business expense, and the new work I build for you may also qualify for the federal R&D tax credit. Talk with your accountant about what you can claim. I’ll provide the documentation you need to file: what we built, when, and the technical problems we worked through.”

Accuracy rules for this note: do not say that 100% of the fee qualifies for the R&D credit; do not quote percentages or dollar amounts of credit; do not promise the credit (keep “may also qualify” and the accountant line); keep it to active development (new work), not maintenance.

Term, notice and on-site work belong in the agreement.

### 8. Next steps — `#next-steps`

**H2:** “Next steps”

Three numbered step cards, stacked. No checkboxes and no requests for passwords on the page.

1. **“Sign the agreements”** — “Two short documents, so we both know where we stand.” Two side-by-side notes (stacked on phones):
   - **“Master services agreement”** — “The ground rules for working together: payment, confidentiality, how your data is handled, who owns the work, and how either of us can end it.”
   - **“Statement of work”** — “This project specifically: what I’m building, which monthly option you’re on, and what’s included.”
2. **“Give me access”** — “I’ll walk you through each one.” Check-outline list:
   - “QuickBooks invites for Velocity Builders, Tiago LLC and Dirt Kings.”
   - “Your OK on the read-only Clover connection.”
   - “A short session together to connect your bank accounts.”
   - “The Thirty Acres rent sheet or account.”
3. **“Tell me what you want to see”** — “Your questions and what you want on the TV. Notes or a voice memo are fine.”

Describe what each agreement covers in plain words only; actual terms live in the documents themselves.

### 9. Next step — `#next-step`

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

**Output nodes:** “Your phone” / “Ask, or change the TV” and “Your office TV” / “See the same numbers”

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
- [ ] Confirm `gh auth status` is authorized for BryanJBryce. Check `git status`, `git branch --show-current` and `git remote -v` in `/Users/bryan/bloomfield/proposal-site`. This folder already contains an initialized repository on `master` with no commits at planning time. Preserve unexpected existing work/remotes and reconcile them before running creation commands.
- [ ] Confirm the proposed repository name is available; if occupied, choose a fresh opaque suffix rather than touching that repository.
- [ ] Inspect every file to be committed and the staged diff. Stage explicit files, never the parent folder. Confirm the full history is suitable for a public repo; do not copy private source material, local QA captures or financial records into it.
- [ ] Create the initial commit, then the public repository and push. The following assumes the initial state described above and the required implementation files are present:

  ```sh
  cd /Users/bryan/bloomfield/proposal-site
  git add PLAN.md README.md .gitignore docs/index.html docs/styles.css docs/.nojekyll
  git diff --cached
  git commit -m "Add Bloomfield proposal page"
  gh repo create BryanJBryce/field-view-7d8c92f4b6e103aa --public --source=. --remote=origin
  git push -u origin master
  ```

  `gh repo create --source` associates the existing checkout; keeping the push separate makes the stages explicit. [GitHub CLI repository creation](https://cli.github.com/manual/gh_repo_create).

- [ ] Enable Pages from `master`, `/docs`. CLI option:

  ```sh
  gh api --method POST repos/BryanJBryce/field-view-7d8c92f4b6e103aa/pages \
    -f 'source[branch]=master' \
    -f 'source[path]=/docs'
  gh api repos/BryanJBryce/field-view-7d8c92f4b6e103aa/pages \
    --jq '{status, html_url, source, https_enforced}'
  ```

  This requires repository administration / Pages settings permission. If Pages is already enabled, inspect the existing configuration before changing it. Do not repeatedly POST. [Pages API](https://docs.github.com/en/rest/pages/pages).

- [ ] Alternatively enable it in GitHub: repository **Settings → Pages → Build and deployment → Deploy from a branch → master → /docs → Save**. Use either CLI or UI, not both. `.nojekyll` keeps this a plain-file deployment. [Publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
- [ ] Verify the Pages deployment reaches successful completion, HTTPS works, the reported URL serves the final page, relative CSS loads, and the robots meta is in the delivered HTML. A configured source or successful push alone is not proof of deployment.
- [ ] Repeat the mobile, wide-screen, keyboard, CTA and network checks on the actual project URL. Share the verified URL with Bryan for delivery to Craig; do not send it to Craig automatically.

## Acceptance checklist for the later review

Review the implementation against this checklist before any publication. Repeat deployment-dependent checks after publishing. Record the commit reviewed, widths/browser tested, defects and fixes, and any untested items. Do not describe source-only inspection as a completed visual or accessibility review.

### Content and scope

- [ ] All 9 sections appear in the specified order with final wording. Every H2 names something Craig gets, except “Next steps” and “Let’s talk.”
- [ ] No contract detail on the page: no on-site rate or hours, initial term, cancellation, “Not included” list, “to confirm” or “if practical” caveats.
- [ ] Monthly options show active development at $3,000 / month and maintenance at $750 / month, with what each includes, and the all-inclusive panel (hardware and KVM, cloud VPCs and compute, up to $200 a month of AI usage).
- [ ] Exactly three QuickBooks connections (Velocity Builders, Tiago LLC, Dirt Kings), read-only Clover for Heritage Homestead, Thirty Acres rent and expenses, Bloomfield Property Group company records, and up to 6 read-only bank accounts. No money movement is implied.
- [ ] Hero, phone mockup and TV all say example data; the TV says “not your accounts.” Values match this plan, six cash balances total $216,000, and the phone answers match the TV.
- [ ] Bryan buys and sets up the computer for the office TV. All six companies show at once, with charts. No panel-count language and no TV brand names.
- [ ] All ten questions are visible in four groups.
- [ ] Copy echoes Craig’s kickoff goals in plain words: no direct quotes, no prior software vendor names, nothing private from the call. Clover is connected, not replaced.
- [ ] No 12-week plan and no “what we can build next” section.
- [ ] “Next steps” starts with signing the master services agreement and statement of work, then access, then questions. No conditions and no request for passwords on the page.
- [ ] CTA gives a reply path without a form, invented email, dummy button, embedded scheduler or contract-acceptance behavior.
- [ ] First-person singular for Bryan; Craig is “you.” No percentages, hours, other clients or prior vendors. No em-dash-heavy or slogan copy.

### Visual and interaction review

- [ ] Inspect rendered views at 320, 390, 768, 1440 and 1920 CSS pixels wide; include a 1920×1080 TV-like view. Save representative mobile and wide screenshots outside the public repo. If actual TV viewing is unavailable, state that limitation.
- [ ] On a phone, the hero action is easy to reach; all source labels wrap; diagram flows downward; TV tiles stack and remain readable. No horizontal page overflow, clipped prices or overlapping arrows.
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
