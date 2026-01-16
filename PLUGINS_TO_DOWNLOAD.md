# Plugins Needed for FictionVerse Project

## Overview
This document lists all the plugins and dependencies needed for the FictionVerse project, organized by template source and priority.

---

## 🎯 Priority 1: Essential Plugins (Start Here)

### React Development Environment
**Source: NPM (via `npm install`)**
```bash
# Core React dependencies (already in Bookland package.json)
npm install react@18.2.0
npm install react-dom@18.2.0
npm install react-router-dom@6.4.5
npm install react-scripts@5.0.1
```

### UI Framework
**Source: NPM**
```bash
# React Bootstrap 2.7.0 (already in Bookland)
npm install react-bootstrap@2.7.0
```

---

## 🎯 Priority 2: Community & Social Features

### WordPress/BuddyPress (For Reference Patterns)
**Source: WordPress.org (Free Plugins)**

#### 1. **BuddyPress**
- **Purpose:** Social networking, member profiles, activity streams
- **URL:** https://wordpress.org/plugins/buddypress/
- **Why Needed:** Study community patterns for React implementation
- **Features:**
  - User profiles
  - Activity streams
  - Friend connections
  - Private messaging
  - Groups/communities
  - Notifications

#### 2. **bbPress**
- **Purpose:** Forum functionality
- **URL:** https://wordpress.org/plugins/bbpress/
- **Why Needed:** Forum/discussion patterns for React
- **Features:**
  - Forums and topics
  - Replies and threaded discussions
  - User roles and permissions
  - Topic subscriptions

#### 3. **Paid Memberships Pro**
- **Purpose:** Membership system
- **URL:** https://wordpress.org/plugins/paid-memberships-pro/
- **Why Needed:** Subscription/tiered access patterns
- **Features:**
  - Membership levels
  - Content restriction
  - Payment integration
  - Member directories

---

## 🎯 Priority 3: E-commerce & Marketplace

### WooCommerce (For Reference)
**Source: WordPress.org (Free Plugin)**

#### 4. **WooCommerce**
- **Purpose:** E-commerce platform
- **URL:** https://wordpress.org/plugins/woocommerce/
- **Why Needed:** Study e-commerce patterns for marketplace
- **Features:**
  - Product management
  - Shopping cart
  - Checkout process
  - Payment gateways
  - Product reviews

#### 5. **WooCommerce Subscriptions**
- **Purpose:** Recurring payments
- **URL:** https://woocommerce.com/products/woocommerce-subscriptions/
- **Cost:** Premium ($199/year)
- **Why Needed:** Subscription tiers for FictionVerse
- **Features:**
  - Recurring billing
  - Subscription plans
  - Trial periods
  - Automatic renewals

#### 6. **WooCommerce Memberships**
- **Purpose:** Content access control
- **URL:** https://woocommerce.com/products/woocommerce-memberships/
- **Cost:** Premium ($149/year)
- **Why Needed:** Premium universe/story access
- **Features:**
  - Content dripping
  - Membership perks
  - Access duration
  - Member-only content

---

## 🎯 Priority 4: WordPress Plugins from KLEO Theme

### KLEO-Specific Plugins
**Source: ThemeForest/Envato (Included with KLEO)**

#### 7. **Kleo Framework**
- **Purpose:** KLEO theme framework
- **Why Needed:** Study component architecture
- **Features:**
  - Custom post types
  - Meta boxes
  - Theme options
  - Shortcodes

#### 8. **Visual Composer / WPBakery Page Builder**
- **Purpose:** Drag-and-drop page builder
- **URL:** https://vc.wpbakery.com/
- **Cost:** Premium ($59)
- **Why Needed:** Page building patterns for React components
- **Features:**
  - Visual editor
  - Component library
  - Row/column layout
  - Frontend/backend editing

#### 9. **Revolution Slider**
- **Purpose:** Advanced slider/carousel
- **URL:** https://revolution.themepunch.com/
- **Cost:** Premium ($85)
- **Why Needed:** Study slider implementations
- **Features:**
  - Multiple slide types
  - Animation effects
  - Layer-based editing
  - Responsive design

---

## 🎯 Priority 5: Additional WordPress Plugins

### Community & Engagement

#### 10. **Ultimate Member**
- **Purpose:** User profiles and membership
- **URL:** https://wordpress.org/plugins/ultimate-member/
- **Cost:** Free (Premium available)
- **Why Needed:** User management patterns
- **Features:**
  - Frontend user registration
  - User profiles
  - Member directories
  - Role-based access

#### 11. **UserPro**
- **Purpose:** Community/user profiles
- **URL:** https://userproplugin.com/
- **Cost:** Premium ($39)
- **Why Needed:** Advanced user profile features
- **Features:**
  - Social login
  - User badges
  - Activity feeds
  - User following

### Content Management

#### 12. **Advanced Custom Fields (ACF)**
- **Purpose:** Custom field management
- **URL:** https://www.advancedcustomfields.com/
- **Cost:** Free (Pro available at $49)
- **Why Needed:** Custom content type patterns
- **Features:**
  - Field groups
  - Repeater fields
  - Flexible content
  - Gallery fields

#### 13. **Pods**
- **Purpose:** Custom content types and fields
- **URL:** https://pods.io/
- **Cost:** Free (Premium available)
- **Why Needed:** Content architecture patterns
- **Features:**
  - Custom post types
  - Custom taxonomies
  - Relationships
  - API integration

### Forum & Discussion

#### 14. **DW Question & Answer**
- **Purpose:** Q&A platform
- **URL:** https://wordpress.org/plugins/dw-question-answer/
- **Cost:** Free (Premium available)
- **Why Needed:** Q&A/help desk patterns
- **Features:**
  - Questions and answers
  - Voting system
  - User reputation
  - Email notifications

#### 15. **AnsPress**
- **Purpose:** Question and answer plugin
- **URL:** https://wordpress.org/plugins/anspress-question-answer/
- **Cost:** Free
- **Why Needed:** Alternative Q&A patterns
- **Features:**
  - Question management
  - Answer system
  - Reputation points
  - Badges and achievements

---

## 🎯 Priority 6: React-Specific Libraries

### From Bookland package.json (Already Listed)

#### UI Components
```bash
npm install swiper@9.1.0              # Touch slider
npm install sweetalert2@11.7.3        # Beautiful alerts
npm install react-countup@6.4.1       # Number animation
npm install react-modal-video@2.0.0   # Video modal
npm install nouislider-react@3.4.1    # Range slider
```

### Additional React Libraries (Recommended)

#### 16. **React Query (TanStack Query)**
- **Purpose:** Data fetching and caching
- **URL:** https://tanstack.com/query/latest
- **Cost:** Free (Open Source)
- **Why Needed:** Efficient data fetching from FastAPI
- **Installation:** `npm install @tanstack/react-query@4.29.0`

#### 17. **React Hook Form**
- **Purpose:** Form management
- **URL:** https://react-hook-form.com/
- **Cost:** Free (Open Source)
- **Why Needed:** Form handling and validation
- **Installation:** `npm install react-hook-form@7.43.0`

#### 18. **React Hot Toast**
- **Purpose:** Toast notifications
- **URL:** https://react-hot-toast.com/
- **Cost:** Free (Open Source)
- **Why Needed:** User notifications
- **Installation:** `npm install react-hot-toast@2.4.0`

#### 19. **Framer Motion**
- **Purpose:** Animation library
- **URL:** https://www.framer.com/motion/
- **Cost:** Free (Open Source)
- **Why Needed:** Smooth animations
- **Installation:** `npm install framer-motion@10.12.0`

#### 20. **React Markdown**
- **Purpose:** Markdown rendering
- **URL:** https://github.com/remarkjs/react-markdown
- **Cost:** Free (Open Source)
- **Why Needed:** Story content display
- **Installation:** `npm install react-markdown@8.0.5`

#### 21. **React Syntax Highlighter**
- **Purpose:** Code syntax highlighting
- **URL:** https://github.com/react-syntax-highlighter/react-syntax-highlighter
- **Cost:** Free (Open Source)
- **Why Needed:** Code snippets in stories
- **Installation:** `npm install react-syntax-highlighter@15.5.0`

#### 22. **React Dropzone**
- **Purpose:** File upload component
- **URL:** https://react-dropzone.js.org/
- **Cost:** Free (Open Source)
- **Why Needed:** Asset uploading
- **Installation:** `npm install react-dropzone@14.2.2`

#### 23. **Draft.js or Slate.js**
- **Purpose:** Rich text editor
- **URL:** https://draftjs.org/ or https://www.slatejs.org/
- **Cost:** Free (Open Source)
- **Why Needed:** Story writing/editing
- **Installation:** `npm install slate-react@0.94.0` OR `npm install draft-js@0.11.7`

#### 24. **React Beautiful DnD**
- **Purpose:** Drag and drop
- **URL:** https://github.com/atlassian/react-beautiful-dnd
- **Cost:** Free (Open Source)
- **Why Needed:** UI element organization
- **Installation:** `npm install react-beautiful-dnd@13.1.1`

---

## 🎯 Priority 7: Backend (FastAPI)

### Python Libraries for FastAPI

#### 25. **FastAPI**
- **Purpose:** Web framework
- **URL:** https://fastapi.tiangolo.com/
- **Cost:** Free (Open Source)
- **Installation:** `pip install fastapi[all]`

#### 26. **SQLAlchemy**
- **Purpose:** ORM (Database)
- **URL:** https://www.sqlalchemy.org/
- **Cost:** Free (Open Source)
- **Installation:** `pip install sqlalchemy`

#### 27. **Pydantic**
- **Purpose:** Data validation
- **URL:** https://docs.pydantic.dev/
- **Cost:** Free (Open Source)
- **Installation:** `pip install pydantic`

#### 28. **Alembic**
- **Purpose:** Database migrations
- **URL:** https://alembic.sqlalchemy.org/
- **Cost:** Free (Open Source)
- **Installation:** `pip install alembic`

#### 29. **Uvicorn**
- **Purpose:** ASGI server
- **URL:** https://www.uvicorn.org/
- **Cost:** Free (Open Source)
- **Installation:** `pip install uvicorn[standard]`

#### 30. **Python-Jose**
- **Purpose:** JWT authentication
- **URL:** https://python-jose.readthedocs.io/
- **Cost:** Free (Open Source)
- **Installation:** `pip install python-jose[cryptography]`

#### 31. **Passlib**
- **Purpose:** Password hashing
- **URL:** https://passlib.readthedocs.io/
- **Cost:** Free (Open Source)
- **Installation:** `pip install passlib[bcrypt]`

#### 32. **Python-Multipart**
- **Purpose:** Form data parsing
- **URL:** https://python-multipart.readthedocs.io/
- **Cost:** Free (Open Source)
- **Installation:** `pip install python-multipart`

#### 33. **Email-Validator**
- **Purpose:** Email validation
- **URL:** https://github.com/JoshData/email-validator
- **Cost:** Free (Open Source)
- **Installation:** `pip install email-validator`

---

## 🎯 Priority 8: Database

#### 34. **MongoDB** OR **PostgreSQL**
- **MongoDB:**
  - URL: https://www.mongodb.com/
  - Cost: Free (Community edition)
  - Why: Flexible document storage for stories/universes
  - Installation: https://www.mongodb.com/try/download/community

- **PostgreSQL:**
  - URL: https://www.postgresql.org/
  - Cost: Free (Open Source)
  - Why: Relational database for structured data
  - Installation: https://www.postgresql.org/download/

**Recommendation:** Start with PostgreSQL for structured data, can add MongoDB later for flexible content.

---

## 🎯 Priority 9: Development Tools

#### 35. **ESLint**
- **Purpose:** Code linting
- **Installation:** `npm install eslint@8.39.0`

#### 36. **Prettier**
- **Purpose:** Code formatting
- **Installation:** `npm install prettier@2.8.8`

#### 37. **Husky**
- **Purpose:** Git hooks
- **Installation:** `npm install husky@8.0.3`

#### 38. **Lint-staged**
- **Purpose:** Pre-commit linting
- **Installation:** `npm install lint-staged@13.2.2`

---

## 🎯 Priority 10: Testing

#### 39. **Jest**
- **Purpose:** Testing framework
- **Installation:** `npm install jest@29.5.0`

#### 40. **React Testing Library**
- **Purpose:** React component testing
- **Installation:** `npm install @testing-library/react@14.0.0`

#### 41. **Cypress**
- **Purpose:** End-to-end testing
- **Installation:** `npm install cypress@12.10.0`

#### 42. **Pytest**
- **Purpose:** Python testing
- **Installation:** `pip install pytest`

---

## 🎯 Priority 11: Deployment

#### 43. **Docker**
- **Purpose:** Containerization
- **URL:** https://www.docker.com/
- **Cost:** Free (Personal edition)
- **Installation:** https://docs.docker.com/get-docker/

#### 44. **Docker Compose**
- **Purpose:** Multi-container orchestration
- **Installation:** Included with Docker

#### 45. **Nginx**
- **Purpose:** Web server/reverse proxy
- **URL:** https://nginx.org/
- **Cost:** Free (Open Source)
- **Installation:** `apt-get install nginx` (Linux)

---

## 📋 Summary Checklist

### Phase 1: Setup (Week 1)
- [ ] Install Node.js and npm
- [ ] Install Python 3.11+
- [ ] Install PostgreSQL
- [ ] Install Docker
- [ ] Create GitHub repository

### Phase 2: Frontend (Week 2)
- [ ] Create React app with Bookland template
- [ ] Install React dependencies (Priority 2)
- [ ] Install UI libraries (Priority 6, #16-24)

### Phase 3: Backend (Week 3)
- [ ] Install FastAPI and dependencies (Priority 7)
- [ ] Set up database (Priority 8)
- [ ] Configure authentication

### Phase 4: WordPress Plugins (Week 4)
- [ ] Install BuddyPress (for patterns)
- [ ] Install bbPress (for patterns)
- [ ] Install other relevant plugins (Priority 3-5)

### Phase 5: Development Tools (Week 5)
- [ ] Install ESLint, Prettier, Husky (Priority 9)
- [ ] Set up testing framework (Priority 10)
- [ ] Configure deployment tools (Priority 11)

---

## 💾 Download Locations Summary

### NPM Packages (Automatic via npm install)
- All React libraries
- All JavaScript dependencies

### WordPress.org (Free Plugins)
- BuddyPress
- bbPress
- Paid Memberships Pro
- WooCommerce
- Ultimate Member
- Advanced Custom Fields
- Pods
- DW Question & Answer
- AnsPress

### WordPress.org (Premium Plugins)
- WooCommerce Subscriptions ($199/year)
- WooCommerce Memberships ($149/year)
- UserPro ($39)
- Visual Composer ($59)
- Revolution Slider ($85)
- ACF Pro ($49)

### Python (via pip)
- All FastAPI dependencies

### System Tools
- Docker (Free)
- PostgreSQL (Free)
- Node.js (Free)
- Python (Free)

---

## 💰 Cost Estimate

### Required Costs:
- **Free Tools:** $0 (All open-source)
- **Premium Plugins (Optional):** $467 (if purchased)
  - WooCommerce Subscriptions: $199/year
  - WooCommerce Memberships: $149/year
  - Visual Composer: $59
  - Revolution Slider: $59
  - UserPro: $39
  - ACF Pro: $49
  - **Total Optional: $467**

### **Recommendation:** Start with free plugins for pattern study, purchase premium later if needed.

---

## 📞 Resources

### Documentation:
- React: https://react.dev/
- FastAPI: https://fastapi.tiangolo.com/
- Bootstrap: https://getbootstrap.com/
- BuddyPress: https://buddypress.org/documentation/
- WooCommerce: https://woocommerce.com/documentation/

### Community:
- Stack Overflow: https://stackoverflow.com/
- Reddit (r/reactjs, r/python): https://www.reddit.com/
- Discord servers for React and FastAPI

---

*Document created: January 16, 2026*
*Total plugins listed: 45*
*Priority system implemented*
*Installation instructions provided*