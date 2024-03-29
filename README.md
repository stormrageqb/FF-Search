# FF-Search

A simple, mobile responsive search application that utilizes the moogle API to search for Final Fantasy characters; I built it to practice fetching data using vanilla JavaScript. After finishing most of the project using one script, I decided to refactor the entire project using the model-view-controller (MVC) architectural pattern for a more real-world codebase, and to better organize the code structure for future development.


## Link

Visit the website here: https://ff-search.vercel.app/

## Screenshots

![Screenshot of landing page](./img/screenshots/screenshot-landing-page.png)

<br>

![Screenshot of game view](./img/screenshots/screenshot-gameview.png)

<br>

![Screenshot of select view](./img/screenshots/screenshot-selectview.png)

<br>

![Screenshot of character view](./img/screenshots/screenshot-characterview.png)

<br>

![Screenshot of character view mobile](./img/screenshots/screenshot-characterview-mobile.png)

<br>

## Description

After I discovered there was a third-party API for the RPG series 'Final Fantasy', I felt making a search application from scratch would be a fun opportunity for me to practice fetching data. As a Final Fantasy fan since childhood, I always enjoy reading about the characters and admiring the character and logo artwork. I used the wonderful [moogleAPI](https://www.moogleapi.com/) to fetch all the data for this application. I had a lot of fun programming this application and felt a great sense of accomplishment and progress solving various kinds of problems associated with displaying the data in an organized and aesthetically pleasing fashion. I learned a great deal throughout this project and I gained more confidence in my abilities as a programmer.

## Functionality

Upon loading the landing page, users will be presented with a nice UI and a handcrafted logo. I took inspiration from the Shinra Electric Power Company logo from Final Fantasy VII.

Below the "Game Select" divider, users can click on the roman numerals associated with the Final Fantasy game they wish to learn more about. Doing so will smoothly scroll the page to the respective Final Fantasy game. Here they will be able to view the game's logo, its platform, and release data, as well as a nice description about the game's history and other facts. In the future, I think it would be helpful to display some images from the game itself below the data about the game to give the user a deeper or more nostalgic impression of the game.

Users also have the option to select a main series game from a left-hand sticky sidebar. Doing so will load the selected game's logo along with a "Character Select" section. The characters displayed here are the characters from that respective game. Clicking on one of the character images will smoothly scroll the page to that character's profile. Data is displayed about the character, such as their Japanese name, gender, job, age, race, height, and weight. Like the games page before it, each character profile also contains a description about that character, their story, and interesting facts about them. (Note: There are characters whose data is either unknown (??) or not included. Where the data is not included, I've added substitute placeholders as necessary).

## Technology

HTML
<br>
CSS
<br>
JavaScript
<br>
MVC architecture
<br>
Mobile responsiveness
<br>
moogleAPI

## Questions:

