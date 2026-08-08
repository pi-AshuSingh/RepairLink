<div align="center">
  <img src="logo.png" alt="RepairLink Logo" width="120" />
  
  # 🛠️ RepairLink
  **Mat Feko, Fix Karo. Mapping North Delhi's kaarigars — repair first, recycle what's left.**

  [![Website Live](https://img.shields.io/badge/Live-repairlink--de1ta.web.app-success?style=for-the-badge&logo=firebase)](https://repairlink-de1ta.web.app)
  [![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)](https://firebase.google.com/)
  [![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://html.com/)
  [![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/Overview.en.html)
  [![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
</div>

<br/>

**RepairLink** is a community-driven platform built for a circular economy. Instead of throwing away a broken mixer or a torn shoe, RepairLink instantly connects you with verified local artisans (*kaarigars*) capable of fixing it. 

---

## 🌟 Comprehensive Feature Set

### 🚀 **Recent Updates & Enhancements**
- 🛡️ **Robust Security:** Mitigated XSS vulnerabilities by escaping user-generated data across map popups and detail panels.
- 🎨 **Premium UI/UX Overhaul:** Implemented elegant glassmorphism (frosted glass) effects, smooth hover animations, and a unified pastel mesh gradient background across all pages.
- 🤖 **Reliable AI Integration:** Deployed a fully responsive, Streamlit-based AI chatbot accessible across all pages (including the admin panel) for seamless assistance.
- 📱 **Mobile-Optimized Navigation:** Redesigned scrollable sidebars in dashboards ensuring critical actions like "Return to Home" and "Back to Map" are always accessible on small screens.
- 📊 **Enhanced Admin Analytics:** Added dynamic tracking of new page visits, live Premium user counts, and automated total revenue calculations.
- ⭐ **Advanced Order Management:** Introduced intuitive Kaarigar rating prompts upon order completion, and interactive stale order tracking for users.

### ✨ **New Additions & Gamification**
- 🏆 **Eco-Gamification System:** Users earn "Waste Points" for every completed repair, unlocking progressive levels (Eco-Beginner, Eco-Warrior, Eco-Champion, Eco-Master).
- 🏅 **Unlockable Badges:** Interactive UI badges unlock based on achievements (*Early Adopter*, *First Repair* 🛠️, *Eco-Saver* 🏆).
- 💰 **Dynamic Service Pricing:** Tiered up-front connection fees (e.g., Cobbler ₹9, Locksmith ₹19, Appliance ₹39) ensuring fair and transparent platform costs.
- 📱 **Kaarigar Engagement Suite:** Dedicated tabs for Kaarigars to track **Earnings**, read **Reviews**, and access **Help & Support** directly from their dashboard.
- 📍 **Interactive Kaarigar Profile Mapping:** Kaarigars can drop pins on an embedded **Leaflet Map** or use 1-click **Auto-Detect GPS** to update their storefront locations securely.
- 📈 **Advanced Admin Analytics:** Comprehensive admin panel with real-time charts displaying revenue streams, page visit metrics, active orders, and service distributions.

### 🛠️ **Core Platform Features**
- 🗺️ **Geo-Fenced Discovery:** Utilizes Leaflet JS & CARTO Voyager tiles with an **Inverted Polygon Mask** to highlight the active service area (North Delhi), dimming out unserviceable regions.
- 👥 **Dedicated Role Portals:** 
  - **User Dashboard (`UserDashboard.html`)**: Track active repairs, eco-impact metrics, and manage premium memberships.
  - **Kaarigar Dashboard (`KaarigarDashboard.html`)**: Profile management, service request handling, and business insights.
  - **Admin Control Center (`Admin.html`)**: Kaarigar verification pipelines, site analytics, and support ticket management.
- 🔒 **Privacy-First Architecture:** Strict Role-Based Access Control (RBAC). Contact numbers and sensitive data are strictly masked from public view and accessible only through authorized requests to prevent data scraping.
- 🌐 **Bilingual Accessibility:** Instant English ↔ Hindi localization toggle, keeping the UI inclusive for diverse demographics without layout shifts.
- 💬 **Integrated AI Support:** Floating, draggable AI Chatbot embedded directly into the platform providing instant, contextual assistance.
- 💳 **Premium Membership Tiers:** Users can subscribe for free priority services and waived upfront connection fees.

## 📊 Platform Analytics & Insights

<div align="center">
  <img src="https://img.shields.io/badge/Total_Commits-243-blue?style=for-the-badge&logo=github" alt="Total Commits" />
  <img src="https://img.shields.io/badge/Collaborators-4-purple?style=for-the-badge&logo=github" alt="Collaborators" />
  <img src="https://img.shields.io/badge/Total_Visits-2175-success?style=for-the-badge&logo=google-analytics" alt="Total Visits" />
  <img src="https://img.shields.io/badge/Active_Users-19-orange?style=for-the-badge&logo=firebase" alt="Users" />
  <img src="https://img.shields.io/badge/Verified_Kaarigars-8-green?style=for-the-badge&logo=firebase" alt="Kaarigars" />
</div>

<br/>

### 👥 Top Contributors

| Collaborator | 🔨 Total Commits | 🌟 Features Added |
| :--- | :---: | :---: |
| **Ashutosh Kumar Singh** | 230 | 95 |
| **Sanvi Gupta** | 11 | 5 |
| **Shreya860** | 1 | 0 |
| **Samya Goel** | 1 | 0 |

### 📈 Website Traffic (Page Visits)

| Page | Views | Popularity |
| :--- | :---: | :--- |
| **`RepairLink.html`** (Core Map) | **644** | 🟢🟢🟢🟢🟢🟢 |
| **`index.html`** (Landing Page) | **502** | 🟢🟢🟢🟢🟢 |
| **`Auth.html`** (Login/Signup) | **286** | 🟢🟢🟢 |
| **`Admin.html`** | **243** | 🟢🟢 |
| **`UserDashboard.html`** | **185** | 🟢 |
| **`Pricing.html`** | **118** | 🟢 |
| **`AboutUs.html`** | **89** | ⚪ |

### 🔥 Live Firebase Stats Snapshot
- **Registered Users:** 19 (including 3 kaarigar accounts)
- **Verified Kaarigars:** 8 (0 pending verifications)
- **Service Orders:** 6 (1 awaiting approval)
- **Support Messages:** 5 (3 unread)

---

## 🏗️ Project Architecture

| Page | Description |
| :--- | :--- |
| **`index.html`** | Landing page featuring a repair vs. replace calculator, dynamic testimonials, an accordion FAQ, and a premium aesthetic. |
| **`RepairLink.html`** | The core map interface where users locate and request services from local kaarigars. |
| **`Pricing.html`** | Transparent breakdown of our dynamic connection fee models and premium plans. |
| **`UserDashboard.html`** | Complete user tracking hub with gamification progress and active repair monitoring. |
| **`KaarigarDashboard.html`**| Business hub for artisans featuring map integration, earnings previews, and request management. |
| **`Admin.html`** | Analytics dashboard with dynamic charts and Kaarigar approval workflows. |
| **`Auth.html`** | Secure authentication handling via Firebase Auth. |
| **`AboutUs.html`** | Mission statement page, featuring an interactive audio equalizer for the custom theme song. |
| **`script.js`** | The frontend brain handling Leaflet maps, Firestore listeners, auth state, and complex UI routing logic. |

---

## 🛠️ Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,firebase,python" />
</div>

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (Zero heavy frameworks for maximum performance)
*   **Backend & Database:** Firebase (Cloud Firestore, Authentication)
*   **Hosting:** Firebase Hosting
*   **Mapping:** Leaflet JS with CARTO basemaps
*   **AI Chatbot (External):** Python, Streamlit, LangChain, Groq

---

## 🚀 Run it Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shreya860/RepairLink.git
   ```

2. **Install Firebase CLI:**
   ```bash
   npm install -g firebase-tools
   ```

3. **Serve the Frontend:**
   You can serve the HTML files using any local web server. For example:
   ```bash
   npx serve . -p 3000
   ```
   Or simply use the VS Code Live Server extension.

4. **Deploying Updates:**
   ```bash
   npx firebase-tools deploy --only hosting
   ```

---

## 🎵 Our Theme Song

We believe fixing things shouldn't be boring! RepairLink has its very own custom-produced theme song. 
Listen to it right here:

<video src="https://github.com/Shreya860/RepairLink/raw/main/theme-song.mp3" controls="controls" style="max-width: 100%;"></video>

---

## 🌐 Connect With Us

Join the RepairLink community and stay updated with our mission to build a circular economy:

*   [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/repairlink-official)
*   [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/repairlink.in/)
*   [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@RepairLink.handleYT)

