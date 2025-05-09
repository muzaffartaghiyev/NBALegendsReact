

# NBA Legends App

The NBA Legends App is a React application that showcases basketball players and their statistics. Users can search for players by name and toggle between the player's image and their career statistics by clicking on their card.

---

## Features

* **Player Search:** Search for NBA players by typing their name in the search bar.
* **Interactive Player Cards:** Click on a player card to toggle between their image and statistics.
* **Dynamic Filtering:** Player list updates in real time as you type in the search bar.
* **Responsive Design:** The application is designed to work seamlessly on all devices.

---

## Preview




## Technologies Used

* **React**: Frontend framework for building the app.
* **SCSS**: For modular and maintainable styles.
* **JavaScript**: Core language for logic and interactivity.

---

## Components Overview

1. **App.jsx**:

   * Manages the state for the search term.
   * Renders the `Header` and `CardContainer` components.

2. **Header.jsx**:

   * Displays the NBA logo and the app title.
   * Provides a search bar for filtering players.

3. **CardContainer.jsx**:

   * Filters and displays the player cards based on the search input.
   * Displays a message if no players match the search term.

4. **PlayerCard.jsx**:

   * Displays individual player information.
   * Toggles between the player's image and statistics on click.

---


## Sample Data Format

The `data.js` file contains an array of player objects. Each object includes:

```javascript
{
  name: "Player Name",
  img: "URL to player's image",
  statistics: [
    "Statistic 1",
    "Statistic 2",
    ...
  ]
}
```


