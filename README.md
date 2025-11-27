# Strudel Music Training

A collection of interactive ear training and music theory exercises built with [Strudel](https://strudel.cc/), a live coding environment for music.

## What is this?

These exercises help you develop your musical ear by learning to recognize:
- **Intervals** - The distance between two notes
- **Major vs Minor Chords** - Understanding the emotional quality of chords
- **Chord Progressions** - Common patterns used in popular music
- **Scales** - The foundation of melody and harmony

## How to Use

### Option 1: Run in Strudel REPL (Recommended)

1. Visit [strudel.cc](https://strudel.cc/)
2. Open one of the exercise files from this repository
3. Copy the entire contents
4. Paste into the Strudel editor
5. Press `Ctrl+Enter` (or `Cmd+Enter` on Mac) to start playback

### Option 2: Navigate the Exercises

Each file contains multiple exercises. **Only one exercise is active at a time** (marked with `$:`).

To switch exercises:
1. Comment out the current active exercise by adding `//` before `$:`
2. Uncomment a different exercise by removing `//` from its `$:` line
3. Press `Ctrl+Enter` to hear the new exercise

**Example:**
```javascript
// This exercise is commented out (inactive)
// $: note("c d e f g a b")
//   .scale("C4:major")
//   .s("piano")

// This exercise is active
$: note("c e g")
  .scale("C4:major")
  .s("piano")
  .slow(3)
```

## Exercises

### 1. Interval Training (`interval_training.str`)
Learn to identify musical intervals from minor 2nd to octave. Each interval has cultural references to help you remember (e.g., Perfect 5th sounds like "Twinkle Twinkle").

### 2. Major vs Minor Chord Training (`major_minor_chord_training.str`)
Distinguish between major chords (bright/happy) and minor chords (dark/sad) in different keys.

### 3. Chord Progression Training (`chord_progression_training.str`)
Recognize common chord progressions used in popular music, including I-IV-V-I, I-V-vi-IV, ii-V-I, and more.

### 4. Major Scale Training (`major_scale_training.str`)
Practice recognizing the major scale pattern.

## Tips for Learning

1. **Start slow** - Don't rush through the exercises
2. **Use active listening** - Really focus on the sound qualities
3. **Sing along** - This helps internalize the intervals and patterns
4. **Practice regularly** - Short daily sessions are better than long infrequent ones
5. **Be patient** - Ear training takes time, but consistent practice pays off

## Strudel Controls

- `Ctrl+Enter` / `Cmd+Enter` - Start/restart playback
- `Ctrl+.` / `Cmd+.` - Stop playback
- Edit the code and press `Ctrl+Enter` to hear your changes immediately

## Learn More

- [Strudel Documentation](https://strudel.cc/learn)
- [Strudel Tutorial](https://strudel.cc/tutorial)
- [Strudel REPL](https://strudel.cc/)

## License

GNU General Public License v3.0 - See LICENSE file for details
