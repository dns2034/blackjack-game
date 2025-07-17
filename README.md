# Blackjack Game

A simple command-line implementation of the classic Blackjack (21) card game in Python.

## Table of Contents
- [How to Play](#how-to-play)
- [Card Values](#card-values)
- [Requirements](#requirements)
- [Game Rules](#game-rules)
- [Example Output](#example-output)

## How to Play

1. The game starts by dealing 2 cards each to the player and the dealer
2. Player goes first and can choose to:
   - "play" to request another card (hit)
   - "stop" to stand with current cards
3. If the player's score exceeds 21, they bust and lose immediately
4. The dealer then draws cards until their score is at least 17
5. Final scores are compared:
   - If dealer busts (score > 21), player wins
   - Higher score wins (without exceeding 21)
   - Equal scores result in a tie

## Card Values
- Number cards (2-10): Face value
- Face cards (Jack, Queen, King): 10 points
- Ace: 11 points

## Requirements
- Python 3.x

Game Rules
- Standard Blackjack rules apply
- Dealer must hit on soft 17
- No splitting, doubling down, or insurance
- Single deck used (shuffled each game)

## Example Output
Cards Player has: [('7', 'Hearts'), ('King', 'Diamonds')]
Score of The Player: 17

What do you want? ["play" to request another card, "stop" to stop]: play

Cards Player has: [('7', 'Hearts'), ('King', 'Diamonds'), ('5', 'Clubs')]
Score of The Player: 22

Cards Dealer has: [('9', 'Spades'), ('Jack', 'Hearts')]
Score of The Dealer: 19
Dealer wins (Player Loss Because Player Score is exceeding 21)
