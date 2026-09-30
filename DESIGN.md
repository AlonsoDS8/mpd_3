---
name: Executive Retail Intelligence
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#89ceff'
  on-secondary: '#00344d'
  secondary-container: '#00a2e6'
  on-secondary-container: '#00344e'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
    letterSpacing: 0.01em
  label-numeric:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: -0.01em
  label-kpi:
    fontFamily: JetBrains Mono
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.03em
  label-tag:
    fontFamily: JetBrains Mono
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system embodies high-velocity strategic decision-making for retail executives, growth marketers, and customer lifecycle directors. It projects extreme precision, analytical depth, and confident clarity. The aesthetic sits at the intersection of Modern Corporate SaaS and Technical Precision, avoiding unnecessary ornamentation in favor of dense, legible, and immediately actionable data narratives.

The visual tone is authoritative and calm: deep slate canvas foundations balance high-energy semantic accents that decode customer cohorts at a glance. Interfaces prioritize signal-to-noise ratio, presenting complex RFM (Recency, Frequency, Monetary) data models as intuitive, navigable spatial planes rather than overwhelming spreadsheets.

## Colors

The palette establishes an executive dark canvas anchored in deep slate navy (`#0F172A`), delivering immense visual depth while drastically reducing eye strain across data-dense dashboards. 

### Role Mapping
- **Primary (`#6366F1` - Electric Indigo):** Primary calls-to-action, system focus indicators, active segment boundaries, and primary regression trendlines.
- **Secondary (`#0EA5E9` - Sky Recency):** Temporal indicators, recent customer lifecycle cohorts, and comparative date markers.
- **Tertiary (`#10B981` - Emerald Monetary):** High-LTV "Champions", revenue acceleration metrics, positive deltas, and top monetary tiers.
- **Warning / At-Risk Accent (`#F59E0B` - Amber Friction):** Declining recency flags, churning segments, and urgent reactivation queues.
- **Neutral Canvas (`#0F172A` - Foundation):** Stratified surface layers use step-up tinting (`#1E293B` for container cards, `#334155` for high-interaction panels and borders).

Contrast ratios strictly meet or exceed WCAG 2.1 AA on all operational badges, metric counters, and chart elements.

## Typography

The typographic hierarchy separates narrative governance from numerical analysis. Plus Jakarta Sans handles primary communication, navigation, and structural headings with geometric clarity and modern terminal cuts. 

For all numeric data displays, RFM percentile tables, currency values, and delta counters, JetBrains Mono is deployed to guarantee tabular alignment, zero visual jitter on streaming updates, and total legibility in high-density matrix grids. All labels and metric indicators require crisp vertical alignment against supporting icon glyphs.

## Layout & Spacing

This design system operates on a responsive 12-column fluid grid tailored for widescreen executive dashboards and modular viewport scalability.

- **Breakpoints:** Mobile (360px–767px, 4 columns, 16px margins), Tablet (768px–1199px, 8 columns, 24px margins), Desktop (1200px+, 12 columns, 32px outer canvas margins).
- **Dashboard Grid Hierarchy:** Analytical cards conform to 3-column (KPI blocks), 6-column (cohort comparisons), and 12-column (global scatter plots, RFM heatmaps) spans.
- **Rhythm & Proximity:** Spacing relies strictly on strict 4px base increments. Internal card padding uses `space-lg`, while inline metric stacks deploy `space-xs` and `space-sm` to maintain atomic grouping.

## Elevation & Depth

Visual hierarchy leverages a low-glare, layered surface model with restrained chromatic boundaries instead of heavy drop shadows:

- **Level 0 (Canvas Base):** Solid `#0F172A`. Deep background layer housing global navigational frames.
- **Level 1 (Card & Module Foundation):** Background `#1E293B` bounded by a subtle 1px border of `#334155` (reduced to 60% opacity). Elevation is supported by a soft 12px ambient blur (`box-shadow: 0 4px 20px -2px rgba(0, 0, 0, 0.4)`).
- **Level 2 (Hover / Active State):** Shift border stroke to `rgba(99, 102, 241, 0.35)` with an expanded ambient glow (`box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.5)`).
- **Level 3 (Modals, Overlays, and Drawers):** Background `#1E293B` with 24px blur backdrop filters, bordered by `rgba(255, 255, 255, 0.12)`, casting deep drop shadows (`box-shadow: 0 20px 40px -10px rgba(0, 0, 0, 0.7)`).

## Shapes

The interface embraces a precise, structural aesthetic with low-radius corners (`roundedness: 1`). Metric cards, chart containers, and modal dialogs use 8px (`rounded-lg`), while interactive buttons, inputs, segmented pill controls, and metadata tags use 4px (`rounded-sm`). This architectural sharpness reinforces analytical precision, preventing visual bloat in high-density tables and grid matrices.

## Components

### Buttons & Interactive Controls
- **Primary:** Background `#6366F1`, text `#FFFFFF`, 4px corner radius, internal padding `0.5rem 1rem`. Focus state reveals a 2px outer ring offset in `#0F172A` with color `#818CF8`.
- **Secondary / Filter Pill:** Translucent surface (`rgba(255, 255, 255, 0.04)`), border `1px solid #334155`, text `#CBD5E1`. On active selection, shifts to `rgba(99, 102, 241, 0.15)` fill with `1px solid #6366F1` and text `#FFFFFF`.

### Analytical Cards & KPI Modules
- Containers apply background `#1E293B`, 1px border in `#334155`, and 8px border radius.
- Cards host a standardized 3-part layout: Card Header (eyebrow label + status dot), Value Anchor (displaying JetBrains Mono KPI with delta indicator), and Visualization Floor (micro sparkline or distribution curve).

### Metric Badges & Cohort Tags
- Monospaced, all-caps metadata chips styled with `label-tag`.
- **Champions / High Monetary:** Fill `rgba(16, 185, 129, 0.12)`, border `rgba(16, 185, 129, 0.3)`, text `#34D399`.
- **At-Risk / Churn Warning:** Fill `rgba(245, 158, 11, 0.12)`, border `rgba(245, 158, 11, 0.3)`, text `#FBBF24`.
- **Recent / New Buyers:** Fill `rgba(14, 165, 233, 0.12)`, border `rgba(14, 165, 233, 0.3)`, text `#38BDF8`.

### Data Tables & Interactive Lists
- Row heights pegged to 40px for dense inspection or 52px for default analytics views.
- Alternating rows avoid striped fills; separation relies exclusively on `1px solid rgba(51, 65, 85, 0.5)`. Row hover creates a swift surface transition to `rgba(255, 255, 255, 0.02)`.

### Form Inputs & Search Filters
- Inputs sit on `#0F172A` inset backgrounds with 1px border `#334155`. Text displays in `Plus Jakarta Sans` regular, placeholder text `#64748B`. Focus state initiates instant transition to border `#6366F1`.