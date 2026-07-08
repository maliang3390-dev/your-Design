# your-Design

A design aesthetics distiller skill — covers all categories of visual design analysis and user experience flow analysis. Analyze styles across regions (US, Japan, China, Europe), industries (SaaS, e-commerce, brand sites, tools), and aesthetics (minimalist, dark mode, luxury, Japanese Wabi-sabi, etc.).

## Key Features

- **Visual design analysis** across 5 dimensions: Gestalt compliance, color system, typography, layout, and component style — each backed by practical UX frameworks and psychology principles
- **User journey analysis** across 6 dimensions: first-screen attention flow, core task conversion, navigation architecture, interaction feedback, drop-off points, and reusable experience patterns
- **Design-to-code gap analysis**: compare UI mockups against live demos, identify fidelity gaps, and get actionable fix suggestions
- **Pattern distillation**: accumulate samples in the same category to automatically extract reusable visual + experience patterns
- **Private library**: all samples and analyses are saved to your local `user/` directory, isolated from public kernel updates

## Installation

Place the skill folder under your skills directory:

```
~/.claude/skills/your-Design/
```

Or import the `.skill` package file if provided.

## Usage

| You say... | Skill does... |
|-----------|---------------|
| "Analyze this site and add it to my library" | Full 5-dim visual analysis + basic journey analysis → sample card saved |
| "Deep dive the conversion flow of X" | Full 6-dim journey breakdown → journey analysis card saved |
| "Summarize design patterns for SaaS websites" | Cross-reference all SaaS samples → distill reusable patterns |
| "Compare the design of X and Y" | Side-by-side dimension comparison table |
| "Design an X with Y style" | Visual style guide + journey architecture recommendations |
| "Check how closely this demo matches the mockup" | 6-item fidelity check + prioritized fix suggestions |
| Share a link in a design context | Proactively ask "Want me to collect and analyze this?" |

## Directory Structure

```
your-Design/
├── SKILL.md                    # Entry point: methodology + commands + module specs
├── references/
│   ├── frameworks.md           # 18 UX frameworks & psychology principles quick-reference
│   └── seeds-public.md         # 30 built-in benchmark samples (updated with kernel)
└── user/                       # Your private library (never overwritten by updates)
    ├── samples/                # Design sample cards
    ├── journeys/               # Deep journey analysis cards
    └── patterns/               # Distilled design patterns
```

## Data Isolation

- `SKILL.md` + `references/` are the **public kernel** — replaced on version updates
- `user/` is your **private library** — never touched by updates
- New kernel versions may add analysis dimensions; older sample cards missing new fields remain fully functional

## Built-in Benchmarks

30 pre-loaded samples across 3 categories:
- **10 SaaS & developer tools**: Linear, Stripe, Vercel, Raycast, Notion, Figma, Resend, Supabase, Webflow, Mural
- **10 Global brand sites**: Apple, Sony, Aesop, Hermes, Bang & Olufsen, Nike, Lexus, Muji, Tesla, IKEA
- **10 Japanese design benchmarks**: Nendo, NDC, ISSEY MIYAKE, Maruoka Castle, iro Inc., SHISEIDO, G-Mark, Kenji Saito, MUJI Japan, Lexus Japan

## License

MIT
