# Mapping-Data-Components-Practice

# Mapping Components Practice - Emojipedia

A React project that practices mapping components by dynamically rendering emoji data from an `emojipedia` dataset. This application displays an interactive dictionary of emojis, where each entry includes an emoji icon, name, and description.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies](#technologies)
6. [Folder Structure](#folder-structure)
7. [Scripts](#scripts)
8. [License](#license)

## Overview

This app renders a collection of emoji entries using React, mapping over a dataset to display each emoji along with its description and meaning. It demonstrates the use of mapping functions, props, and reusable components in React.

## Installation

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/Mapping-Data-Components-Practice.git

**Navigate to the project directory:**

bash
cd your-repo

**Install the dependencies:**

bash
npm install

**Start the development server:**

bash
npm start
Open http://localhost:3000 in your browser to view the app.

## Usage
The application imports an emojipedia dataset containing emoji data. Each emoji entry includes an icon, name, and description. The app maps over this data to render an Entry component for each item in the dataset.

**Example**
In emojipedia.js:

javascript

const emojipedia = [
  {
    id: 1,
    emoji: "💪",
    name: "Tense Biceps",
    meaning:
      "“You can do that!” or “I feel strong!” Arm with tense biceps. Also used in connection with doing sports, e.g., at the gym."
  },
  // Additional emojis...
];
export default emojipedia;


## Components
- App: The main component that maps over emojipedia data and renders each Entry.
- Entry: A reusable component that displays each emoji's details, such as the icon, name, and description.

## Features
- Dynamic Data Rendering: Uses .map() to dynamically generate components from a dataset.
- Reusable Components: The Entry component is a reusable template for each emoji entry.

## Technologies
- React (v18.3.1)
- React DOM (v18.3.1)
- CSS for styling in styles.css

## Scripts
- start: Runs the app in development mode with react-scripts start.
- build: Builds the app for production with react-scripts build.
- test: Runs the test suite with react-scripts test --env=jsdom.
- eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.
