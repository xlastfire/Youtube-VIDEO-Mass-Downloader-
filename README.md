# YouTube Video Downloader

## Description

A command-line tool to download high-quality YouTube videos from single videos, playlists, or channels. This tool utilizes `yt-dlp` for video downloading and `ffmpeg` for video merging. It also features a multi-threaded download process with a sleek terminal interface, providing a progress bar and clean user experience.

### Features:
- Download videos from single video URLs, playlists, or YouTube channels.
- Retrieves the highest quality video and audio streams.
- Merges video and audio to MP4 format using `ffmpeg`.
- Supports multi-threaded downloading for fast and efficient video downloads.
- Clean and user-friendly interface with progress bars.
- Option to customize the save location for downloaded videos.

## Requirements
- Python 3.6+
- `yt-dlp`
- `ffmpeg`
- `tqdm`
- `colorama`
- `pyfiglet`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/youtube-video-downloader.git
   cd youtube-video-downloader
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Make sure you have `ffmpeg` installed and accessible in your system's PATH.

4. Download and install `yt-dlp` and `colorama`:

   ```bash
   pip install yt-dlp colorama
   ```

### Usage

1. Run the script:

   ```bash
   python youtube_video_downloader.py
   ```

2. You will be prompted to input:
   - The YouTube video, playlist, or channel URL.
   - The directory name where the videos will be saved (optional).

3. The program will fetch the video URLs and start downloading them in the highest available quality to the specified directory.

4. Once the download is complete, you'll see a message indicating success.

### Example:

```bash
Video/Playlist/Channel URL: https://www.youtube.com/playlist?list=PLxKrR3VjggMv5oYFeOBtQzPimH8mMlhzI
Directory Name: My_Videos
```

### Notes:
- If downloading a playlist or channel, the program will download videos for all entries.
- Ensure that `ffmpeg.exe` is installed and its path is correctly set in the script (`FFMPEG_PATH`).

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgements
- Thanks to [yt-dlp](https://github.com/yt-dlp/yt-dlp) for the video downloading functionality.
- Thanks to [ffmpeg](https://ffmpeg.org/) for video and audio merging.
- Thanks to [pyfiglet](https://github.com/pwaller/pyfiglet) for the banner text.
```
