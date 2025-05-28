# 🎮 Team Role Assignment

A simple web app for quickly assigning players to teams and roles (DPS, Support, Tank) — perfect for party games, esports, or Overwatch-style team setups!

## Features
Add up to 18 players (3 teams × 6 players)

Automatically assign players to teams and roles based on party size

Supports 1–3 teams with balanced role distribution

Easy player management (add, remove, clear all)

Responsive, user-friendly interface

## Getting Started
### 1. Clone or Download

'''
git clone https://github.com/pieterhk-444/RivalsRandom
cd team-role-assignment
'''

### 2. Open in Browser
Just open index.html in your web browser.
No build tools or dependencies required!

### 3. Usage
Enter player names and click Add Player.
When ready, click Assign Teams & Roles.
Teams and roles will be displayed.
Use Clear All to reset.

## How It Works
Players are shuffled and split into 1–3 teams.

Each team gets a balanced mix of DPS, Support, and Tank roles.

Role distribution scales with team size (see code for details).

## File Structure
.
├── index.html
├── resources/
│   └── index.css

- index.html: Main web app (HTML + JS)

- resources/index.css: Stylesheet

## Customization
Change team or role names in the HTML/JS as needed.

Adjust max players, team sizes, or role distribution logic in the script.

## Credits
Built by Pieter Kruger

Inspired by team randomizers 
