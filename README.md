# Digital Audio Workstation Lite, Synthesizer and Audio Editor

## ./SYNTH
Primary feature: Audio synthesizer oscilloscope inspired test in browser without using any audio file or third party softwares.

Uses local Browser / Web Audio API to synthesize digital sound effects with options.

> Export supports  `.mp3` `.wav` `.ogg`

#### `[Modes]` — Clicking the page header switches between Synthesizer and Editor. 

`⏏` Eject button to leave Editor mode.

`⌘` To switch visualizer types.

`月` Switch Themes.

`E` Export and download edited file.

#### `[Load Files]` — Click on visualizer display panel ( Drag and drop is also supported ) 

## ./EDITOR
Usage: Tap Display Visualizer / Drag and drop files to the visualizer to load any audio files.

> **Update Patches**

Importing now supports all media types as long as audio codec is present such as `.mp4` `.mp3` etc.

> `[!]` Metadata edits are saved for `.mp3` exports only. 


### Edits `.mp3` and `.wav`
- Tags / Metadata
- Effects (Reverb/Dostrtions)
- Equalizer low-focal-mid-high-highes
- Converts to [ `.mp3` `.wav` `.ogg` ]

><img width="1902" height="980" alt="image" src="https://github.com/user-attachments/assets/50669351-f73a-4b1d-9707-29266bda6bb7" />
><img width="1899" height="984" alt="image" src="https://github.com/user-attachments/assets/322588b9-4483-4cb8-aed1-236219dccf50" />
><img width="1898" height="980" alt="image" src="https://github.com/user-attachments/assets/536dda86-227d-41e0-b80b-4b33e5f3c64a" />
><img width="1896" height="983" alt="image" src="https://github.com/user-attachments/assets/8f0453e1-286e-4e0d-b682-947617c0797e" />
><img width="1896" height="983" alt="image" src="https://github.com/user-attachments/assets/cd9bd3f1-d246-4159-b98d-605157056fc1" />
><img width="1881" height="924" alt="image" src="https://github.com/user-attachments/assets/6245e068-1585-4a93-9ce4-4b079538d5db" />
><img width="1896" height="925" alt="image" src="https://github.com/user-attachments/assets/a0ce806e-a241-4378-9bc3-0bf9906e0f14" />
><img width="1893" height="922" alt="image" src="https://github.com/user-attachments/assets/4720b345-6384-4fc6-89b9-9754cf1c99f3" />
><img width="1887" height="907" alt="image" src="https://github.com/user-attachments/assets/1500ebc0-2390-4e2e-8060-8fb9a6ab59a0" />
><img width="1882" height="922" alt="image" src="https://github.com/user-attachments/assets/91fe847c-45ed-4f42-be87-e2f8521f0bf8" />
><img width="1406" height="845" alt="image" src="https://github.com/user-attachments/assets/e644100b-c893-42e0-984e-472ebe0c3a70" />

## ./WORKSTATION
Usage: A lightweight Digital Audio Workstation (DAW) environment for sequencing tracks.
This was achieved with [WebAudioFont](https://github.com/surikov/webaudiofont) 
The audio synthesizer is a demonstration which uses sample-based synthesis to play musical instruments in the browser with purely codes without any audio files.

> **Features**

- Multi-track sequencing with Piano Roll interface.
- Support for Samples (imported from Editor), Legacy Synths, and WebAudioFont Instruments.
- Per-track Effects (Distortion, Reverb, EQ).
- Global Project settings (BPM, Duration, Snap).
- Export full mix to `.wav`, `.mp3`, and `.ogg`.

> **Controls**

`Keys` Toggle mobile/virtual keyboard.
`♫/✥` Switch between Draw Mode (add notes) and Lasso Mode (select multiple).
`REC` Real-time MIDI recording via keyboard or touch.
`Undo/Redo` History state management.

### ./Requirements are included by default.

## Usage
### WEB-APP
[https://xetsue.github.io/synth/](https://xetsue.github.io/synth/)
- The web app runs locally on your browsers, no data collection are made. Your privacy is secured.
- You can use the "E" to export your file as .json playlist to quickly load the same project back onto the web-app. This app does not have an autosave so make sure to always save when neccessary.
- There is a dedicated UNDO and REDO button when needed, this is also true for LOCAL-APP.

### LOCAL-APP
Download from [Here](https://github.com/xetsue/synth/archive/refs/heads/main.zip)
Extract the `.zip` file anywhere on your device.
Open the index.html in any browser and starts using the app.

## Compatibility
- This code is purely HTML, so the only requirement is any web browser to open up the frontend UI. 
- There is no third party requirements set and needed for this to be possible. 
- This code does not need Internet Connection to run. It can natively run OFFLINE completely.

## Notice / Milestone
> Audio trimming

> Watermarking (WIP)

> .OGG metadatas
