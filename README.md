# Find The Traitor 🎭

**Find The Traitor** is a real-time multiplayer social deduction game where players join a private room, answer questions, and vote to identify the traitor among them.

🌐 **Live Demo:** https://findthetraitor.com

## 🎮 Features

* **Private Game Rooms** — Create or join rooms to play with friends.
* **Real-Time Multiplayer** — Keep players connected and synchronise game activity.
* **Question and Answer Gameplay** — Players respond to questions as part of each round.
* **Voting System** — Vote to identify the suspected traitor.
* **Game State Management** — Manage game progression and player interactions throughout a session.
* **Web-Based Experience** — Play directly in a browser without installing an application.

## 🛠️ Tech Stack

| Technology   | Purpose                                                    |
| ------------ | ---------------------------------------------------------- |
| Next.js      | React-based web application framework                      |
| TypeScript   | Type-safe application development                          |
| Tailwind CSS | Responsive user interface styling                          |
| Supabase     | Backend services, data storage and real-time functionality |
| Vercel       | Application deployment and hosting                         |
| Git & GitHub | Version control and source code management                 |

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

* Node.js and npm
* A Supabase account and project
* Git

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Navigate into the project directory:

   ```bash
   cd YOUR_PROJECT_FOLDER
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env.local` file in the project root and add your Supabase configuration:

   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

   Replace the placeholder values with the appropriate credentials from your Supabase project.

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open http://localhost:3000 in your browser.

**Note:** The environment variable names above are examples. Use the exact names expected by your application's Supabase configuration. Any required database tables, policies, or other Supabase setup must also be configured.

## 🧠 Development

This project provided practical experience in:

* Building a full-stack web application using Next.js and TypeScript.
* Implementing multiplayer gameplay and coordinating game state.
* Integrating Supabase for backend functionality and data management.
* Managing application state across different stages of a game.
* Using Git and GitHub for version control.
* Deploying a web application using Vercel.

AI-assisted development tools were used to support implementation and problem-solving throughout development.

## 🌍 Play Online

Try the game here: **[findthetraitor.com](https://findthetraitor.com)**

## 📄 License

No licence has been specified. All rights are reserved by default unless a licence is added to the repository.
