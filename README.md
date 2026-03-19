# TicOX Play

![TicOX Play Logo](https://via.placeholder.com/150x50?text=TicOX+Play) <!-- Replace with actual logo if available -->

A sleek and interactive Tic-Tac-Toe game built with modern web technologies. Challenge a friend to a classic game of X's and O's with smooth animations and responsive design.

## 🚀 Features

- **Classic Gameplay**: Traditional 3x3 grid Tic-Tac-Toe for two players
- **Real-time Win Detection**: Instantly identifies winners, draws, and game states
- **Score Tracking**: Maintains a persistent score across multiple rounds
- **Smooth Animations**: Engaging popup notifications with CSS animations
- **Mobile-Friendly**: Fully responsive design that adapts to any screen size
- **Fast Performance**: Optimized with Vite for quick load times

## 🛠️ Tech Stack

- **Frontend Framework**: React 19 (using functional components and hooks)
- **Build Tool**: Vite 7 (for rapid development and production builds)
- **Styling**: Pure CSS with custom properties, CSS Grid, and media queries
- **State Management**: React Context API for game state handling

## 📁 Project Structure

```
TicOX-o/
├── public/
│   └── ... (static assets)
├── src/
│   ├── main.jsx              # Application entry point
│   ├── App.jsx               # Main app component
│   ├── App.css               # App-specific styles
│   ├── index.css             # Global styles and CSS variables
│   ├── components/
│   │   └── board.jsx         # Game board, squares, and result popup
│   └── context/
│       └── gameContext.jsx   # Game state management (board, turns, scores)
├── package.json              # Project dependencies and scripts
├── vite.config.js            # Vite configuration
├── eslint.config.js          # ESLint configuration
└── index.html                # HTML template
```

## 🎮 How to Play

1. The game starts with Player X.
2. Click on any empty square to place your mark (X or O).
3. Players alternate turns until someone wins or the board is full.
4. Win by getting three marks in a row (horizontally, vertically, or diagonally).
5. If the board fills without a winner, it's a draw.
6. Scores are tracked and displayed at the top.

## 🏁 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TicOX-o.git
   cd TicOX-o
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in the terminal).

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic Tic-Tac-Toe game
- Built with love using React and Vite

---

Enjoy playing TicOX Play! 🎉
