# Web Design Using Javascript 

## Level 1: Automatic Table and Date Search

* Level 1 of the assignment is under the folder: **UFO-level-1**. This contains the `index.html` file, a basic HTML web page that was created to display the dynamic table of UFO sightings.  A copf of this HTML file is also placed in the root of the Github repo for a github page.

* Using the UFO dataset that was provided in the form of an array of JavaScript objects, code was written in `app.js` that appends a table to the web page and then adds new rows of data for each UFO sighting.

* Each UFO sighting will have data for `date/time`, `city`, `state`, `country`, `shape`, and `comment`.

* A simple filter form was created using a date form where a user can select a date value from a dropdown menu. A function called `filterTable()` was created using JavaScript that listens for events and searches through the `date/time` column to find rows that match user input and displays these to the webpage.

* A function called `resetTable()` clears the body of the table, populates the dropdown menu with unique date values from the dataset and displays all data to the table as a starting point.


## Level 2: Multiple Search Categories

* Level 2 of the assignment is under the folder: **UFO-level-2**. This contains the `index.html` file, created to display the dynamic table of UFO sightings with an advanced filter option.

* Using multiple select dropdowns, JavaScript code was written in `app-advanced.js` so the user can set multiple filters and search for UFO sightings using the following criteria based on the table columns:

  1. `date/time`
  2. `city`
  3. `state`
  4. `country`
  5. `shape`

* An additional function `populateDropdowns()` was written to automatically populate the dropdown menus with unique values for each category. These options were sorted in ascending order using `d3.ascending` for ease of use when selecting.
