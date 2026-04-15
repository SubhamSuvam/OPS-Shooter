OPS Shooter by Subham

#Overview

OPS Shooter is a browser-based top-down shooter game where players control a character, defeat enemies, and earn points. The game includes user authentication, an in-game shop, a leaderboard system, and mobile touch controls.

#Features

· User authentication system with local storage persistence
· Real-time shooting mechanics with auto-aim functionality
· Enemy spawning that scales with player score
· Health system with purchtable upgrades
· Points system for defeating enemies
· High score leaderboard
· Mobile-friendly touch controls
· Background music and sound effects
· Responsive canvas that adapts to screen size

#How to Play

1. Enter your username, password, and age to create an account or log in
2. Click the PLAY button or select Lets Play from the home screen
3. Use arrow keys or on-screen joystick to move your character
4. Press spacebar or tap the FIRE button to shoot
5. The game auto-aims at the nearest enemy
6. Defeat enemies to earn points
7. Avoid enemy contact or you will lose health
8. Game ends when health reaches zero

#Controls

a. Desktop:

· Arrow keys for movement
· Spacebar for shooting

b. Mobile:

· On-screen directional pad for movement
· Large FIRE button for shooting

#Game Elements

a. Player Character: A hero unit that follows mouse/touch movement input and automatically rotates toward the nearest enemy.

b. Enemies: Red units that spawn from screen edges and move toward the player. Spawn rate increases as score gets higher.

c. Bullets: Yellow projectiles fired from the player toward the nearest enemy.

d. Health System: Each player starts with a base number of hearts. Losing all hearts ends the game.

e. Points: Earned by defeating enemies. Two points per kill.

#Shop System

The ARMORY section allows players to purchase extra health using points earned in-game. Each upgrade costs 499 points and increases maximum health by one. Maximum health cap is nine hearts.

#Leaderboard

The leaderboard displays all registered users sorted by their highest score achieved in a single game.

#Profile Section

View your account details including username, age, current points balance, and total points earned.

#Required Assets

a. The game expects the following audio files to function properly:

· fire.mp3 - Shooting sound effect
· damage.wav - Hit sound when player takes damage
· die.mp3 - Game over sound
· start.wav - Game start sound
· lobby.mp3 - Background music for menus
· music.mp3 - Background music during gameplay

b. The game expects the following image files:

· hero.png - Player character sprite
· enemy.png - Enemy unit sprite
· road.jpg - Game canvas background image

!If these files are missing, the game will still function but visual and audio elements will use fallback graphics and silent fallbacks.

#Technical Details

Built with vanilla HTML5, CSS3, and JavaScript. Uses Canvas API for rendering and LocalStorage for data persistence. No external dependencies required.

#Browser Compatibility

Works on all modern browsers that support HTML5 Canvas and ES6 JavaScript. Designed for both desktop and mobile devices with responsive layout.

#Data Storage

User data is stored locally in the browser using localStorage. Data persists between sessions and includes:

· User credentials
· Points balance
· Maximum health upgrades purchased
· High score

#Known Limitations

Audio playback may be blocked by browser autoplay policies. User interaction is required before audio will play. The game will continue to function without audio.

#Development

Created by Subham (me) as a demonstration of HTML5 game development capabilities including canvas rendering, real-time game loops, collision detection, and local data persistence.

#File Structure

Single HTML file containing all styles, markup, and JavaScript. External assets required are limited to the image and audio files listed above. All files should be placed in the same directory for proper loading.