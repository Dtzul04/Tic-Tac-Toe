# Tic-Tac-Toe

A classic tic-tac-toe game built with React, following the official [React tutorial](https://react.dev/learn/tutorial-tic-tac-toe).

This project walks through core React concepts—components, props, state, and event handling—by building a playable game step by step.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser. The page reloads automatically when you save changes.

### Other scripts

| Command           | Description              |
| ----------------- | ------------------------ |
| `npm run build`   | Production build         |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run ESLint               |

## Project Structure

```
src/
├── App.jsx      # Board and Square components
├── App.css      # Game board styles
├── main.jsx     # App entry point
└── index.css    # Global styles
```

## How It Works

- **`Square`** — A clickable button that tracks its own value with `useState`. Clicking a square sets it to `"X"`.
- **`Board`** — Renders a 3×3 grid of nine `Square` components.

As you continue the tutorial, state will be lifted to the `Board` component so turns alternate between X and O, moves are tracked, and winners are detected.

## Learn More

- [React Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)
- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vite.dev/)

## Tech Stack

- [React 19](https://react.dev/)
- [Vite 8](https://vite.dev/)
