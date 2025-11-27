# Agent Guidelines for Strudel Music Training

## Project Overview
Collection of Strudel music education exercises (.str files) for ear training and music theory.

## File Structure
- `.str` files: Strudel pattern files containing music exercises
- Each file focuses on a specific topic (intervals, chords, progressions, scales)

## Code Style
- **Language**: Strudel DSL (JavaScript-like syntax)
- **Comments**: Use `//` for educational explanations and instructions
- **Active code**: Only ONE exercise should be uncommented/active at a time (marked with `$:`)
- **Inactive code**: Comment out alternative exercises with `// $:` to allow users to activate them
- **Formatting**: Maintain consistent indentation and spacing for readability
- **Educational structure**: Include learning instructions, tips, and musical context in comments
- **Parameters**: Use descriptive parameter names like `.scale()`, `.s()`, `.slow()`, `.gain()`

## Development
- No build, test, or lint commands needed
- Files are executed directly in Strudel environment
- Manual testing via Strudel REPL/web interface

## License
GNU General Public License v3.0
