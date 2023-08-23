# PostCall for Call Center - Transcription and Subtitling Tool

PostCall is a user-friendly tool designed to transcribe audio and video files from call center recordings, with the option to add subtitles to the resulting transcription. This tool is built using Python and leverages the Whisper ASR (Automatic Speech Recognition) library for accurate and efficient transcription.

## Features

- Transcribe audio and video files from call center recordings.
- Option to automatically detect the spoken language.
- Choose from different model sizes for transcription accuracy.
- Generate transcriptions and add subtitles to the video.
- Save transcriptions in various formats, including SRT, TXT, VTT, TSV, JSON, and more.
- Intuitive user interface with customizable themes.

## Requirements

- Python 3.x
- Whisper ASR library (`whisper`): Install using `pip install whisper-asr`
- FFmpeg: Required for subtitle addition to video files. You can download FFmpeg from [here](https://ffmpeg.org/download.html).

## Installation

1. Clone or download this repository to your local machine.
2. Install the Whisper ASR library using `pip`:

   ```
   pip install whisper-asr
   ```

3. Download and install FFmpeg from the [official website](https://ffmpeg.org/download.html).

## Usage

1. Run the script by executing `python postcall_tool.py` in the terminal.
2. The GUI application will open, allowing you to configure settings and upload audio/video files.
3. Choose the model size, language, task (transcription or translation), and device (CPU or GPU).
4. Click the "Upload Audio/Video" button to select the file you want to transcribe.
5. Click the "Start" button to begin the transcription process.
6. Once the transcription is complete, view and save the results in various formats.

## Adding Subtitles to Video

1. After transcribing a video file, click the "Add Subtitle to Video" button.
2. Choose where you want to save the subtitle file and specify the filename.
3. The tool will automatically add the generated subtitle to the video file.

## Saving Transcriptions

1. After transcription, click the "Save" button to export the transcription results.
2. Choose the desired format (SRT, TXT, VTT, TSV, JSON, etc.).
3. Specify the location and filename for the exported transcription.

## Themes

PostCall supports different themes:
- System
- Dark
- Light

You can change the theme using the "Theme" dropdown menu in the top right corner of the application.

## Contributing

Contributions to this project are welcome. Feel free to open issues, suggest improvements, or submit pull requests.

## Credits

This tool was created by Tony Esposito.

## License

This project is licensed under the [MIT License](LICENSE).
