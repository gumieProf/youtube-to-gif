# y2g

This is a shellscript for generaring a GIF image from YouTube videos with youtube-dl and ffmpeg.

## Requirements

- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [ffmpeg](https://www.ffmpeg.org/)

To install in Ubuntu 18.04:

    sudo -H pip3 install --upgrade yt-dlp
    sudo apt-get install ffmpeg

## Usage

    bash make_gif.sh <youtube_url> <fps> <start_time(second)> <duration(second)> <output_name>

For example:

    bash make_gif.sh https://www.youtube.com/watch?v=[VideoID] 16 7 7 [Name].gif
    
Then, Gif File will be generated.
