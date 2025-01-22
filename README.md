# Markdown to Google Docs Converter

## Description
This project provides a Python script designed to convert markdown meeting notes into a well-formatted Google Doc. The script uses the Google Docs API to create and format the document directly in Google Colab.

## Features
- Converts markdown headers (#, ##, ###) to corresponding Google Doc styles (Heading 1, Heading 2, Heading 3).
- Preserves nested bullet point structures with proper indentation.
- Converts markdown checkboxes (`- [ ]`) to Google Doc checkboxes.
- Highlights assignee mentions (`@name`) with bold text.
- Adds footer details with distinct styling.

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone <repository-url>
