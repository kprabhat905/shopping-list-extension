# SnapStash Chrome Extension

SnapStash is a simple Chrome extension that lets you save items from your current browser tab into categorized shopping lists. You can preview, categorize, and manage your saved items directly from the extension popup.

## Features

- Save the current tab's title and URL as a shopping list item.
- Categorize items (Books, Clothes, Shoes, Electronics, Pets, Health).
- View and manage your saved items by category.
- Delete items from your list.
- Data is synced using Chrome's storage, so your list is available across devices.

## Installation

1. **Clone or Download the Repository**

   Download this folder to your computer.

2. **Load the Extension in Chrome**

   - Open Chrome and go to `chrome://extensions/`
   - Enable **Developer mode** (top right).
   - Click **Load unpacked** and select the `shopping-list-extension` folder.

3. **Usage**

   - Click the SnapStash icon in your Chrome toolbar.
   - Select a category and click **Save Item** to add the current tab.
   - View, organize, and delete items from the popup.

## File Structure

```
shopping-list-extension/
├── background.js
├── manifest.json
├── popup.css
├── popup.html
├── popup.js
└── images/
    └── icon128.png
```

- **manifest.json**: Extension configuration.
- **background.js**: Initializes storage on install.
- **popup.html**: The extension's popup UI.
- **popup.css**: Styles for the popup.
- **popup.js**: Handles logic for saving, displaying, and deleting items.
- **images/icon128.png**: Extension icon.

## Development

- Edit `popup.js`, `popup.html`, or `popup.css` as needed.
- Reload the extension in `chrome://extensions/` after making changes.

## License

This project is for educational purposes.
