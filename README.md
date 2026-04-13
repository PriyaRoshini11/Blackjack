# Blackjack game

A simple command-line Blackjack game built using Python. This project simulates a Blackjack game where you play against the computer (dealer).

🎮 Game Overview

This is a text-based implementation of the classic Blackjack card game. The player competes against a computer dealer following standard Blackjack-inspired rules.

🧾 House Rules
The deck is unlimited in size
There are no jokers
Cards:
Jack, Queen, King → 10
Ace → 11 or 1

Card deck used:

cards = [11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]
Cards are drawn randomly with equal probability
Cards are not removed after drawing
The computer acts as the dealer

⚙️ Features
Random card dealing 🎲
Automatic score calculation
Blackjack detection (Ace + 10)
Ace value adjustment (11 → 1 when needed)
Dealer logic (draws until score ≥ 17)
Win/Lose/Draw comparison
Replay option

🧠 Game Logic
1. Card Dealing
Both player and computer receive 2 cards initially
2. Score Calculation
Blackjack (Ace + 10) → Score = 0
If score > 21 and contains Ace → Ace becomes 1
3. Player Turn
Choose:
'y' → draw another card
'n' → pass
4. Dealer Turn
Dealer draws cards until score is at least 17
5. Result Comparison
Highest score wins (without exceeding 21)
Blackjack beats all

🏆 Winning Rules
Blackjack → Instant win
Score > 21 → Lose
Dealer > 21 → Win
Equal scores → Draw

💻 Sample Gameplay
Your cards: [10, 7], current score: 17
Computer's first card: 9

Type 'y' to get another card, type 'n' to pass: n

Your final hand: [10, 7], final score: 17
Computer's final hand: [9, 8], final score: 17

Draw 🙃

Inspired by:
https://games.washingtonpost.com/games/blackjack
