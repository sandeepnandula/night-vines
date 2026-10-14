# 🌠 Night Vines

Draw vines across the night sky. Falling stars play them as music.

**[▶ Play it live](https://sandeepnandula.github.io/night-vines/)**

Night Vines is a small musical toy that runs in your browser. Draw glowing vines with your finger or mouse, and every star that lands on one plays a note. Stars can bounce from vine to vine, so a single star can play a whole little melody. You don't need any musical skill, because every note is always in key.

It works on phones, tablets and computers, with nothing to install.

## How to play

1. Open the [live site](https://sandeepnandula.github.io/night-vines/) and tap **Start**.
2. Draw a vine anywhere on the sky.
3. Watch the stars fall. When one hits a vine, it plays a note and the vine lights up.
4. Tap an empty spot in the sky to drop a star from there.

Notes get higher from left to right across the screen, so where you draw changes the melody.

## Features

- **Four instruments:** Harp, Bell, Marimba and Kalimba. Each vine keeps the sound it was drawn with, so you can mix them.
- **Three moods:** Calm, Dreamy and Wonder each use a different musical scale.
- **Bounce:** stars bounce off vines and arc to the next one, up to 5 times, getting softer each time. It's on by default.
- **Stars and Speed sliders:** set how many stars fall and how fast they move, from slow motion to double speed.
- **Star shower:** drops a burst of stars at once.
- **Loop recorder:** record up to 30 seconds of play, and it repeats as a loop while you keep playing on top.
- **Saved garden:** your vines and settings are kept in your browser, so they're still there when you come back.
- **Hide controls:** clears the screen for a clean view.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `S` | Star shower |
| `R` | Start or stop recording a loop |
| `B` | Turn bounce on or off |
| `Z` | Undo the last vine |

## Tips

- Draw short, cupped vines like little bowls, and bouncing stars will ping back and forth inside them.
- Stack vines in different instruments at different heights for chain reactions.
- Try slow speed with the Dreamy mood for a calm, floating sound.
- On iPhone and iPad, turn off the silent switch to hear sound.

## How it's built

Night Vines is one `index.html` file with plain HTML, CSS and JavaScript. There are no frameworks and no build step.

- Graphics are drawn on an HTML canvas.
- Sounds are generated live with the Web Audio API, so there are no audio files.
- Your garden is saved with `localStorage`, which stays on your own device.

### Run it yourself

Download `index.html` and open it in any modern browser. That's it.

## Inspiration

Inspired by *Falling Stars*, a 2011 iPad and iPhone "digital toy" app from Trident Vitality, where you drew vines and falling stars turned them into music. That app is no longer available, so Night Vines is a fresh take on the idea, built for the web.

## License

MIT License. Feel free to use, change and share it.
