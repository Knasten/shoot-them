# Responsivness

![picture of responsivenss](./assets/readme-img/response.jpg)

# Shoot Them!

<a href="https://knasten.github.io/shoot-them/" target="_blank" rel="noopener">Link To Website</a>

# Content

1. [Presentation](#Presentation--top)
2. [User Experience (UX)](#user-experience-ux--top)
3. [Flowchart](#flowchart--top)
4. [Wireframes](#Wireframes--top)
5. [User Stories](#User-Stories--top)
6. [Colors](#Colors--top)
7. [Features](#Features--top)
8. [Testing](#Testing--top)
9. [Bugs](#Bugs--top)
10. [Validation](#Validation--top)
11. [Tools](#Tools--top)
12. [Deployment](#Deployment--top)
13. [Credits](#Credits--top)
14. [Update 1.1](#update-11--top)

# Presentation | [top](#Responsivness)

* Shooter game in which you are supposed to hit the targets as they appear. You got 60 seconds to rack up as many points as possible.
* My main purpose of this site was to create an easy yet viable way to train your aim and muscle memory.
  - Aswell as make it possible for more people to train their aim no matter what equipment they are presented with.
* Made by me as part of an education to become an full-stacked-developer.
  ![picture of full-page](./assets/readme-img/full-page.jpg)
* Design wise my goal has been to create something that pleases the eyes and works well for the user.


# User-Experience-(UX) | [top](#Responsivness)
As for user experience I went for a simple look.  
A header, 2 buttons, a gamearea, score and timer. All the components used in this site to make it better and more comfortable for you the user.  
As mentioned above you will find an game area with timer and score. The timer tells you how many seconds there is left on the round. Score tells the score...
In this game area you will also see alot of target become visible as you hunt them down for glory.
As soon as game is started an alert will pop up explaining the rules while pausing the game until the user decides to continue.  
When a game ends an alert box will appear telling you how good score you got and how long you played for.

# Flowchart | [top](#Responsivness)
- It starts with the page being loaded and calling for the targets to be created based on screen width.
- As for the other you will be able to see what my plan started with below.
- [flowchart](./assets/readme-img/flowchart.png)
- Besides what can be seen above I have implemented some helper functions for changing buttons and resetting after games.

# Wireframes | [top](#Responsivness)
- Wireframes was made prior to updating the site.
- I wanted to use a wireframe because this makes it easier to envision the site and how to make it a reality.
- It was made using [Uizard](https://uizard.io/)
    ![Wireframe](./assets/readme-img/Wireframe.png)

# User-Stories | [top](#Responsivness)

| **As a user I would like to**                      | **So that I can**                             |
| -------------------------------------------------- | --------------------------------------------- |
| Be able to track my score                          | measure if I am getting any better            |
| Be able to track how much time there is left       | focus on just hitting the targets             |
| Get feedback on what is happening                  | know when there is actions being taken        |

| **As a site owner I would like to**                | **So that I can**                             |
| -------------------------------------------------- | --------------------------------------------- |
| entertain my visitors                              | continue getting support for any new projects |


# Colors | [top](#Responsivness)
- For header I choose to go with a dark purple color, I wanted a dark color to make it stick out.
- For game background I went with the classic black. This makes the targets appear much brighter and therefore easier to spot.
- The targets are red and I choose this color because it will really stand out against the black.
- If the stop button is active it displays with a bright red color representing danger/warning
- If the start button is active it displays with a light-purple color to show it is active. Matching the header.
- If the stop/start button is inactive it displays with a gray color to show that it is inactive.


# Features | [top](#Responsivness)

* Header
    * Main purpose for the header is to introduce the user to the site.
    * Has a purple backgound color which I think goes along very well with the theme.
![picture of header](./assets/readme-img/header.jpg)

* Controls
    * Start button, linked to start game function and is disabled upon game start.
    * Stop button, linked to stop game function and is enabled upon game start.
     - If game hasn't been stopped before 60 seconds has passed, the game calls the stop function by itself.
     ![picture of button](./assets/readme-img/controls.jpg)
    * Score
        * In the middle top of the gamewindow you can find your score. This increases each time you successfully hits a target.
        * For each score you get, targets visible time decreases with 10ms
* Game-Window
    * It is in this window the game will be played, all targets appear within this window.
    * Targets
        * Theese are created upon loading the window.
          - Depending on screen-size different amount of targets appear.
![picture of game-window](./assets/readme-img/game-window.jpg)
* Text
    * Just below game window you can find a small box of text explaining the game rules. (This has been changed to alertbox)
![picture of text box below game-window](./assets/readme-img/text-below.jpg)
* Footer
    * Here you can find a link to my Github profile page. Opens in a new tab for better user experience.
    * You can also find information text and as written in footer the game will be improved later.
![picture of the footer](./assets/readme-img/footer.jpg)

# Testing | [top](#Responsivness)

* Tested this site using responsiveness tools.
* Tested to work on phones, tablets and PC's
* Tested on phone (OnePlus 7 Pro) everything worked and looked neat.
* Page was tested in several different browsers including chrome, firefox and Microsoft Edge.
* I have manually tested that.. 
    * you can only start one game at a time
    * if a game has ended you are able to start a new one.
    * number of targets should always coincide with actual targets on screen.
    * targets do not appear outside of gamewindow
    * when target is hit score increases
    * timer is working and counting down
    * when timer reaches 0 game ends.
    * Upon starting game start button is disabled and stop button enabled
    * Upon ending game start button is enabled and stop button disabled

# Bugs | [top](#Responsivness)
* Upon deploying the website I noticed that script and stylesheet was not being loaded as intended. I soon realised it had to do with my pathways not being correct. After adding "./" to all pathways it is working.
* Any bug reports can be sent to hampusjojo@gmail.com for review.

# Validation | [top](#Responsivness)

* HTML
    * No Faults when runnning it through the WSC3 Validator.<br>
     ![picture of WSC3 Validation of the HTML](./assets/readme-img/html-vali.jpg)
* CSS
    * No Faults when runnning it through the Jigsaw Validator.<br>
     ![picture of Jigsaw Validation of the CSS](./assets/readme-img/css-vali.jpg)
* JavaScript
    * One error found which exist cause I call the function from within the HTML.<br>
     ![picture of javascript validation](./assets/readme-img/js-vali.jpg)

# Tools | [top](#Responsivness)

* Gitpod was used during the process of making this website.
    * HTML5 was used for marking up the website.
    * CSS3 was used for styling the website.
    * JavaScript was used for the logic of my website.
* I used [GitHub](https://github.com/) to deploy my website.
* I used [FontAwesome Ver.5.15.4](https://fontawesome.com/) for the github icon at the bottom of the page and the icon next to page name. (favicon)
* I used [Stackoverflow](https://stackoverflow.com/) to read and learn more about java while writing this.
* I also used [W3Schools](https://www.w3schools.com/) to read up about intervals and timeouts.
* I used [Lighthouse](https://developers.google.com/web/tools/lighthouse) to evaluate my website. <br>
![picture of lighthouse report](./assets/readme-img/lighthouse.jpg)

# Deployment | [top](#Responsivness)

* To deploy this project follow steps below:
  -  Go to [repository](https://github.com/Knasten/shoot-them)
  -  Click the green gitpod button
  -  Make any desired changes too code or html
  -  Save your repository
  -  Locate your repository
  -  Enter settings for your repository
  -  Click pages tab on the navbar to the left
  -  Select your branch from the drop-down menu
  -  Deploy.
  -  Deployed! You should now have a clickable link which should look like this "https://GITHUB_USERNAME.github.io/REPOSITORY_NAME/"

# Credits | [top](#Responsivness)

* For the "function scoreIncrement()" I borrowed code from our love maths project we did in school just prior to starting this portfolio project. (Credit goes to CodeInstitute)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
    
    
# Update-1.1 | [top](#Responsivness)

## New implementations
 - Added function to create targets based on screen size
 - Better sized targets
 - Phones have smaller sized targets, this to fit some more targets and make it more scaleable for smaller screens
 - Buttons have feedback for user and shuts off depending on if game is started or not
 - Added timer

## Future Implemetations
 - Add possibility for the user to select number of targets
 - Add possibility to select how long targets appear
 - Scoreboard to keep track of who has gotten the best score.
 - Regional scoreboard to keep track of score in your closer proximity

## New UI
 - Buttons has gotten a touch up. Added JS to disable and change classes depending on game state.
 - New timer can be seen under the score to better keep track of progress.
 - Besides this it is a general touch up of how it used to look.
 - Most of text has been put to alert boxes to clean up the looks of the site.

### Picture new site looks
 - ![Picture new UI](./assets/readme-img/newpage.jpg)

 #### Picture new footer
 - ![Picture new footer](./assets/readme-img/newfooter.png)

## Testing
 - Buttons has been manually tested both in-game and out of game.
 - Game has been test run and after finished round. Player gets the wanted feedback.

## Bugfixes / User Concern Fixes [top](#Responsivness)
 - Before players could start several games at once, this has been resolved.
 - No feedback for user, solved by adding timer and alerts after each game.
 - Game ended too early, increased round time by 300ms
 - stopGame(); sometimes ran it sequence twice, now controlled by an if statement.
 - Container not fiting on some sizes, solved by adding more variants of number of targets.