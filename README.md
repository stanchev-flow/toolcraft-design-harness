# Toolcraft Design Harness

A single-page, self-contained reference for the design system inside
[`@pixel-point/toolcraft`](https://www.npmjs.com/package/@pixel-point/toolcraft) v0.0.12 —
Pixel Point's starter kit for building personal creative design tools with AI.

Built as research/inspiration material for our Webflow Design Harness project.

**Live page:** https://stanchev-flow.github.io/toolcraft-design-harness/

## What's inside

- **Tokens** — the full extracted token system (OKLCH color, radii, type scale, spacing) plus
  the system patterns (color-mix hairlines, data-attribute state variants, keyboard-only focus,
  theme scoping). The header switch flips the page between their dark and light token sets live.
- **Components** — all 89 shipped pieces: 23 schema controls (with the compound value parts
  acceptance tests must cover), 20 primitives, 28 composites, the panel system, and the runtime
  surfaces.
- **Contract files** — a browsable tree of every AI-agent instruction file: `AGENTS.md`,
  the 11 `docs/toolcraft/` contract docs, and the 6 workflow skills the CLI installs.

Everything is one `index.html` with no external requests — open it locally or via the Pages URL.

## Attribution & license

All documented tokens, components, docs, and skills are the work of
[Pixel Point](https://pixelpoint.io) and ship publicly in the
`@pixel-point/toolcraft` npm package, governed by the **Toolcraft Designer License**
(see `LICENSE.md` in the package). This page reproduces their documentation for
team study/reference only; it is not a redistribution of the runtime for reuse.
If we ship anything commercial derived from their *code*, we need a commercial
license from Pixel Point — borrowing architectural *patterns* is fine.

- Blog: [How to craft personal design tools with AI](https://pixelpoint.io/blog/how-to-craft-personal-design-tools-with-toolcraft/)
