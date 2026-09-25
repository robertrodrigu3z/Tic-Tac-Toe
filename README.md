# Tic-Tac-Toe Game

I used this project as a personal test/experiment to see the impact and power of vibe-coding, done through Kiro. All code and the following README.md messages were written by AI.

A modern tic-tac-toe game built with React, Vite, and TypeScript, following Vercel's React best practices for optimal performance and user experience.

## ✨ Features

### Game Features
- ✅ **Complete Game Logic**: Win detection (rows, columns, diagonals), draw detection, turn alternation
- ✅ **Score Tracking**: Persistent scoreboard tracking wins for X, O, and draws
- ✅ **Winning Animation**: Visual celebration when a player wins with highlighted squares
- ✅ **Active Player Indication**: Clear visual feedback showing whose turn it is
- ✅ **Game Controls**: Reset current game or clear all scores

### UI/UX Features
- 🎨 **Modern Design**: Clean, card-based layout with pastel green color scheme
- ✨ **Smooth Animations**: Entrance animations, hover effects, and winning celebrations
- 📱 **Fully Responsive**: Optimized for mobile, tablet, and desktop
- ♿ **Accessible**: ARIA labels for screen readers
- 🎯 **Visual Feedback**: Hover states, active player indicators, and status messages

### Performance Features (Vercel React Best Practices)
- ⚡ **Optimized Re-renders**: Uses `memo`, `useMemo`, and `useCallback` strategically
- 🚀 **Lazy State Initialization**: Efficient initial state creation
- 📊 **Derived State**: Winner calculated from board state, no redundant storage
- 🎯 **Stable References**: Callback functions with proper dependencies
- 🏗️ **Component Separation**: No inline component definitions
- 📦 **Early Exit Patterns**: Optimized conditional logic

## 🎮 How to Play

1. **Take Turns**: Players take turns clicking empty squares
2. **Win Condition**: Get three in a row (horizontally, vertically, or diagonally)
3. **Draw**: If all squares are filled with no winner, it's a draw
4. **New Game**: Click "New Game" to start fresh while keeping scores
5. **Reset Scores**: Click "Reset Scores" to clear the scoreboard

## 🛠️ Tech Stack

- **React 18** - UI library with modern hooks
- **TypeScript** - Type safety and better developer experience
- **Vite** - Lightning-fast build tool and dev server
- **CSS3** - Modern animations and responsive design
- **Vercel Best Practices** - Performance-optimized React patterns

## 📦 Getting Started

### Prerequisites

Node.js v16 or higher recommended

### Installation

Dependencies are already installed. If you need to reinstall:

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Then open your browser to the URL shown (typically `http://localhost:5173`)

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## 🎨 Design System

### Color Palette (Pastel Green)
- **Primary**: `#66bb6a` - Main green for text and interactive elements
- **Primary Light**: `#81c784` - Accents and borders
- **Primary Dark**: `#4caf50` - Hover states and emphasis
- **Background Main**: `#e8f5e9` - Light green gradient base
- **Background Secondary**: `#f1f8e9` - Lighter green for squares
- **Card Background**: `#ffffff` - Clean white for cards

### Typography
- **Title**: Bold, large, with subtle text shadow
- **Body**: Clean sans-serif, highly readable
- **Weights**: 500 (medium), 700 (bold), 900 (black)

### Spacing System
- **XS**: 8px
- **SM**: 12px
- **MD**: 20px
- **LG**: 32px
- **XL**: 48px

## 📱 Responsive Design

The game automatically adapts to different screen sizes:

- **Desktop** (>600px): Full-size board with spacious layout
- **Mobile** (<600px): Compact board with touch-optimized controls

## ⚡ Performance Optimizations

Following [Vercel's React Best Practices](https://github.com/vercel-labs/agent-skills):

1. **Hoisted Constants** - `WINNING_LINES` defined outside component
2. **Memoized Components** - `Square` and `PlayerInfo` wrapped in `memo()`
3. **Lazy State Init** - `useState(() => Array(9).fill(null))`
4. **Derived State** - Winner computed with `useMemo()`, not stored
5. **Stable Callbacks** - `useCallback()` for `handleClick` and `resetGame`
6. **Early Exits** - Optimized conditional checks
7. **No Inline Components** - All components properly extracted

## 🧪 Code Quality

- ✅ TypeScript strict mode enabled
- ✅ Proper type definitions for all props
- ✅ ESLint ready configuration
- ✅ Accessible HTML semantics
- ✅ Clean component separation

## 📄 License

MIT

## 🙏 Acknowledgments

- Design inspired by modern UI/UX principles
- Performance patterns from [Vercel's React Best Practices](https://github.com/vercel-labs/agent-skills)
- Built with best practices for production-ready React applications
