# Election Process Interactive Assistant

A single-page interactive web app that explains the election process, timelines, and steps. It includes a sidebar navigation of election stages, step details, and an AI-powered chat assistant for election questions.

## Features

- Two-panel layout with a sidebar and main content area
- Six election steps with step numbers, labels, and time periods
- Step detail card with tags and summary information
- Chat interface with full conversation history
- Quick question buttons for common election topics
- Demo AI mode with pre-written responses
- Light/dark mode support via CSS variables
- Responsive layout for mobile
- Accessible design with keyboard support and ARIA labels

## Files

- `index.html` - main application file containing HTML, CSS, and JavaScript

## How to Use

1. Open `index.html` in a browser.
2. Click an election step in the sidebar to view details.
3. Ask a question in the chat input or use one of the quick question buttons.

## Demo Mode

The app currently includes a demo mode with pre-written AI responses. To enable real AI responses using Google Gemini:

1. Create a Google Cloud project at https://console.cloud.google.com/
2. Enable the **Generative Language API**.
3. Create an API key in **APIs & Services > Credentials**.
4. Replace the placeholder key in `index.html`:

```javascript
const GOOGLE_API_KEY = "DEMO_KEY"; // Replace with your real Google API key
```

5. Save the file and refresh the browser.

## GitHub

Repository: https://github.com/jancysen/Election-Process-Interactive-Assistant
