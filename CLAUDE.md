# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a single-page educational website (`index.html`) that explains Windows Dynamic Memory for Hyper-V virtual machines. The website is designed to be accessible to non-native English speakers with simple explanations, interactive demos, and visual representations.

## Architecture

The project is a self-contained HTML file with embedded CSS and JavaScript:

- **HTML Structure**: Single-page layout with sections for concepts, examples, and interactive demos
- **CSS**: Responsive design with mobile-first approach, color-coded elements for different memory states
- **JavaScript**: Interactive memory allocation simulator with configurable RAM sizes and pressure levels

### Key Components

- **Memory Pressure Visualization**: Interactive slider that demonstrates memory allocation from 0-150% pressure
- **Pagefile Demonstration**: Shows performance impact when memory usage exceeds RAM limits
- **Configurable Examples**: Dropdown selector for different RAM sizes (4GB to 64GB)
- **Static Examples**: Fixed demonstrations in the "Memory vs Pagefile Usage" section

## Development Workflow

Since this is a static HTML file, development is straightforward:

1. **Testing**: Open `index.html` in any modern web browser
2. **Mobile Testing**: Use browser dev tools to test responsive design on different screen sizes
3. **Interactive Features**: Test the pressure slider and RAM size dropdown to ensure proper calculations

## Design Principles

- **Simple Language**: Written for non-native English speakers
- **Visual Learning**: Color-coded memory bars (green=RAM, red=pagefile)
- **Progressive Disclosure**: Information organized from basic concepts to advanced topics
- **Performance Education**: Clear demonstration of pagefile performance impact

## Memory Pressure Thresholds

The interactive demo uses specific thresholds:
- Low pressure: 0-49%
- Medium pressure: 50-79%
- High pressure: 80-99%
- Critical pressure: 100%+ (triggers pagefile usage)

At exactly 100% pressure, the VM uses maximum allocated RAM. Above 100%, pagefile usage begins with corresponding performance warnings.