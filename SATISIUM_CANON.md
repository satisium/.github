# SATISIUM

# Satisium Design — Master Reference Report

**Status:** Canonical Architecture Blueprint (Hollow Map v1)

**Scope:** Batch 1 of 3 — Chapters 1 to 3 (Vision, Complete Product Map & Monetization)

## Chapter 1: Vision, Philosophy & Ecosystem Boundaries

### 1.1 Core Thesis

**Holding Brand:** `SATISIUM` (*The Satisium Umbrella*)

**Guiding Law:** **"Everything is Code. Context is Premium."**

Modern software teams lose enormous speed translating visual intent back and forth across dead, proprietary silos (`.fig`, `.pptx`, `.aep`, closed web builders). Satisium eliminates that translation tax by treating every layer of product design—inspiration metadata, design tokens, behavioral motion, UI primitives, visual variants, and AI rules—as **raw, copy-owned, AI-legible code living directly inside Git**.

- **100% Code Ownership:** Users never lock their frontend into a proprietary runtime or closed cloud editor. Everything Satisium outputs is readable, modifiable, and standard enough for both human design engineers and AI coding agents to work on without friction.
- **Context as the Moat:** When humans and AI share the exact same structured, code-native constraints, iteration speed compounds instead of decaying into visual drift and broken logic.

### 1.2 The "Design in Code" Thesis (Replacing Figma Without Cloning It)

Satisium Design does **not** attempt to build a brittle drag-and-drop DOM clone of Figma in the browser. Instead, it deconstructs the **four real jobs** builders open Figma for and solves each one natively in code:

| **Job Currently Done in Figma** | **Why Traditional Design Tools Break Here** | **The Satisium Design-in-Code Replacement** |
| --- | --- | --- |
| **1. Gathering Taste & Direction** | Static screenshots stripped of real typography, color math, and interactive feel. | **Inspo + Mooderboard** capturing live web system DNA and synthesizing actionable design direction. |
| **2. 0 → 80% Layout & System Setup** | Hand-drawing static rectangles that must be rebuilt from scratch in React and Tailwind. | **Modular Design Studios + Satisium UI** dropping code-owned tokens, runtimes, and Dumb UI blocks straight into the repo. |
| **3. 80 → 100% Visual Craft & Exploration** | Tweaking mockups that lie about real responsive behavior, fonts, states, and motion physics. | **Tweak** editing props, states, and Git-like visual branches directly inside the live running app and writing winning changes back to source code. |
| **4. Stakeholder Review & Handoff** | Redlines, outdated prototypes, and endless Slack threads asking why production doesn't match Figma. | Live code branches, deterministic fixtures, and real-browser review with zero handoff translation layer. |

### 1.3 Umbrella Isolation (`Design` vs. `Labs`)

Satisium enforces a strict architectural, legal, and domain wall between its developer-tool ecosystem and its independent software ventures:

- **Part I — Satisium Design (`pillar: "design"`):** The unified, code-native frontend operating system and tool suite. Every product in this pillar lives strictly on **`.satisium.com`** subdomains (never `.dev`, `.io`, or `.app`), sharing umbrella brand equity, cross-subdomain analytics, and cohesive visual identity.
- **Parts II & III — Satisium Labs (`pillar: "labs"`):** Standalone consumer and B2B SaaS ventures hosted on completely isolated, independently acquirable domains. Satisium Labs is **strictly parked** during the current execution phase so 100% of energy goes into Satisium Design.

### 1.4 Broader ShipOS Alignment (Suites 1–8)

Satisium Design is built to stand completely on its own, while aligning cleanly with the long-term **ShipOS** 8-suite product lifecycle control plane so nothing needs to be rewritten later:

- **Suite 1 (Plan):** Git-stored discovery, strategy, scope fences, and lifecycle stages (adopted inside every Satisium Design repo from Day 1).
- **Suite 2 (Design):** Split into **Suite 2A (Brand & Frontend Design — *Satisium Design*)** and **Suite 2B (System & Data Design)**, which remains disabled for stateless local-first tools and activates cleanly only for stateful apps (e.g., Mooderboard cloud sync, Marketplace).
- **Suite 3 (Build):** Thin app core, pure headless logic, and Dumb UI assembly.
- **Suite 4 (Verify):** Linting, architectural boundary gates, automated tests, and accessibility checks.
- **Suite 5 (Ship):** Hosting, DNS, health checks, zero-key boot, and versioned releases.
- **Suite 6 (Commerce & Legal):** Legal pages across all apps; billing and entitlements activated strictly for paid products.
- **Suite 7 (Growth & Narrative):** SEO/AEO/GEO, social embeds, launch runbooks, community, and viral acquisition utilities.
- **Suite 8 (Intelligence):** Cross-subdomain telemetry, production error tracking, and user demand signals.

Satisium Design adopts the lightweight repo conventions of Suites 1–8 immediately without building a heavy central ShipOS dashboard prematurely.

### 1.5 Gen 0 → Gen 1 Bootstrapping Strategy

A common trap when building a suite of design tools is the **Stage-0 Compiler Paradox**: waiting to build real apps until every authoring studio exists. Satisium eliminates this deadlock through a two-generation bootstrap:

- **Gen 0 (Now):** Every Satisium Design repo reserves clean, standardized **Design System Sockets** populated with hand-authored Satisium baseline code. This lets you immediately build and ship high-priority products (`Tweak`, `Satisium UI`, studios) with zero waiting.
- **Gen 1 (As Studios Ship):** Each standalone authoring studio (`Color`, `Typography`, `Surface`, `Motion`) exports universal code plus its own AI rules snippet directly into those exact pre-existing sockets—upgrading every Gen 0 app cleanly with zero architectural rewrites.

## Chapter 2: Complete Satisium Design Product Map

Satisium Design is structured as **9 focused products** across a self-reinforcing **4-layer loop**:

> **Discover** (`Inspo`) → **Capture & Synthesize** (`Mooderboard`) → **Author** (`Color` / `Type` / `Surface` / `Motion` + `Ease`) → **Build & Craft** (`Satisium UI` + `Tweak`) → **Distribute & Monetize** (`Design System Marketplace`)
> 

Each product solves one sharp job and passes work cleanly to the next without forcing a user to adopt the entire suite on Day 1.

### Layer 1 — Discovery & Capture

#### Unified Product: **Inspo + Mooderboard** `[HOLLOW — TO BE DETAILED]`

One unified product built on a single underlying specimen engine, presented through two complementary surfaces:

- **Inspo (Curated Public Breakdown Gallery):** The SEO/viral front door curating strictly **shippable web and product craft** across seven concrete dimensions:
    1. **Complete System Breakdowns (Flagship):** End-to-end teardowns showing how typography, color, surface, motion, and launch assets work together as one coherent product identity.
    2. **Typography & Font Pairings:** Live-rendered font stacks (display, UI body, mono, editorial), scale rhythms, and numeric/tabular styling in real interfaces.
    3. **Color & Surface Craft:** Light/dark surface hierarchies, hairline border contrast, semantic palettes, elevation treatments, and ambient/shader surfaces.
    4. **Motion & Micro-Interactions:** Short, crisp interactive clips (sheet physics, dialog reveals, button feedback, tab morphs, transitions) that bridge naturally into `Ease` and `Motion Studio`.
    5. **UI Patterns & Functional Anatomy:** Real working interfaces categorized by job (dashboards, command palettes, pricing tables, settings, onboarding, empty/loading/error states, dense workbenches).
    6. **Launch, Brand & Social Artifacts:** OG images, app icons/squircles, favicons, changelog pages, GitHub social previews, hero 3D mockups, and launch trailers.
    7. **Copy & Microcopy Patterns:** Sharp headlines, concise feature callouts, empty-state copy, and crisp CTAs.
- **Inspo Anti-Bloat Fence (Explicit Exclusions):** Zero print design, packaging, physical industrial design, character illustration, generic photography, or unbuildable concept renders. Everything curated must translate directly into real shipped software.
- **Mooderboard (Private Design-Engineer Bookmarking & Capture Workbench):** The daily utility for saving references from Inspo *and* anywhere across the open web, covering three jobs:
    1. **Multi-Format Capture:** Lightweight browser extension + quick save for URLs, cropped regions, specific DOM elements, short motion clips, OG cards, font sightings, and copy snippets.
    2. **Automatic System DNA Extraction:** Captures live engineering metadata alongside visual screenshots (detected font stacks/weights, color swatches, spacing/radius cues, and OG/meta assets) so users never repeat manual DevTools inspections.
    3. **Project Boards & Direction Synthesis:** Organizes captures into project-scoped boards mapped to Satisium's design dimensions, with user annotations (*why* a reference was saved), feeding directly into Layer 2 studios and AI design context.
- **Rollout Discipline:** Starts tightly curated on Inspo and local-first + lightweight browser extension on Mooderboard before activating Suite 2B cloud sync, media storage, and team accounts.

### Layer 2 — Design System Authoring

Every core studio in Layer 2 owns a single, non-overlapping visual or behavioral dimension and stays **100% local-first and universal** (zero login required). Each studio independently exports clean, copy-owned code (Tailwind v4 / CSS / TypeScript) **plus** its own standalone AI design rules snippet—so it works seamlessly in *any* repository, not just Satisium apps.

- **Color Studio** `[HOLLOW — TO BE DETAILED]`
Perceptual OKLCH color architecture, light/dark surface stepping, semantic contrast locking, and `shadcn`compatible color outputs enforcing zero raw hex/gray drift.
- **Typography Studio** `[HOLLOW — TO BE DETAILED]`
Font pairing architecture, fluid type scales, optical alignment craft (such as cap-height/leading alignment, metric-matched fallbacks, `tabular-nums`, line-wrapping, and OpenType controls), and Next.js font loading outputs.
- **Surface Studio** `[HOLLOW — TO BE DETAILED]`
Geometry, spacing density, concentric border-radius relationships, dark/light hairline border contrast, multi-layered elevation, and stacking hierarchy.
- **Motion Studio (`motion.satisium.com`)** `[HOLLOW — TO BE DETAILED]`
System-level motion architecture—duration scales, semantic motion roles, Apple-style interruptible physics behavior (velocity-preserving retargeting), choreography, and global reduced-motion guarantees. **Strictly separated from `Ease`.**
- **Ease (`ease.satisium.com` — Standalone Utility — LIVE `v1.0.0`)**
Strictly a lean, local-first, MIT-licensed kinetic curve workbench for **previewing, customizing, duel-comparing, and exporting individual Bézier and Spring curves—and nothing else**. It never bloats into system-level motion tokens. Once `motion.satisium.com` ships, `Ease` gains one single zero-bloat bridge inside its Export flow to hand an active curve directly into Motion Studio via URL `#hash`.

### Layer 3 — Design-in-Code (Build & Craft)

- **Satisium UI & UI Pro (`ui.satisium.com` — CORE LIVE)**
    
    Open-code, `shadcn`-compatible animated primitives (free MIT core) paired with agency-grade Dumb UI SaaS blocks, complete application screens, and templates (`UI Pro`), built to drop directly into Satisium's design sockets.
    
- **Tweak (`tweak.satisium.com` + Embeddable Devtool — NEXT FLAGSHIP)** `[HOLLOW — TO BE DETAILED]`
    
    The live in-app visual workbench running directly inside a developer's local app: real-time component prop and variant editing, live state toggling, Git-like visual branching for exploring directions side by side, clean AST write-back of winning edits to source code, and guaranteed zero-byte production bundle stripping.
    
- **Satisium Format & Guardrails**
    
    The opinionated Next.js/`shadcn` repository standard—enforcing strict separation between pure headless `core/` logic and Dumb UI views, pluggable design system sockets, and mechanical linters so humans and AI can redesign UI rapidly without ever breaking application logic.
    

### Layer 4 — Distribution & Ecosystem Marketplace

#### **Design System Marketplace** `[HOLLOW — TO BE DETAILED]`

A distribution storefront that handles the **complete, pre-harmonized system** job for developers who do not want to piece four studios together manually. It distributes original, cleanly licensed, code-owned **Product Identity Packs** (Color + Typography + Surface + Motion + OG/Launch templates + unified `DESIGN.md` AI rules) that snap straight into Satisium's design sockets—or any standard Next.js/Tailwind repo.

- **Synergy with Inspo + Mooderboard:** Inspo captures high-intent discovery traffic; anonymous Mooderboard save trends act as a live demand radar showing exactly which aesthetics design engineers want most; the Marketplace converts that demand into one-click installable production systems.
- **Strict 3-Stage Rollout (Eliminating Cold-Start & Ops Risk):**
    1. **Stage 1 — First-Party Storefront:** Satisium publishes original, agency-grade systems directly (zero third-party payouts, moderation, or security-audit overhead).
    2. **Stage 2 — Open Community Registry:** PR-vetted free, open-source community systems submitted via GitHub, building supply, backlinks, and creator trust.
    3. **Stage 3 — Full Creator Marketplace:** Vetted third-party paid systems with automated security validation, creator payouts, and platform revenue share—launched *only* after Stages 1 & 2 prove steady weekly install demand.
- **Editorial Reference vs. Commercial Licensing Fence:** Inspo and Mooderboard exist strictly for editorial study and personal reference of live software. Every pack distributed on the Marketplace must be **100% original, cleanly licensed craft** (open-source fonts bundled directly; commercial foundry fonts wired strictly as bring-your-own swap-in slots)—never copied clones of third-party brands.

### Explicit Exclusions & Adjacent Placements (Anti-Bloat Policy)

- **Permanently Dropped Standalone Studios:** Dedicated Bento Grid, Shadow-only, Form-only, and Chart-only studios are permanently excluded. Layout/form/chart patterns belong inside `Satisium UI` as copy-owned blocks; elevation/shadows belong inside `Surface Studio`.
- **Downstream Suite 7 Acquisition Utilities (Adjacent, Not Core Design):** Code-native **3D Mockups / Launch Studio**, **Pitch Studio** (React web decks), and **Satisium Video UI** (Remotion-based motion/launch videos) remain cleanly positioned in Suite 7 (Growth & Narrative) as high-leverage viral launch utilities rather than bloating Satisium Design's core engineering focus.

## Chapter 3: Monetization & Commercial Architecture

### 3.1 Commercial Philosophy

Developers resist paying monthly rent for static code generators or local tools, gladly pay **one-time** for high-craft code assets they own permanently, and willingly pay **recurring** for real cloud sync, media storage, and team collaboration infrastructure. Satisium Design matches each product to the exact model developers trust.

### 3.2 The Complete Revenue Model

| Tier / Channel | Products Covered | Revenue Model | Primary Strategic Role |
| --- | --- | --- | --- |
| **Tier 1 — Free & Open-Source Wedges** | `Ease`, `Satisium UI` (core primitives), public `Inspo`, solo/universal exports across Layer 2 Studios, `Tweak` Core (local solo workflow), and the open Satisium Format/Guardrails. | **$0 (MIT / Free)** | Drives GitHub stars, X virality, SEO/AEO dominance, Discord community growth, and zero-friction standard adoption of the Satisium format. |
| **Tier 2 — High-Margin Code Assets** | `Satisium UI Pro` (SaaS blocks, screens, templates), Stage 1 First-Party Design System Packs, and **Satisium All-Access Pass** (code bundle). | **One-Time / Tiered Lifetime Deal** *(Solo / Team / Agency tiers)* `[HOLLOW — TO BE DETAILED]` | Generates immediate, high-margin Year-1 cashflow with near-zero ongoing server cost—funding the ecosystem independently. |
| **Tier 3 — Cloud & Team Workspace** | **Satisium Pro Workspace:** Cloud-synced `Mooderboard` (extension sync, unlimited boards, media storage, AI synthesis) and **`Tweak` Team** (shareable review branches & client/team handoff). | **Recurring SaaS** *(Monthly / Annual seat or workspace)* `[HOLLOW — TO BE DETAILED]` | Builds durable MRR strictly tied to features carrying genuine ongoing cloud, storage, sync, or team collaboration value. |
| **Tier 4 — Ecosystem Marketplace** | Stage 3 **Design System Marketplace** (vetted third-party creators selling code-owned system packs and UI block packs). | **Platform Take-Rate / Commission** `[HOLLOW — TO BE DETAILED]` | Compounds ecosystem revenue and catalog breadth without requiring Satisium to personally author every design system. |
| **Side Stream — Open-Source Backing & Direct Sponsors** | **GitHub Sponsors** (corporate README/docs logo tiers, active immediately) + **Direct Tool Sponsorships** (1–2 curated monochrome slots on high-traffic public pages like `Inspo` once clearing 50k+ monthly dev visits). | **Monthly Recurring / Flat Slot Fee** *(e.g., $250–$2,000/mo)* | Adds prestige logos and high-margin side revenue without ad-blocker loss or visual clutter. |

### 3.3 Five Non-Negotiable Commercial Guardrails

1. **Zero Unbounded Ongoing Costs Inside Lifetime Deals:** One-time LTDs strictly cover **code-owned assets** (`UI Pro`, first-party system packs, local tools). Anything incurring recurring cloud storage, media bandwidth, or LLM token costs lives strictly inside the recurring SaaS tier—and every AI-powered feature enforces **BYOK (Bring Your Own Key)** or strict monthly credit caps so heavy usage never turns unprofitable.
2. **One Unified Account & Entitlement Layer:** A single Satisium identity or license key unlocks everything a customer owns across every `.satisium.com` subdomain—never fragmented logins or separate billing accounts per tool.
3. **Merchant of Record (MoR) First:** All global commercial billing runs through a Merchant of Record (such as Polar, Paddle, or Lemon Squeezy) to automate international VAT/GST/sales-tax compliance, invoicing, and eventual creator payouts cleanly without manual tax administration. `[HOLLOW — TO BE DETAILED]` *(final provider selection deferred until first paid launch gate)*.
4. **Clean Asset & Font Licensing:** Paid code packs bundle only permissively licensed code and open-source fonts, keeping commercial font licenses strictly external and user-supplied.
5. **Zero Display Ad Networks (House Ads & Curated Sponsors Only):** Never run Google AdSense or generic dev ad networks (e.g., Carbon) inside Satisium tools—they lose 50–70% to developer ad blockers and cheapen visual trust. Prioritize house cross-promotion (`Satisium UI Pro`, `Tweak`) from Day 1, and reserve 1–2 curated, monochrome direct devtool sponsorships strictly for high-traffic public pages once clearing 50k+ monthly visits.

### 3.4 Three-Wave Commercial Rollout (Matched to Build Sequence)

Monetization activates progressively alongside real product launches—never ahead of product utility:

- **Wave 1 (Fastest Cashflow):** Free acquisition wedges (`Ease`, `Satisium UI` core, `Tweak` Core) build developer traffic and trust → convert directly into **`Satisium UI Pro` (LTD)**.
- **Wave 2 (System Monetization):** Authoring Studios (`Motion`, `Color`, `Type`, `Surface`) prove and standardize the pluggable Satisium sockets → launch the **Stage 1 First-Party Design System Storefront** (individual packs + All-Access Pass).
- **Wave 3 (Recurring Scale & Platform):** Launch cloud-synced **Inspo + Mooderboard** + **`Tweak` Team** recurring SaaS → graduate the Storefront through Stage 2 (Open Community Registry) into the **Stage 3 Creator Marketplace**.

Review **Batch 1 (Chapters 1–3)** closely—let me know if anything needs adjustment, addition, or sharper wording, or give the green light and I will generate **Batch 2 (Chapters 4–6: The 5-Zone Hollow App Skeleton, 3-Layer Template & Sync Architecture, and End-to-End Execution Lifecycle)**.

# Satisium Design — Master Reference Report

**Status:** Canonical Architecture Blueprint (Hollow Map v1)

**Scope:** Batch 2 of 3 — Chapters 4 to 6 (The 5-Zone Hollow App Skeleton, 3-Layer Template & Sync Architecture, and End-to-End Execution Lifecycle)

## Chapter 4: The 5-Zone Hollow App Skeleton (Inside Every Satisium Repo)

Every Satisium Design repository—whether a lean stateless utility like `Ease`, a developer tool like `Tweak`, or a stateful workspace like `Inspo + Mooderboard`—shares the exact same **5-zone internal architecture**. Zones that a specific tool does not need remain cleanly disabled rather than being cloned and manually pruned.

### 4.1 Zone 1 — Identity & Umbrella Envelope

The non-negotiable metadata and legal wrapper that binds every standalone repo back to the Satisium family:

- **Single Source of Truth (`config/site.ts`):** Centralizes product identity, taxonomy (`ecosystem`, `pillar`, `cluster`, `product_type`, `app_id`, `app_name`), repository metadata, author handles, and canonical URLs so no other file ever hardcodes product strings.
- **Strict Domain Purity:** Enforces `.satisium.com` for all `pillar: "design"` apps and strictly isolated domains for `pillar: "labs"` apps.
- **Brand Lockup & Umbrella Navigation:** Standardized `"A tool by Satisium"` attribution, consistent visual icon/squircle mark, and a lightweight Satisium App Switcher linking users across the suite.
- **Dependency-Free Legal Surfaces:** Standard `/privacy`, `/terms`, and `/cookies` pages rendered via a lightweight, zero-Fumadocs Markdown parser so legal compliance never drags heavy documentation frameworks into lean apps.

### 4.2 Zone 2 — Plan & Lifecycle Zone (Suite 1)

A product's strategy, scope boundaries, and current release stage live **inside its own Git repository**—never buried in forgotten chat logs or external boards—so humans, AI coding agents, and eventually ShipOS always share the same ground truth.

#### A. Versioned Planning Artifacts (`.satisium/plan/`) `[HOLLOW — TO BE DETAILED]`

Six modular, version-controlled files (any file irrelevant to a tool's archetype is cleanly omitted or disabled):

1. **`charter.md`:** Product thesis, PR/FAQ, target audience, and brand positioning.
2. **`releases.json`:** Explicit release milestones with hard **in-scope vs. out-of-scope fences** for each stage, preventing AI scope creep and premature feature sprawl.
3. **`flows/*.flow.yaml`:** Deterministic user journeys, required routes, explicit UI states (`empty`, `loading`, `error`, `active`), and interaction shortcuts shared across UI design and automated tests.
4. **`domain-glossary.json`:** Canonical domain nouns locked across UI copy, TypeScript types, and AI prompts to eliminate naming drift.
5. **`topology.json`:** Declares the app's archetype (e.g., stateless local-first workbench vs. stateful cloud SaaS) and explicitly toggles which ShipOS suites and Opt-In Capabilities are **active** versus **disabled**.
6. **`business-model.json` *(Optional)*:** Pricing tiers and entitlement boundaries—present only for commercial tools and disabled cleanly for free MIT utilities.

#### B. Canonical Product Lifecycle Stages & Progressive Gates

Every repo declares its active lifecycle stage, which automatically filters what both humans and AI should care about right now:

| **Lifecycle Stage** | **Core Objective** | **Stage Gate Focus (What Matters Here)** |
| --- | --- | --- |
| **`pre-beta` / `alpha`** | Prove the core engine and interaction loop. | Pure headless `core/` works, Dumb UI boundaries hold, zero-key boot passes, basic smoke tests pass. *External launch ops stay suppressed.* |
| **`beta`** | Validate with early design engineers. | Consent-gated analytics + error tracking active, early feedback loop open (Discord/GitHub), core docs or interactive playground usable, major flows covered. |
| **`v1` (Public Launch)** | Full public release into the Satisium umbrella. | Full technical verification (`pnpm verify`) **plus** every external umbrella gate in `.satisium/readiness.json` (DNS, PostHog super-properties, SEO/JSON-LD, `llms.txt`, verified `/api/og`, legal, changelog, Discord launch, app switcher). |
| **`v2+` (Major Evolution)** | Planned architectural or capability expansion. | New scope fence locked in `releases.json` before code begins; contract changes explicitly versioned. |
| **`finished` (Maintenance)** | Feature-complete, stable ecosystem asset (e.g., `Ease` `v1.x`). | Accepts bug fixes, security patches, and Umbrella Spine syncs only; zero unplanned feature creep. |
| **`archived`** | Graceful sunset if a tool is retired. | Frozen read-only repository with a clear static notice. |

#### C. Governance Speed & External Ops Tracking

- **The Fast-Path Patch Lane:** Minor visual polish, bug fixes, copy edits, and non-breaking internal improvements after launch bypass full Suite 1 spec ceremony so planning discipline never slows down day-to-day craftsmanship.
- **External Readiness Tracker (`.satisium/readiness.json`) `[HOLLOW — TO BE DETAILED]`:** Tracks every non-code, human-verified umbrella requirement (DNS mapping, live PostHog event checks, OG embed visual inspection, Discord setup, announcement posts) with explicit `"pending" | "done" | "skipped"` states evaluated against the active release stage.

### 4.3 Zone 3 — Design System Sockets `[HOLLOW — TO BE DETAILED]`

Reserved, non-overlapping plug-in slots built directly into the repo so every dimension of a design system—**Color**, **Typography**, **Surface**, **Motion**, and **AI Design Rules**—remains modular, copy-owned, and swappable.

- **Architected for Foolproof Craft (Not Flat Variables Alone):** Each socket is designed to accommodate up to four coordinated layers once its owning studio is finalized:
    1. **Static Token Layer:** CSS / Tailwind v4 variables and utility definitions.
    2. **Behavioral Runtime & Thin Primitives Layer:** Copy-owned TypeScript engines, hooks, or thin React wrappers where CSS alone cannot guarantee craft (such as Apple-style velocity-preserving interruptible motion or optical typography helpers).
    3. **AI Behavioral Rules:** Concise domain Do's and Don'ts merged into the repo's design context so agents never break subtle craft.
    4. **Studio-Specific Mechanical Lint Plug-In:** Automated ESLint / `doctor` rules shipped by that studio to catch violations mechanically.
- **Strict Namespace Ownership:** No two design sockets write to or override the same concern, enabling clean Gen 0 (hand-authored baseline) → Gen 1 (studio-generated drop-in) upgrades with zero repo refactoring.

### 4.4 Zone 4 — Strict Code Separation (Headless Core + Dumb UI)

The structural foundation that enables fast AI iteration, deterministic testing, and `Tweak`'s live in-app visual editing without ever risking application logic.

- **Headless `core/`:** 100% pure TypeScript domain logic, schemas, state machines, and pure reducers. **Zero** React, DOM, `window`, or framework imports allowed.
- **Prop Contracts (`.contract.ts`):** Explicit, serializable TypeScript interfaces defining the exact surface between logic and presentation.
- **Dumb UI Views (`.view.tsx`):** Pure visual presentation components driven strictly by props and strictly ephemeral local visual state (such as hover, open popover, or focus rings). Domain state management, `useEffect`, `fetch`, `localStorage`, router hooks, and global stores are **mechanically banned**.
- **Deterministic Fixtures (`.fixtures.ts`):** Static mock states (`empty`, `loading`, `error`, `populated`, edge cases) allowing every view to be rendered, visually inspected, and edited in complete isolation without running backend logic or live stores.
- **Thin Glue Containers (`.container.tsx`):** Minimal wiring layer that connects `core/` state, browser side effects, and actions to Dumb UI views.
- **Imperative 120fps Performance Paths:** High-frequency interactive surfaces (such as motion playgrounds, scrubbers, or canvas clocks like `Ease`'s `TrackConductor`) bypass React render cycles via isolated imperative DOM/RAF conductors while keeping state boundaries clean.
- **Practical React & Next.js Escape Hatches:** To prevent rigid purity from causing boilerplate bloat, three pragmatic exceptions are explicitly permitted:
    1. **Static & Content Pages:** Purely static routes (e.g., legal pages, simple marketing copy) do not require artificial container/contract ceremony.
    2. **React Server Components (RSC) as Containers:** Server Components may fetch data directly and pass plain serializable props straight into Dumb UI views—eliminating redundant client container wrappers.
    3. **Slot-Based Composition:** Complex layouts use React `children` / named slot props to avoid prop-drilling explosions while keeping every individual leaf view pure and isolated.

### 4.5 Zone 5 — Opt-In Capabilities

Blank architectural slots activated strictly when declared in `.satisium/plan/topology.json`:

- **Marketing & Landing Surfaces** (hero, features, comparison, pricing).
- **Documentation Engine** (interactive docs, multi-pane layouts, automated `llms-full.txt` generation).
- **Component & Block Registry** (`shadcn`compatible previewer and registry build pipeline).
- **Auth, Database & Backend (Suite 2B)** (activated strictly for stateful products like cloud `Mooderboard` or `Marketplace`; completely absent from local-first tools).
- **Billing, Commerce & Entitlements (Suite 6)** (unified Merchant of Record + license checks; completely absent from free MIT tools).

## Chapter 5: The 3-Layer "Template" & Sync Architecture

### 5.1 Why Monolithic Starter Templates Fail

Cloning a "kitchen-sink" starter repo that bundles documentation frameworks, Redis hooks, multiple landing presets, registries, and a dozen root manuals forces every new product into **prune-first debt**:

- Stripping unused features leaves behind ghost paths in dead-code, test, and env configs.
- Unused directories and conflicting docs distract AI coding agents.
- Every engineering improvement invented in a real app (such as `Ease`'s pure `core/`, fixed PostHog consent, monochromatic OG card, and zero-Fumadocs legal renderer) becomes trapped inside a one-way fork instead of flowing cleanly back to the ecosystem.

Satisium permanently replaces the monolithic template with a **3-layer modular foundation**.

### 5.2 Layer 1 — Bare Starter Core `[HOLLOW — TO BE DETAILED]`

A razor-thin Day-0 Next.js + Tailwind v4 + `.satisium/` repository shell containing **only** what every single Satisium app requires from Minute 1:

- Zero unused marketing presets, zero bundled docs engines, zero backend/DB clients.
- Guaranteed **Zero-Key Boot Rule**: strict parity between runtime env validation and `.env.example` so every freshly initialized repo boots, builds, lints, and passes unit tests with a completely empty `.env.local`.
- Pre-wired 5-Zone Hollow App Skeleton and base mechanical enforcement scripts.

### 5.3 Layer 2 — Syncable Umbrella Spine `[HOLLOW — TO BE DETAILED]`

The shared operational layer common across all `*.satisium.com` products—maintained as a clean, versioned spine that pushes improvements forward into existing repos via reviewable PR diffs rather than manual copy-pasting:

- Cross-subdomain PostHog proxy (`/ingest`), consent gate, 6 mandatory umbrella super-properties, and error observability wiring.
- Monochromatic dynamic `/api/og` card and PWA/app icon baseline.
- Dependency-free Markdown legal renderer (`/privacy`, `/terms`, `/cookies`).
- Umbrella SEO/AEO/GEO helpers (JSON-LD graph, AI-welcoming `robots.ts`, `sitemap.ts`, `llms.txt` conventions).
- Base OKLCH semantic tokens, Satisium shell motion baseline, `/api/health` endpoint, shared ESLint boundary rules, and `scripts/doctor.mjs`.

### 5.4 Layer 3 — Opt-In Module Registry `[HOLLOW — TO BE DETAILED]`

All high-craft optional blocks previously packed into the monolithic starter—landing/hero presets, pricing sections, Fumadocs layouts (`spatial` and `three-pane`), component registry/previewer, and Redis/telemetry extensions—extracted into clean, add-on-demand modules pulled **only** when a tool's `topology.json` activates them.

### 5.5 Governance: The Rule of Two

To keep both the Bare Starter Core and the Syncable Umbrella Spine permanently lean, Satisium enforces the **Rule of Two**:

> **No abstraction, utility, helper, or operational file enters `satisium-core` or the Umbrella Spine until at least two real, shipped Satisium apps independently prove the need for it.**
> 

One-off experiments live cleanly inside the single product repo that needs them until a second product confirms they belong to the family.

## Chapter 6: End-to-End Execution Lifecycle (Build → Develop → Deploy → Maintain)

This four-phase operating loop removes ecosystem complexity from human memory and prevents AI drift across the full life of every tool.

### 6.1 Phase 1 — BUILD (Brainstorm-to-Setup)

*Goal: Move from a finished architecture brainstorm to a clean, compliant repo shell in minutes—with zero manual pruning.*

1. **Free Product Brainstorming:** Ideate architecture, core mechanics, and user flows in any AI chat without worrying about umbrella boilerplate.
2. **Portable Blueprint Handoff (`SATISIUM_CANON.md` + `SATISIUM_BLUEPRINT.md`) `[HOLLOW — TO BE DETAILED]`:** Once the idea is clear, drop the compact portable Satisium Blueprint into the chat. The AI maps the product onto the 5-Zone Skeleton and outputs two concrete artifacts:
    - A structured **`product.manifest.json`** (slug, pillar, cluster, archetype, active opt-in modules, initial Suite 1 scope fences, North-Star milestone events, and core SEO copy).
    - A scoped **coding kickoff prompt** tailored to the coding agent.
3. **Deterministic Setup (Script, Not Manual AI Edits):** Feed `product.manifest.json` into a deterministic initialization step on top of the Bare Starter Core. It populates `config/site.ts`, pulls only requested Opt-In Modules, scaffolds `.satisium/plan/` and `.satisium/readiness.json` (all external gates set to `"pending"`), and leaves zero ghost paths behind.
4. **Day-0 Shell Lock:** Confirm `pnpm doctor` and `pnpm dev` pass green on an empty `.env.local` before writing the first line of product code.

### 6.2 Phase 2 — DEVELOP (Zero-Drift Human + AI Loop)

*Goal: Keep coding agents fast, focused, and mechanically incapable of violating design or architecture boundaries.*

1. **Universal Cross-IDE Context Router (`AGENTS.md`):** One compact (<60-line) `AGENTS.md` at repo root (with `CLAUDE.md` pointing directly to it so Cursor, Claude Code, VS Code, and other agents read one source) routes agents strictly to **task-scoped rule files** inside `.satisium/org/` `[HOLLOW — TO BE DETAILED]`:
    - Design rules (loaded for UI/visual tasks).
    - Engineering & boundary rules (loaded for `core/` and wiring tasks).
    - SEO & Analytics rules (loaded only when touching metadata, routes, or telemetry).
    - Brand, Social & Launch rules (never loaded into pure React/TypeScript coding sessions).
    - App-specific specs & explicit documented overrides (`.satisium/app/`).
2. **Auto-Generated Reality (`.satisium/generated/repo-facts.json`):** A lightweight sync script scans the actual repository on disk (routes, key files, env keys, exports, test counts) so agents read live ground truth—permanently eliminating hand-maintained context packs that go stale after refactors.
3. **4-Layer Mechanical Enforcement:** Prose rules get ignored under deep context; mechanical gates do not. Every repo enforces quality across four layers:
    - **Layer 1 — ESLint AST Rules:** Blocks React/DOM imports inside `core/**`; blocks stores, `useEffect`, `fetch`, `localStorage`, and router hooks inside `*/*.view.tsx`; blocks raw `keydown` listeners outside centralized hotkey handlers (unless explicitly whitelisted in app overrides).
    - **Layer 2 — Zero-Provider Isolation Cage:** Renders Dumb UI views and their `.fixtures.ts` inside an isolated local harness with **zero** global auth, store, or router providers—proving mechanically that views are 100% pure and `Tweak`ready.
    - **Layer 3 — Repository Invariant Doctor (`scripts/doctor.mjs`):** Validates domain purity, OKLCH-only tokens, zero raw grays/hex, zero Tailwind slash-opacity modifiers, typed `ROUTES`, zero-key env parity, and confirms every file path referenced in `AGENTS.md`, `knip.json`, and `vitest.config.ts` actually exists on disk.
    - **Layer 4 — Human Diff Clarity:** Clear separation of `core/`, `.view.tsx`, and `.container.tsx` keeps PRs scannable in seconds.
4. **Strict Agent Git Boundary:** AI agents never execute autonomous `git commit`, `git push`, `git reset`, or release commands—human review remains the final checkpoint.

### 6.3 Phase 3 — DEPLOY (Stage-Aware Release Gates)

*Goal: Eliminate forgotten analytics, broken OG cards, stale `llms.txt`, and missed Discord/GitHub steps—without relying on fragile passive AI reminders.*

1. **Automated Technical Gate (`pnpm verify`):** Runs linting, TypeScript strict typecheck, Vitest unit suite with coverage, Playwright + Axe accessibility verification, Knip dead-code detection, and production `next build`.
2. **Pull-Based Stage-Filtered Readiness Audit (`pnpm doctor --release`):** Instead of hoping an AI spontaneously remembers a 40-item launch list mid-debug, release readiness is pulled explicitly at milestone boundaries. `pnpm doctor --release` reads the current target stage in `.satisium/plan/releases.json` (`alpha`, `beta`, or `v1`) alongside `.satisium/readiness.json` and blocks tagging until every automated check and every required human gate for that stage is marked `"done"` (or explicitly `"skipped"` with a reason).
3. **Structured Release Pipeline:** Uses conventional commits (`commitlint` + Husky + `lint-staged`) and Changesets to generate accurate `CHANGELOG.md` entries and clean versioned releases.

### 6.4 Phase 4 — MAINTAIN (Low-Burn N-Repo Operations)

*Goal: Run 5–10 live Satisium tools sustainably as a solo founder without drowning in weekend maintenance.*

1. **Umbrella Spine Sync:** Improvements made to shared operational files (legal parser, OG template, PostHog consent, `doctor.mjs`, ESLint boundary configs) sync cleanly across every active and maintained repo via automated diff PRs—ending fork drift permanently.
2. **Org-Level GitHub Inheritance (`[github.com/satisium/.github](https://github.com/satisium/.github)`):** Centralizes `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, and Issue/PR templates at the GitHub organization level so they are inherited automatically across every `satisium/*` repo instead of being duplicated and maintained `N` times.
3. **Grouped Dependency Hygiene:** Weekly grouped Dependabot/Renovate PRs (one batched patch/minor PR per repo rather than dozens of noisy individual alerts).
4. **Always-On Observability:** Zero-extra-vendor PostHog Error Tracking (respecting consent and `/ingest` proxy) paired with lightweight uptime monitoring on `/api/health` across every live `.satisium.com` subdomain.
5. **Strict Portfolio Focus (`active` vs. `finished` vs. `archived`):** At most **1–2 repos** remain in `active` feature development at any time. Feature-complete tools graduate cleanly into `finished` (maintenance mode), protecting founder energy for the next high-leverage build.

Review **Batch 2 (Chapters 4–6)** closely—let me know if anything needs refining or if we are locked and ready for **Batch 3 (Chapters 7–10: The 8 Umbrella Operational Standards, Current Reality Audit, Immediate Execution Roadmap, and the Complete `[HOLLOW]` Fill-In Register)**.

# Satisium Design — Master Reference Report

**Status:** Canonical Architecture Blueprint (Hollow Map v1)

**Scope:** Batch 3 of 3 — Chapters 7 to 10 (The 8 Umbrella Operational Standards, Current Reality Audit, Immediate Execution Roadmap & The `[HOLLOW]` Fill-In Register)

## Chapter 7: The 8 Umbrella Operational Standards (Cross-App Consistency Checklist)

Every product under `*.satisium.com` adheres to these eight operational pillars so the entire ecosystem feels engineered by one cohesive studio—never like disconnected side projects.

### 7.1 Identity, Domain Purity, App Switcher & Cross-Product Handoffs

- **Brand Lockup:** Unified `SATISIUM` holding brand, `"A tool by Satisium"` attribution, `#f2470c` brand accent, and consistent squircle icon mark.
- **Domain Purity:** `pillar: "design"` apps live strictly on `.satisium.com` subdomains; `pillar: "labs"` apps live strictly on independent, acquirable domains.
- **Single Config Source:** All product identity, taxonomy, legal, author, and repo metadata flows from `config/site.ts`.
- **Ecosystem Navigation & Handoffs:** Shared lightweight **Satisium App Switcher** connecting live tools, plus one-click **cross-product state handoffs** (such as passing a curve via URL `#hash` from `ease.satisium.com` directly into `motion.satisium.com`).

### 7.2 Design System & Visual Craft Rules

- **OKLCH Semantic Tokens Only:** All styling consumes semantic tokens (`bg-background`, `bg-muted`, `bg-card`, `text-foreground`, `border-border`). Raw hex/RGB values, raw Tailwind grays, and Tailwind slash-opacity modifiers (e.g., `bg-secondary/70`) are mechanically banned.
- **Typography & Motion Discipline:** Centralized typography stack (`Plus Jakarta Sans`, `Inter`, `IBM Plex Mono`, `Newsreader`, `Caveat`, `Nulshock`) and centralized shell motion tokens (`lib/motion.ts` — `SPRING.*`, `EASE.*`, `DURATION.*`, and `SATISIUM_*` "Quiet Precision" shell transitions).
- **Open-Code Craft:** `shadcn` open-code primitives, smooth view-transition theme switching (`lib/theme-transition.ts`), and borderless/shadowless doc surfaces when documentation is enabled.

### 7.3 Engineering, Accessibility & Security Hygiene

- **Zero-Key Boot Rule:** Strict parity between runtime env validation (`lib/env.ts`) and `.env.example` so every repo boots, lints, tests, and builds cleanly with an empty `.env.local`.
- **Centralized Primitives:** Typed `ROUTES` (zero literal `href="/..."`), centralized `lib/nav.ts`, `lib/hotkeys.ts`, and `lib/logger.ts` (zero `console.log`).
- **Type & A11y Discipline:** Zero `any`, zero `as unknown as`, mandatory `aria-label` on all icon-only buttons, and desktop workstation guard (`min-width: 1024px`) for dense studio workbenches.
- **Security Headers:** Centralized CSP (`lib/csp.mjs`), HSTS, and `X-Robots-Tag: noindex` on internal or non-public routes.

### 7.4 Unified Analytics, Consent & Error Observability

- **Consent-First Telemetry:** Explicit consent gate (`localStorage["satisium-analytics-consent"]` + `ConsentBanner`) before firing tracking events.
- **First-Party Cross-Subdomain PostHog:** Proxied through `/ingest` rewrites with `cross_subdomain_cookie: true`, `person_profiles: "identified_only"`, and `disable_session_recording: true`.
- **6 Mandatory Super-Properties:** `ecosystem`, `pillar`, `cluster`, `product_type`, `app_id`, and `app_name` attached to every event across the suite.
- **Milestone-Only Event Quota:** Track high-signal demand milestones (copy, export, mode switch, branch apply, search)—never noisy continuous drags or scroll spam.
- **Production Observability:** PostHog Error Tracking (respecting consent and `/ingest`) for silent client-side crashes, paired with lightweight uptime monitoring on `/api/health` across every live domain.

### 7.5 SEO, AEO & GEO (Search & AI Discoverability)

- **Umbrella Knowledge Graph (JSON-LD):** Links every product back to `Organization: The Satisium Umbrella` using structured `WebSite`, `Organization`, `WebApplication` (with `featureList`), `SiteNavigationElement`, `FAQPage`, `WebPage`, `BreadcrumbList`, and `SoftwareSourceCode` schemas.
- **AI Crawler Access:** `robots.ts` explicitly welcomes AI crawlers (`GPTBot`, `ClaudeBot`, `PerplexityBot`, `Google-Extended`, `Applebot-Extended`).
- **Machine-Readable Docs & Context:** Accurate `public/llms.txt` declared in `alternates.types` (plus `llms-full.txt` and per-page `.md` generation for doc-enabled apps), prioritized `sitemap.ts`, and strict metadata length budgets (`defaultTitle ≤ 60 chars`, `description 120–155 chars`).

### 7.6 Social, Dynamic OG Cards & Legal

- **Monochromatic Dynamic `/api/og`:** Standardized `1200×630` OG card (`#f8f8f8` outer frame, `#090809` dark inner card, inline Satisium mark, `#f2470c` accent, `"A tool by Satisium"`, `PlusJakartaSans-Bold.ttf`) paired with Twitter `summary_large_image` (`@iamsatish4564`) and complete PWA/app icon suite.
- **Lightweight Legal Surfaces:** `/privacy`, `/terms`, and `/cookies` rendered via the dependency-free Markdown legal parser and `LegalFooter`.

### 7.7 GitHub Org, Releases & CI Gates

- **Org-Level Inheritance (`[github.com/satisium/.github](https://github.com/satisium/.github)`):** Centralizes `CODEOWNERS`, `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, and Issue/PR templates at the org level so every `satisium/*` repo inherits them automatically under MIT (for open-source tools).
- **Automated Quality Pipeline:** Husky + `lint-staged` + `commitlint` (conventional commits), Changesets + `CHANGELOG.md`, grouped weekly Dependabot PRs, `pnpm doctor`, and `pnpm verify` (`lint`, `typecheck`, Vitest with coverage, Playwright + Axe WCAG audit, Knip dead-code check, Lighthouse CI, and production build).

### 7.8 Community, Discord, Audience & Launch Runbook

- **Central Satisium Discord Server:** Shared umbrella spaces (`The Lobby`: `#announcements`, `#welcome`, `#the-journal`; `Community`: `#introductions`, `#general`, `#design-engineering`, `#showcase`, `#founders`) paired with either a dedicated 3-channel product category (`#<slug>-support`, `#<slug>-chat`, `#<slug>-requests`) for flagship tools or a shared tagged forum for smaller utilities—seeded with a standardized kickoff post linking Live URL + GitHub repo (which also live-tests both OG embeds).
- **Owned Audience Capture:** One unified, low-noise **Satisium Changelog / Studio Drops** mailing list (or release digest) shared across all free tools so viral traffic converts into a launch audience you own.
- **Repeatable Launch Runbook `[HOLLOW — TO BE DETAILED]`:** Standardized release-week checklist covering demo video spec, X thread structure, Show HN / Reddit / Product Hunt timing, Discord `#announcements` + `#the-journal` posts, and cross-linking across live apps.

## Chapter 8: Current Reality Audit (Grounded Baseline)

No assumptions or speculative rewrites—this is the exact state of every existing asset today and the single clean action required for each:

| **Asset** | **Current Reality** | **Immediate Action** |
| --- | --- | --- |
| **`ui.satisium.com`** | Live open-source, `shadcn`-compatible animated React component library hosted on Vercel (built prior to the new template spine). | **Light external Umbrella Spine alignment only** (PostHog super-properties/proxy, `/api/og`, `llms.txt`, legal). Do **not** rewrite internals. |
| **`ease.satisium.com`** | Shipped `v1.0.0` local-first curve workbench proving pure headless `core/`, 120fps `TrackConductor`, 40 Vitest files, fixed PostHog consent, monochromatic OG card, and zero-Fumadocs legal parser. | Run a quick hygiene sweep (remove stale `v0.12.0` docs, ghost paths in `knip.json`/`vitest.config.ts`/`.env.example`/`AGENTS.md`, and unused starter remnants) → mark lifecycle state as **`finished` (maintenance)**. |
| **`starter-template`** | Monolithic `v1.0.0` starter bundling Fumadocs, Redis, 4 landing presets, registry, and 12+ root Markdown docs. | **Retire as a direct clone source.** Extract reusable optional blocks into `satisium-modules`, and extract `satisium-core` + `Umbrella Spine` from `ease`'s proven stripped-down foundation. |
| **GitHub Org & Discord** | `[github.com/satisium](https://github.com/satisium)` org and Satisium Discord server (`Satisium UI` + `Ease` categories) are live.    | Create `[github.com/satisium/.github](https://github.com/satisium/.github)` org-default repo to eliminate per-repo template duplication. |
| **`Tweak`** | Next flagship build (in-app prop customizer, variants, Git-like visual branching, AST write-back). | First product built end-to-end on the new **Bare Core + Suite 1 + Dumb UI + Readiness Gate** rails. |
| **`motion.satisium.com`** | Scope boundary locked (system-level motion tokens & interruptible physics, strictly separate from `Ease`). | Parked cleanly—next product to spec and build once `Tweak` is rolling. |

## Chapter 9: Immediate Execution Roadmap

To avoid falling into an endless meta-architecture detour, foundation work is **strictly capped at 1–2 days** before pivoting immediately into real product execution:

1. **Step 1 — Lock the Source of Truth (Hours 1–2):**
    - Create `satisium-org` containing this finalized **`SATISIUM_CANON.md`**, the compact **`SATISIUM_BLUEPRINT.md`** (Brainstorm-to-Setup handoff), `.satisium/org/` scoped rules, and the `.satisium/readiness.json` template.
    - Create `[github.com/satisium/.github](https://github.com/satisium/.github)` with org-inherited community, security, and Issue/PR templates.
2. **Step 2 — Extract `satisium-core` & Gatekeepers (Day 1–2):**
    - Extract the lean **Bare Starter Core** and **Syncable Umbrella Spine** from `ease`'s evolved foundation.
    - Park optional landing, pricing, Fumadocs, registry, and Redis blocks from `starter-template` into **`satisium-modules`**.
    - Wire ESLint AST boundary rules (`core/` purity + `.view.tsx` Dumb UI lock), upgraded `scripts/doctor.mjs` (including `-release`), and `pnpm context:sync` (`repo-facts.json`). Verify zero-key boot passes green.
3. **Step 3 — Align Existing Live Apps (Day 2 Afternoon):**
    - Complete `ease`'s hygiene sweep and graduate it to `finished` (maintenance) mode.
    - Apply light external Umbrella Spine alignment to `ui.satisium.com`.
4. **Step 4 — Build & Ship `Tweak` End-to-End (Day 3 Onward):**
    - Run `Tweak` through the full pipeline: `SATISIUM_BLUEPRINT.md` → Suite 1 `.satisium/plan/` (`alpha` → `beta` → `v1` scope fences) → `satisium-core` init → pure headless `core/` + Dumb UI workbench → dogfood `Tweak` on itself → `pnpm verify` + `pnpm doctor --release` → public launch on `tweak.satisium.com`.
5. **Step 5 — Next Product Wave (Post-`Tweak`):**
    - Plan and build **`motion.satisium.com`** (connecting `Ease` via `#hash` bridge) → Layer 2 Authoring Studios (`Color`, `Typography`, `Surface`) → **`Satisium UI Pro`** (Wave 1 cashflow) → unified **`Inspo + Mooderboard`** → staged **Design System Marketplace**.

## Chapter 10: The "Intentionally Hollow" Fill-In Register

Every box below has been **deliberately left hollow** in this report so nothing is prematurely hardcoded. As we move into detailing and building, we will fill these in systematically one by one:

### A. Foundation & Template Artifacts *(Fill Next — 1–2 Day Cap)*

- `[HOLLOW]` **Exact File-by-File Extraction Map:** Precise list of files going into `satisium-core` vs. `Umbrella Spine` vs. `satisium-modules`.
- `[HOLLOW]` **`SATISIUM_BLUEPRINT.md`:** Exact 1-page Brainstorm-to-Setup prompt and `product.manifest.json` schema.
- `[HOLLOW]` **Universal AI Context & Rules:** Exact contents of the <60-line `AGENTS.md` router and `.satisium/org/` scoped rule files (`design`, `engineering`, `seo-analytics`, `brand-social`).
- `[HOLLOW]` **Suite 1 & Readiness Templates:** Exact lightweight templates for `.satisium/plan/` (`charter.md`, `releases.json`, `flows/`, `domain-glossary.json`, `topology.json`, `business-model.json`) and `.satisium/readiness.json`.
- `[HOLLOW]` **Upgraded Mechanical Gatekeepers:** Exact ESLint AST rules (`core/` + `.view.tsx`), `scripts/doctor.mjs --release` checks, and `context:sync` (`repo-facts.json`) generator.
- `[HOLLOW]` **Launch Runbook:** Exact release-week distribution playbook inside `.satisium/org/brand-social.md`.

### B. Product Specifications & Internal Architectures *(Fill When Building Each Product)*

- `[HOLLOW]` **`Tweak`:** Prop discovery model, variant/branching state tree, AST write-back bridge, zero-byte production stripping, and `tweak.satisium.com` playground spec.
- `[HOLLOW]` **`motion.satisium.com`:** System-level motion token architecture, Apple-style interruptible physics runtime, reduced-motion contract, and `Ease` `#hash` import bridge.
- `[HOLLOW]` **Color, Typography & Surface Studios:** Exact 4-slot universal outputs (static tokens, behavioral runtimes/primitives, standalone AI rules snippet, studio-specific lint plugins) for each studio.
- `[HOLLOW]` **Inspo + Mooderboard:** Specimen data model, browser extension capture flow, live system DNA extraction spec, curation pipeline, and Suite 2B cloud-sync transition.
- `[HOLLOW]` **Design System Marketplace:** Pack manifest format, Stage 1 storefront catalog, Stage 2 PR registry submission rules, and Stage 3 creator security/payout architecture.

### C. Commercial & Billing Details *(Fill Before First Paid Release Gate)*

- `[HOLLOW]` **Merchant of Record Selection:** Final choice between Polar, Paddle, or Lemon Squeezy.
- `[HOLLOW]` **Exact Pricing & Tiers:** Final numbers for `Satisium UI Pro` LTD tiers, Stage 1 System Packs / All-Access Pass, recurring Satisium Pro Workspace plans, AI credit caps/BYOK rules, and Stage 3 Marketplace commission rate.

All 10 chapters of your **Satisium Design Master Reference Report** are now complete—you can combine Batches 1, 2, and 3 directly into `SATISIUM_CANON.md` as your permanent source of truth.

Which **`[HOLLOW]`** box from **Section 10A** do you want to open and fill first to kick off execution—the **exact file-by-file split for `satisium-core` / `Umbrella Spine` / `satisium-modules`**, or drafting **`SATISIUM_BLUEPRINT.md` + `.satisium/readiness.json`**?