<div align="center">

<img src="bateks-logo.png" alt="BATEK'S List Manager Logo" width="260" />

# BATEK'S — List Manager

</div>

A simple, responsive list management website for organising products, tracking prices, and marking items as pending or completed. It works directly in your browser, without a server or database.

## Features

- **Responsive design:** Works on desktop, tablet, and mobile screens.
- **Simple sign-in:** Access is limited to four predefined accounts, including a demo account for testing.
- **Add items:** Record a name, product, and price for each entry.
- **Pending and Completed lists:** Check an item to mark it completed; uncheck it to move it back to Pending.
- **Edit and delete:** Update or remove items from either list.
- **Numbered items and pagination:** Browse longer lists easily.
- **Search:** Find items in your lists.
- **Amount summaries:** View the total amount for all items, Pending items, and Completed items separately. Totals cover all pages, not just the visible page.
- **Automatic local saving:** Changes are saved in the browser using `localStorage`, with separate data for each account.

## Getting Started

1. Download or clone the project.
2. Open `list-manager.html` in Google Chrome (or another modern browser).
3. Sign in with an account configured in the application (or use the demo login below).
4. Add items and manage their status from the dashboard.

No installation, build step, or internet connection is needed.

## Demo Login

Use these credentials to try the website:

| Field | Value |
|---|---|
| **User ID** | `demo` |
| **Password** | `demo` |

The demo account has its own locally saved list, separate from the other accounts. Other account credentials are not included in this README.

## How to Use

1. **Add an item:** Enter its name, product, and price, then save it.
2. **Complete an item:** Select its checkbox to move it to **Completed**.
3. **Reopen an item:** Clear the checkbox to move it back to **Pending**.
4. **Make changes:** Use the edit or delete action on an existing entry.
5. **Track amounts:** Check the summary cards to see totals for all, pending, and completed items.
6. **Browse items:** Use search and pagination to navigate your lists.

## Technology

- HTML5
- CSS3 (responsive layouts and gradient styling)
- Vanilla JavaScript
- Browser `localStorage`

## Project Structure

```text
list-manager/
├── list-manager.html   # Complete website (HTML, CSS and JavaScript)
├── bateks-logo.png     # Logo for the README
└── README.md           # Project instructions
```

## Important Notes

- Data is stored **locally in the current browser**, not in an online database. It does not automatically sync between devices or browsers.
- Clearing site data, using private browsing, or switching to a different browser/storage context may remove or hide saved lists.
- The browser-side sign-in is intended for basic personal use. It is **not secure authentication** for sensitive information or a public multi-user service.
- Back up important information separately; `localStorage` is not a replacement for a database or reliable backup.

## License

No license has been specified for this project.
