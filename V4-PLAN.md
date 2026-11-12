
# Feather Browser v4.0

## Goal
Build a customizable browser-like web application
with tabs, navigation, bookmarks, and compatible
interactive websites displayed inside Feather.

## Existing features to preserve
- Dark, OLED, and light themes
- Accent colors and wallpapers
- Bookmarks and shortcuts
- Custom tabs and address bar
- Search engine selection
- Settings saved locally

## Architecture
- Feather browser interface
- Established web-proxy framework integration
- Service worker for supported navigation
- Compatible server-side transport
- Hosting that supports required connections

## Development stages
1. Preserve the v3 frontend
2. Set up a working development environment
3. Integrate and test the browsing engine
4. Connect Feather's tabs and navigation
5. Improve mobile and desktop layouts
6. Deploy and test

## Security
- Do not store passwords on the proxy server
- Do not log browsing content
- Do not expose an unrestricted public fetch endpoint
- Respect website access and authentication rules
