# Ahmed Ounissi - Developer Portfolio

The source code for my personal portfolio website, designed to showcase my skills in IT Support, Software Engineering, and Automation. Built with a focus on performance, cleanliness, and modern web standards.

🔗 **Live Demo:** [https://ahmed-ounissi.github.io/devportfolio](https://ahmed-ounissi.github.io/devportfolio)

## 🚀 Tech Stack

- **[Astro](https://astro.build/)** - Static site generator for blazing fast performance
- **[Tailwind CSS v4](https://tailwindcss.com/)** - Utility-first styling
- **[TypeScript](https://www.typescriptlang.org/)** - Type safety and maintainability
- **[Tabler Icons](https://tabler.io/icons)** - Clean, consistent iconography

## 🛠️ Project Structure

```bash
devportfolio/
├── public/          # Static assets (favicons, images)
├── src/
│   ├── components/  # Reusable UI components (Hero, About, Projects)
│   ├── pages/       # Route definitions (index.astro)
│   ├── styles/      # Global styles and Tailwind configuration
│   └── config.ts    # Centralized content configuration
├── astro.config.mjs # Astro build configuration
└── package.json     # Project dependencies
```

## 💻 Local Development

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ahmed-ounissi/devportfolio.git
    cd devportfolio
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Start the development server:**
    ```bash
    npm run dev
    ```

## 📦 Deployment

This project is configured for automated deployment to **GitHub Pages** using GitHub Actions.

### How it works:
1.  Push changes to the `main` branch.
2.  The `.github/workflows/deploy.yml` action triggers automatically.
3.  Astro builds the site and deploys it to the `gh-pages` environment.

## 📝 Customization

All content is managed via `src/config.ts`. To update the portfolio:
1.  Open `src/config.ts`.
2.  Edit the `siteConfig` object (name, social links, projects, etc.).
3.  Commit and push the changes.

---
*© 2025 Ahmed Ounissi.*
