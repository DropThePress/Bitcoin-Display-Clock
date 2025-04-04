# Bitcoin Price Display Clock

Turn any old mobile phone into a dedicated Bitcoin price display! This single HTML file connects to multiple price APIs (with automatic failover between 10 sources) to show the current BTC price as large as possible on your screen.

![Bitcoin Price Display Screenshot](screenshots/display.jpg)

## Features

- **Giant Price Display**: Shows the Bitcoin price as large as possible on your screen
- **Multiple APIs**: Connects to 10 different price sources
- **Automatic Failover**: If one API fails, it switches to the next automatically
- **Dynamic Update Frequency**: Uses the fastest API available (as quick as 1-second updates)
- **Auto-scaling**: Adapts to any screen size or orientation
- **Fullscreen Mode**: Tap anywhere to toggle fullscreen

## How to Use

1. Download the [bitcoin-display.html](bitcoin-display.html) file
2. Open it in any web browser on your phone
3. Tap the screen to go fullscreen
4. Keep your device plugged in for a permanent display

## Screenshot

![Bitcoin Display in Action](screenshots/in-use.jpg)

## API Sources

The display uses these price sources (in order of priority):
- Binance (1 second updates)
- Coinbase (5 second updates)
- Bitstamp (5 second updates)
- And 7 more backup sources

## License

This project is free to use and modify.
