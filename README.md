# Digit Span

A single-page short-term memory trainer. A sequence of digits is shown together for a few seconds, then you type it back from memory using the keyboard or the on-screen keypad.

**Live app:** https://jpolache.github.io/STM/

## How it works

- Rounds start at a span of 2 digits, with no two consecutive digits repeating.
- Get it right and the next round adds a digit.
- Get it wrong and the next round drops a digit (minimum of 1).
- Your longest correct span is saved as a personal best in the browser's local storage.
- **Restart** resets the current run back to a span of 2 at any time.

## Running locally

No build step or dependencies — just open [index.html](index.html) in a browser.

## Deployment

The `main` branch is published via GitHub Pages from the repo root, so pushes to `main` redeploy the live site automatically.
