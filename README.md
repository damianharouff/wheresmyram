# Windows Dynamic Memory Educational Guide

An interactive, single-page website that explains Windows Dynamic Memory for Hyper-V virtual machines in simple, accessible language.

## Overview

This educational resource helps users understand how Windows Dynamic Memory works, including memory allocation, pressure levels, and the performance impact of pagefile usage. The content is written with simple language to be accessible to non-native English speakers.

## Features

- **Interactive Memory Demo**: Adjustable slider showing memory allocation from 0-150% pressure
- **Configurable RAM Sizes**: Support for 4GB, 8GB, 12GB, 16GB, 32GB, and 64GB configurations
- **Pagefile Visualization**: Clear demonstration of performance impact when exceeding RAM limits
- **Responsive Design**: Works on desktop and mobile devices
- **Visual Learning**: Color-coded memory bars and performance indicators

## Memory Pressure Levels

- **Low (0-49%)**: VM comfortable with current memory
- **Medium (50-79%)**: VM adding memory gradually
- **High (80-99%)**: VM needs memory urgently
- **Critical (100%+)**: VM using slow pagefile storage

## Usage

Simply open `index.html` in any modern web browser. No server or build process required.

## Educational Content

The guide covers:

- What Dynamic Memory is and how it works
- Memory pressure concepts with visual examples
- Configuration settings and best practices
- Performance impact of exceeding RAM allocation
- Benefits of using Dynamic Memory

## Technical Details

- Self-contained HTML file with embedded CSS and JavaScript
- No external dependencies
- Responsive design using CSS Grid and Flexbox
- Interactive elements built with vanilla JavaScript

## Browser Compatibility

Works with all modern browsers including:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Contributing

This is an educational resource. If you find errors or have suggestions for improvements, please open an issue or submit a pull request.

## License

This educational content is provided as-is for learning purposes.