---
# the default layout is 'page'
icon: fas fa-gear
order: 5
---

Trucaption settings can be modified via the "Settings" button in the editor window.

## Transcription Engine

- Engine
  - Browser Native (free, uses built-in speech recognition, requries browser support)
  - [Azure Speech Services](/azure/) (paid service)
  - [Speechly](/speechly) (paid service)

## Translation Settings

Currently, the only supported translation engine is Google Cloud Translate.

- **API Key**: API Key from Google Cloud configuration.
- **Translate interim transcripts**: Display translations of interim transcripts. Note: this will significantly increase translation API usage.
- **Languages**: Select languages for translation

## Display Settings

- **Maximum Lines**: adjusts the number of lines that are displayed on the editor and viewer screens. This can be useful to improve performance when running Trucaption for a long time. Set to -1 to keep all lines in the window.
- **Default Font Size**: changes the default font size selected when the editor or viewer windows are opened.
- **Clear temporary transcript on stop**: When enabled, interim transcripts are erased when "Stop Listening" is pressed. When disabled, interim transcripts are converted to final transcripts and can then be edited. (For more information on final vs. interim transcripts, see [this article](/final-vs-interim/)).
- **Display text in all caps**: Show captions in all caps instead of case provided by translation engine.
