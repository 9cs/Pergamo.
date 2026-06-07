# Pergamo

A modern, high-performance platform for practicing ENEM (Brazilian High School National Exam) questions. Pergamo provides a seamless study experience with a massive database of real exam questions, immediate feedback, and interactive performance tracking.

## 🚀 Key Features

- **Massive Question Bank:** Access to **3,500+ real questions** spanning from 2009 to 2024.
- **Instant Explanations:** Get immediate feedback with detailed explanations to understand the reasoning behind every answer.
- **Smart Shuffling:** Alternatives are dynamically shuffled for every attempt, preventing "positional memory" and ensuring you actually learn the content.
- **Subject-Specific Tracks:** Practice by specific disciplines (Mathematics, Physics, History, etc.) or broader knowledge areas (Nature Sciences, Humanities).
- **Responsive & Minimalist:** A clean, distraction-free interface built with Radix UI and Tailwind CSS, fully optimized for both desktop and mobile.
- **Performance Analytics:** Track your accuracy, total study time, and average speed per question at the end of each session.
- **Full Media Support:** High-quality rendering of complex diagrams, charts, and texts exactly as they appeared in the original exams.

## 🛠️ Tech Stack

- **Framework:** [Next.js 15](https://nextjs.org/) (App Router)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **State & UI:** [shadcn/ui](https://ui.shadcn.com/) / [Radix UI](https://www.radix-ui.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Infrastructure:** [Upstash Redis](https://upstash.com/) for rate limiting and [Vercel](https://vercel.com/) for edge-optimized deployment.

## 🤝 Credits & Acknowledgments

Pergamo is built upon the excellent foundation provided by the [enem-api](https://github.com/yunger7/enem-api), originally created by [Luís (yunger7)](https://github.com/yunger7). 

**What's new in this fork?**
- **Expanded Database:** Added over 1,000 additional questions, including the most recent 2023 and 2024 exams.
- **UI Refactor:** Completely new frontend built with Next.js 15 and modern Tailwind components.
- **Enhanced Logic:** Improved question filtering, shuffling algorithms, and explanation rendering.

## 📂 Project Structure

- `app/`: Next.js App Router logic and API endpoints.
- `components/`: Modular React components (modals, buttons, question displays).
- `public/year/`: The project's "database" — a massive collection of JSON files and images organized by year.
- `lib/`: Utility functions and core configuration.

## 🏃 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/pergamo.git
   cd pergamo
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   bun install
   ```

3. **Configure environment variables:**
   Create a `.env.local` file:
   ```env
   UPSTASH_REDIS_REST_URL=your_url
   UPSTASH_REDIS_REST_TOKEN=your_token
   ```

4. **Run development:**
   ```bash
   npm run dev
   ```

## 📄 License

This project is licensed under the MIT License.

---
Built to empower Brazilian students through technology and open-access education.
