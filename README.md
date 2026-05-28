# Akana to Apigee X Migration Strategy

Self-contained HTML presentation for an executive and enterprise architecture audience.

The deck presents a product-by-product migration approach from a poorly governed Akana API gateway estate to a well-architected Apigee X implementation on Google Cloud. It uses Minto Pyramid, SQCA, MECE structuring, and visual decision frameworks while keeping the content practical and recommendation-led.

## Contents

- `index.html` - standalone deck with embedded CSS and JavaScript
- No external dependencies are required
- Printable with browser print support
- Keyboard navigation: left/right arrows, page up/down, home/end

## Scope Covered

- Apigee X on Google Cloud
- Shared VPC and external load balancing coexistence with Akana
- Ping identity integration
- Gateway and runtime migration
- Developer portal and app onboarding
- CI/CD, certificates, policy standards, and governance
- Product-led migration factory using one Apigee Product at a time
- Challenges, pitfalls, and prevention recommendations

## View Locally

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://127.0.0.1:8765/index.html
```

## Publish With GitHub Pages

This repo can be published as a static site because the deck is a single `index.html` file.

Recommended GitHub Pages settings:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

## Presentation Structure

1. Executive answer
2. Minto Pyramid and SQCA storyline
3. Target-state architecture
4. Product migration factory
5. Product taxonomy and onboarding model
6. Platform controls
7. Outcome-based scorecard
8. Challenges, pitfalls, and prevention
