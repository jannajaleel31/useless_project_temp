<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# WhyClick!🎯


## Basic Details
### Team Name: DUOS


### Team Members
- Team Lead: Janna Jaleel - LBSITW 
- Member 2: Fathima Nasha C P - LBSTIW
  

### Project Description
A completely hands-free media player designed for peak laziness. Instead of touching a mouse or keyboard,  wave their hands to rewind and forward, and yell voice commands to manage the volume. It also includes an "Audio-Only" cloak mode when you just want to listen without the screen distracting you.

### The Problem (that doesn't exist)
Reaching across the desk to touch a keyboard or mouse while binge-watching videos causes unacceptable wrist fatigue, disrupts snacking efficiency, and demands far too much physical exertion from modern couch potatoes.

### The Solution (that nobody asked for)
We turned the user into a human remote control. By capturing audio frequencies and percussive transients through the laptop microphone, you can now wave your hands to the right of cam to skip forward, wave your hands to left of cam to re-watch a clip, and verbally order the player to adjust the volume.

## Technical Details
### Technologies/Components Used
For Software:
- **HTML5 & CSS3:** Semantic layout, custom UI components, responsive layout, CSS grid/flexbox, backdrop filters, and CSS keyframe animations (screen-shake and pulse effects).
- **Vanilla JavaScript (ES6+):** Core application architecture, DOM manipulation, state management, and real-time event handling with zero external runtime dependencies.
- **HTML5 Canvas API:** - Offscreen 64×48 canvas downsampling for fast pixel-difference extraction.
  - Transparent particle rendering overlay generating 60 FPS real-time motion trails ("Jedi Sparks").
- **MediaStreams API (`navigator.mediaDevices.getUserMedia`):** Captures raw video and high-sensitivity, uncompressed room audio streams from the user's webcam and microphone.
- **Computer Vision (Pixel Differencing & Spatial Masking):** Custom temporal frame-differencing algorithm calculating pixel brightness deltas across partitioned horizontal split-zones (Left Zone vs. Right Zone) for touchless gesture tracking.
- **Web Speech API (`SpeechRecognition` / `webkitSpeechRecognition`):** Low-latency voice engine featuring continuous listening, phonetic regex tokenization, alias matching, and a 1.2-second debounce mechanism to eliminate double-firing.
- **HTML5 Media Elements (`<video>` API) & Blob URLs:** Video playback control, volume scaling, dynamic scrubbing, and local file handling via `URL.createObjectURL` and memory management (`URL.revokeObjectURL`).


### Implementation
# Installation


# Run


### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

# Diagrams
![Workflow](Add your workflow/architecture diagram here)
*Add caption explaining your workflow*

For Hardware:

# Schematic & Circuit
![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

# Build Photos
![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- [Name 1]: [Specific contributions]
- [Name 2]: [Specific contributions]
- [Name 3]: [Specific contributions]

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



