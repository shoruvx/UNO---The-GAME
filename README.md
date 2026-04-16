# UNO --- The GAME

A beautiful, OpenGL-powered UNO game for macOS.

## 🚀 How to Play
1. **Goal**: Be the first player to get rid of all the cards in your hand.
2. **On Your Turn**: You must match the top card on the **Discard Pile** by either **Color** or **Number**.
3. **Special Cards**:
   - **Skip**: The next player misses their turn.
   - **Reverse**: Reverses the direction of play.
   - **Draw Two**: The next player draws two cards and misses their turn.
   - **Wild**: Player decides the next color to be matched.
   - **Wild Draw Four**: Player decides the next color AND the next player draws four cards and misses their turn.
4. **Drawing**: If you don't have a match, you must draw a card from the **Draw Pile**.
5. **Winning**: The first player to have no cards left wins the round!

## 🎮 Controls
- **Mouse**: 
  - Click a card in your hand to play it.
  - Click the **Draw Pile** (left side) to draw a card.
  - Click the color boxes when playing a Wild card.
  - Click the **Top-Right Corner** to view in-game help.
- **Keyboard**: 
  - **Press 'H'**: Toggle the in-game 'How to Play' instruction screen.

## 🛠 Prerequisites
Ensure you have the following installed on your Mac:
- **Homebrew**
- **CMake** (`brew install cmake`)
- **GLFW** (`brew install glfw`)
- **OpenGL** (Included with macOS)

## 🏗 Building and Running
1. **Clone the repository**:
   ```bash
   git clone https://github.com/srshoruv/UNO---The-GAME.git
   cd UNO---The-GAME
   ```
2. **Build the project**:
   ```bash
   mkdir -p build
   cmake -S . -B build
   cmake --build build
   ```
3. **Run the game**:
   ```bash
   ./build/UNO___The_GAME
   ```
   *Note: Always run the game from the project root so it can find the texture assets.*

---
Developed with ❤️ by [srshoruv](https://github.com/srshoruv).
