# Arkyn

kyn's personal website, hosted on GitHub Pages. A single `index.html`, plus a
`404.html` in the same style.

It has a scroll-driven 3D flower at the bottom, a JA / EN toggle, and an
anonymous message box (messages are stored in Firebase Firestore and can only be
read from the Firebase console).

## Credits

- **Spider lily**: from [cupidbity/spiderlily](https://github.com/cupidbity/spiderlily)
  by cupidbity, an interactive spider lily built with Three.js and MediaPipe
  hand tracking.

## Built with

- [Three.js](https://threejs.org/) and [anime.js](https://animejs.com/) for the flower
- [MediaPipe Tasks Vision](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) for the optional hand-tracking "manual mode"
- [Lenis](https://lenis.darkroom.engineering/) for smooth scrolling
- [Firebase Firestore](https://firebase.google.com/docs/firestore) for the message box
- [EB Garamond](https://fonts.google.com/specimen/EB+Garamond) and [Noto Serif JP](https://fonts.google.com/noto/specimen/Noto+Serif+JP) from Google Fonts
