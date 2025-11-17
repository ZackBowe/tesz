# Youware Project Documentation

## Project Overview
This is an interactive birthday greeting website with smooth slide navigation functionality. The project combines romantic content with engaging user interactions through multiple slides and choice-based navigation.

## Key Features
- **Interactive Slide System**: 8 different slides with smooth transitions and animations
- **Choice-based Navigation**: Users can make decisions that affect the flow (envelope opening choice)
- **Animated Elements**: Floating clouds, bouncing emojis, wiggling characters
- **Responsive Design**: Mobile-friendly layout with gradient backgrounds
- **Clickable Characters**: Interactive Pompompurin and cloud images with rotation effects

## Architecture
- **Single Page Application**: All slides contained in one HTML file
- **CSS Animations**: Keyframe animations for floating, bouncing, and wiggling effects
- **JavaScript Navigation**: Slide management with showSlide(), nextSlide(), and choice functions
- **CDN Assets**: Images hosted on Youware CDN for fast loading

## Content Structure
1. **Title Slide**: Introduction with animated kawaii clouds and Pompompurin characters
2. **Memories Slide**: Grid layout for photo placeholders
3. **Music Slide**: Audio player section with song information
4. **Choice Slide**: Interactive envelope with "Open it" or "No ty" options
5. **Crying Slide**: Fallback slide if user chooses "No ty"
6. **Birthday Message**: Main heartfelt birthday message
7. **Special Message**: Romantic confession and LDR message
8. **Final Slide**: Closing with date and "Start Over" option

## Interactive Elements
- **Next Buttons**: Primary navigation with gradient styling and hover effects
- **Choice Buttons**: Branching navigation for envelope interaction
- **Clickable Images**: Characters spin and scale when clicked
- **Smooth Transitions**: CSS animations for slide appearances

## Styling
- **Color Scheme**: Pink gradient theme (#ff9a9e to #fecfef)
- **Typography**: Arial font family with various sizes for hierarchy
- **Layout**: Flexbox and Grid layouts for responsive design
- **Animations**: CSS keyframes for floating, bouncing, wiggling, and slide transitions

## Development Notes
- All animations use CSS keyframes for smooth performance
- Images are loaded from Youware CDN with proper alt attributes
- Mobile responsive with media queries for smaller screens
- No external dependencies - pure HTML, CSS, and JavaScript
