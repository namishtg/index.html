# index.html
Privacy Policy for Industrial47 WhatsApp Manager
A Microsoft Edge extension that allows you to tag and organize your WhatsApp Web chats with custom tags for better organization and filtering.

## Features

- 🏷️ **Tag Assignment**: Easily assign custom tags to any WhatsApp chat
- 🎨 **Custom Colors**: Create tags with personalized colors
- 📊 **Visual Organization**: See tag indicators on chats in your chat list
- 🔍 **Smart Filtering**: Filter chats by clicking tags in the top bar
- 💾 **Data Management**: Export and import your tag data
- 🌓 **Dark Mode Support**: Works with both light and dark WhatsApp themes

## Installation

### Method 1: Load as Unpacked Extension (Recommended for Development)

1. **Download and Extract**: Download this extension folder to your computer
2. **Open Edge Extensions**: Navigate to `edge://extensions/` in Microsoft Edge
3. **Enable Developer Mode**: Toggle "Developer mode" in the top-right corner
4. **Load Extension**: Click "Load unpacked" and select the `whatsapp-chat-tagger` folder
5. **Verify Installation**: The extension should appear in your extensions list

### Method 2: Install from Microsoft Store (Coming Soon)
The extension will be available on the Microsoft Edge Add-ons store in the future.

## How to Use

### 1. Accessing WhatsApp Web
- Open [web.whatsapp.com](https://web.whatsapp.com) in Microsoft Edge
- Make sure you're logged in and can see your chat list
- The extension will automatically initialize when WhatsApp Web loads

### 2. Using the Top Bar
- A purple gradient bar will appear at the top of WhatsApp Web
- This bar displays all your available tags as clickable pills
- Click any tag pill to filter chats that have that tag
- Click "Show All" to remove filtering and see all chats

### 3. Tagging Chats
- **Find the Tag Button**: Look for the 🏷️ emoji button that appears on the right side of each chat
- **Open Tag Modal**: Click the tag button to open the tagging interface
- **Select Tags**: Check or uncheck tags to assign/remove them from the chat
- **Save Changes**: Click "Save Tags" to apply your selections

### 4. Managing Tags
- **Access Tag Manager**: Click the extension icon in your browser toolbar
- **View Statistics**: See how many tags you have and how many chats are tagged
- **Create New Tags**: Use the form at the bottom to create new tags with custom names and colors
- **Delete Tags**: Remove tags you no longer need (will also remove from all chats)

### 5. Visual Indicators
- Tagged chats will show small colored pills next to their names
- Each tag pill displays the tag name in the tag's custom color
- Multiple tags per chat are supported and will all be displayed

### 6. Data Management
- **Export**: Click "Export Data" to download your tags and assignments as a JSON file
- **Import**: Click "Import Data" to restore from a previously exported JSON file
- **Backup**: Regular exports are recommended to preserve your organization system

## Default Tags

The extension comes with four pre-configured tags:
- 🔵 **Work** (Purple)
- 💖 **Family** (Pink)
- 🟠 **Important** (Orange)
- 🟢 **Friends** (Green)

You can modify, delete, or add to these tags as needed.

## Troubleshooting

### Extension Not Loading
- Ensure you've enabled Developer mode in Edge extensions
- Check that all files are present in the extension folder
- Reload the extension after making any changes

### Top Bar Not Appearing
- Make sure you're on web.whatsapp.com (not the mobile site)
- Refresh the WhatsApp Web page after installing the extension
- Check browser console (F12) for any error messages

### Tag Buttons Not Visible
- The buttons appear as 🏷️ emoji on the right side of each chat
- They may be subtle - look carefully or hover over the chat area
- Try refreshing WhatsApp Web if buttons don't appear

### Tags Not Saving
- Ensure the extension has proper permissions
- Check that you have storage space available
- Try reloading the extension

## Privacy & Data

- **Local Storage Only**: All tag data is stored locally on your device
- **No External Servers**: The extension doesn't send data to any external services
- **WhatsApp Web Only**: The extension only operates on web.whatsapp.com
- **No Message Access**: The extension only interacts with chat names and interface elements

## Browser Compatibility

- **Microsoft Edge**: Fully supported (Chromium-based)
- **Google Chrome**: Compatible (same codebase)
- **Other Browsers**: Not tested, may require modifications

## File Structure

```
whatsapp-chat-tagger/
├── manifest.json          # Extension configuration
├── content.js             # Main functionality (top bar, buttons, modals)
├── styles.css             # Visual styling
├── background.js          # Background processes and storage
├── popup.html             # Tag management interface
├── popup.js               # Popup functionality
├── icons/                 # Extension icons
│   ├── icon16.png
│   ├── icon32.png
│   ├── icon48.png
│   └── icon128.png
└── README.md              # This file
```

## Development

### Making Changes
1. Edit the relevant files in the extension folder
2. Reload the extension in `edge://extensions/`
3. Refresh WhatsApp Web to see changes

### Debugging
- Use browser Developer Tools (F12) to inspect console messages
- Check the extension's background page for background script errors
- Monitor storage in DevTools > Application > Storage

## Version History

### v1.0.0 (Current)
- Initial release
- Basic tag creation and assignment
- Top bar filtering interface
- Data export/import functionality
- Visual tag indicators

## Support

For issues, suggestions, or contributions:
- Check the troubleshooting section above
- Review browser console for error messages
- Ensure all files are properly installed

## License

This extension is provided as-is for personal use. Modify and distribute according to your needs.
