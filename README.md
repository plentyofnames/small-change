# Small Change

A small browser-based **Web MIDI** app that sends **Program Change**
messages: small change, in other words. Sibling of
[Sea Change](https://github.com/plentyofnames/sea-change), its Proteus 2000
specific big sibling.

▶︎ **Live app:** https://plentyofnames.github.io/small-change/

Pick a MIDI output and channel, click a numbered button, and the program
change goes out. Works with anything that responds to program changes.

## Features

- **MIDI output picker** that follows devices as they're plugged in and
  unplugged.
- **Channel 1–16.**
- **1–128 program buttons** (set how many you need), with the last one sent
  highlighted.
- Optional **Bank Select** before each program change: MSB (CC 0), plus LSB
  (CC 32) if your gear wants it.
- One self-contained `index.html`: no build step, no dependencies.

## Requirements

- A **Web MIDI–capable browser**: Chrome/Chromium-based (Chrome, Edge,
  Opera, Brave), or Firefox 108+. Safari has no Web MIDI. No SysEx
  permission is needed.

## License

MIT
