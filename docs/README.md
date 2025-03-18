# Gaze Data Analysis Documentation

This directory contains documentation for the Gaze Data Analysis Tool, a web application for analyzing eye-tracking data.

## Overview

The Gaze Data Analysis Tool allows researchers and analysts to upload eye-tracking data in CSV format and perform various analyses, including:

- Basic statistical analysis of gaze coordinates
- Visualization of gaze paths
- Identification of fixations and saccades
- Heat map generation of gaze concentration

## Getting Started

To use the documentation:

1. Browse the HTML documentation by opening `index.html` in your web browser
2. Refer to the user guide for detailed instructions on using the tool
3. Check the API documentation if you're integrating with the tool programmatically

## Documentation Structure

- `index.html` - Main documentation page with interactive examples
- `user-guide.md` - Comprehensive guide for using the application
- `api-reference.md` - Technical documentation for developers
- `examples/` - Directory containing example datasets and usage scenarios

## Data Format Requirements

The tool accepts CSV files with the following columns:

- Timestamp (in milliseconds)
- X coordinate (in pixels)
- Y coordinate (in pixels)
- Additional optional columns (pupil size, validity, etc.)

## Visualization Types

The documentation covers how to use and interpret:

- Gaze path plots
- Velocity charts for saccade detection
- Fixation maps and heat maps
- Statistical summary visualizations

## Troubleshooting

Common issues and their solutions are documented in the troubleshooting section of the user guide. For additional help, please refer to the main project README or open an issue in the project repository.

## Contributing to Documentation

We welcome contributions to improve this documentation. Please see the main project README for contribution guidelines.
