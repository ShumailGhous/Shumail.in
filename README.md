# 3x+1 Conjecture Explorer

A simple web-based tool to explore the **Collatz Conjecture** (also known as the 3x+1 problem). This project allows users to visualize the sequence for any starting number, batch-analyze ranges, and compare sequences between different numbers.

## Features
- Visualize the 3x+1 sequence for any positive integer.
- Batch analyze sequences for a range of numbers.
- Compare sequences of two different numbers.
- Provides key statistics such as steps to reach 1, maximum value, and average value.
- Interactive charting powered by [Chart.js](https://www.chartjs.org/).

## How to Use
1. Open the `index.html` file in any modern web browser.
2. Use the input fields and buttons to:
   - Enter a number and visualize its 3x+1 sequence.
   - Analyze a range of numbers to see how many steps each number takes to reach 1.
   - Compare two numbers to observe their sequence patterns side by side.

## UI Overview
- **Controls Section**: 
  - Input fields for single number and range-based analysis.
  - Buttons for visualization, batch analysis, and comparison.
- **Chart Area**:
  - Displays the visual representation of sequences.
- **Statistics Section**:
  - Shows key metrics about the sequence.

## File Structure
- `index.html`: The main HTML file that includes the structure and logic of the application.
- `README.md`: Project documentation (this file).
- External dependency: `Chart.js` (loaded via CDN).

## Example
### Single Number Visualization
- Enter a number (e.g., `27`) in the **Enter number** field.
- Click **Visualize Sequence** to see the sequence and statistics.

### Batch Analyze
- Enter a start and end range (e.g., `1` to `100`).
- Click **Batch Analyze** to observe how many steps each number takes.

### Comparison
- Enter two numbers (e.g., `19` and `27`) when prompted.
- Click **Compare Sequences** to see their sequences on the same chart.

## Technologies Used
- **HTML**: Structure of the web page.
- **CSS**: Styling for a modern and minimalistic design.
- **JavaScript**: Logic for sequence generation, chart rendering, and user interaction.
- **Chart.js**: Visualization of the sequences.


## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute.

---

Happy exploring the mysterious 3x+1 conjecture!
