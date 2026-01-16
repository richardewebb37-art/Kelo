# Blueprint Theme Specifications

## Theme Overview

The Blueprint Theme transforms The FictionVerse into a **construction site for stories** - where narratives are built, universes are architected, and creativity is engineered. This theme uses the visual language of architectural blueprints, technical drawings, and construction documentation.

---

## Visual Metaphors

### Construction Site Metaphor
- **Stories = Buildings under construction**
- **Universes = Construction projects**
- **Writers = Architects/Engineers**
- **Readers = Site inspectors/Visitors**
- **Chapters = Building floors/levels**
- **Characters = Construction crew**
- **Lore = Foundation/blueprints**

### Terminology Updates
- "Explore" → "Survey the Site"
- "Read" → "Inspect"
- "Write" → "Draft/Design"
- "Publish" → "Approve for Construction"
- "Community" → "Construction Crew"
- "Profile" → "Contractor Profile"

---

## Blueprint Paper Backgrounds

### Background Types

**1. Classic Blueprint (Primary)**
- Deep blue background (#001F3F to #0066CC gradient)
- White grid lines (20px spacing)
- Major grid lines every 100px (thicker)
- Corner registration marks (⊕)
- Edge measurement rulers
- Subtle paper texture overlay

**2. Technical Drawing (Secondary)**
- Light cream/white background (#E8F4F8)
- Blue grid lines
- Technical annotations
- Dimension markers
- Title block in corner

**3. Construction Site (Accent)**
- Concrete texture background
- Yellow caution stripes
- Safety signage elements
- Industrial metal textures

**4. Aged Blueprint (Vintage)**
- Faded blue tones
- Yellowed paper effect
- Worn edges
- Coffee stains (subtle)
- Vintage stamps

### Grid System Implementation

```css
.blueprint-background {
  background-color: var(--blueprint-dark);
  background-image: 
    /* Fine grid */
    linear-gradient(rgba(255,255,255,0.1) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.1) 1px, transparent 1px),
    /* Major grid */
    linear-gradient(rgba(255,255,255,0.2) 2px, transparent 2px),
    linear-gradient(90deg, rgba(255,255,255,0.2) 2px, transparent 2px);
  background-size: 
    20px 20px,
    20px 20px,
    100px 100px,
    100px 100px;
  background-position: 
    0 0,
    0 0,
    0 0,
    0 0;
}
```

---

## UI Element Styles

### Navigation Elements

**Top Bar (Title Block)**
```
┌─────────────────────────────────────────────────────┐
│ THE FICTIONVERSE          REV: 2.0    [USER AVATAR] │
│ DIGITAL CONSTRUCTION PLATFORM                        │
└─────────────────────────────────────────────────────┘
```

**Bottom Navigation (Tool Bar)**
```
┌──────┬──────┬──────┬──────┬──────┐
│ HOME │ CREW │  FV  │ SITE │ TASK │
│  🏠  │  👥  │  ⊕   │  🔍  │  📋  │
└──────┴──────┴──────┴──────┴──────┘
```

### Content Cards

**Universe Card (Project Blueprint)**
```
┌─────────────────────────────────────┐
│ ⊕ PROJECT: [Universe Name]          │
├─────────────────────────────────────┤
│                                     │
│  [Preview Image/Diagram]            │
│                                     │
├─────────────────────────────────────┤
│ GENRE: [Genre Badge]                │
│ STATUS: [Original/Inspired]         │
│ STORIES: [Count]                    │
│                                     │
│ DESCRIPTION:                        │
│ [Universe description text...]      │
│                                     │
├─────────────────────────────────────┤
│        [INSPECT SITE →]             │
└─────────────────────────────────────┘
```

**Chapter Card (Floor Plan)**
```
┌─────────────────────────────────────┐
│ LEVEL [Chapter #]: [Title]          │
├─────────────────────────────────────┤
│ SPECIFICATIONS:                     │
│ • Word Count: [####]                │
│ • Status: [Complete/Draft]          │
│ • Last Updated: [Date]              │
├─────────────────────────────────────┤
│        [INSPECT LEVEL →]            │
└─────────────────────────────────────┘
```

### Buttons

**Primary Action Button (Construction Yellow)**
```
╔═══════════════════╗
║   APPROVE BUILD   ║
╚═══════════════════╝
```
- Yellow background (#FFD700)
- Black text
- Bold border
- Drop shadow effect
- Hover: Slight lift animation

**Secondary Button (Blueprint Style)**
```
┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┐
│   REVIEW PLANS    │
└ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┘
```
- Transparent background
- Dashed white border
- White text
- Hover: Solid border

**Icon Button (Tool)**
```
┌───┐
│ ⚙ │
└───┘
```
- Small square
- Single icon
- Minimal border
- Hover: Background fill

### Forms

**Input Field (Specification Entry)**
```
┌─────────────────────────────────────┐
│ FIELD LABEL:                        │
├─────────────────────────────────────┤
│ [User input here...]                │
└─────────────────────────────────────┘
```

**Textarea (Technical Notes)**
```
┌─────────────────────────────────────┐
│ NOTES:                              │
├─────────────────────────────────────┤
│                                     │
│ [Multi-line input area...]          │
│                                     │
│                                     │
└─────────────────────────────────────┘
```

### Modals

**Authentication Modal (Site Access)**
```
╔═══════════════════════════════════════╗
║  SITE ACCESS REQUIRED                 ║
╠═══════════════════════════════════════╣
║                                       ║
║  [CONTRACTOR LOGIN]  [NEW CONTRACTOR] ║
║                                       ║
║  ┌─────────────────────────────────┐ ║
║  │ USERNAME: [____________]        │ ║
║  │ PASSWORD: [____________]        │ ║
║  └─────────────────────────────────┘ ║
║                                       ║
║         [ENTER SITE →]                ║
║                                       ║
╚═══════════════════════════════════════╝
```

---

## Typography Treatments

### Headings (Technical Labels)
```css
h1 {
  font-family: 'Orbitron', sans-serif;
  font-weight: 900;
  text-transform: uppercase;
  letter-spacing: 2px;
  color: var(--white-line);
  text-shadow: 0 0 10px rgba(0, 102, 204, 0.5);
}
```

### Body Text (Specifications)
```css
p {
  font-family: 'Roboto Mono', monospace;
  font-size: 14px;
  line-height: 1.6;
  color: rgba(255, 255, 255, 0.9);
}
```

### Annotations (Hand-written Notes)
```css
.annotation {
  font-family: 'Architects Daughter', cursive;
  font-size: 16px;
  color: var(--yellow-highlight);
  transform: rotate(-2deg);
}
```

---

## Icon System

### Construction-Themed Icons

**Navigation Icons**
- Home: 🏗️ Construction crane
- Community: 👷 Hard hat workers
- Logo: ⊕ Registration mark
- Explore: 🔍 Magnifying glass over blueprint
- Challenges: 📋 Clipboard with checklist

**Action Icons**
- Read: 👁️ Inspection eye
- Write: ✏️ Technical pencil
- Edit: 🔧 Wrench
- Delete: 🗑️ Demolition
- Save: 💾 Blueprint filing
- Share: 📤 Blueprint distribution
- Like: 👍 Approval stamp
- Comment: 💬 Site notes

**Status Icons**
- Complete: ✓ Approved stamp
- In Progress: ⚠️ Under construction
- Draft: 📝 Sketch
- Published: 🏆 Final approval

---

## Animation Effects

### 1. Blueprint Drawing Animation
Elements appear as if being drawn on blueprint paper:
```css
@keyframes blueprint-draw {
  from {
    stroke-dashoffset: 1000;
    opacity: 0;
  }
  to {
    stroke-dashoffset: 0;
    opacity: 1;
  }
}
```

### 2. Construction Build-Up
Content builds from bottom to top:
```css
@keyframes build-up {
  from {
    transform: translateY(100%);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}
```

### 3. Stamp Effect
Elements appear with stamp animation:
```css
@keyframes stamp {
  0% {
    transform: scale(0) rotate(-45deg);
    opacity: 0;
  }
  50% {
    transform: scale(1.2) rotate(-5deg);
  }
  100% {
    transform: scale(1) rotate(0deg);
    opacity: 1;
  }
}
```

### 4. Measurement Scan
Scanning line moves across element:
```css
@keyframes scan {
  0% {
    left: -100%;
  }
  100% {
    left: 100%;
  }
}
```

### 5. Blueprint Reveal
Content fades in with grid overlay:
```css
@keyframes blueprint-reveal {
  0% {
    opacity: 0;
    filter: blur(10px);
  }
  100% {
    opacity: 1;
    filter: blur(0);
  }
}
```

---

## Special Elements

### Corner Brackets
```html
<div class="blueprint-card">
  <span class="corner-bracket top-left"></span>
  <span class="corner-bracket top-right"></span>
  <span class="corner-bracket bottom-left"></span>
  <span class="corner-bracket bottom-right"></span>
  <!-- Content -->
</div>
```

### Measurement Lines
```html
<div class="measurement">
  <span class="line"></span>
  <span class="label">100px</span>
  <span class="line"></span>
</div>
```

### Technical Stamps
```html
<div class="stamp approved">
  <span class="stamp-text">APPROVED</span>
  <span class="stamp-date">2024-01-16</span>
</div>
```

### Annotation Arrows
```html
<div class="annotation-arrow">
  <svg class="arrow">
    <path d="M0,0 L50,50" />
    <polygon points="50,50 45,45 55,45" />
  </svg>
  <span class="annotation-text">Important detail</span>
</div>
```

---

## Page-Specific Treatments

### Home Page (Site Overview)
- Large blueprint background
- Hero section with construction crane silhouette
- "Under Construction" aesthetic for features
- Blueprint-style feature cards
- Technical diagram for universes section

### Explore Page (Site Survey)
- Grid view of project blueprints
- Filter panel styled as specification sheet
- Search bar as measurement tool
- Cards with project status indicators

### Universe Page (Project Details)
- Large blueprint header with project name
- Tabs styled as folder tabs
- Chapter list as floor plans
- Character cards as crew profiles
- Lore as foundation documents

### Reader Page (Inspection View)
- Clean white background (technical drawing paper)
- Blue text on white for readability
- Minimal distractions
- Chapter navigation as floor selector
- Annotation tools for notes

### Community Page (Construction Crew Hub)
- Bulletin board aesthetic
- Posted notices and announcements
- Crew member profiles
- Forum threads as work orders
- Events as scheduled inspections

---

## Responsive Adaptations

### Mobile (< 768px)
- Simplified grid overlay
- Larger touch targets
- Bottom navigation priority
- Reduced animation complexity
- Optimized blueprint backgrounds

### Tablet (768px - 1024px)
- Balanced grid density
- Touch-friendly interactions
- Adaptive layouts
- Medium complexity animations

### Desktop (> 1024px)
- Full grid overlay
- Detailed annotations
- Complex animations
- Multiple columns
- Rich visual effects

---

## Implementation Checklist

- [ ] Create blueprint background variations
- [ ] Design corner bracket system
- [ ] Implement grid overlay
- [ ] Create measurement line components
- [ ] Design technical stamps
- [ ] Build annotation arrow system
- [ ] Create construction-themed icons
- [ ] Implement drawing animations
- [ ] Design button variations
- [ ] Create card templates
- [ ] Build form components
- [ ] Design modal layouts
- [ ] Implement responsive breakpoints
- [ ] Test accessibility
- [ ] Optimize performance

---

This blueprint theme specification provides a comprehensive guide for implementing the construction/architectural aesthetic across The FictionVerse platform.