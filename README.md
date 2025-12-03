# WINDOWS - Interactive Prototype

An interactive web-based art installation exploring themes of voyeurism, surveillance, and the inversion of observation perspective.

## Concept

*"You think you are observing them"*

WINDOWS is a low-fidelity interactive experience that challenges the viewer's perception of who is the observer and who is being observed. Through a series of progressively unsettling interactions, users discover they are not the watchers, but the watched.

## Features

### Page 01 - Window Selection
- 6 interactive window slots in 4:3 format
- Hover effects to indicate interactivity
- Long press interaction to brighten windows
- Click to open individual room views

### Page 02 - Room Information
- Full-screen room view with atmospheric effects:
  - Flickering light simulation
  - Moving shadow animations
  - Noise overlay for surveillance aesthetic
  - Blurry figure that progressively approaches with each visit
- Navigation controls:
  - **Back**: Return to grid (darkens and distorts visited window)
  - **Zoom In**: Proceed to revelation

### Page 03 - Monitoring Reversal
- Dark interface revealing the truth
- REC indicator showing real-time recording
- Mouse tracking effect (your movements are followed)
- Revelation text: "They saw you."
- After 6-10 seconds, triggers final state

### Final State
- All windows transform to show shadowed figures
- Figures gaze toward the viewer
- The observed becomes the observer

## How to Use

1. **Open the prototype**: Simply open `index.html` in a modern web browser
2. **Select a window**: Click on any of the 6 windows
3. **Explore the room**: Observe the animations and approaching figure
4. **Zoom in**: Click "Zoom In" to proceed
5. **Experience the reversal**: Move your mouse and wait for the final revelation
6. **Return to see the truth**: All windows now reveal who was really watching

## Design Principles

- **Low-fidelity aesthetic**: Wireframe style with gray tones
- **Minimal UI**: Simple, stark interface elements
- **Progressive revelation**: Each interaction reveals more of the truth
- **Persistence**: Visited windows remain darkened, figure gets closer with each visit
- **Culmination**: Final state shows the complete inversion

## Technical Details

- Single HTML file (no dependencies)
- Vanilla JavaScript
- CSS animations and transitions
- Responsive design
- Works in all modern browsers

## Themes Explored

- **Voyeurism**: The impulse to observe others
- **Surveillance**: Who watches the watchers?
- **Power dynamics**: The shift from observer to observed
- **Privacy**: The illusion of anonymous observation
- **Digital monitoring**: Modern surveillance culture

## Installation

No installation required. Simply open `index.html` in your web browser.

For best experience:
- Use a desktop/laptop browser
- Full screen mode recommended
- Speakers optional (currently no audio, but can be added)

## Future Enhancements

Possible additions:
- Ambient sound design
- Additional room variations
- Multiple figure types
- Webcam integration for true mirror effect
- Save state across sessions
- Mobile-optimized version

---

*An interactive exploration of observation, privacy, and the digital gaze.*