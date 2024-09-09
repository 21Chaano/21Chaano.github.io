---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Automatic Strategy Inference for Games"
date: 2024
published: false
labels:
  - Jupyter
  - Python
  - GitHub
summary: "Automatic Strategy Inference for Games is a Vertically Integrated Project (VIP) led by professor Naranya Santhanam at UH Manoa that I collaborated on. The goal is to use reinforcement learning to teach a computer to play Huligutta. [VIP project page](https://manoa.hawaii.edu/uh-vip/project/asig/)"
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

## Intro and Rules

Huligutta is based on a board game from India of the same name. The objective is to corner all the tigers as the goat player or capture enough of the goats as the tiger player. Players take turns making moves. The types of moves depend on the phase of the game. In the beginning/placement phase, the goat player will place goats on the board. Goat player places a goat, tiger player moves one of their 3 tigers. Alternate and repeat until 15 goats have been placed. Once all 15 goats are placed, then begins the movement phase. In this phase, the goat player will move one of their goats to adjacent places on the board with the intent of cornering the tigers. Throughout the game, the tiger player is trying to capture goats. Tigers can only move to adjacent spaces, just like goats, but also has the ability to jump across a goat in the adjacent space if the next space in line with the tiger and goat is vacant.

## Project Details

The objective of this project is to use machine learning and reinforcement learning to teach a computer how to play Huligutta. The computer takes the role of the goat player. We implemented a value iteration that allows the goat player to look-ahead two moves. This look-ahead function takes in possible game states that would occur if a move was made, then return the move that would be the "best" move based on a value function finds the "value" of a possible move, and then returns the move that has the highest probability of winning. With this two step look-ahead gives the computer/goat player a roughly 95% win rate. The tiger player follows a "greedy algorithm". This means that the tigers will make a random move until they see that one of the tigers could capture a goat. If a capture is possible in that move, then the tiger will make that move.

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
