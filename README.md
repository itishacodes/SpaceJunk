# 🌌 Space Junk

Every object ever launched into the void. An interactive digital galaxy canvas where anyone can draw, name, and archive their custom cosmic debris permanently in real-time.

🔗 **Live Project Link:** [Click here to explore the Galaxy](https://itishacodes.github.io/SpaceJunk/)

---

## 🚀 Features

* **Interactive Space Canvas:** Draw your own rockets, UFOs, or alien lifeforms using an HTML5-powered drawing board.
* **Real-time Cosmic Deployment:** Watch your creation instantly join the permanent collective space archive without refreshing the page.
* **Global Archive Gallery:** A beautiful, filterable archive equipped with real-time countdown badges showing the lifespan of active space debris.
* **Secure Infrastructure:** Powered by a dual-locked cloud backend with strictly monitored domain-level data pipelines.

---

## 🛠️ Tech Stack

* **Frontend:** Semantic HTML5, Custom CSS3 (Glassmorphic Dark Space Theme), Native JavaScript (ES6+).
* **Graphics Engine:** HTML5 Canvas API for smooth mouse/touch rendering.
* **Backend & Database:** Firebase Realtime Database (NoSQL) for instant cross-client syncing.
* **Hosting:** GitHub Pages.

---

## 🛡️ Security Architecture

To prevent unauthorized database pollution, the network pipeline is secured via:
1.  **Google Cloud HTTP Referrer Restrictions:** The API tokens are explicitly restricted to respond only to requests originating from the production domain.
2.  **Firebase Structural Rules:** Data schemas validate strings, enforce length limits, and prevent existing records from being overwritten or deleted.
