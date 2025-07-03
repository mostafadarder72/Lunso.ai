# Lunso.ai - All-in-One Platform

This is the comprehensive website for Lunso.ai, featuring a tourism management system and integrated WhatsApp chat functionality with both English and Arabic versions.

## Project Structure

```
lunsoai/
├── assets/
│   ├── images/          # Image files (PNG, JPG, etc.)
│   ├── icons/           # Icon SVG files
│   └── svg/             # Other SVG graphics
├── pages/
│   ├── en/              # English pages
│   │   ├── home.html    # Main tourism homepage
│   │   └── demo.html    # Tourism demo page
│   └── ar/              # Arabic pages
│       ├── home-ar.html # Arabic tourism homepage
│       └── demo.html    # Arabic demo page
├── chat/                # WhatsApp chat application
│   ├── assets/          # Chat-specific assets
│   ├── components/      # React components
│   ├── styles/          # Chat-specific styles
│   └── index.html       # Chat application entry point
├── build/               # Build artifacts and static files
├── .htaccess           # Apache configuration
└── README.md           # This file
```

## Features

### Tourism Management System
- **Multi-language Support**: English and Arabic versions
- **Responsive Design**: Optimized for various screen sizes
- **Tourism Solutions**: Tour, Car, Hotel, Boat, Space, Event, Tickets, Flight management
- **Performance Optimized**: Organized assets and build structure

### WhatsApp Chat Integration
- **Real-time Chat Interface**: WhatsApp-style messaging
- **Contact Management**: User profiles and conversation history
- **Media Support**: Text, images, and file sharing
- **Responsive Design**: Mobile-first chat experience
- **Theme Support**: Light/dark mode compatibility

## File Organization

### Assets
- **images/**: Contains all image files (PNG, JPG, etc.)
- **icons/**: Contains icon SVG files (icon-*.svg)
- **svg/**: Contains other SVG graphics and illustrations

### Pages
- **en/**: English language pages
  - `home.html`: Main tourism platform homepage
  - `demo.html`: Tourism system demo
- **ar/**: Arabic language pages
  - `home-ar.html`: Arabic tourism platform homepage
  - `demo.html`: Arabic tourism system demo

### Chat Application
- **chat/**: Dedicated WhatsApp chat application
  - **assets/**: Chat-specific images and resources
  - **components/**: React components for chat functionality
  - **styles/**: Chat-specific CSS and styling
  - **index.html**: Chat application entry point

### Build
- Contains all build artifacts, static files, and generated content

## Integration Features

1. **Unified Navigation**: Seamless navigation between tourism and chat features
2. **Consistent Design**: Shared design language across both systems
3. **Language Support**: Both systems support English and Arabic
4. **Responsive Layout**: Optimized for desktop and mobile devices

## Performance Enhancements

1. **Organized Assets**: Images, icons, and SVGs are properly categorized
2. **Clean Structure**: Removed duplicate and unused files
3. **Consistent Naming**: All files follow a consistent naming convention
4. **Separated Concerns**: Build artifacts are separated from source files
5. **Modular Architecture**: Chat and tourism systems are modular and independent

## Usage

### Tourism Management
- Access the main tourism platform at `/pages/en/home.html` or `/pages/ar/home-ar.html`
- Navigate through different tourism solutions (Tour, Car, Hotel, etc.)
- Request demos and contact support



## Maintenance

- Update assets in their respective directories
- Add new pages to the appropriate language folder
- Keep build artifacts in the build/ directory
- Maintain consistent naming conventions
- Update chat components in the chat/ directory
- Ensure both systems maintain responsive design and performance
