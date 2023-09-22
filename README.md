## Project:

* Hangman

---

### Team Members

* Sushil Kandel, skandel@myune.edu.au

---

### Description and Demo Video

> The hangman game is a word-guessing simple game typically placed by two or more players. One player thinks of word and keep it secret, while the other player try to guess the word one letter at a time. The word is represented by a series of blank spaces one for each letter in the word. In this game, player need to guess the word and try to find out that word. The game has a used key letters, series of blank spaces, play and stop music option, and a image of hangman with available lives.

### [Demo Video](https://cdnapisec.kaltura.com/p/424421/sp/42442100/embedIframeJs/uiconf_id/7033932/partner_id/424421?iframeembed=true&playerId=kaltura_player&entry_id=1_f6dctp3c&flashvars%5BstreamerType%5D=auto)

### Some difficulties and their solutions:

> #### Highscore API- delay
>
> I was intending to implement the Highscore API and tried to utilize its database but being a solo member of project, it was very difficult for me to complete this feature. However, by the time I had everything finished and was ready to focus on the final documentation, demo video, refining code etc. the API was still in development so I decided to leave it out of our feature to keep the rest of my progress on track.

### Links to Wiki Pages

> [Features Page](https://gitlab.une.edu.au/cosc220-2023/classproject/-/issues/108 "Solo Project - Hangman")
>
> [Group Page](https://gitlab.une.edu.au/cosc220-2023/classproject/-/wikis/Group%2015)

### Group Branch Name:

> [Solo_WordGame](https://gitlab.une.edu.au/cosc220-2023/classproject/-/tree/Solo_WordGame?ref_type=heads)

### Git Issue Numbers:

 1. [Group 15](https://gitlab.une.edu.au/cosc220-2023/classproject/-/wikis/Group%2015)
 2. [Hangman Feature](https://gitlab.une.edu.au/cosc220-2023/classproject/-/issues/108 "Solo Project - Hangman")
 3. [Developing Game Enviroment for Client and Server](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/109 "Developing Game Enviroment for Client and Server")
 4. [Developing GUI for Word Guess](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/119 "Developing GUI for Word Guess")
 5. [Increment in Score for current guessing](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/113 "Increment in Score for current guessing")
 6. [Working with lives of the player](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/112 "Working with lives of the player")
 7. [Sending score to High Score using High Score API](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/114 "Sending score to High Score using High Score API")
 8. [Adding functionality for word guessing](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/111 "Adding functionality for word guessing")
 9. [Play and Stop Music](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/214 "Play and Stop Music")
10. [Key Not Pressed](https://gitlab.une.edu.au/cosc220-2023/classproject/-/work_items/215 "Key not Pressed")

### List of Main Classes:

#### Clients Side:

> * **HangmanClient**
> * **HangmanPanel**
> * **ImagePanel**
> * **KeywordPanel**
> * **RiddlePanel**

#### Common:

> * **Tools**

#### Server Side:

> * **HangmanGameServer**
> * **HangmanGameAchievement**
> * **HangmanGame**

### List of Test Classes

> **HangmanPanel Test:**
>
> * **disableInputGameLostTest() -** function to check whether the input is disabled or not when game is lost
> * **disableInputGameWinTest() -** function to check whether the input is disabled or not when game is win

> **KeywordPanel Test:**
>
> * **availableLetterTest() -** function to set the letterUsed = true when letter is used
> * **resetLetterTest() -** function to reset all the unused letter after new game

### Team Member's Personal Contributions:

#### Sushil Kandel in Snake Game (G15 Main Issue)

> * Desigining and Implementing the server and client
> * Setting up Snake Server
> * Setting up Snake GUI
> * Intergrating server and client in Minigames
> * Desigining Snake game Main Menu panel, Help panel, Score panel

#### Sushil Kandel in Hangman Game (G15 Solo Main Issue)

> * Setting up server for Hangman
> * Integrating Server into Minigames
> * Designing Hangman Game menu panel with Score panel, Help Panel
> * Designing Hangman Game panel
> * Designing Keyword Panel
> * Designing Riddle Panel for blank spaces
> * Designing Image panel for background and hangman
> * Working in functionality of key pressed in Keyword Panel and Server
> * Working in functionality of blank spaces in Riddle Panel
> * Integrating all the panels in Hangman
> * Adding some functionality for player score
> * Adding music functionality to play and stop music
> * Controlling the lives of player
> * Working with lives of player when player guessed wrong word
> * Handling the server and client
> * Fixed Bugs and Refining code
> * **HighScore Section (Eliminate this Features because of Delay)**
> * Created and Worked on Issues in Wiki Page for documentation
> * Record Demo Video
> * Class Diagram
> * Unit Testing
