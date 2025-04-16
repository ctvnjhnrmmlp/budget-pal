# Budget Pal

**Smart Expense Tracker w/ Data Insights**

> _"Classic, but elevated."_
> Budget Pal helps you take control of your finances by combining intuitive daily budgeting with visual data insights and smart suggestions — all in a sleek, user-friendly interface.

## Overview

**Budget Pal** is a modern web-based expense tracker that simplifies personal finance management through easy expense logging, intelligent budgeting goals, and insightful analytics.

### Solves:

- Tracking daily expenses with ease
- Monitoring spending habits visually
- Receiving AI-driven savings suggestions

### For:

- Individuals and families managing budgets
- Students, freelancers, and professionals aiming to save smarter

### Uniqueness:

- Combines simplicity with smart features
- Uses visualizations to drive actionable insights
- Optionally enhanced with OpenAI for intelligent suggestions

## Why Budget Pal?

Most finance apps are either too complex or too basic. Budget Pal bridges the gap by focusing on:

- **Simplicity** – Easy daily expense input and target setting
- **Intelligence** – Smart suggestions based on patterns or AI
- **Visualization** – Meaningful charts to understand your habits
- **Speed to Value** – MVP built in 2 days, emphasizing speed and clarity

## Features

- Daily Expense Input – Track expenses with a few clicks
- Budget Target System – Set monthly goals, monitor progress
- Data Visualization – View spending trends via Pie and Line charts
- Smart Suggestions – AI or rule-based system for saving tips
- Minimal & Focused – Designed to help, not overwhelm

## 🛠 Tech Stack

| Layer        | Technology                         |
| ------------ | ---------------------------------- |
| Frontend     | **Next.js**, **Tailwind CSS**      |
| Charts       | **Chart.js**                       |
| Backend      | **Prisma ORM**, **PostgreSQL**     |
| Intelligence | **OpenAI API** or rule-based logic |

## Roadmap

- [x] Phase 1: MVP with core features
- [ ] Phase 2: Add user authentication
- [ ] Phase 3: Enable data export (CSV/PDF)
- [ ] Phase 4: Mobile responsiveness & PWA support
- [ ] Phase 5: AI-powered prediction and budget optimization

## Getting Started

### Prerequisites

- Node.js & npm
- PostgreSQL
- Git
- (Optional) OpenAI API key

### Installation

```bash
git clone https://github.com/your-username/budget-pal.git
cd budget-pal
npm install
```

### Environment Variables

Create a `.env` file from `.env.example` and fill in:

```env
DATABASE_URL=your_postgresql_database_url
OPENAI_API_KEY=your_openai_api_key (optional)
```

### Run the App

```bash
npm run dev
```

## Architecture

```
[Frontend (Next.js)] → [Backend (Prisma/PostgreSQL)] → [AI Engine (OpenAI or logic-based)]
```

## Deployment

- **Cloud:** Ideal for Vercel or Railway
- **Database:** PostgreSQL (hosted or local)
- **AI Integration:** Optional with OpenAI API

## Contributing

We welcome community contributions!

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit and push your changes
4. Open a pull request

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

- Inspired by modern finance apps
- Built by John Rommel Octaviano
- Powered by OpenAI, Next.js, and the community
