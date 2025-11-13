# Overhead Prayer Resizer
A RuneLite plugin that resizes overhead prayer icons using adjustable scale settings and size limits.

## Features
- Adjustable scaling for overhead prayer icons  
- Minimum and maximum size clamps to prevent extreme scaling  
- Optional toggles for enabling or disabling resizing  
- Clean, lightweight overlay implementation  
- Automatic icon offsetting to maintain correct on-screen positioning after scaling  

## How It Works
The plugin intercepts overhead prayer sprites, applies the configured scale factor, clamps the final size within defined limits, and redraws the resized icon using a custom overlay. Offsetting logic ensures that resized icons remain correctly aligned above the target.

## Installation
1. Clone or download this repository.  
2. Open the project in IntelliJ with the RuneLite plugin development environment configured.  
3. Build and run using the RuneLite dev client.  
4. Enable **Overhead Prayer Resizer** in the RuneLite plugin list.

## Configuration
All scaling, limits, and enable/disable options can be adjusted from the RuneLite plugin panel.
