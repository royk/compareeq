# Static EQ Curve Comparator

A web-based tool for comparing and analyzing audio tracks using frequency analysis and AI-powered mixing advice.

## Features

- **Audio Comparison**: Upload and compare two audio tracks side by side
- **Waveform Visualization**: View and interact with audio waveforms
- **Frequency Analysis**: Generate detailed EQ curve comparisons
- **AI-Powered Mixing Advice**: Get mixing recommendations using OpenAI's GPT-4
- **Interactive Controls**: 
  - Zoom in/out functionality
  - Adjustable analysis length
  - Playback controls for both tracks
  - Custom context input for more specific advice

## Usage

1. Open `index.html` in a modern web browser
2. Upload your audio track and a reference track
3. Use the waveform controls to select and analyze specific sections
4. Adjust the analysis length as needed
5. View the EQ curve comparison chart
6. (Optional) Enter your OpenAI API key and additional context to get AI-powered mixing advice

## Requirements

- Modern web browser with JavaScript enabled
- Audio files in a supported format (MP3, WAV, etc.)
- OpenAI API key (optional, for mixing advice feature)

## Technical Details

The application uses:
- Chart.js for visualization
- Web Audio API for audio processing
- OpenAI's GPT-4 for AI-powered mixing advice

## Privacy

- All audio processing is done locally in your browser
- When using the AI advice feature, your audio analysis data is sent to OpenAI's servers
- Your OpenAI API key is only used for the AI advice feature and is not stored

## License

This project is open source and available under the MIT License.
