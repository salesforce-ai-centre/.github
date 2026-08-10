# Salesforce AI Centre

Internal home for the AI Centre team. This page is a map of everything we build — immersive experiences, AI & Salesforce demos, and the platform underneath them.

Our work spans three broad areas:

- **Immersive experiences & activations** — games, installations, IoT-driven exhibits, XR and voice experiences.
- **AI & Salesforce demos** — Agentforce, Heroku AI and Data Cloud demonstrations that connect experiences back to the platform.
- **Platform & foundations** — the shared design system, Salesforce metadata, packages, gateways and dashboards everything else is built on.

---

## 🧭 New here? Start with these

| Repo | What it is |
| --- | --- |
| [aic-design-system](https://github.com/salesforce-ai-centre/aic-design-system) | Our shared design system — components + tokens. Start here for any UI work. |
| [mesh](https://github.com/salesforce-ai-centre/mesh) · [packages](https://github.com/salesforce-ai-centre/packages) | Shared Salesforce metadata and npm packages (`@mesh/*`) reused across projects. |
| [signal](https://github.com/salesforce-ai-centre/signal) | Live documentation and operational oversight dashboard — the "you are here" for the AI Centre. |
| [.github](https://github.com/salesforce-ai-centre/.github) | This repo — org profile, community health files and shared standards. |

---

## 📦 Project catalogue

Every active repository in the org, grouped by theme. Descriptions come from each repo's GitHub description where set; the rest are inferred from the repo name and need confirming — open the repo for the real detail.

### Platform & foundations

Shared infrastructure, tooling and design assets that other projects build on.

| Repo | Lang | Visibility | Description |
| --- | --- | --- | --- |
| [aic-design-system](https://github.com/salesforce-ai-centre/aic-design-system) | TypeScript | Private | Design system — Storybook components + tokens, hosted on quicker. |
| [mesh](https://github.com/salesforce-ai-centre/mesh) | Apex | Private | Centralised Salesforce metadata (Apex, LWC, Objects). |
| [mesh-monorepo](https://github.com/salesforce-ai-centre/mesh-monorepo) | TypeScript | Private | Monorepo for Mesh services and applications. |
| [packages](https://github.com/salesforce-ai-centre/packages) | TypeScript | Private | Shared npm packages (`@mesh/*`). |
| [control](https://github.com/salesforce-ai-centre/control) | Apex | Private | Salesforce control / administration package. |
| [bridge](https://github.com/salesforce-ai-centre/bridge) | TypeScript | Private | Multi-protocol device gateway. |
| [signal](https://github.com/salesforce-ai-centre/signal) | TypeScript | Private | Live documentation and operational oversight dashboard. |
| [vault](https://github.com/salesforce-ai-centre/vault) | TypeScript | Private | Secure storage / secrets service. |
| [aicentre-linker](https://github.com/salesforce-ai-centre/aicentre-linker) | JavaScript | Private | Short link codes, maintained in the org. |

### AI, Agentforce & Salesforce demos

Experiences and tools that put the Salesforce platform and AI front and centre.

| Repo | Lang | Visibility | Description |
| --- | --- | --- | --- |
| [aicentre-agentforce-discovery](https://github.com/salesforce-ai-centre/aicentre-agentforce-discovery) | JavaScript | Private | Agentforce discovery demo. |
| [aicentre-heroku-ai](https://github.com/salesforce-ai-centre/aicentre-heroku-ai) | TypeScript | Private | Heroku AI integrations. |
| [ai-centre-agenda](https://github.com/salesforce-ai-centre/ai-centre-agenda) | TypeScript | Private | AI-powered agenda planning tool (Next.js) — generates schedules, exports branded Slides/images. |
| [aicentre-stable-diffusion](https://github.com/salesforce-ai-centre/aicentre-stable-diffusion) | TypeScript | Private | Stable Diffusion image-generation experience. |
| [aicentre-imagine](https://github.com/salesforce-ai-centre/aicentre-imagine) | JavaScript | Private | Generative "Imagine" experience. |
| [engage](https://github.com/salesforce-ai-centre/engage) | TypeScript | Private | Engagement platform. |
| [aicentre-engage](https://github.com/salesforce-ai-centre/aicentre-engage) | — | Private | Engagement experience / activation. |
| [111-platform](https://github.com/salesforce-ai-centre/111-platform) | TypeScript | Private | Internal platform project. |
| [aicentre-royalties](https://github.com/salesforce-ai-centre/aicentre-royalties) | TypeScript | Private | Royalties tracking. |
| [aicentre-centrepass](https://github.com/salesforce-ai-centre/aicentre-centrepass) | JavaScript | Private | CentrePass — access / pass management. |

### Immersive experiences & activations

Games, installations, IoT exhibits, XR and voice — the things visitors interact with.

| Repo | Lang | Visibility | Description |
| --- | --- | --- | --- |
| [aicentre-interactive](https://github.com/salesforce-ai-centre/aicentre-interactive) | JavaScript | Private | Host platform for our web-based activations. |
| [arcade](https://github.com/salesforce-ai-centre/arcade) | TypeScript | Private | AI/ML arcade games. |
| [aquarium](https://github.com/salesforce-ai-centre/aquarium) | TypeScript | Private | Digital aquarium display. |
| [photo-wall](https://github.com/salesforce-ai-centre/photo-wall) | TypeScript | Private | Photo wall display. |
| [aicentre-photo-kiosk](https://github.com/salesforce-ai-centre/aicentre-photo-kiosk) | — | Private | Photo kiosk experience. |
| [aicentre-webxr](https://github.com/salesforce-ai-centre/aicentre-webxr) | JavaScript | Private | WebXR experience. |
| [wayfinder](https://github.com/salesforce-ai-centre/wayfinder) | HTML | Private | Wayfinder navigation app. |
| [wayfinder-reader](https://github.com/salesforce-ai-centre/wayfinder-reader) | C | Private | Reader / device companion for Wayfinder. |
| [aicentre-escape-room-controller](https://github.com/salesforce-ai-centre/aicentre-escape-room-controller) | Python | Private | Controller + MQTT server for the escape room. |
| [aicentre-hunt](https://github.com/salesforce-ai-centre/aicentre-hunt) | JavaScript | Private | Scavenger hunt experience. |
| [aicentre-scav-hunt-2](https://github.com/salesforce-ai-centre/aicentre-scav-hunt-2) | TypeScript | Private | Scavenger hunt experience (v2). |
| [aicentre-lego-crane](https://github.com/salesforce-ai-centre/aicentre-lego-crane) | JavaScript | Private | LEGO crane installation. |
| [lego-city](https://github.com/salesforce-ai-centre/lego-city) | TypeScript | Private | LEGO city installation. |
| [turing-test](https://github.com/salesforce-ai-centre/turing-test) | TypeScript | Private | Turing test experience. |
| [voice-avatar](https://github.com/salesforce-ai-centre/voice-avatar) | TypeScript | Private | Voice-driven avatar. |
| [aicentre-voice](https://github.com/salesforce-ai-centre/aicentre-voice) | TypeScript | Private | Voice experience / service. |
| [aicentre-living-london](https://github.com/salesforce-ai-centre/aicentre-living-london) | TypeScript | Private | "Living London" experience. |
| [beam](https://github.com/salesforce-ai-centre/beam) | TypeScript | Private | Beam Display — source for the display app. |
| [beam-display-releases](https://github.com/salesforce-ai-centre/beam-display-releases) | — | Public | Public installer + update feed for Beam Display. |
| [aicentre-beam-2.0](https://github.com/salesforce-ai-centre/aicentre-beam-2.0) | — | Private | Next-generation Beam Display. |
| [aicentre-taister](https://github.com/salesforce-ai-centre/aicentre-taister) | TypeScript | Private | Interactive experience. |
| [aicentre-watts-the-prompt](https://github.com/salesforce-ai-centre/aicentre-watts-the-prompt) | JavaScript | Private | "Watts the Prompt" game. |
| [formula-1](https://github.com/salesforce-ai-centre/formula-1) | TypeScript | Public | Formula 1 racing experience. |
| [aicentre-f1-local](https://github.com/salesforce-ai-centre/aicentre-f1-local) | Python | Public | Local runtime for the Formula 1 experience. |
| [dreamforce-assets](https://github.com/salesforce-ai-centre/dreamforce-assets) | JavaScript | Private | Assets for Dreamforce activations. |

### Web & digital presence

Public-facing sites and web utilities.

| Repo | Lang | Visibility | Description |
| --- | --- | --- | --- |
| [aicentre-website](https://github.com/salesforce-ai-centre/aicentre-website) | TypeScript | Public | AI Centre website. |
| [aicentre-splash](https://github.com/salesforce-ai-centre/aicentre-splash) | HTML | Public | Example of branding your My Domain. |
| [map](https://github.com/salesforce-ai-centre/map) | TypeScript | Private | Interactive map. |
| [aicentre-qrcode-generator](https://github.com/salesforce-ai-centre/aicentre-qrcode-generator) | JavaScript | Private | QR code generator. |

### Bots & integrations

| Repo | Lang | Visibility | Description |
| --- | --- | --- | --- |
| [slack-app](https://github.com/salesforce-ai-centre/slack-app) | JavaScript | Private | Slack application. |
| [boost-slack-coins](https://github.com/salesforce-ai-centre/boost-slack-coins) | JavaScript | Private | Slack coins / rewards bot. |

### Organisation & meta

| Repo | Lang | Visibility | Description |
| --- | --- | --- | --- |
| [.github](https://github.com/salesforce-ai-centre/.github) | — | Public | Org profile, community health files and shared standards. |
| [demo-repository](https://github.com/salesforce-ai-centre/demo-repository) | HTML | Private | A repository showcasing GitHub features. |

---

## 🛠️ Tech stack

Most of our work is built with:

- **TypeScript / JavaScript** — web apps, experiences and Node services (React, Next.js).
- **Apex & LWC** — Salesforce platform work, centralised in [mesh](https://github.com/salesforce-ai-centre/mesh).
- **Python** — device controllers, local runtimes and ML tooling.
- **C** — firmware and device-level integrations.
- **MQTT & multi-protocol gateways** — IoT and physical installations, via [bridge](https://github.com/salesforce-ai-centre/bridge).

---

## 🚀 Getting started

Because projects vary, always start with the target repo's own `README`. In general:

```bash
# Clone (requires org membership)
git clone https://github.com/salesforce-ai-centre/<repo>.git
cd <repo>

# For Node/TypeScript projects
npm install
npm run dev

# Shared packages are published under the @mesh/* scope
```

New projects should adopt the [aic-design-system](https://github.com/salesforce-ai-centre/aic-design-system) for UI and reuse the shared [packages](https://github.com/salesforce-ai-centre/packages) rather than re-implementing common utilities.

---

## 🤝 Contributing & standards

- **Branch, don't push to `main`.** Open a pull request and request review.
- **Follow the design system** for anything user-facing.
- **Keep secrets out of code** — use [vault](https://github.com/salesforce-ai-centre/vault) and environment configuration, never commit credentials.
- **Write a `README`** for every repo describing what it is, how to run it, and who owns it.
- Shared community health files (contribution guidelines, code of conduct, issue/PR templates) live in this **[.github](https://github.com/salesforce-ai-centre/.github)** repo and apply org-wide.

---

## 📇 Contact

- **Operational dashboard:** [signal](https://github.com/salesforce-ai-centre/signal)
- **Questions:** reach out in the team's Slack workspace.
