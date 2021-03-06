# jQuery based Crystal Collector Game

### Overview

A fun and interactive game for web browsers. The app dynamically updates HTML pages with the jQuery library.

### Folder Structure

1. Create a new GitHub repo for the app, and clone it to the computer.
2. Inside the app folder, create an `index.html` file.
3. Still inside theapp folder directory, make a folder called `assets`.
   * Inside the `assets` directory, make three additional folders: `javascript`, `css` and `images`.
     * In the `javascript` folder, make a file called `game.js`.
     * In the `css` folder, make a file called `style.css`.
     * In the `css` folder, make a file called `reset.css`. Paste into it the code found from the Meyerweb Reset.
     * In the images folder, save any of the images you plan on using.
4. Set up the repository to deploy to Github Pages.
5. Push the above changes to GitHub. 

### CrystalsCollector Game

![Crystal Collector](Images/1-CrystalCollector.jpg)

1. [Watch the demo](homework_demos/crystalsCollector_demo.mp4).
2. The player will have to guess the answer, just like in Word Guess. The player will guess with numbers instead of letters. 
3. Here's how the app works:
   * There will be four crystals displayed as buttons on the page.
   * The player will be shown a random number at the start of the game.
   * When the player clicks on a crystal, it will add a specific amount of points to the player's total score. 
     * the game will hide this amount until the player clicks a crystal.
     * When they do click one, update the player's score counter.
   * The player wins if their total score matches the random number from the beginning of the game.
   * The player loses if their score goes above the random number.
   * The game restarts whenever the player wins or loses.
     * When the game begins again, the player should see a new random number. Also, all the crystals will have four new hidden values. Of course, the user's score (and score counter) will reset to zero.
   * The app should show the number of games the player wins and loses. To that end, do not refresh the page as a means to restart the game.

##### Option 1 Game design notes

* The random number shown at the start of the game should be between 19 - 120.

<<<<<<< HEAD
* Each crystal should have a random hidden value between 1 - 12.
=======
* Each crystal should have a random hidden value between 1 - 12.
