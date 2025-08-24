# AirConsole Website for Google TV

This is a complete AirConsole game website that works with Google TV and mobile devices as controllers.

## Features

- **TV Screen**: Optimized for Google TV with large text and touch-friendly interface
- **Mobile Controller**: Touch-based controller interface for smartphones
- **Real-time Communication**: Instant connection between TV and mobile devices
- **QR Code Integration**: Easy connection setup with QR code scanning
- **Responsive Design**: Works on various screen sizes and resolutions
- **Game Mechanics**: Simple movement and action-based gameplay

## How It Works

1. **TV Display**: The game runs on your Google TV or any large screen
2. **Mobile Controller**: Players use their smartphones as game controllers
3. **AirConsole Platform**: Handles the communication between devices
4. **QR Code**: Players scan a QR code to connect their phones to the TV

## Setup Instructions

### 1. Deploy the Website

You can deploy this website using any of these methods:

#### Option A: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload the `airconsole-website.html` file
3. Rename it to `index.html`
4. Enable GitHub Pages in repository settings
5. Your site will be available at `https://yourusername.github.io/repositoryname`

#### Option B: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `airconsole-website.html` file
3. Rename it to `index.html`
4. Your site will be deployed instantly

#### Option C: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Create a new project
3. Upload the files
4. Deploy automatically

### 2. Access on Google TV

#### Method A: Using Google TV Browser
1. Open the browser on your Google TV
2. Navigate to your deployed website URL
3. The TV interface will automatically load

#### Method B: Using Chromecast
1. Cast your browser tab to Chromecast
2. Navigate to your website
3. The game will display on your TV

#### Method C: Using Android TV Browser
1. Install a browser app on your Android TV
2. Navigate to your website
3. The game will load automatically

### 3. Connect Mobile Controllers

1. **On TV**: A QR code will appear on the screen
2. **On Mobile**: Open your phone's camera or QR scanner app
3. **Scan**: Scan the QR code displayed on the TV
4. **Connect**: Your phone will open the controller interface
5. **Play**: Start controlling the game!

## Game Controls

### Mobile Controller
- **D-Pad**: Move the player character around
- **A Button**: Action button (adds 10 points)
- **B Button**: Special action (adds 20 points)

### TV Display
- Shows the game state
- Displays connection status
- Shows player score
- Provides game instructions

## Technical Details

### AirConsole SDK
The website uses the official AirConsole SDK (version 1.7.0) for:
- Device communication
- Controller management
- Real-time messaging
- Connection handling

### Responsive Design
- **TV Mode**: Large text and buttons for TV viewing
- **Mobile Mode**: Touch-optimized controller interface
- **Auto-detection**: Automatically switches based on screen size

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Changing Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
    --primary-color: #74b9ff;
    --secondary-color: #e84393;
    --background-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Adding New Game Features
1. **New Controls**: Add buttons to the mobile controller
2. **Game Logic**: Modify the JavaScript game functions
3. **Visual Effects**: Add CSS animations and effects
4. **Scoring System**: Customize the scoring mechanics

### Multiplayer Support
The current version supports multiple controllers. To add multiplayer features:
1. Track individual player scores
2. Add player identification
3. Implement turn-based or simultaneous gameplay
4. Add player-specific visual elements

## Troubleshooting

### Common Issues

**QR Code Not Working**
- Ensure the website is deployed with HTTPS
- Check that the AirConsole SDK is loading properly
- Try refreshing the page

**Mobile Controller Not Connecting**
- Make sure both devices are on the same network
- Check that the QR code is clearly visible
- Try using the direct URL instead of QR code

**Game Not Responding**
- Check browser console for errors
- Ensure JavaScript is enabled
- Try a different browser

**Performance Issues**
- Close other browser tabs
- Check internet connection
- Try on a different device

### Debug Mode
Open browser developer tools (F12) to see:
- Connection status
- Error messages
- Device information
- Message logs

## Advanced Features

### Adding More Games
You can extend this template to create:
- Racing games
- Puzzle games
- Quiz games
- Drawing games
- Music games

### Integration with Other Platforms
- **Firebase**: For persistent data storage
- **WebRTC**: For direct peer-to-peer communication
- **WebGL**: For 3D graphics
- **Web Audio API**: For sound effects

## License

This project is open source and available under the MIT License.

## Support

For issues with:
- **AirConsole Platform**: Visit [airconsole.com](https://airconsole.com)
- **Google TV**: Check Google TV support documentation
- **Website Deployment**: Refer to your hosting provider's documentation

## Contributing

Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

---

**Enjoy your AirConsole game on Google TV!** 🎮📱📺
