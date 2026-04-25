# Trigoban

A small puzzle game inspired by Sokoban - but played on a triangular grid.

Play it here: https://lexeko.github.io/trigoban/

## What is this?

Trigoban takes the classic "push the boxes onto targets" idea and twists it just enough to feel new.

Instead of a square grid, everything happens on alternating triangles. That small change makes movement feel different in a surprising way:

- besides up/down, there are also angled movements
- what looks like a straight push often becomes a zig-zag
- some situations become orientation challenges instead of simple path finding

It's simple to learn, but quickly becomes a spatial puzzle.

## How to play

- Move the player around the board
- Push boxes onto all target tiles
- You can only push one box at a time
- You cannot pull boxes

Controls:
- Arrow keys or QWEADZXC. Latter also cover diagonal movements.
- Press Space to show movement hints for 5 seconds.
- Hover the worker to show movement hints while hovering.

Tip:
What looks like a straight path often isn't - think in diagonals. When a move would push a box, hints show a translucent preview of where that box will land.

## Why triangles?

The triangular grid removes the symmetry you're used to in Sokoban.

That leads to:
- zig-zag movement instead of straight lines
- direction-dependent pushes
- new types of deadlocks
- puzzles that feel familiar but behave differently

No extra mechanics - just different geometry.

## Project goals

- Keep the rules minimal and clean
- Let the grid itself create the challenge
- Explore new puzzle patterns without adding complexity

## Tech

- Single HTML file
- Vanilla JavaScript
- SVG rendering
- LocalStorage for saving progress

No frameworks, no build step - just open and play.

## Saving

Your progress is saved automatically in your browser:
- current level
- solved levels
- move counts

Refresh the page and you'll continue where you left off.

## License

Copyright (c) 2026 Alexey Konoplev

This project is licensed under the MIT License.

You are free to use, modify, and distribute this code, including for commercial purposes, as long as you include the original copyright and license notice.

## Notes

This is an experimental puzzle system.
If you enjoy it, or if something feels confusing or broken, that's valuable feedback.
