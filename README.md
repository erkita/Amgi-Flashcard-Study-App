# Amgi - Flashcard Study App

### Overview of Amgi
* Original idea from [AnkiWeb](https://ankiweb.net/about)
* Fullstack project
* Flashcard app for studying
* Worked in group of 4

### Built With
* MongoDB
* Express
* React
* Redux
* NodeJS
* JWT

### Link to App
https://amgiapp.herokuapp.com/

### About This Application
* Amgi is a personalized flashcard web browser app intended for individual users that allows users to:
  * create user account 
  * create, read, and delete flashcards and flashcard decks
  * keep track and create personalized deck based on each flashcard's difficulty level to recall (again, hard, good, easy)

### Demo
Create deck and flashcard
![create-deck-card](https://user-images.githubusercontent.com/82434097/184241318-5439005a-7e58-4479-a464-52764eaef0bf.gif)

Practice flashcards and mark their recallability
![practice](https://user-images.githubusercontent.com/82434097/184241422-3429b501-f320-492f-827a-f3f564c556cb.gif)

Delete flashcard and deck
![delete](https://user-images.githubusercontent.com/82434097/184241462-50794c58-8239-4cab-a792-cff9030141d0.gif)

### Test
* Backend Node.js CRUD APIs were tested with Mocha and Chai
* Tests written for `user.js`, `flashcard.js`, and `deck.js` classes in `server`

### GitHub Workflow
* On every push from dev and main branch, Github workflow will be triggered. This will run tests on all backend APIs to see if changes will make any backend interferences
* Push on dev branch will also automatically deploy to Heroku
* Future work: if any bugs were to be pushed and crashes the application, revert back to previous commit

### Installation
* Prerequisite: source-code editor that can run Javascript (Amgi developers used VS Code) and Javascript installed
* To clone this repo on your local machine:

  `git clone https://github.com/neu-seattle-cs5500-summer2022/project-SM22-erkita-vmalecode-stefanisindarto-cathylee12.git`

* To install the package, run: `npm install`

### Usage
* Serve the app: `npm start`

* Run tests: `npm test`
