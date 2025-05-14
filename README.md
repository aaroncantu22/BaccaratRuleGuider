# 🎴 Baccarat 3rd Card Rule Assistant

A web-based tool to simulate and understand the complex third card drawing rules of **Punto Banco Baccarat**, one of the most popular casino card games. This application allows players to input hand totals and optional third cards, then automatically evaluates the game using official Baccarat rules.

## 💡 Features

- ✅ Real-time evaluation of player and banker hands.
- ✅ Handles natural hands (8 or 9) automatically.
- ✅ Implements full third card draw logic for both Player and Banker.
- ✅ Color-coded and styled scoreboard for visual clarity.
- ✅ Detailed breakdown of decision-making logic for both sides.
- ✅ Winner announcement with visual highlights.
- ✅ Reset button to clear all inputs and results.

## 📁 File Structure

- `baccarat.html` — The main standalone file containing:
  - HTML layout
  - Embedded CSS styles
  - JavaScript logic for decision-making

## 🧠 Baccarat Rules Overview (Implemented Logic)

- **Natural Rule**: If either the Player or Banker has a total of 8 or 9, the game ends immediately.
- **Player Rule**: If the Player total is 5 or less, they draw a third card.
- **Banker Rule**: Banker’s action depends on:
  - Their own total
  - Whether the Player drew a third card
  - The value of the Player's third card (if drawn)

All of these conditions are dynamically evaluated in the app with clear feedback.

## 🚀 How to Use

1. Open `baccarat.html` in any modern web browser.
2. Enter the Player and Banker hand totals (0–9).
3. If applicable, enter third cards for Player and Banker.
4. Click **Evaluate Hand** to see:
   - Who draws
   - What the final totals are
   - Who wins
5. Click **Reset** to start over.

## 📷 Screenshot

![Screenshot Example](https://via.placeholder.com/800x400?text=Baccarat+3rd+Card+Rule+Assistant)  
*(Replace with actual screenshot)*

## 🛠 Suggestions for Future Enhancements

- Mobile responsiveness and layout improvements.
- External JS/CSS file separation.
- Accessibility enhancements (ARIA roles, keyboard support).
- Pre-filled test scenarios for learning.
- Language support for multilingual users.
- Option to export results or download a report.

## 👨‍💻 Author

Created by **Aaron Cantu**  
Senior CSCI Major, Fresno State  
Casino Night 2025 Web App Series 🎲

## 📜 License

This project is released under the MIT License.
