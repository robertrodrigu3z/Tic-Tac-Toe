# Tic-Tac-Toe Game

I used this project as a personal test to see the impact of vibe-coding, done through Kiro.

A tic-tac-toe game built with React, Vite, and TypeScript, styled with a hand-drawn aesthetic featuring a dark background and red elements.

## Features

- ✅ Win detection (rows, columns, diagonals)
- ✅ Draw detection
- ✅ Turn alternation between X and O
- ✅ Reset button to start a new game
- ✅ Hand-drawn visual style matching the reference design
- ✅ Responsive design for mobile devices

## Getting Started

### Prerequisites

Make sure you have Node.js installed (v16 or higher recommended).

### Installation

Dependencies are already installed. If you need to reinstall:

```bash
npm install
```

### Running the Development Server

```bash
npm run dev
```

Then open your browser to the URL shown in the terminal (typically `http://localhost:5173`).

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## How to Play

1. Players take turns clicking on empty squares
2. X goes first
3. Get three in a row (horizontally, vertically, or diagonally) to win
4. If all squares are filled with no winner, it's a draw
5. Click "Reset Game" to start a new game

## Tech Stack

- **React** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **CSS3** - Styling with custom hand-drawn aesthetic
