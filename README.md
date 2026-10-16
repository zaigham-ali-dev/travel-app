Triply — Smart Travel & Budget Planner

**Plan smarter. Travel better. Spend wisely.**

Triply is a travel planning and budgeting web application designed to help travelers manage expenses, estimate travel costs, compare destinations, and plan their trips more efficiently.

Live Demo:** [Visit Triply](https://travel-app-ggdg.vercel.app/)

---

Features

- Travel Planning** — Organize trips and explore destinations.
- Travel Budget Calculator** — Estimate travel expenses and manage your budget.
- Cost of Living Comparison** — Compare living costs between destinations.
- Currency Conversion** — Make travel expenses easier to understand across currencies.
- Expense Tracking** — Keep track of spending during your travels.
- Accommodation Comparison** — Compare accommodation options when planning a trip.
- AI Budget Recommendations** — Get smarter budget-planning suggestions where supported.
- Route Optimization** — Plan travel routes more efficiently where supported.
- Daily Spending Forecasts** — Estimate daily spending to help stay within budget.
- Authentication** — Sign in and sign up using supported authentication methods.
- Responsive Design** — Use the application across desktop, tablet, and mobile screens.

Tech Stack

| Technology | Purpose |
| Next.js | Web framework |
| React | User interface |
| TypeScript | Type-safe development |
| Tailwind CSS | Styling and responsive layouts |
| Firebase Authentication | User authentication |
| Cloud Firestore | Cloud database, where configured |
| Vercel | Deployment and hosting |

Getting Started

Follow these steps to run Triply locally.

Prerequisites

- Node.js
- npm
- A Firebase project with the services required by the application enabled

### 1. Clone the repository

```bash
git clone https://github.com/Zaigham-Ali-cyber/travel-app.git
```

### 2. Navigate to the project

```bash
cd travel-app
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env.local` file in the project root and add the Firebase configuration variables required by your application.

Use the exact variable names referenced in your Firebase configuration code. Never commit private credentials, service-account keys, or other secrets to GitHub.

### 5. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

Project Structure

```text
travel-app/
├── app/                 # Application pages and routes
├── components/          # Reusable UI components
├── lib/                 # Shared libraries and utilities
├── public/              # Static assets
├── firebase.ts          # Firebase configuration
├── package.json         # Dependencies and scripts
├── package-lock.json    # Dependency lockfile
├── next.config.ts       # Next.js configuration
├── tsconfig.json        # TypeScript configuration
└── README.md             # Project documentation
```

Security

- Keep secret credentials out of source control.
- Use environment variables for sensitive configuration.
- Configure Firebase Authentication and Firestore security rules appropriately.
- Never expose Firebase Admin SDK credentials in client-side code.

Deployment

Triply is deployed on Vercel.

**Live Application:** https://travel-app-ggdg.vercel.app/

For your own deployment, connect the GitHub repository to Vercel, configure the required environment variables, and deploy the project.

Project Goal

Triply aims to make travel planning more organized by bringing budgeting, expense management, destination research, and travel planning tools together in one application.

Developer

**Zaigham Ali**

- GitHub: [@Zaigham-Ali-cyber](https://github.com/Zaigham-Ali-cyber)

License

No license has been specified yet. All rights are reserved by default unless a license is added to the repository.

---

If you find this project interesting, consider starring the repository!
