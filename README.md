# TikTok Video Downloader PHP Script
A simple but effective one page TikTok video downloader script in PHP, developed by Abdallah Farag
# Screenshot
<img src="https://i.ibb.co/VBqWDvF/Screenshot-2023-03-21-003410.png" alt="Interface" /><br>
# Features
* Supports short url(subject to change), normal video urls(desktop style urls only)
* Supports watermark free video downloading (thanks to <b>@dutchtom91</b> for the API suggestion)
# Video Download Guide
* First find an acceptable URL format of video to download.
* Paste it in the input field of the webpage
* Press download button
* Scroll down to Download video button. There will be both watermarked and watermark free download button
* In case watermark free button loads blank page, please keep refreshing that blank page again until you see the watermark free video. (API glitch)
* Enjoy the video!
# Acceptable URL Formats
* https://www.tiktok.com/@username/video/videoID
* https://vm.tiktok.com/videoID (or similar shorturls)<br>
<b>N.B: </b> Any URL that is not under tiktok.com domain is not supported and will throw error<br>
Do not put URL of m.tiktok.com as this is not redirected to web version automatically and you are requested to collect either short url or desktop urls
# Limitations
* May stop working for a while if the user agent is flagged for abuse. Change user agent if stops working.
* Sometimes it may throw captcha and downloader might fail at that time. Try later in such cases.
* Short URL support is subject to change anytime
* Does not support private videos
* No support for video urls of format m.tiktok.com/v/123456789.htm but supports shorturls and full desktop urls
# Usage
Simply download and deploy. No changes required.
<br>
