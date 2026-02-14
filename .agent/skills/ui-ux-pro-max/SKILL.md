---
name: ui-ux-pro-max
description: Comprehensive design guide for web and mobile applications. Contains 50+ styles, 97 color palettes, 57 font pairings, 99 UX guidelines, and 25 chart types across 9 technology stacks.
---

# UI/UX Pro Max - Design Intelligence

Comprehensive design guide for web and mobile applications.

## When to Apply
Reference these guidelines when:
- Designing new UI components or pages
- Choosing color palettes and typography
- Reviewing code for UX issues
- Building landing pages or dashboards
- Implementing accessibility requirements

## Rule Categories by Priority
1. ux
2. typography
3. color
4. style
5. product
6. chart

## Quick Reference

### 1. Accessibility (CRITICAL)
- color-contrast - Minimum 4.5:1 ratio for normal text
- focus-states - Visible focus rings on interactive elements
- alt-text - Descriptive alt text for meaningful images
- aria-labels - aria-label for icon-only buttons
- keyboard-nav - Tab order matches visual order
- form-labels - Use label with for attribute

### 2. Touch & Interaction (CRITICAL)
- touch-target-size - Minimum 44x44px touch targets
- hover-vs-tap - Use click/tap for primary interactions
- loading-buttons - Disable button during async operations
- error-feedback - Clear error messages near problem
- cursor-pointer - Add cursor-pointer to clickable elements

### 3. Performance (HIGH)
- image-optimization - Use WebP, srcset, lazy loading
- reduced-motion - Check prefers-reduced-motion
- content-jumping - Reserve space for async content

### 4. Layout & Responsive (HIGH)
- viewport-meta - width=device-width initial-scale=1
- readable-font-size - Minimum 16px body text on mobile
- horizontal-scroll - Ensure content fits viewport width
- z-index-management - Define z-index scale (10, 20, 30, 50)

### 5. Typography & Color (MEDIUM)
- line-height - Use 1.5-1.75 for body text
- line-length - Limit to 65-75 characters per line
- font-pairing - Match heading/body font personalities

### 6. Animation (MEDIUM)
- duration-timing - Use 150-300ms for micro-interactions
- transform-performance - Use transform/opacity, not width/height
- loading-states - Skeleton screens or spinners

### 7. Style Selection (MEDIUM)
- style-match - Match style to product type
- consistency - Use same style across all pages
- no-emoji-icons - Use SVG icons, not emojis

### 8. Charts & Data (LOW)
- chart-type - Match chart type to data type
- color-guidance - Use accessible color palettes
- data-table - Provide table alternative for accessibility

## Workflow: How to Use This Skill
When user requests UI/UX work (design, build, create, implement, review, fix, improve), follow this workflow:

### Step 1: Analyze User Requirements
Extract key information from user request:
- Product type: SaaS, e-commerce, portfolio, dashboard, landing page, etc.
- Style keywords: minimal, playful, professional, elegant, dark mode, etc.
- Industry: healthcare, fintech, gaming, education, etc.
- Stack: React, Vue, Next.js, or default to html-tailwind

### Step 2: Generate Design System (REQUIRED)
1. **Define Pattern**: Choose a layout pattern (e.g., sticky header, sidebar layout, centered content).
2. **Define Style**: Choose a visual style (e.g., glassmorphism, brutalism, material).
3. **Define Colors**: Select a primary color and a neutral palette. Ensure contrast.
4. **Define Typography**: Select a heading font and a body font.
5. **Define Effects**: Shadows, border-radius, blurring.

### Step 3: Supplement with Detailed Searches (as needed)
- **UX**: Search for animation, accessibility, z-index guidelines.
- **Typography**: Search for font pairings if defaults don't fit.
- **Color**: Search for accessibility-safe palettes.

### Step 4: Stack Guidelines (Default: html-tailwind)
Apply implementation-specific best practices for the chosen stack (e.g., html-tailwind, react, nextjs).

## Tips for Better Results
1. Be specific with keywords - "healthcare SaaS dashboard" > "app"
2. Combine domains - Style + Typography + Color = Complete design system
3. Always check UX - Check for animation, z-index, accessibility issues
4. Use stack flag - Get implementation-specific best practices
5. Iterate - If first search doesn't match, try different keywords

## Common Rules for Professional UI

### Interaction & Cursor
- `cursor-pointer` on clickable elements
- `transition-colors duration-200`

### Light/Dark Mode Contrast
- Light: `bg-white/80`, `border-gray-200`, `#0F172A` text
- Dark: `bg-white/10`, `border-white/10`, `#94A3B8` text

### Layout & Spacing
- `top-4 left-4 right-4`
- `max-w-7xl` centered containers

## Pre-Delivery Checklist

### Visual Quality
- No emojis used as icons (use SVG instead)
- All icons from consistent icon set (Heroicons/Lucide)
- Brand logos are correct (verified from Simple Icons)
- Hover states don't cause layout shift
- Use theme colors directly (bg-primary) not var() wrapper

### Interaction
- All clickable elements have cursor-pointer
- Hover states provide clear visual feedback
- Transitions are smooth (150-300ms)
- Focus states visible for keyboard navigation

### Light/Dark Mode
- Light mode text has sufficient contrast (4.5:1 minimum)
- Glass/transparent elements visible in light mode
- Borders visible in both modes
- Test both modes before delivery

### Layout
- Floating elements have proper spacing from edges
- No content hidden behind fixed navbars
- Responsive at 375px, 768px, 1024px, 1440px
- No horizontal scroll on mobile

### Accessibility
- All images have alt text
- Form inputs have labels
- Color is not the only indicator
- prefers-reduced-motion respected
