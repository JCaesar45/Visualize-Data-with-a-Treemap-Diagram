````markdown

# Treemap Diagram Visualization

Welcome to the Treemap Diagram Visualization project! This project allows you to create an interactive treemap diagram that visualizes data based on different datasets, such as Kickstarter pledges, movie sales, or video game sales. This README will walk you through the necessary components, user stories, and how to run the project.

## Objective

The goal of this project is to build an app that visualizes data using a treemap diagram, similar in functionality to the example provided [here](https://treemap-diagram.freecodecamp.rocks). You are tasked with fulfilling the user stories listed below to ensure the app meets the required specifications.

## Technologies Used

- HTML
- CSS
- JavaScript
- D3.js (Data-Driven Documents)

## User Stories

1. **Title**: My tree map should have a title with a corresponding id="title".
2. **Description**: My tree map should have a description with a corresponding id="description".
3. **Tiles**: My tree map should have rect elements with a corresponding class="tile" that represent the data.
4. **Colors**: There should be at least 2 different fill colors used for the tiles.
5. **Attributes**: Each tile should have the properties data-name, data-category, and data-value containing their corresponding name, category, and value.
6. **Area Correspondence**: The area of each tile should correspond to the data-value amount, with larger tiles for larger values.
7. **Legend**: My treemap should have a legend with corresponding id="legend".
8. **Legend Rect Elements**: My legend should have rect elements with a corresponding class="legend-item".
9. **Legend Fill Colors**: The rect elements in the legend should use at least 2 different fill colors.
10. **Tooltip**: I can mouse over an area and see a tooltip with a corresponding id="tooltip" that displays more information.
11. **Tooltip Data-Value**: My tooltip should have a data-value property that corresponds to the data-value of the active area.

## Dataset Options

You can choose any of the following datasets to create your treemap visualization:

- [Kickstarter Pledges](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/kickstarter-funding-data.json)
- [Movie Sales](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/movie-data.json)
- [Video Game Sales](https://cdn.freecodecamp.org/testable-projects-fcc/data/tree_map/video-game-sales-data.json)

## Project Structure

```
/your-project-directory
|-- index.html
|-- styles.css
|-- script.js
|-- README.md
```

### `index.html`

This file contains the main HTML structure for the treemap visualization, including the title, description, and div elements for the treemap and legend.

### `styles.css`

This file contains the CSS styles for your treemap visualization. You can customize colors, fonts, layouts, and hover effects to give your treemap a unique look.

### `script.js`

This file initializes the D3.js visualization, creates the treemap layout, and handles the mouse events for the tooltip and legend.

### `README.md`

This file provides information about your project, including how to use it, the technologies used, and any other relevant details.

## How to Run the Project

1. Clone the repository or create a new HTML file that contains the code from `index.html`, CSS styles from `styles.css`, and JavaScript functionality from `script.js`.

2. Open `index.html` in your web browser.

3. Ensure the D3.js library is either linked from a CDN or included in your project to allow for the visualization to work correctly. You can use the following CDN link in your HTML file:
   ```html
   <script src="https://d3js.org/d3.v7.min.js"></script>
   ```

4. To run the tests, you can use the following CDN link for freeCodeCamp's testing suite:
   ```html
   <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
   ```

5. Open your browser's console to see the test results running after the page loads.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Conclusion

Once you have successfully passed all the tests and are satisfied with your treemap visualization, be sure to submit the URL to your working project for review. Happy coding!
