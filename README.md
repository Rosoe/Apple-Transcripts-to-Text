# Apple Podcast Transcript Converter 🎙️ → 📝

Convert Apple Podcast TTML transcripts into clean, readable text with this browser-based tool. Extract and process podcast transcripts stored locally on your MacOS device with ease.

## Why This Tool Exists

As someone who regularly takes notes on podcasts using Zotero, I noticed a significant limitation in Apple's podcast transcript system. While Apple invests computational resources in generating high-quality transcripts using Language Learning Models (LLMs), they restrict users from copying more than 200 words at a time (as of 12/02/2025). This limitation creates several issues:

- Forces users to either manually copy small sections or reprocess entire episodes through speech-to-text LLMs
- Creates unnecessary environmental impact by requiring redundant AI processing
- Makes academic and research work unnecessarily cumbersome
- Limits accessibility and practical use of already-generated transcripts

This tool solves these problems by:

- Providing free (as in freedom and cost) access to already-processed transcripts
- Eliminating the need for redundant AI processing
- Making transcript extraction accessible to non-technical users
- Maintaining complete privacy through local-only processing
- Offering full transparency with open-source code

## Features

- 🔄 Convert TTML (Timed Text Markup Language) files to plain text
- 👥 Preserve speaker identification and labeling
- ⏱️ Maintain timestamp information in [MM:SS] format
- 💻 100% browser-based processing - no data sent to servers
- ⬇️ Download converted transcripts as text files
- 🔒 Privacy-focused: all processing happens locally

## How to Use

1. Download the [index.html](https://github.com/Rosoe/Apple-Transcripts-to-Text/blob/main/index.html) file and open it in your browser of choice.
2. Open the episode in the MacOS Podcasts app and click 'Transcript' (or ··· > 'View Transcript')
3. Access the transcript file:
   - Open Finder
   - Press `Cmd+Shift+G` or select 'Go' > 'Go to Folder'
   - Enter: `~/Library/Group Containers/243LU875E5.groups.com.apple.podcasts`
4. Navigate through the TTML folder to find your transcript
5. Copy the entire .ttml file contents
6. Paste into the converter and click "Convert Text"
7. Download or copy your formatted transcript

## Technical Details

- Built with vanilla JavaScript for maximum compatibility
- Uses the native DOMParser for XML processing
- Implements intelligent speaker tracking and formatting
- Preserves sentence structure and word spacing
- Handles complex TTML attributes and timing information

## Why Use This Tool?

Apple Podcasts stores transcripts in TTML format, which isn't easily readable. This converter transforms complex XML markup into clean text while maintaining important features like:

- Speaker identification
- Accurate timestamps
- Natural sentence formatting
- Proper paragraph breaks

Perfect for:
- Content creators
- Podcast producers
- Researchers
- Students
- Anyone needing accessible podcast transcripts

## Privacy & Security

This tool runs entirely in your browser. No data is ever sent to external servers, making it safe for processing sensitive or confidential content.

## Contributing

Found a bug or want to contribute? Open an issue or submit a pull request on GitHub. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Keywords: Apple Podcasts, transcript converter, TTML to text, podcast transcription, MacOS podcast tools, XML transcript converter, podcast accessibility, local transcript processing, Apple podcast transcripts
