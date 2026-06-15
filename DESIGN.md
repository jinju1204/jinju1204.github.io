## Overview

A dark space-themed personal portfolio design system. Deep midnight navy canvas with violet-purple accents, clean sans-serif type, and a deliberately minimal layout where content breathes against a dark background.

The defining choice is **deep dark backgrounds**: every section uses `#0a0a1a` or `#12122a` as the base, with `#1a1a35` for cards. There are subtle borders, no heavy shadows, no distracting patterns.

**Inter / system-ui** carries the entire type hierarchy. Display names use bold weight (700–800) with gradient fills. Body text stays at regular weight for readability.

The system reaches for color sparingly — Violet (`#7c6af7`) and soft purple (`#a78bfa`) as the single accent pair. The result is a calm, focused reading experience with a futuristic feel.

**Key Characteristics:**
- **Dark midnight canvas**: `#0a0a1a` body background, `#1a1a35` card surfaces
- **Single accent pair**: Violet `#7c6af7` + soft purple `#a78bfa` for headings, links, and highlights
- **Muted body text**: `#94a3b8` for secondary content — never pure white on dark
- **Thin borders**: `1px solid #2d2d5a` separates regions without heavy dividers
- **Border-radius 8–12px** on cards; circular avatar with glow shadow
- **Fixed navbar** with backdrop blur — floats above content
- **Smooth scroll** between anchor sections
- **Responsive grid** collapses to single column on mobile (breakpoint: 600px)
- **Gradient text** on hero name: linear-gradient from violet to soft purple
- **Emoji/icon accents** used sparingly as visual anchors (🌠 ✦)

## Color Palette

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#0a0a1a` | Page background |
| `--surface` | `#12122a` | Section backgrounds |
| `--card` | `#1a1a35` | Card backgrounds |
| `--accent` | `#7c6af7` | Primary accent, borders, buttons |
| `--accent2` | `#a78bfa` | Headings, links, tags |
| `--text` | `#e2e8f0` | Body text |
| `--muted` | `#94a3b8` | Secondary text |
| `--border` | `#2d2d5a` | Dividers and card borders |

## Typography

- **Display / Hero**: 2.5rem, font-weight 800, gradient fill
- **Section headings (h2)**: 1.6rem, `--accent2`, bottom border
- **Card headings (h3)**: 1rem, `--accent2`
- **Body**: 1rem / line-height 1.7, `--text`
- **Secondary / muted**: 0.85–0.9rem, `--muted`
- **Tags**: 0.75rem, rounded pill, `--accent` border

## Components

- **Avatar**: 120px circle, gradient background, emoji center, violet glow shadow
- **Navbar**: fixed, 60px height, blur backdrop, logo left + nav links right
- **Cards**: `--card` bg, `1px --border` border, `12px` radius, `1.5rem` padding
- **Buttons**: primary (filled violet) and outline (transparent + violet border)
- **Tags/Badges**: pill shape, dark indigo fill, violet border, small font
- **Course grid**: auto-fill columns, min 200px each
- **CV items**: flex row with colored year label on left

## Page Rhythm

Fixed nav (60px) → Hero section (centered, avatar + name + bio + CTAs) → CV → Projects → Courses → Contact → AI Usage → Footer
