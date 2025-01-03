# WEB102 Prework - Sea Monster Crowdfunding Official

Submitted by: Amanda Lee

Sea Monster Crowdfunding Official is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 4 hours spent in total

## Required Features

The following **required** functionality is completed:

* [v] The introduction section explains the background of the company and how many games remain unfunded.
* [v] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [v] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [v] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [v] Search bar to input keyword for specific games user is looking for.
* [ ] Navigation bar to seperate pages of different component display (such Statistics, Our Game, Search Game, Intro Page for Each Game)
* [ ] Add New Game functionality
* [ ] Add period of each fundraising

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://i.imgur.com/A2C4nFt.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Direct link to demo: [https://i.imgur.com/A2C4nFt.gif](https://i.imgur.com/A2C4nFt.gif)

## Notes
### DOM (Document Object Model)
- Used JavaScript to interact with HTML elements dynamically
- Implemented event listeners for search and filter functionality
- Created and manipulated elements using methods like `getElementById`, `createElement`

### Functions
- Built organized, reusable functions for displaying games and handling search
- Used named functions for better code readability and maintenance
- Example: `searchGames()`, `showSearchGames()`

### Array Methods
#### Filter
- Implemented search functionality using `Array.filter()`
- Filtered games based on funding status and search keywords
- Example: `GAMES_JSON.filter(game => game.name.toLowerCase().includes(searchTerm))`

#### Reduce
- Calculated total funding and other statistics
- Processed game data to generate summary information

### Challenges Encountered
1. **Search Implementation**
   - Needed to handle case sensitivity in search
   - Added empty search handling

2. **Data Display**
   - Handled empty states appropriately

## License

    Copyright [2025] [Amanda Lee]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
