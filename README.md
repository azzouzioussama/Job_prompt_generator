# Job Prompt Generator

A React-based prompt generator for building tailored job application prompts and cover letters for IT support positions.

## Overview

This repository contains the main UI component `App.jsx`, which accepts a job description and generates combined prompts for:

- CV rewrite in LaTeX format
- Short French cover letters

The app provides clipboard copy and download actions for generated prompts.

## Features

- Paste a job description and generate tailored prompts
- Extract a job title automatically from the description
- Copy generated text to clipboard
- Download prompt output as a `.txt` file
- Simple French UI for job preparation

## Usage

This repository currently includes the React component only. To run it locally:

1. Create a React app or add this file to an existing React project.
2. Install dependencies such as `react`, `react-dom`, and `lucide-react`.
3. Import `App.jsx` into your app entry point.
4. Start your React development server.

## Notes

- The current code is a UI component and does not include a full project setup.
- If you want to run this project directly, add a `package.json` and build configuration (for example, Vite or Create React App).

## License

This project is licensed under the MIT License.
