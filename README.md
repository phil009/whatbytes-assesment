# WhatBytes - Skill Assessment Platform

A modern skill assessment dashboard built with Next.js and shadcn/ui, featuring interactive charts, real-time score updates, and a responsive layout.

![WhatBytes Dashboard](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/bandicam%202025-02-26%2013-27-53-269.jpg-ZMmO3YKyFc9LqC8ZouXvOVYc3Scr2i.jpeg)

## Features

- 📊 Interactive performance analytics
- 📱 Responsive design with collapsible sidebar
- 📈 Real-time score updates
- 📋 Syllabus-wise analysis
- 🎯 Detailed question analysis
- 📊 Performance comparison graphs

## Tech Stack

- [Next.js 14](https://nextjs.org/) - React framework
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [shadcn/ui](https://ui.shadcn.com/) - UI components
- [Recharts](https://recharts.org/) - Charting library
- [React Circular Progressbar](https://www.npmjs.com/package/react-circular-progressbar) - Circular progress indicators
- [Iconify](https://iconify.design/) - Icon system

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm/yarn/pnpm

### Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/whatbytes.git
cd whatbytes
```

2. Install dependencies:
```
npm install
```

3. Start the development server:

```
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.


## Project Structure

```
whatbytes/
├── app/
│   ├── layout.tsx        # Root layout with header and sidebar
│   ├── page.tsx          # Dashboard page
│   ├── skill-test/      # Skill test feature
│   │   ├── page.tsx
│   │   ├── comparison-graph.tsx
│   │   ├── score-chart.tsx
│   │   └── update-scores-modal.tsx
│   └── internship/      # Internship feature
│       └── page.tsx
├── components/
│   ├── app-sidebar.tsx   # Main sidebar component
│   └── ui/              # shadcn/ui components
├── public/              # Static assets
└── README.md
```

## Features in Detail

### Skill Test Dashboard

The skill test dashboard provides a comprehensive view of user performance:

- **Quick Statistics**: Shows rank, percentile, and correct answers
- **Comparison Graph**: Bell curve showing performance distribution
- **Syllabus Analysis**: Topic-wise performance breakdown
- **Question Analysis**: Score visualization with circular progress


### Interactive Updates

Users can update their scores through a modal interface:

- Update rank
- Update percentile
- Update current score
Changes are reflected in real-time across all visualizations.


### Responsive Design

- Full sidebar on desktop (≥1024px)
- Collapsible sidebar on mobile/tablet (<1024px)
- Logo acts as sidebar trigger on smaller screens
- Optimized layout for all device sizes
