# Coil PNR

## Overview

This is a single-page web application designed for A.S Shipping Agencies to manage and check coil data. The application is built as a Progressive Web App (PWA) that integrates with Google Sheets for data storage and management through Google Apps Script.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

The application follows a simple client-server architecture with:

**Frontend**: Single HTML file with embedded CSS and JavaScript
**Backend**: Google Apps Script serving as a serverless backend
**Data Storage**: Google Sheets as the primary database
**Deployment**: Static hosting with PWA capabilities

The architecture is designed for simplicity and ease of deployment without requiring traditional server infrastructure.

## Key Components

### Frontend Architecture
- **Single Page Application**: Built entirely in one HTML file for easy deployment
- **Progressive Web App**: Configured with PWA manifest and meta tags for mobile app-like experience
- **Responsive Design**: Mobile-first approach with full-screen support and touch optimization
- **CSS Custom Properties**: Centralized theming system with defined color palette and design tokens

### Backend Integration
- **Google Apps Script**: Serverless backend handling HTTP requests (GET/POST)
- **CORS Handling**: Cross-origin resource sharing configured for web app access
- **Anonymous Access**: Designed to work without user authentication for broader accessibility

### Data Management
- **Google Sheets Integration**: Direct spreadsheet manipulation through Apps Script
- **Real-time Data**: Live connection to Google Sheets for immediate data updates
- **Form Handling**: POST request processing for data submission
- **Query Support**: GET request handling for data retrieval

## Data Flow

1. **User Interaction**: User interacts with the web interface
2. **Request Processing**: Frontend sends HTTP requests to Google Apps Script endpoint
3. **Data Operations**: Apps Script performs CRUD operations on Google Sheets
4. **Response Handling**: Results are returned to the frontend and displayed to the user
5. **Real-time Updates**: Changes are immediately reflected in the Google Sheets backend

## External Dependencies

### Google Services
- **Google Sheets API**: Core data storage and manipulation
- **Google Apps Script**: Serverless execution environment
- **Google Drive**: File storage and sharing permissions

### Web Standards
- **PWA Manifest**: For mobile app installation capabilities
- **Service Worker Ready**: Infrastructure prepared for offline functionality
- **Web App Manifest**: Proper PWA configuration with icons and display settings

## Deployment Strategy

### Frontend Deployment
- **Static Hosting**: Can be deployed to any static hosting service (GitHub Pages, Netlify, Vercel)
- **PWA Installation**: Users can install as a mobile app through browser
- **No Build Process**: Direct deployment of HTML file without compilation

### Backend Deployment
- **Google Apps Script**: Deploy as web app with public access
- **Configuration Required**: 
  - Replace placeholder spreadsheet ID with actual Google Sheets ID
  - Deploy with "Execute as: Me" and "Who has access: Anyone"
  - Update frontend with actual Apps Script web app URL

### Security Considerations
- **Anonymous Access**: Designed for public use without authentication
- **CORS Configuration**: Proper cross-origin headers for web access
- **Content Security Policy**: Basic CSP implementation for security

The application prioritizes simplicity and ease of deployment while maintaining functionality for coil data management. The Google Sheets integration provides a familiar interface for data management while the PWA features ensure a native app-like experience on mobile devices.
