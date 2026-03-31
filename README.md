# 🥛 Milk Jug Puzzle Game
An interactive web-based puzzle game where you need to measure exactly 1 liter of milk using three jugs of different capacities: 12L, 7L, and 5L. Track your moves and try to achieve the optimal solution!

## 🎮 Game Overview

You have three jugs:
- **12L Jug** - starts full with 12 liter of milk
- **7L Jug** - starts empty
- **5L Jug** - starts empty

The goal is to get exactly **1 liter** of milk in any jug by pouring milk between the jugs while using the **minimum number of pours**.

## ✨ Features

- **Smooth Liquid Animation** - Watch the milk level rise and fall in each jug with smooth transitions
- **Smart Pour Buttons** - Buttons automatically hide when:
  - Source jug is empty
  - Destination jug is full
- **Directional Arrows** - Visual indicators showing pour direction:
  - ➡️ Pour to jug on the right
  - ⬅️ Pour to jug on the left
- **Victory Detection** - Automatically detects when you achieve 1 liter in any jug
- **Responsive Design** - Works on desktop and mobile devices
- **Visual Feedback** - Real-time volume display and bucket fill animation

## 🎯 How to Play

1. **Pour Milk**: Click the arrow buttons below each jug to pour milk into another jug
2. **Valid Moves Only**: Buttons are only shown when pouring is possible (source not empty AND destination not full)
3. **Watch the Animation**: The liquid level in each bucket animates smoothly as you pour
4. **Goal**: Achieve exactly 1 liter in any jug to win, while beating the optimal move count!

## 🕹️ Controls

| Button | Action |
|--------|--------|
| **➡️ 7L** or **⬅️ 7L** | Pour from current jug to the 7L jug |
| **➡️ 5L** or **⬅️ 5L** | Pour from current jug to the 5L jug |
| **🍼 FILL 12L** | Reset - fills 12L and empties others |

## 🧩 Puzzle Logic

This is a classic water jug puzzle. The challenge is to measure exactly 1 liter using only pouring operations (no markings except full capacity). Each pour either:
- Empties the source jug completely, OR
- Fills the destination jug completely, OR
- Does both if the source has exactly the remaining space
  
## 🏆 Winning Condition

The game celebrates when you achieve exactly 1 liter in any jug with:
- Victory message animation
- Special congratulatory text
- Visual celebration effect

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **CSS Transitions** - Smooth liquid level animations
- **Event Delegation** - Efficient button handling
- **Responsive Design** - Flexbox and media queries
- **State Management** - Simple array-based jug state

## 📱 Browser Support

Works on all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome for Android)
