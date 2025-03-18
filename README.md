# Gaze-Coordinate-Statistics

This project is a simple web application that allows you to upload a CSV file containing gaze coordinates and calculate various statistics about the data.

## File Structure

```bash
eye-tracking-analytics/
├── src/
│   ├── core/
│   │   ├── preprocessing.js
│   │   ├── fixation-detection.js
│   │   └── metrics-calculation.js
│   ├── ml/
│   │   ├── classifier.js
│   │   └── model-persistence.js
│   ├── visualization/
│   │   ├── chart-manager.js
│   │   └── aoi-renderer.js
│   └── utils/
│       ├── logger.js
│       └── data-validation.js
├── docs/
│   ├── index.html
│   ├── styles/
│   │   └── main.css
│   └── assets/
│       ├── example.csv
│       └── demo-video.mp4
├── models/
│   └── pretrained/
│       └── fixation-classifier.json
├── tests/
│   ├── unit/
│   └── integration/
├── .github/
│   └── workflows/
│       └── ci.yml
├── package.json
├── webpack.config.js
├── Dockerfile
└── README.md
```

## Features

- Upload a CSV file with gaze coordinates
- Calculate basic statistics like mean, median, and standard deviation
- Visualize the data in a scatter plot

## Technologies Used

- HTML/CSS/JavaScript
- D3.js for data visualization
- Papa Parse for CSV parsing

## Installation

1. Clone the repository
2. Open the `index.html` file in your browser

## Usage

1. Upload a CSV file containing gaze coordinates
2. Click the "Process Data" button to calculate statistics and display the scatter plot

## File Structure

- `index.html`: Main HTML file with the interface
- `style.css`: CSS for styling the application
- `script.js`: JavaScript for processing the data and updating the UI

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes and commit them
4. Push to your fork and create a pull request  

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
