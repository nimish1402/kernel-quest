# Kernel Quest
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/KernelQuest/KernelQuest)
![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/KernelQuest/KernelQuest?utm_source=oss&utm_medium=github&utm_campaign=KernelQuest%2FKernelQuest&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)
[![Netlify Status](https://api.netlify.com/api/v1/badges/85915b75-a977-4f0d-88ad-f346d86a01cd/deploy-status)](https://app.netlify.com/projects/kernelquest/deploys)

**Learn Operating Systems Visually**

Kernel Quest is an interactive platform for learning core Operating System concepts through visualizations, simulators, and comprehensive notes. It is designed for students, educators, and anyone interested in understanding how operating systems work under the hood.

## Features

- **Interactive Visualizers**: Step-by-step animations for:
  - Page Replacement Algorithms (FIFO, LRU, Optimal, etc.)
  - CPU Scheduling Algorithms (FCFS, SJF, Round Robin, Priority, etc.)
  - Disk Scheduling Algorithms (FCFS, SSTF, SCAN, C-SCAN, etc.)
- **Comprehensive Notes**: Clean, documentation-style notes with diagrams and concept highlights for topics like memory management, process management, file systems, and more.
- **Algorithm Comparison**: Compare different algorithms side by side.
- **Modern UI**: Responsive, accessible, and themeable interface with dark mode support.

## Tech Stack

- **Framework**: [Next.js 15.2.4](https://nextjs.org/) — built on [React 19.1.0](https://react.dev/) and [TypeScript 5.8.3](https://www.typescriptlang.org/)
- **Styling & UI**: [Tailwind CSS 3.4.17](https://tailwindcss.com/), [Radix UI](https://www.radix-ui.com/), [Lucide React Icons](https://lucide.dev/)
- **Visualization & Animation**: [Framer Motion 12.16.0](https://www.framer.com/motion/), [Recharts](https://recharts.org/)
- **Backend & Payments**: [Supabase 2.49.9](https://supabase.com/), [Stripe](https://stripe.com/)
- **Forms & Validation**: [React Hook Form 7.57.0](https://react-hook-form.com/), [Zod 3.25.49](https://zod.dev/)
- **Tooling**: [pnpm](https://pnpm.io/) — workspace-aware, fast package manager

> See `package.json` for the full list of dependencies.

## Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm
- pnpm
  
### Installation
Fork and Clone the repository:
```bash
git clone https://github.com/your-username/KernelQuest.git
cd KernelQuest
```

Install pnpm globally if you haven't already
```bash
npm install -g @pnpm/exe@latest-10
```

Install dependencies:
```bash
pnpm install 
```

### Running Locally

Start the development server:
```bash
pnpm dev 
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

### Building for Production
```bash
pnpm build # or npm run build or yarn build
```


---

**Kernel Quest** is open source and maintained by the community. If you find it useful, consider starring the repo and sharing it with others!

---


