# W1---PRACTICE---JES6-JS-Doc-Modules-File-IO

This repository contains practice exercises focused on modern JavaScript (ES6+), Node.js modules, documentation using JSDoc, and file input/output operations. It's structured as a learning project with multiple exercises to reinforce concepts step-by-step.

---

## 📁 Project Structure

W1---PRACTICE---JES6-JS-Doc-Modules-File-IO/
├── Ex-1/ # File IO practice (sync/async)
│ └── Student.js
├── Ex-2/ # Duration class implementation
│ └── model/
│ └── Duration.js
├── Ex-3/ # Race score management system
│ ├── model/
│ │ ├── Duration.js
│ │ └── RaceResult.js
│ ├── service/
│ │ └── RaceResultsService.js
│ ├── race-scores/
│ │ └── data/
│ │ └── raceScores.json
│ ├── mainInit.js
│ └── mainLoad.js

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. Initialize and install dependencies:
    ```npm init -y
    ```npm install

3. Optional (recommended tools):
    ```npm install -g nodemon jsdoc

## 🧪 How to Run

### Exercise 1 – File IO

```cd Ex-1
```node Student.js
# or use nodemon
```nodemon Student.js

### Exercise 2 – Duration Class

Test the Duration class inside model/Duration.js using a custom test file or by integrating with Ex-3.

### Exercise 3 – Race Score System

Create race results and save them:
```node Ex-3/mainInit.js

Load and view results:
```node Ex-3/mainLoad.js

## 📝 JSDoc

Generate HTML documentation (after installing jsdoc):
```jsdoc Ex-3/model/Duration.js Ex-3/model/RaceResult.js -d docs
Open docs/index.html in your browser.

## 📚 Concepts Covered

* Modern JavaScript (ES6+ features)
* ECMAScript modules vs CommonJS
* File system (fs) operations (sync/async)
* Creating reusable classes and services
* JSON file manipulation
* JSDoc for code documentation