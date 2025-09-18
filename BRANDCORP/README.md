# BRANDCORP

BRANDCORP is a platform designed to connect social media creators with brands for authentic, admin-verified partnerships. It provides a secure environment for brands to find creators, submit partnership requests, and manage campaigns, while creators can showcase their profiles and collaborate with trusted brands.

## Features

- **Admin Authentication:** All users and partnerships are verified by an admin for quality assurance.
- **Creator & Brand Registration:** Separate registration flows for creators and brands.
- **Dashboard:** Custom dashboards for creators, brands, and admins.
- **Detailed Analytics:** View stats and analytics for campaigns, users, and platform performance.
- **Privacy Protection:** Sensitive contact details are only accessible to admins.
- **Partnership Requests:** Brands can request partnerships with creators; admins facilitate and authenticate every deal.
- **Search & Filters:** Brands can search for creators by category, followers, platform, and more.
- **Responsive UI:** Modern, mobile-friendly interface using Tailwind CSS.

## Tech Stack

- **Frontend:** React (via CDN, Babel in-browser compilation)
- **Styling:** Tailwind CSS, Font Awesome
- **State Management:** React Context API
- **Mock Data:** In-memory JavaScript objects (no backend)

## Getting Started

1. **Clone or Download the Project**
   - Place all files in a folder (e.g., `BRANDCORP`).

2. **Open `index.html`**
   - Double-click or open in your browser.
   - No build step required; all dependencies are loaded via CDN.

3. **Demo Accounts**
   - Creator: `maya@example.com` / `password123`
   - Brand: `priya@stylecorp.com` / `brand123`
   - Admin: `admin@brandcorp.com` / `admin123`

## Usage

- **Home:** Overview and call-to-action for creators and brands.
- **Register/Login:** Create or access your account.
- **Dashboard:** 
  - Creators: View campaigns, analytics, and manage profile.
  - Brands: Search creators, manage campaigns, view analytics.
  - Admins: Approve users, manage partnerships, view platform stats.
- **How It Works:** Step-by-step explanation of the platform process.
- **Contact:** Contact form and company info.

## Customization

- All logic and UI are in `index.html` (React via Babel).
- To add features, edit the `<script type="text/babel">` section.
- For production, consider migrating to a full React project with backend support.

## License

This project is for demonstration and educational purposes only.
