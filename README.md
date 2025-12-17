# Provis Technologies Homepage Clone

A responsive and interactive clone of the Provis Technologies Private Limited official homepage. This project demonstrates advanced layout techniques using Tailwind CSS, custom CSS animations, and functional JavaScript components.

## 🚀 Features

* **Responsive Hero Section**: Includes a dynamic navigation bar with dropdown menus, a "Green Glow" visual effect, and a call-to-action (CTA) for booking meetings.
* **Brand Carousel**: An infinite-scroll animation displaying various partner and client logos.
* **Interactive Service Tabs**: A tabbed interface allowing users to toggle between AI Development, SaaS, and eCommerce services with smooth transitions.
* **Process Visualization**: A "4 Simple Steps" section (Discover, Design, Test, Support) featuring synchronized progress bars and image cross-fades.
* **Product Backbone Grid**: A visual representation of the technology stack (CRM, Payments, Cloud Infra, etc.) connected by a dotted architectural layout.
* **Mobile Optimized**: Fully responsive design with a dedicated mobile hamburger menu and stackable grid layouts for smaller screens.

## 🛠️ Tech Stack

* **HTML5**: Semantic structure.
* **Tailwind CSS (v4.1.16)**: Used via CLI and CDN for utility-first styling and rapid development.
* **JavaScript (Vanilla)**: For tab switching, menu toggling, and the automated process animation.
* **Font Awesome**: For scalable vector icons.

## 📂 Project Structure

* `index.html`: Main entry point containing the structure and inline scripts for interactivity.
* `input.css`: Source CSS file using `@import "tailwindcss"` and custom keyframe animations.
* `output.css`: The compiled Tailwind CSS file used in the production environment.
* `package.json`: Contains project dependencies, specifically Tailwind CSS and its CLI.
* `template/`: Directory for storing local assets like logos and background images (referenced in HTML).

## ⚙️ Installation & Setup

1.  **Clone the repository**:
    ```bash
    git clone <your-repository-url>
    ```
2.  **Install dependencies**:
    Ensure you have [Node.js](https://nodejs.org/) installed, then run:
    ```bash
    npm install
    ```
3.  **Build CSS**:
    If you make changes to `input.css`, recompile using Tailwind CLI:
    ```bash
    npx @tailwindcss/cli -i ./input.css -o ./output.css --watch
    ```
4.  **Run the project**:
    Open `index.html` in your preferred browser.

## 📝 License

This project is a clone created for educational/demonstration purposes. All original branding and content rights belong to **Provis Technologies Private Limited**.
