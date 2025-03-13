# MAD-Homework-03
Mobile App Development Homework 3

## Requirements:
1. Create a Flutter Project:
- Start a new Flutter project using your preferred development environment
3. Design the User Interface:
- Design a user interface that includes a grid of face-down cards (e.g., 4x4 or 6x6 grid).
- Each card should initially display a back design (e.g., a common pattern or image).
- You can use GridView or other Flutter widgets to create the card grid.
3. Implement State Management:
- Use a state management approach (e.g., Provider) to manage the game state.
- Define a data model for the cards, including properties for their front and back designs, and their current state (face-up or face-down).
4. Card Flipping Animation:
- Implement an animation that flips the cards from face-down to face-up and vice versa when tapped.
- Utilize animation widgets like AnimatedBuilder or AnimatedContainer to create the flip animation effect.
5. Game Logic:
- Implement the game logic to track which cards are currently face-up and face-down.
- When a player taps two face-down cards, check if they match. If they do, keep them faceup; otherwise, flip them face-down again.

### Extra Task for graduate students : Timer and Scoring System

## Requirements:
Add a timer that starts when the game begins.
- Display the timer on the screen, counting the time taken to match all pairs.
- Implement a basic scoring system where players earn points for each matched pair.
- Deduct points if the player mismatches cards, or alternatively, provide bonus points for matching pairs quickly.
