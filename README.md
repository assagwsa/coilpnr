# Coil Data Checker - Progressive Web App (PWA)

## Overview
This is the PWA-enabled version of your Coil Data Checker application for A.S. Shipping Agencies Pvt Ltd, converted from your GitHub Pages website at https://assagwsa.github.io/coilpnr/

## What's New
✅ **Installable as Mobile App** - Users can install directly from Chrome browser
✅ **Custom Coil Icon** - Professional metallic coil icon for app branding
✅ **Full-Screen Experience** - Opens without browser bars like a native app
✅ **Offline Functionality** - Works even without internet connection
✅ **Home Screen Integration** - Appears on mobile home screen
✅ **Zero Functionality Changes** - All tabs, features, and operations work exactly the same

## Installation Instructions for Users

### Mobile Installation (Android/iOS):
1. Open Chrome browser on your mobile device
2. Visit your updated website
3. Chrome will show "Add to Home Screen" notification
4. Tap "Install" or "Add to Home Screen"
5. App icon appears on home screen with coil design
6. Tap the icon to open the app in full-screen mode

### Desktop Installation:
1. Open Chrome browser on desktop
2. Visit your website
3. Look for install icon (⊕) in address bar
4. Click to install as desktop app

## Technical Changes Made

Only 7 lines added to your existing HTML file:

### In `<head>` section (3 lines):
- App manifest for PWA configuration
- Custom coil icon (120x120 and 192x192)
- Apple touch icon for iOS devices

### Before closing `</script>` (4 lines):
- Service worker registration for offline functionality
- Basic caching for improved performance

## Features Preserved
- ✅ Tab menu system (Coil Processing, Generate Reports, Google Sheets)
- ✅ QR code scanning functionality
- ✅ Google Sheets integration with password protection
- ✅ Vehicle and coil management
- ✅ Report generation (Text, PDF, Print, Share)
- ✅ Coil search suggestions
- ✅ All existing styling and responsiveness

## File Structure
- `index.html` - Updated HTML file with PWA features
- `README-GitHub.md` - This installation guide
- `CHANGES.md` - Technical documentation of modifications

## Deployment Instructions
1. Replace your current `index.html` file on GitHub Pages with the updated version
2. Commit and push changes to your repository
3. GitHub Pages will automatically deploy the PWA-enabled version
4. Users can now install your app directly from the browser

## Browser Compatibility
- ✅ Chrome (Android/Desktop) - Full PWA support
- ✅ Safari (iOS) - Limited PWA support, works as web app
- ✅ Edge (Desktop) - Full PWA support
- ✅ Firefox (Android/Desktop) - Basic PWA support

## Support
The app maintains all existing functionality while adding mobile installation capabilities. No changes to your Google Sheets integration or any operational features.