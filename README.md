# Circus  Game

Circus Catcher Game is a single-player 2D game where you control a clown who tries to catch falling shapes. Your goal is to collect three consecutive shapes of the same color to make them vanish and increase your score. The game also features golden plates that double your points when collected. Be careful of bombs falling too; they can reduce your score!

## Game Features

- Dynamic loading of shapes: The game supports multiple shapes, including plates and small Batman logos, loaded dynamically from a specific folder. You can easily add more shapes as needed.
- Variety of falling objects: Besides plates, the game includes bombs and Batman logos as falling objects.
- Score system: Collect three consecutive shapes of the same color to earn points. Golden plates double your points.
- Difficulty levels: The game offers three levels of difficulty, increasing the number of bombs and the speed of falling plates as you progress.

## Design Patterns Used

Circus Catcher Game incorporates various design patterns to maintain a clean and extensible codebase:

- **Facade:** Provides a unified interface to the game's subsystems, simplifying interactions with complex systems.
- **Factory:** Responsible for creating different types of shapes and objects dynamically.
- **Strategy:** Allows you to change the game's behavior by selecting different difficulty levels.
- **Flyweight:** Optimizes memory usage by sharing common data between similar objects.
- **Singleton:** Ensures that certain classes have only one instance throughout the game's execution.

Certainly, you can add instructions on how users can download the repository locally. Here's an updated installation section in your README that includes instructions on downloading the repository:

## Installation

Follow these steps to download the project and run the game on your local machine:

1. **Clone the Repository:**

   To download the project files to your local machine, open your terminal or command prompt and use the following command to clone the repository:

   ```bash
   git clone https://github.com/JumanaWanass/Circus-Game.git
   ```

   This will create a local copy of the entire project on your computer.

2. **Check Your Java Installation:**

   Ensure you have Java installed on your system. You can check your Java version by running the following command in your terminal or command prompt:

   ```bash
   java -version
   ```

   If Java is not installed, you can download and install it from the official website: [Download Java](https://www.oracle.com/java/technologies/javase-downloads.html).

3. **Navigate to the Project's Directory:**

   Change your working directory to the project folder:

   ```bash
   cd Circus-Game
   ```

4. **Navigate to the `dist` Directory:**

   Once you're inside the project directory, navigate to the `dist` directory where you'll find the `CircusGame.jar` file:

   ```bash
   cd dist
   ```

5. **Run the Game:**

   To start the game, execute the following command:

   ```bash
   java -jar CircusGame.jar
   ```

   The game should launch, allowing you to use the keyboard to control the clown and catch falling shapes.

Enjoy playing the game, and feel free to customize and enhance it as you see fit!
