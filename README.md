# x402 Agents Payments Dashboard

A simple, responsive dashboard built with HTML, CSS, and JavaScript to monitor HTTP 402 (x402 protocol) payments for AI agents.

This dashboard features:
- A collapsible sidebar with navigation
- Dark mode toggle (with persistent state via localStorage)
- Placeholder sections for displaying recent transactions, active agents, and payment summaries

## Features

- **Sidebar Layout**: Clean navigation for Home, Payments, Agents, Transactions, and Settings.
- **Header**: Includes page title and dark mode switch.
- **Data Cards**: Grid-based placeholders for real-time data lists (e.g., agent transactions in USDC).
- **Responsive Design**: Works on desktop and mobile.
- **Dark Mode**: Toggles between light and dark themes, saved in browser storage.

## Demo

Copy the code below into an `index.html` file and open it in your browser for a live preview.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>x402 Agents Payments Dashboard</title>
    <link rel="stylesheet" href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css">
    <style>
        /* CSS from previous code */
        /* (Paste the full <style> block here for brevity, it's the same as provided) */
    </style>
</head>
<body>
    <!-- Full HTML structure as provided previously -->
</body>
</html>
```

## Installation & Usage

No dependencies required – pure vanilla HTML/CSS/JS.

1. Save the full code as `index.html`.
2. Open in any modern browser.
3. Toggle dark mode and collapse sidebar to test interactivity.

## Future Enhancements

- Integrate real-time data via WebSockets or API fetches.
- Add charts for payment trends (e.g., using Chart.js).
- Connect to actual x402 protocol endpoints for live agent payment monitoring.

## License

MIT License – feel free to use, modify, and distribute.
