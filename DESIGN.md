<!-- SEED: re-run /impeccable document once there's code to capture the actual tokens and components. -->

---
name: Cafe Website
description: A warm, unhurried neighborhood cafe that feels like it's been waiting for you.
---

# Design System: Cafe Website

## 1. Overview

**Creative North Star: "The Corner Table"**

This design system starts from one image: the corner table at a cafe that has been there forever, worn smooth by years of regulars. The light is warm. The menu is handwritten. The welcome is real. Every decision should make a first-time visitor feel like they've been here before.

The palette is full and deliberate: an oat cream canvas anchored by a terracotta primary and a sage counterpoint. The type pairing leans editorial without feeling precious; a serif display face gives the cafe a quiet identity, while the humanist sans keeps body copy friendly and approachable. Motion is responsive, not theatrical: the site breathes, it doesn't perform.

This system explicitly rejects the visual language of food delivery apps: no transactional grids, no star-rating decorations, no "add to cart" as the primary action. It also rejects the corporate chain template: nothing that could belong equally to a thousand other cafes. The reference is the local bistro or corner pub that has been there for decades, full of character, slightly worn-in, irreplaceable.

**Key Characteristics:**
- Full warm palette: cream base, terracotta primary, sage secondary, layered and deliberate
- Serif display paired with humanist sans; strong typographic hierarchy, warm not fussy
- Responsive motion: smooth state transitions, a few gentle entrance animations, alive not theatrical
- Photography-forward: the room and the people carry as much weight as the product
- Old-world warmth and texture; character over polish

## 2. Colors

A full palette built from three named roles: a warm neutral base, a terracotta primary, and a sage secondary. The base canvas is warm (oat, cream, or parchment, never pure white). The primary is earthy and inviting. The secondary provides organic counterpoint without competing.

### Primary
- **Terracotta / Burnt Clay** (`[to be resolved during implementation]`): The primary accent. Used on calls-to-action, key decorative elements, and section markers. Earthy, sun-warmed, inviting.

### Secondary
- **Sage / Warm Olive** (`[to be resolved during implementation]`): Secondary accent. Supporting color for tags, subtle highlights, and freshness counterpoints to the terracotta. Not green-coded; warm-coded.

### Neutral
- **Oat Cream** (`[to be resolved during implementation]`): Background canvas. The surface IS the warmth. Never cold, never pure white.
- **Warm Espresso Brown** (`[to be resolved during implementation]`): Primary text and dark surfaces. Deep brown, never black. Tinted toward the brand hue.
- **Dusty Sand** (`[to be resolved during implementation]`): Secondary neutral for dividers, inactive states, and muted text.

### Named Rules
**The Three-Voice Rule.** This palette has three deliberate roles: neutral base, terracotta primary, sage secondary. A fourth color introduced without a named role is a color introduced without a reason.

**The No-White Rule.** There is no pure white in this system. Every surface is warmed toward the brand hue. Stark white makes the cafe feel like a hospital or a tech company. That is not the corner table.

## 3. Typography

**Display Font:** Serif display — Cormorant Garamond, Playfair Display, or similar; `[to be chosen at implementation]`
**Body Font:** Humanist sans — DM Sans, Source Sans 3, or similar; `[to be chosen at implementation]`

**Character:** A serif display face lends quiet authority and a sense of history: the kind of type you'd find on a hand-lettered sign or a decades-old menu board. The humanist sans keeps body copy warm and readable, never sterile.

### Hierarchy
- **Display** (light or regular, large, tight leading): Hero headlines and the cafe name. Conveys place, not product.
- **Headline** (regular or medium, wide leading): Section openers, menu category names.
- **Title** (medium): Individual items, pull quotes, featured moments.
- **Body** (regular, 16-18px, 65-75ch max line length, relaxed leading): Descriptive copy, about text, menu descriptions.
- **Label** (medium, small, subtle letter-spacing): Navigation items, tags, captions. Not uppercase by default.

### Named Rules
**The Hierarchy Rule.** Every screen should have one Display element and one Headline. Two Displays fight for attention; none leaves the page without gravity.

## 4. Elevation

This system uses gentle ambient depth rather than strong structural shadows. Surfaces layer softly, like late-afternoon light on a wooden table. Nothing is sharply lifted; depth is implied, not announced.

Responsive motion energy means surfaces respond to interaction with subtle shadow shifts on hover. At rest, most surfaces are flat or near-flat.

**The Warm Shadow Rule.** Any box-shadow in this system is tinted toward the brand's warm hue. A gray shadow reads as software. A warm shadow reads as atmosphere.

## 5. Components

No components yet. Re-run `/impeccable document` once there's code to extract real component patterns.

## 6. Do's and Don'ts

### Do:
- **Do** let photography carry the emotional weight. A good room photo or close-up of a cup is worth more than three paragraphs of copy.
- **Do** use the terracotta primary sparingly as a true accent. Its warmth lands harder when it's not everywhere.
- **Do** use the serif display face for anything that names the place, a section, or a moment. Type is the handwriting of the brand.
- **Do** vary spacing for rhythm. Tight sections next to generous ones create the unhurried feeling of a real space.
- **Do** design mobile-first. Most visitors discover this cafe on a phone, walking by or searching nearby.
- **Do** warm every surface. The canvas is never neutral-gray or pure white.

### Don't:
- **Don't** use transactional-first layouts: no star-rating grids, no "add to cart" as the primary action, no food delivery app patterns (Uber Eats, DoorDash UI).
- **Don't** use pure white (#fff) anywhere. Warm the canvas.
- **Don't** use pure black for text. The deep espresso brown is the darkest tone.
- **Don't** use gradient text. It decorates without meaning.
- **Don't** use identical card grids (icon + heading + text, repeated endlessly). The menu is not a product catalog.
- **Don't** use border-left stripes as colored accents on list items. Use background tints or leading icons instead.
- **Don't** make it feel like a corporate chain. Nothing templated, nothing mass-produced, nothing interchangeable with a thousand other cafes.
