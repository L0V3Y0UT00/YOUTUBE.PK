yt-dlp --cookies cookies.txt -i --yes-playlist -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]" -o "~/YouTube_Playlist/%(title)s.%(ext)s" "https://youtube.com/playlist?list=PLAPNIuJfKgBL7glSPV8xLcONvBEYLZt8y&si=s-kHbJg5XdEQWvMK"


https://write.corbpie.com/downloading-a-youtube-channel-with-yt-dlp/


 yt-dlp --cookies cookies.txt --no-check-certificate --extractor-args "youtube:player_client=web" --list-formats "https://www.youtube.com/watch?v=S8tHV6VeukM"
