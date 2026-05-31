# SMMTor - Professional SMM Panel & Mobile Application

SMMTor is an enterprise-grade Social Media Marketing (SMM) Panel solution featuring a highly responsive, custom PHP backend and a robust, modern mobile client app built using Flutter. This hybrid architecture ensures real-time synchronisation of services, orders, payments, and tickets.

---

## 🚀 Key Features

### 💻 Web Administration & Client Panel (PHP)
- **Advanced Dashboard:** Real-time analytics, 30-day performance charts (via Chart.js), and quick-action shortcuts.
- **Dynamic Order Gateway:** Automated SMM service placement, status checking, and automatic/manual refills.
- **Admin Managed Payments:** Live database-driven payment methods (bKash, Nagad, Rocket, Stripe, etc.) configurable directly from the admin panel.
- **Support Tickets System:** Integrated chat-like customer helpdesk with instant notifications.
- **Developer API Access:** Complete developer API (`/api/v2`) allowing clients to automate SMM actions programmatically.
- **Affiliate & Referral:** Integrated system for users to invite friends and earn commission dynamically.

### 📱 Native Mobile Application (Flutter)
- **Real-Time Data Sync:** 100% dynamic fetching from the PHP backend via secure REST API (No slow Web-Views).
- **Theme Mode Switcher:** Sleek, animated Sun-Moon toggle switch embedded globally inside a unified header.
- **Network Resilience:** Plays Store-compliant offline tracking using native `connectivity_plus` triggers.
- **Payment Method Dropdown:** Elegant, dynamically rendered dropdown listings that match the backend's active gateways.
- **Seamless Support:** Directly open new tickets or track refill status on-the-go.

---

## 🛠️ Technology Stack

| Layer | Technologies Used |
| :--- | :--- |
| **Backend Core** | PHP 8.1, MySQL, Composer |
| **Web Frontend** | Twig Templating, Bootstrap 5, Sneat Admin Template |
| **Mobile App** | Flutter (Dart), Riverpod (State Management), Dio (Networking) |
| **Libraries** | Chart.js, PHPMailer, Google 2FA, Leaflet Map |

---

## 📁 Repository Directory Structure

```
smmpanel/
├── admin-theme/             # Admin panel assets and views
├── assets/                  # Public web assets (JS, CSS, Images)
├── core/                    # Core PHP application logic
│   ├── application/         # Admin views (header, footer, index) & controllers
│   ├── classes/             # Main helper classes
│   ├── controller/          # User-side controllers (addfunds, refill, login)
│   └── database.php         # Database configuration file
├── database.sql             # MySQL database template for fresh install
├── mobile/                  # Flutter mobile application codebase
│   ├── lib/
│   │   ├── core/            # Global UI widgets, themes, and network clients
│   │   └── features/        # Modular features (auth, orders, profile, support)
│   └── pubspec.yaml         # Dart dependencies
└── server/                  # Standalone secure API gateway for the mobile app
```


---

## 🔒 License & Usage
This project is licensed under a **Proprietary Commercial Software License**. Unauthorized copying, redistribution, modification, or reselling of this source code is strictly prohibited. Please refer to the [LICENSE](file:///c:/smmpanel/smmpanel/LICENSE) file for the full legal terms.
