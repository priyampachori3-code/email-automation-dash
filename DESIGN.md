# AI Inbox Bento Dashboard — Design System Specification

Extracted directly from Stitch project: `projects/4696442842543192731`

---

## 1. Aesthetic Philosophy & Visual Principles

The AI Inbox Bento Dashboard is built upon executive minimalism, tactile monochromatic bento surfaces, and high-clarity triage density.

### Core Tenets
1. Sculpted Bento Radii
2. Inverted Focal Tile
3. Restrained Color Discipline
4. Action-First Hierarchy
5. Clean Interaction Fidelity

---

## 2. Color Palette & Design Tokens

### Canvas & Surface Tokens
- surface / background: `#F8F9FC`
- surface-container-lowest: `#FFFFFF`
- surface-container-low: `#F3F3F6`
- surface-container: `#EDEEF1`
- primary-container: `#1B1B1B`

### Typography & Text Tokens
- on-surface: `#191C1E`
- on-surface-variant: `#444748`
- secondary: `#595F67`
- on-primary: `#FFFFFF`

### Status Indicators
- High Priority: red
- Waiting / Medium: amber
- Done / Low: green

---

## 3. Layout Architecture & Component Structure

### Navigation Sidebar
- Left column with floating white pills
- Brand mark: logo + Inbox
- Status tabs: Needs action, Waiting, High priority, Done, All

### Bento Grid Row 1
- Overview Tile
- Weekly Trend Tile
- Handled Progress Ring Tile

### Main Section: Email Queue
- Category filter
- Search bar
- 2-column grid of cards

### Slide-over Detail Drawer
- backdrop blur overlay
- right panel slide-in
- thread detail, summary, attachments, history
