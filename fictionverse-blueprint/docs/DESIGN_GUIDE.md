# FictionVerse Blueprint - Design Guide

## Design Philosophy

The FictionVerse Blueprint theme transforms the cyber-futuristic aesthetic into a **construction/architectural blueprint** style, maintaining the platform's innovative spirit while embracing a technical, industrial design language.

---

## Color Palette

### Primary Colors
```css
--blueprint-blue: #0066CC;        /* Classic blueprint blue */
--blueprint-dark: #001F3F;        /* Deep blueprint background */
--blueprint-light: #E8F4F8;       /* Light blueprint paper */
--white-line: #FFFFFF;            /* White technical lines */
--yellow-highlight: #FFD700;      /* Construction yellow accent */
```

### Secondary Colors
```css
--grid-line: rgba(255, 255, 255, 0.2);  /* Blueprint grid lines */
--shadow-blue: rgba(0, 102, 204, 0.3);  /* Glow effects */
--construction-orange: #FF6B35;          /* Warning/accent color */
--steel-gray: #6C757D;                   /* Neutral elements */
--concrete-gray: #ADB5BD;                /* Muted text */
```

### Semantic Colors
```css
--success: #28A745;               /* Green for success states */
--warning: #FFC107;               /* Yellow for warnings */
--danger: #DC3545;                /* Red for errors */
--info: #17A2B8;                  /* Cyan for information */
```

---

## Typography

### Font Families

**Primary Font (Headings)**
- Font: "Orbitron", "Rajdhani", or "Saira Condensed"
- Style: Bold, technical, industrial
- Use: Headings, titles, navigation

**Secondary Font (Body)**
- Font: "Roboto Mono", "Source Code Pro", or "IBM Plex Mono"
- Style: Monospace, technical
- Use: Body text, descriptions, technical details

**Accent Font (Special)**
- Font: "Architects Daughter" or "Permanent Marker"
- Style: Hand-drawn, sketch-like
- Use: Annotations, highlights, special callouts

### Font Sizes
```css
--text-xs: 0.75rem;    /* 12px - Small labels */
--text-sm: 0.875rem;   /* 14px - Secondary text */
--text-base: 1rem;     /* 16px - Body text */
--text-lg: 1.125rem;   /* 18px - Large body */
--text-xl: 1.25rem;    /* 20px - Small headings */
--text-2xl: 1.5rem;    /* 24px - Section headings */
--text-3xl: 1.875rem;  /* 30px - Page headings */
--text-4xl: 2.25rem;   /* 36px - Hero headings */
--text-5xl: 3rem;      /* 48px - Large hero */
--text-6xl: 3.75rem;   /* 60px - Extra large */
```

### Font Weights
```css
--font-light: 300;
--font-normal: 400;
--font-medium: 500;
--font-semibold: 600;
--font-bold: 700;
--font-black: 900;
```

---

## Spacing System

### Base Unit: 4px

```css
--space-1: 0.25rem;   /* 4px */
--space-2: 0.5rem;    /* 8px */
--space-3: 0.75rem;   /* 12px */
--space-4: 1rem;      /* 16px */
--space-5: 1.25rem;   /* 20px */
--space-6: 1.5rem;    /* 24px */
--space-8: 2rem;      /* 32px */
--space-10: 2.5rem;   /* 40px */
--space-12: 3rem;     /* 48px */
--space-16: 4rem;     /* 64px */
--space-20: 5rem;     /* 80px */
--space-24: 6rem;     /* 96px */
```

---

## Layout & Grid

### Container Widths
```css
--container-sm: 640px;
--container-md: 768px;
--container-lg: 1024px;
--container-xl: 1280px;
--container-2xl: 1536px;
```

### Grid System
- 12-column grid for desktop
- 6-column grid for tablet
- 4-column grid for mobile
- Gutter: 24px (--space-6)

### Blueprint Grid Overlay
- Technical grid lines every 20px
- Major grid lines every 100px
- Measurement markers on edges
- Corner registration marks

---

## Visual Effects

### Blueprint Paper Texture
```css
background: 
  linear-gradient(rgba(255,255,255,0.05) 1px, transparent 1px),
  linear-gradient(90deg, rgba(255,255,255,0.05) 1px, transparent 1px),
  var(--blueprint-dark);
background-size: 20px 20px;
```

### Technical Line Style
```css
border: 2px solid var(--white-line);
border-style: dashed; /* or solid for main elements */
```

### Glow Effects
```css
box-shadow: 
  0 0 10px rgba(0, 102, 204, 0.5),
  0 0 20px rgba(0, 102, 204, 0.3),
  0 0 30px rgba(0, 102, 204, 0.1);
```

### Sketch/Hand-drawn Effect
```css
filter: url(#sketch-filter);
/* SVG filter for hand-drawn appearance */
```

---

## Component Styles

### Buttons

**Primary Button (Construction Yellow)**
```css
background: var(--yellow-highlight);
color: var(--blueprint-dark);
border: 2px solid var(--blueprint-dark);
font-weight: var(--font-bold);
text-transform: uppercase;
letter-spacing: 1px;
box-shadow: 4px 4px 0 var(--blueprint-dark);
```

**Secondary Button (Blueprint Blue)**
```css
background: transparent;
color: var(--white-line);
border: 2px dashed var(--white-line);
font-weight: var(--font-semibold);
```

**Ghost Button**
```css
background: transparent;
color: var(--blueprint-blue);
border: 2px solid var(--blueprint-blue);
```

### Cards

**Blueprint Card**
```css
background: rgba(255, 255, 255, 0.05);
border: 2px solid var(--white-line);
border-style: dashed;
backdrop-filter: blur(10px);
position: relative;
/* Add corner brackets */
```

**Technical Diagram Card**
```css
background: var(--blueprint-light);
color: var(--blueprint-dark);
border: 3px solid var(--blueprint-blue);
/* Add measurement lines and annotations */
```

### Forms

**Input Fields**
```css
background: rgba(255, 255, 255, 0.1);
border: 2px solid var(--grid-line);
border-bottom: 3px solid var(--blueprint-blue);
color: var(--white-line);
font-family: monospace;
```

**Labels**
```css
color: var(--yellow-highlight);
font-weight: var(--font-bold);
text-transform: uppercase;
font-size: var(--text-sm);
letter-spacing: 1px;
```

---

## Iconography

### Icon Style
- Line-based icons (2px stroke)
- Construction/industrial themed
- Technical drawing aesthetic
- Consistent sizing: 24px, 32px, 48px

### Icon Categories
1. **Navigation**: Compass, ruler, blueprint, hammer
2. **Actions**: Wrench, gear, pencil, eraser
3. **Status**: Checkmark, warning triangle, info circle
4. **Social**: Hard hat profiles, construction crew
5. **Content**: Book with blueprint, story scaffold, universe blueprint

---

## Animation Principles

### Timing Functions
```css
--ease-in: cubic-bezier(0.4, 0, 1, 1);
--ease-out: cubic-bezier(0, 0, 0.2, 1);
--ease-in-out: cubic-bezier(0.4, 0, 0.2, 1);
--bounce: cubic-bezier(0.68, -0.55, 0.265, 1.55);
```

### Duration
```css
--duration-fast: 150ms;
--duration-normal: 300ms;
--duration-slow: 500ms;
```

### Blueprint-Specific Animations
1. **Drawing Effect**: Lines appear as if being drawn
2. **Blueprint Reveal**: Content fades in with grid overlay
3. **Construction Build**: Elements "build up" from bottom
4. **Measurement Scan**: Scanning line effect across elements
5. **Stamp Effect**: Elements appear with stamp/seal animation

---

## Responsive Breakpoints

```css
/* Mobile First Approach */
--breakpoint-sm: 640px;   /* Small tablets */
--breakpoint-md: 768px;   /* Tablets */
--breakpoint-lg: 1024px;  /* Small laptops */
--breakpoint-xl: 1280px;  /* Desktops */
--breakpoint-2xl: 1536px; /* Large screens */
```

### Mobile Considerations
- Larger touch targets (min 44px)
- Simplified grid overlay
- Reduced animation complexity
- Optimized image sizes
- Bottom navigation priority

---

## Accessibility

### Color Contrast
- Minimum 4.5:1 for normal text
- Minimum 3:1 for large text
- Ensure blueprint blue has sufficient contrast

### Focus States
```css
:focus {
  outline: 3px solid var(--yellow-highlight);
  outline-offset: 2px;
}
```

### Screen Reader Support
- Semantic HTML elements
- ARIA labels where needed
- Skip navigation links
- Alt text for all images

---

## Blueprint-Specific Elements

### Corner Brackets
```
┌─────────────┐
│             │
│   Content   │
│             │
└─────────────┘
```

### Measurement Lines
```
├──────── 100px ────────┤
```

### Annotation Arrows
```
    ↓
[Element]
    ↑
```

### Registration Marks
```
⊕ (at corners of important elements)
```

### Technical Stamps
- "APPROVED"
- "DRAFT"
- "REVISION 1.0"
- "CLASSIFIED"

---

## Usage Guidelines

### Do's
✓ Use blueprint grid as background
✓ Maintain technical drawing aesthetic
✓ Use construction terminology
✓ Include measurement annotations
✓ Apply consistent line weights
✓ Use monospace fonts for technical data

### Don'ts
✗ Mix too many colors
✗ Use rounded corners excessively
✗ Ignore grid alignment
✗ Overcomplicate layouts
✗ Use decorative fonts for body text
✗ Forget mobile optimization

---

## Implementation Notes

1. **CSS Custom Properties**: Use CSS variables for all design tokens
2. **Modular CSS**: Separate files for different concerns
3. **BEM Naming**: Use Block-Element-Modifier methodology
4. **Progressive Enhancement**: Start with basic styles, add enhancements
5. **Performance**: Optimize images, minimize CSS, lazy load when possible

---

This design guide ensures consistency across the entire FictionVerse Blueprint platform while maintaining the technical, construction-themed aesthetic.