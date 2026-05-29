# tufte-viz

A [Claude Code](https://code.claude.com) skill for ideating and critiquing data
visualizations using **Edward Tufte's** principles — data-ink ratio, chartjunk
elimination, graphical integrity, lie factor, small multiples, and data density.

> **Attribution:** This skill was created by **aparente** and originally published as a
> [public gist](https://gist.github.com/aparente/e48c353755958621b3c0004593105a90). This
> repository is a credited redistribution, repackaged as a plugin marketplace so it can be
> installed from within Claude Code. See [ATTRIBUTION.md](./ATTRIBUTION.md) for details.
> The original gist has no stated license; no ownership is claimed here.

**🔗 Live demo gallery: [grmooney.com/tufte-viz](https://grmooney.com/tufte-viz/)**

## Install

From inside Claude Code:

```
/plugin marketplace add GarrettMooney/tufte-viz
/plugin install tufte-viz@tufte-viz
```

Then verify it's available:

```
/plugin
```

The skill activates automatically when you design, critique, or review data
visualizations, dashboards, or reports.

## What it does

- **For new visualizations:** clarifies the data story, selects a Tufte-appropriate
  approach, designs with data-ink in mind, and runs the eraser / collision / Tufte tests
  before shipping.
- **For critiquing existing visualizations:** checks graphical integrity (lie factor,
  baselines, 3D distortion), identifies chartjunk, evaluates data-ink ratio, and suggests
  concrete before/after improvements.

## Contents

```
skills/tufte-viz/
├── SKILL.md                          # the skill definition
├── references/
│   ├── tufte-principles.md           # core principles (Visual Display of Quantitative Information)
│   └── analytical-design.md          # analytical design, sparklines, layering, micro/macro
└── demo/                             # example visualizations — view live at grmooney.com/tufte-viz
    ├── giss-temperature.html
    ├── kyoto-sakura.html
    ├── sunspot-butterfly.html
    └── sunspot-pretty.html
```
