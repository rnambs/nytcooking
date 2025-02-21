# Chrome Extension for NYT Cooking Paywalls

This is a simple Chrome extension that removes the paywall from NYT Cooking recipes.

## Installation

1. Download or clone this repository (or download the repo as a zip file)
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked" and select the extension folder

## Usage

Once installed, the extension will automatically hide the paywall on NYT Cooking recipes. When you first open a recipe, you may have to provide your browser access to the extension, and then it will work automatically.

## Files
- `manifest.json`: Extension configuration
- `content.js`: Main script that handles modal hiding with CSS (lightweight)