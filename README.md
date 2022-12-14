## About my project
## Code Institute Portfolio Project 2 covering Javascript, HTML and CSS 

<h1 align="center">Sunhill Adventures Website</h1>

Welcome to my repository for PP2.

This project is deployed at: https://ian-ibcirl.github.io/CI-PP2-SunhillAdventures/ 

The last update to this file was: **November 14th, 2022**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

------


## Index
* [User Experience (UX)](#user-experience-ux) 
* [Features](#features)
* [Design](#design)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Gitpod Reminders](#gitpod-reminders)
* [Credits](#credits)
* [Release History ](#release-history) 

## Project Goals

My goals have been to:
1) develop a website which 
2) enables me to demonstrate newly learned javascript skills, 
3) courtesy of the Code Institute (codeinstitute.com). 
4) Following initial review of recommended options, 
5) I began researching financial charting of securities, and 
6) simple text based adventure gaming web development. 
7) I found https://www.youtube.com/watch?v=R1S_NhKkvGA which 
8) looks like the right way to go,
9) so I have developed my game on that basis, and extended the features.
10) utilising Javascript, HTML and CSS, with 
11) Bootstrap's powerful, feature-packed frontend toolkit.

12) I have added a keyboard fight sequence at the end of the game (with buttons for mobile/touch)
12a) For resubmission i added the option to go straight to the fight to shorten the assessment/game play

13) so i created the player (possibly later adding the option to name the player) and enemy (gaoler)
14) I added attacking keys ASD with event listeners and button onclick handlers
15) I added health bar
16) I added game completion notification (win/lose) followed by restart

17) I updated some of the game messages to make the results more obvious and document an issue with the hammer logic.

------

## User Experience (UX)

-   ### User stories

    -   #### A. First Time Visitor Goals

            1. As a First Time Visitor, I want to begin playing the game.
            2. As a First Time Visitor, I want to understand what i can see as a player
            3. As a First Time Visitor, I want to know what my game options are.
            4. As a First Time Visitor, I want to find an entertaining story.
            5. As a First Time Visitor, I want to win the game.

    -   #### B. Returning Visitor Goals

            1. As a Returning Visitor, I want to begin playing the game because i enjoyed it before.
            2. As a Returning Visitor, I want to see what else i can see as a player
            3. As a Returning Visitor, I want to recall what my game options are.
            4. As a Returning Visitor, I want to revist an entertaining story and try other options.
            5. As a Returning Visitor, I want to win the game and improve my result.

## Features
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 


### Existing Features

-   __F01 Title and menu__
    - The top of the screen shows the name of the game with menu options to restart and find out about the game.

-   __F02 Scene description__
    - The bottom half of the screen shows the what the player sees and their options.

-   __F03 Player Action buttons/choices__
    - The lower portion of the screen shows buttons that can be clicked to make choices that advance the game.

-   __F04 Player Action results__
    - The subsequent screens and alerts tell the player the result of their actions, and any incorrect actions.


### Future Features 
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

- __Timeline__
    - A 'Timeline' page could be added to provide more historical context for participants who would like to know more about the origins of the game, its characters and its reception in the community.

- __Sprites__
    - Sprites (graphical player and enemy representations, beyond the health bars shown) could be added to provide more visual context for participants who would like to experience more about the context of the game and its characters.

- __Refactoring__
    -   I could probably find a way to refactor the code to use more functions and less repeated code, but don't want to risk breaking logic at this stage.

## Design
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

-   ### Process Flow
    -   I have developed the game with a process flow as the basis for the game logic and supporting JavaScript.
    -   I do also want to refine the keyboard handling and visualisation of player and gaoler health for the battle to escape.
    -   I could probably find a way to refactor the code to use more functions and less repeated code.
    
    A diagram of the process flow is here.
    <img src="./assets/docs/processflow.png">  
    

-   ### Responsiveness
    -   I have developed the game to be responsive on mobile devices and browsers.
    -   As the manual testing section will show, i have successfully deployed responsive initial and subsequent stages of the game.

    Screenshots of the responsiveness are here.
    <img src="./assets/docs/responsive.png">  
    
    and and earlier version here.
    
    <img src="./assets/docs/responsivenesstestingscreen2.png">  
    
    
-   ### Imagery
    -   I am working to find images to choose that will be eye-catching, informative and bright.  The colours in the images will be chosen to help convey a sense of adventure and excitement. The images will show Adventure participants to align with the main story line of the adventure. They will be chosen to ensure the site is clear and easy to use.

    - Colors from http://www.paletton.com/ 
    - main image from https://www.pexels.com/@jwfotografia/ 
    - and earlier images from https://www.pexels.com/
    - compressed with https://tinyjpg.com/ 
    - JPG to avif from https://convertio.co/jpg-avif/ 

-   ### Colour Scheme
    -  A palette has been chosen to convey a sense of adventure. 
    
    An image of the potential palette is here.
    <img src="./assets/docs/NZ+Color+Palettes-01.jpg"> 
    

-   ### Typography
    -   Google Fonts are imported for potential use from Oswald fonts by assets\css\style.css. 

-   ### Wireframes

    Home Page Wireframe 1
    <img src="./assets/docs/wireframe-homepage.png">
    

## Technologies Used
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 
* [see also Credits ](#credits)


### Languages Used

-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

-   [Balsamiq:](https://balsamiq.com/) for wireframes during the design process.
-   [Git:](https://git-scm.com/) was used for version control in the Gitpod environment to commit to Git, with comments, and Push to GitHub and publish to the public cloud.
-   [GitHub:](https://github.com/) is used as the repository for the source code, and GitPages for hosting.
-   [Chrome DevTools](https://developer.chrome.com/docs/devtools/) for checking and testing the site.
-   [Google Fonts:](https://fonts.google.com/) for 'Lato' and 'Oswald' fonts.
-   [Convertio JPG to avif:](https://convertio.co/jpg-avif/) to convert PNG and JPG to avif images.
-   [WAVE evaluation tool](https://chrome.google.com/webstore/detail/wave-evaluation-tool/) to test accessibility and other errors - very useful and easy to use.
-   [WAVE results for site](https://wave.webaim.org/report#/https://ian-ibcirl.github.io/CI-PP2-SunhillAdventures/)
-   [picture for button backgrounds](https://stackoverflow.com/questions/9415851/how-to-change-the-background-image-of-a-button-using-javascript)
-   [JSHint](https://jshint.com/) was used to check for Javascript errors and recommendations
-   [Squoosh](https://squoosh.app/editor) was a better AVIF converter and preserved colors on IOS/Safari 16

## Testing 
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

-   ### Responsiveness
    -   I have developed the game to be responsive on mobile devices and browsers.
    -   Updating responsiveness score with AVIF rather than PNG results in images not loading on older Apple iOS - does work on iOS 16 now.
    -   As the manual testing section will show, i have successfully deployed responsive initial and subsequent stages of the game.


-   ### CI feedback
    Following CI feedback, I have addressed the following issues:
    -   Criteria 1.1 - I have added navigation to the about page and the 404 page, fixing other link issues there. 
        These were not previously finally tested, as identified as nice to haves in meetups.
    -   Criteria 1.2 - I have eliminated contrast ratio issues by reverting to black on white or vice versa, 
        to eliminate any accessibility risk. I changed the player/gaoler health text background to address this risk while using some colour.
    -   Criteria 1.4 - I have eliminated image backgrounds from buttons and changed the background and 
        put black text with white background where previously text background was transparent, and an accessibility risk.
    -   Criteria 1.5 - I have eliminated multiple background images and settled on a single image that 
        captures the spirit of the game, relying on text descriptions to convey the scene.
    -   Criteria 1.8 - I have addressed readme image issues for file type case, so workflow is more visible, without compressing sections, 
        and added a direct link to the fight scene which was previously there, but undiscovered by superficial game play, and readme workflow filetype issues, 
        if the player did not discover the door to the fight scene, which i have also highlighted in the about.
    -   Criteria 1.9 - as above, i have ensured solid white or black backgrounds with the 
        black or white text respectively, to ensure text does not get lost in images and result in accessibility risk.
    -   Criteria 2.2 - I have revisited nice to have about and 404 pages to ensure they also meet HTML validation, 
        and rechecked the main index.html
    -   Criteria 2.8 - I have revisited the nice to have about and 404 pages to ensure all links work as well as the 
        header link which previously worked.
    -   Criteria 3.4 - I have fixed broken links on 404 page.
    -   Criteria 4.7 - I have moved the javascript load to the end of the file in the correct location just above the closing body tag
    -   Criteria 4.9 - I have changed all file types to lower case. These were generated on a PC so needed manual changing.
    -   Criteria 4.10 - I have moved the javascript to an assets subfolder
    -   Criteria 6.3 - Website is fully functional and player and gaoler health did previously change but 
        had to make fight sequence more obvious to superficial examination.
    -   Criteria 6.4 - resolved about.html javascript issues, and put onclick instructions that don't require javascript.
    -   Criteria 6.5 - resolved directory structure and file locations for javascript
    -   Additional - cleaned up console logging with logic to prevent undefined output. Left some in as useful to show evolution and purpose of code.
        Would love to do more code refactoring.


    Screenshots of the responsiveness are here.
    <img src="./assets/docs/responsive.png">  
      

-   [JSHint](https://jshint.com/) was used to test for Javascript errors and recommendations

### Validator Testing
### WAVE (Web Accessibility Evaluation Tool)
Good results. No errors. Managed to eliminate all alerts and contrast errors.

WAVE Results
<img src="./assets/docs/wave.png">

[WAVE results for site](https://wave.webaim.org/report#/https://ian-ibcirl.github.io/CI-PP2-SunhillAdventures/)


[HTML Validator](https://validator.w3.org/)
Good results all round.

Index HTML Results
<img src="./assets/docs/htmlvalidation.png">
<img src="./assets/docs/abouthtmlvalidation.png">
<img src="./assets/docs/404htmlvalidation.png">


Index CSS Results
<img src="./assets/docs/cssvalidation.png">



[Google Chrome Lighthouse Validator results.](https://github.com/GoogleChrome/lighthouse/blob/HEAD/docs/user-flows.md) 

Lighthouse Results
<img src="./assets/docs/lighthouse.png">

### Browser Compatibility

- Testing has been carried out on the following browsers :
    - Chrome Version 103.0.5060.134 (Official Build) (64-bit)
    - Firefox 102.0 release
    - Edge Version Version 103.0.1264.62 (Official build) (64-bit)
    - Safari on macOS Version 12.1.2 (12607.3.10) and iPhone/iPad IOS 9.3, 10.3.4 and 15.6.
    
## Testing visitor stories
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

- Friends and family were able to access the website and provide valuable user experience feedback for the adventure experience, accessibility/readability and content length.
- The testing table shows test cases, the results and reference to the Feature which the test case proved:

### Test Cases and Results

1. As a First Time Visitor, I want to understand the main purpose of the site and learn more about the game.

| **Feature**                     | **Action**                          | **Expected Result**                                                                     | **Actual Result** |
|---------------------------------|-------------------------------------|-----------------------------------------------------------------------------------------|-------------------|
| Hero Section & call to action| First section displayed on the page | visitor can see immediately and read what type of adventure they can expect from site | PASS              |
| Adventures                         | Check the options for adventure           | Find what choices for adventure are available                                         | PASS              |


1. As a First Time Visitor, I want to begin playing the game.
Result = PASS
2. As a First Time Visitor, I want to understand what i can see as a player
Result = PASS
3. As a First Time Visitor, I want to know what my game options are.
Result = PASS
4. As a First Time Visitor, I want to find an entertaining story.
Result = PASS
5. As a First Time Visitor, I want to win the game.
Result = PASS

1. As a Returning Visitor, I want to begin playing the game because i enjoyed it before.
Result = PASS
2. As a Returning Visitor, I want to see what else i can see as a player
Result = PASS
3. As a Returning Visitor, I want to recall what my game options are.
Result = PASS
4. As a Returning Visitor, I want to revist an entertaining story and try other options.
Result = PASS
5. As a Returning Visitor, I want to win the game and improve my score.
Result = PASS



### Known bugs

- No technical bugs identified, although the logic behind the hammer needs further work, as it's not clear if the desired advantage is being applied.
- Also need to work on the wider logic to stop the hammer scene being replayed and make it more clear, to suggest the hammer was dropped and needs to be picked up again, or some such story flow.
- Intention of defending is for gaoler health to still go down due to exhaustion if not actual attack so added trick shot to defence to support decreased gaoler health.
- Over the course of the project, 
    1) various layout issues with 
        - horizontal scrolling and more
    2)  let textItem = textItems.find(o => o.item === TextItemNumber)
        - took a while to get this array find code to work
        - typo in o.item member name took a while to pin down (looking in the wrong place) 
        - o is a placeholder and => is a function pointer
        - helpful demo here https://stackoverflow.com/questions/12462318/find-a-value-in-an-array-of-objects-in-javascript
    3)  had fun trying to add visuals for buttons and scenes.
        - found helpful code here https://stackoverflow.com/questions/9415851/how-to-change-the-background-image-of-a-button-using-javascript)
    4)  Having trouble getting final update for win/lose display update before
        alert. Tried window.location.reload() before alert. Will keep trying.
    5)  Had to use AVIF image format to get faster Lighthouse performance results. 
        However, initial compression resulted in incorrect colors. 
        So I found - [Squoosh](https://squoosh.app/editor) was a better AVIF converter 
        and preserved colors on IOS/Safari 16, which is needed to see AVIF on Apple 
        phones, laptops and desktops.


## Deployment
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

### How this site was deployed
In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu.
From the source section drop-down menu, select the Master Branch.
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
Any changes pushed to the master branch will take effect on the live project.

The live link can be found here - https://ian-ibcirl.github.io/CI-PP2-SunhillAdventures/

### How to clone the repository
Go to the https://github.com/ian-IBCIRL/CI-PP2-SunhillAdventures repository on GitHub.
Click the "Code" button to the right of the screen, click HTTPs and copy the link there.
Open a GitBash terminal and navigate to the directory where you want to locate the clone.
On the command line, type "git clone" then paste in the copied url and press the Enter key to begin the clone process.

## Credits
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

-   ### Source code

    - Code Institute tutors, mentors and colleagues in Slack channels.
    - Github pages - https://github.com/
    - Bootstrap documentation https://getbootstrap.com/docs/4.6/getting-started/introduction/ 
    - I decided to start using bootstrap for this project but didn't use it much (yet)
    - found a decent random range generator https://www.educative.io/answers/how-to-generate-a-random-number-between-a-range-in-javascript 

-   ### Images

    - Adventure images https://www.pexels.com/ 
    - favicon.ico generation https://favicon.io/favicon-generator/
    - Colors from [Lilybug Design](https://www.lilybugdesign.co.nz/colour-wall)

 
------

## Release History
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

I have continually developed this repository to help give you the best experience. Here is the version history:

**24 August 2022:** Initial Commit.

**30 August 2022:** Added keyboard functionality for fight sequences.

**05 September 2022:** Fixed some relative file paths for background flooring.

**15 September 2022:** updated documentation for process flow.

**20 September 2022:** reviewed media/screen layouts and player grid/keys.

**23 September 2022:** added health display with width of player/gaoler. Improved added menu pages.

**24 September 2022:** added fight state to distinguish need to handle keys and filter keys needed.

**27 September 2022:** significantly updated readme and corrected validator reccomendations.

**8 November 2022:** corrected accessibility colours, spacing and added direct to fight option.

**14 November 2022:** changed some text and flow logic to support hammer and defending mechanics. More work needed.

------

## FAQ 
* [Back to index](#index) 
* [Back to top of README.md](#about-my-project) 

**Why have you developed this ?**

I like gaming and a good interactive story

---

Happy coding!
