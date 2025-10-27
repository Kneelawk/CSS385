# Program 3 Submission

## Writeup

In physball, I have chosen to use a raw JSON file for storing game preferences on desktop. This file will be stored in the OS-specific preferences location, which is `~/.config/physball/prefs.json` on linux. I also considered using a full database system that would allow much more data to be managed much more efficiently, but I figured that would be overkill for the amount of data I need to save. I also considered using a binary file for the smaller file size and because it would be simpler in some ways. However I found that because the amount of data I need to store is so small, the size benifits of having a binary file would be negligible. I settled on using a raw JSON file for saving my preferences because the game preferences do not need to be obfuscated in any way, and in fact, it makes more sense to have the game preferences file be easily editable by players. I decided on JSON instead of TOML because JSON is slightly better for file size, which is something I would like to take into consideration when I start storing preferences in the browser's local storage too.

## Video Demonstration

I recorded a single video and then encoded it as an H264 `.mp4` file and an AV1 `.webm` file. The AV1 file has better quality but not all devices can play AV1 videos yet.

[H264 Encoded Video Demonstration]
[AV1 Encoded Video Demonstration]

## Notes

There currently seems to be a bug in the Bevy game engine that causes the window to not resize immediately when the component is updated. Instead I need to restart the app with the new specified resolution for the window to open at the new size. Hopefully this bug will be fixed soon.
