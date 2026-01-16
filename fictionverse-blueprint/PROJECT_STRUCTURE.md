# FictionVerse Blueprint - Project Structure

## Directory Organization

```
fictionverse-blueprint/
│
├── assets/                          # All static assets
│   ├── images/
│   │   ├── backgrounds/            # Blueprint background images (user will upload)
│   │   ├── buttons/                # Button assets from Envato Elements
│   │   ├── icons/                  # Icon sets and custom icons
│   │   └── logos/                  # FictionVerse logos and branding
│   │
│   └── fonts/                      # Custom fonts for blueprint theme
│
├── styles/                         # CSS/Styling files
│   ├── main.css                   # Main stylesheet
│   ├── blueprint-theme.css        # Blueprint-specific styles
│   ├── components.css             # Component-specific styles
│   ├── animations.css             # Animation definitions
│   └── responsive.css             # Mobile/tablet responsive styles
│
├── pages/                          # HTML pages
│   ├── index.html                 # Home/Landing page
│   ├── explore.html               # Explore universes page
│   ├── universe.html              # Universe detail page
│   ├── reader.html                # Story reader page
│   ├── community.html             # Community hub page
│   ├── challenges.html            # Challenges page
│   ├── profile.html               # User profile page
│   └── settings.html              # Settings page
│
├── components/                     # Reusable HTML components
│   ├── common/                    # Common components
│   │   ├── header.html           # Top navigation bar
│   │   ├── footer.html           # Footer component
│   │   ├── bottom-nav.html       # Bottom navigation bar
│   │   └── auth-modal.html       # Authentication modal
│   │
│   ├── sections/                  # Page sections
│   │   ├── hero.html             # Hero section
│   │   ├── features.html         # Features section
│   │   ├── universes.html        # Universes showcase
│   │   └── about.html            # About section
│   │
│   └── ui/                        # UI elements
│       ├── buttons.html          # Button variations
│       ├── cards.html            # Card components
│       ├── forms.html            # Form elements
│       └── modals.html           # Modal dialogs
│
├── scripts/                        # JavaScript files
│   ├── main.js                   # Main application logic
│   ├── navigation.js             # Navigation handling
│   ├── auth.js                   # Authentication logic
│   ├── api.js                    # API calls and data fetching
│   ├── animations.js             # Animation controllers
│   └── utils.js                  # Utility functions
│
└── docs/                          # Documentation
    ├── DESIGN_GUIDE.md           # Design system documentation
    ├── COMPONENT_LIBRARY.md      # Component usage guide
    └── BLUEPRINT_THEME.md        # Blueprint theme specifications

```

## File Purposes

### Assets Directory
- **backgrounds/**: Will contain all blueprint background images uploaded by user
- **buttons/**: Will store button assets downloaded from Envato Elements
- **icons/**: Navigation icons, feature icons, social icons
- **logos/**: FictionVerse logo variations for blueprint theme
- **fonts/**: Construction/technical fonts for blueprint aesthetic

### Styles Directory
- **main.css**: Core styles, CSS variables, base typography
- **blueprint-theme.css**: Blueprint-specific colors, textures, effects
- **components.css**: Styling for all reusable components
- **animations.css**: Keyframe animations, transitions, effects
- **responsive.css**: Media queries for mobile/tablet layouts

### Pages Directory
Each HTML file represents a main page from the original React app:
- **index.html**: Landing page with hero, features, universes sections
- **explore.html**: Browse and filter universes
- **universe.html**: Universe details with tabs (chapters, characters, lore)
- **reader.html**: Clean reading interface for story chapters
- **community.html**: Community hub (clubs, forums, events, trending)
- **challenges.html**: Writing challenges and prompts
- **profile.html**: User profile and statistics
- **settings.html**: User preferences and account settings

### Components Directory
Reusable HTML snippets that can be included across pages:
- **common/**: Navigation, footer, modals used site-wide
- **sections/**: Large page sections for the landing page
- **ui/**: Small UI elements like buttons, cards, forms

### Scripts Directory
- **main.js**: Application initialization, global state
- **navigation.js**: Page routing, menu interactions
- **auth.js**: Login/signup, session management
- **api.js**: Backend API communication
- **animations.js**: Particle effects, scroll animations
- **utils.js**: Helper functions, data formatting

### Docs Directory
- **DESIGN_GUIDE.md**: Color palette, typography, spacing rules
- **COMPONENT_LIBRARY.md**: How to use each component
- **BLUEPRINT_THEME.md**: Blueprint aesthetic guidelines

## Design Approach

### Blueprint Theme Elements
1. **Backgrounds**: Construction blueprint paper textures
2. **Grid System**: Technical grid lines and measurements
3. **Typography**: Industrial/technical fonts
4. **Colors**: Blueprint blue tones, white lines, yellow highlights
5. **Icons**: Construction-themed icons and symbols
6. **Buttons**: Industrial/mechanical button designs
7. **Effects**: Blueprint sketch effects, technical diagrams

### Construction Aesthetic
- Blueprint paper backgrounds with grid patterns
- Technical drawing style for UI elements
- Construction/architectural terminology
- Industrial design patterns
- Mechanical/engineering visual metaphors

## Next Steps

1. **User uploads blueprint backgrounds** → Place in `assets/images/backgrounds/`
2. **Download Envato Elements assets** → Place in `assets/images/buttons/`
3. **Create base HTML structure** → Build page templates
4. **Develop blueprint CSS theme** → Style with construction aesthetic
5. **Implement JavaScript functionality** → Add interactivity
6. **Test and refine** → Ensure responsive and functional

## Notes

- All paths are relative for easy deployment
- Structure mirrors original React app functionality
- Modular design for easy maintenance
- Ready for blueprint backgrounds integration
- Prepared for Envato Elements assets