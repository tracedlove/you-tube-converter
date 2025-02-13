YouTube Video Converter Engine - README
=======================================

Overview:
---------
This script is a YouTube video converter engine that allows you to download and convert YouTube videos to various formats such as MP3, MP4, WEBM, and more. It also provides options for batch processing, playlist downloading, and the ability to customize download locations and formats.

Features:
---------
- Convert YouTube videos to MP3, MP4, or WEBM formats.
- Convert multiple files at once via a list of URLs.
- Download entire YouTube playlists.
- Customize download location and output format.
- View logs for general, success, and error messages.

Requirements:
-------------
- **yt-dlp**: The script uses **yt-dlp** to download and convert YouTube videos.
  - You can install **yt-dlp** using Python:
    ```bash
    pip install yt-dlp
    ```
  - Alternatively, you can download the **yt-dlp** binary from [GitHub Releases](https://github.com/yt-dlp/yt-dlp/releases).

Setup Instructions:
-------------------
1. **Install yt-dlp**:
   - Ensure **yt-dlp** is installed or placed in the same directory as the script.
   - You can install it via Python with:
     ```bash
     pip install yt-dlp
     ```

2. **Run the Script**:
   - Double-click the `converter.bat` file to launch the YouTube Video Converter Engine.
   - The script will automatically create necessary directories for logs, converted files, and history.

3. **Choose an Option**:
   - Upon starting the script, you'll be presented with a menu to choose the desired conversion option (e.g., MP3, MP4, WEBM).
   - Follow the prompts to enter the YouTube URL and choose any additional settings (e.g., download location, format).

4. **Logs**:
   - Logs are stored in the `logs` directory.
     - **log.txt**: General log.
     - **error_log.txt**: Errors encountered during the process.
     - **success_log.txt**: Successful conversions.

5. **Download Playlist**:
   - You can enter the URL of a YouTube playlist to download all videos in the playlist.

6. **Settings**:
   - You can change the download location and output format by selecting the settings option in the menu.

Script Functions:
----------------
1. **Convert to MP3 (Best Quality)**:
   - Converts a YouTube video to MP3 with the best audio quality.

2. **Convert to MP4 (Best Video + Audio)**:
   - Converts a YouTube video to MP4 with the best video and audio quality.

3. **Convert to WEBM (Best Quality)**:
   - Converts a YouTube video to WEBM format with the best quality.

4. **Custom Conversion**:
   - Allows for custom quality settings for audio and video formats.

5. **Multi-file Conversion**:
   - Allows batch conversion of YouTube videos by providing a list of URLs in a text file.

6. **Playlist Download**:
   - Downloads all videos from a YouTube playlist.

7. **Change Settings**:
   - Customize download locations and output formats.

8. **View Logs**:
   - View general, error, or success logs.

9. **Exit**:
   - Exit the program and close the script.

Logs:
-----
- Logs are automatically generated and stored in the `logs` folder.
- You can view them from the script's menu under the "View Logs" option.

Troubleshooting:
----------------
- **Missing yt-dlp**: If you encounter an error saying **yt-dlp** is not found, ensure it is properly installed by following the setup instructions.
- **Invalid URL**: Ensure the URL entered is valid and points to a YouTube video or playlist.

License:
--------
This script is free to use, modify, and distribute. If you need help or support, feel free to reach out to the author @Complicat_d on Discord.

Credits:
--------
- Developed by @Complicat_d (Discord).
- Powered by **yt-dlp** for downloading and converting YouTube videos.
