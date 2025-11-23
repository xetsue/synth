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


## Instruments [ 179 Types ]
The following are instruments included inside the Workstation.

### Instrument Library 

### Piano
| ID | Instrument Name |
| :---: | :--- |
| 0 | Acoustic Grand Piano |
| 1 | Bright Acoustic Piano |
| 2 | Electric Grand Piano |
| 3 | Honky-tonk Piano |
| 4 | Electric Piano 1 |
| 5 | Electric Piano 2 |
| 6 | Harpsichord |
| 7 | Clavinet |

### Chromatic Percussion
| ID | Instrument Name |
| :---: | :--- |
| 8 | Celesta |
| 9 | Glockenspiel |
| 10 | Music Box |
| 11 | Vibraphone |
| 12 | Marimba |
| 13 | Xylophone |
| 14 | Tubular Bells |
| 15 | Dulcimer |

### Organ
| ID | Instrument Name |
| :---: | :--- |
| 16 | Drawbar Organ |
| 17 | Percussive Organ |
| 18 | Rock Organ |
| 19 | Church Organ |
| 20 | Reed Organ |
| 21 | Accordion |
| 22 | Harmonica |
| 23 | Tango Accordion |

### Guitar
| ID | Instrument Name |
| :---: | :--- |
| 24 | Acoustic Guitar (nylon) |
| 25 | Acoustic Guitar (steel) |
| 26 | Electric Guitar (jazz) |
| 27 | Electric Guitar (clean) |
| 28 | Electric Guitar (muted) |
| 29 | Overdriven Guitar |
| 30 | Distortion Guitar |
| 31 | Guitar Harmonics |

### Bass
| ID | Instrument Name |
| :---: | :--- |
| 32 | Acoustic Bass |
| 33 | Electric Bass (finger) |
| 34 | Electric Bass (pick) |
| 35 | Fretless Bass |
| 36 | Slap Bass 1 |
| 37 | Slap Bass 2 |
| 38 | Synth Bass 1 |
| 39 | Synth Bass 2 |

### Strings
| ID | Instrument Name |
| :---: | :--- |
| 40 | Violin |
| 41 | Viola |
| 42 | Cello |
| 43 | Contrabass |
| 44 | Tremolo Strings |
| 45 | Pizzicato Strings |
| 46 | Orchestral Harp |
| 47 | Timpani |

### Ensemble
| ID | Instrument Name |
| :---: | :--- |
| 48 | String Ensemble 1 |
| 49 | String Ensemble 2 |
| 50 | Synth Strings 1 |
| 51 | Synth Strings 2 |
| 52 | Choir Aahs |
| 53 | Voice Oohs |
| 54 | Synth Choir |
| 55 | Orchestra Hit |

### Brass
| ID | Instrument Name |
| :---: | :--- |
| 56 | Trumpet |
| 57 | Trombone |
| 58 | Tuba |
| 59 | Muted Trumpet |
| 60 | French Horn |
| 61 | Brass Section |
| 62 | Synth Brass 1 |
| 63 | Synth Brass 2 |

### Reed
| ID | Instrument Name |
| :---: | :--- |
| 64 | Soprano Sax |
| 65 | Alto Sax |
| 66 | Tenor Sax |
| 67 | Baritone Sax |
| 68 | Oboe |
| 69 | English Horn |
| 70 | Bassoon |
| 71 | Clarinet |

### Pipe
| ID | Instrument Name |
| :---: | :--- |
| 72 | Piccolo |
| 73 | Flute |
| 74 | Recorder |
| 75 | Pan Flute |
| 76 | Blown bottle |
| 77 | Shakuhachi |
| 78 | Whistle |
| 79 | Ocarina |

### Synth Lead
| ID | Instrument Name |
| :---: | :--- |
| 80 | Lead 1 (square) |
| 81 | Lead 2 (sawtooth) |
| 82 | Lead 3 (calliope) |
| 83 | Lead 4 (chiff) |
| 84 | Lead 5 (charang) |
| 85 | Lead 6 (voice) |
| 86 | Lead 7 (fifths) |
| 87 | Lead 8 (bass + lead) |

### Synth Pad
| ID | Instrument Name |
| :---: | :--- |
| 88 | Pad 1 (new age) |
| 89 | Pad 2 (warm) |
| 90 | Pad 3 (polysynth) |
| 91 | Pad 4 (choir) |
| 92 | Pad 5 (bowed) |
| 93 | Pad 6 (metallic) |
| 94 | Pad 7 (halo) |
| 95 | Pad 8 (sweep) |

### Synth Effects
| ID | Instrument Name |
| :---: | :--- |
| 96 | FX 1 (rain) |
| 97 | FX 2 (soundtrack) |
| 98 | FX 3 (crystal) |
| 99 | FX 4 (atmosphere) |
| 100 | FX 5 (brightness) |
| 101 | FX 6 (goblins) |
| 102 | FX 7 (echoes) |
| 103 | FX 8 (sci-fi) |

### Ethnic
| ID | Instrument Name |
| :---: | :--- |
| 104 | Sitar |
| 105 | Banjo |
| 106 | Shamisen |
| 107 | Koto |
| 108 | Kalimba |
| 109 | Bagpipe |
| 110 | Fiddle |
| 111 | Shanai |

### Percussive (Melodic)
| ID | Instrument Name |
| :---: | :--- |
| 112 | Tinkle Bell |
| 113 | Agogo |
| 114 | Steel Drums |
| 115 | Woodblock |
| 116 | Taiko Drum |
| 117 | Melodic Tom |
| 118 | Synth Drum |
| 119 | Reverse Cymbal |

### Sound Effects
| ID | Instrument Name |
| :---: | :--- |
| 120 | Guitar Fret Noise |
| 121 | Breath Noise |
| 122 | Seashore |
| 123 | Bird Tweet |
| 124 | Telephone Ring |
| 125 | Helicopter |
| 126 | Applause |
| 127 | Gunshot |

### Drum Kit
| ID | Instrument Name |
| :---: | :--- |
| 35 | Bass Drum 2 |
| 36 | Bass Drum 1 |
| 37 | Side Stick |
| 38 | Snare Drum 1 |
| 39 | Hand Clap |
| 40 | Snare Drum 2 |
| 41 | Low Tom 2 |
| 42 | Closed Hi-hat |
| 43 | Low Tom 1 |
| 44 | Pedal Hi-hat |
| 45 | Mid Tom 2 |
| 46 | Open Hi-hat |
| 47 | Mid Tom 1 |
| 48 | High Tom 2 |
| 49 | Crash Cymbal 1 |
| 50 | High Tom 1 |
| 51 | Ride Cymbal 1 |
| 52 | Chinese Cymbal |
| 53 | Ride Bell |
| 54 | Tambourine |
| 55 | Splash Cymbal |
| 56 | Cowbell |
| 57 | Crash Cymbal 2 |
| 58 | Vibra Slap |
| 59 | Ride Cymbal 2 |
| 60 | High Bongo |
| 61 | Low Bongo |
| 62 | Mute High Conga |
| 63 | Open High Conga |
| 64 | Low Conga |
| 65 | High Timbale |
| 66 | Low Timbale |
| 67 | High Agogo |
| 68 | Low Agogo |
| 69 | Cabasa |
| 70 | Maracas |
| 71 | Short Whistle |
| 72 | Long Whistle |
| 73 | Short Guiro |
| 74 | Long Guiro |
| 75 | Claves |
| 76 | High Wood Block |
| 77 | Low Wood Block |
| 78 | Mute Cuica |
| 79 | Open Cuica |
| 80 | Mute Triangle |
| 81 | Open Triangle |

### Legacy
These are appended inside the code acting as a failsafe alternative incase the import from `WebAudioFont.js` fails, legacy here are built-in into the `.html` so if other categories fail, this one should remain available in most cases.
| ID | Instrument Name |
| :---: | :--- |
| piano | Piano |
| bell | Bell |
| pad | Pad |
| 8bit | 8-bit |




## Notice / Milestone
> Audio trimming

> Watermarking -- HEX Lines

> .OGG metadatas
