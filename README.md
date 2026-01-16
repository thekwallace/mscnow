# MSCNow

**MSCNow** is a streamlined macOS utility for quickly generating and sending MIDI Show Control (MSC) GO cues. Designed for live production workflows, it provides a wizard-style interface for rapid cue creation.

## Features

- **Wizard-Style UI** - Step through cuelist selection, cue entry, and confirmation in a clean, focused interface
- **Smart Cue Entry** - Enter single cues, comma-separated lists, or sequential ranges (e.g., `1-10`)
- **Live MIDI Output** - Send cues directly to any MIDI device with configurable delays
- **Export to MIDI File** - Generate standard MIDI files with Pro Tools compatibility
- **Quick Open** - Create temporary MIDI files and open them directly in your DAW
- **Device ID & Command Format** - Configure MSC device ID and command format (all/lighting/sound)

## System Requirements

- macOS 14.0 (Sonoma) or later
- Apple Silicon or Intel Mac

## Installation

1. Download the latest DMG from [Releases](https://github.com/thekwallace/mscnow/releases)
2. Open the DMG and drag MSCNow to your Applications folder
3. Launch MSCNow

## Usage

1. **Enter Cuelist** - Specify which cuelist the cues belong to
2. **Enter Cues** - Type cue numbers as:
   - Single cue: `5`
   - List: `1, 5, 10`
   - Range: `1-20`
3. **Confirm & Send** - Choose to:
   - **Send Live** - Transmit cues via MIDI output
   - **Open** - Create temp file and open in default app
   - **Export** - Save as a MIDI file

### Options

- **Single Cue Mode** - When enabled, generates individual GO commands instead of sequential
- **Include GO_OFF** - Adds a release cue at the end of the sequence

## Settings

Access settings via the gear icon to configure:
- **MIDI Output Device** - Select destination for live output
- **Device ID** - MSC device ID (0-127, or All Call)
- **Command Format** - Lighting, Sound, Machinery, etc.
- **Delay Between Cues** - Timing for live output sequences
- **Auto GO_OFF** - Automatically enable GO_OFF for certain input types

## Support

For help and support, visit our [Support Page](https://thekwallace.github.io/mscnow/support).

## License

Copyright 2025-2026 kwallace.com LLC. All rights reserved.
