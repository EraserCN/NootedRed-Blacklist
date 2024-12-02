# NootedRed-Blacklist
 A blacklist of apps that would cause graphical artefacts amongst other problems when using AMD iGPU-based laptops for hackintoshing.

When using the NootedRed.kext for integrated graphics on a Hackintosh, certain applications may not function properly. Below is a list of known incompatible apps:


## Broken Apps
- SublimeText
 	- Workaround: Use other code editors such as VScode
- Tencent QQ
	- Workaround: Use Electron-based older version

## Partially Broken Apps
- Parsec
	- Issue: Hardware Decoding won't work
	- Workaround: Switch to software decoder 
- Lark/Feishu
	- Issue: Lark/Feishu meetings broken
	- Workaround: Use web-based version for meetings
- Spotify
	- Issue: Music Video doesn't work
	- Workaround: N/A
- Discord
	- Issue: Gifs menu doesn't work
 	- Workaround: Disable Hardware Acceleration in Settings -> Advanced
- Sunshine
	- Issue: Hardware decoder won't work
 	- Workaround: N/A

## Incompatible Chromium-based Browsers
- Google Chrome
- Microsoft Edge
- Brave Browser
- Opera
- Vivaldi
	- Workaround: Use Safari/Firefox
 	- Another Workaround: Open Chromium-based browsers with `open -a /path/to/broswer.app --args --disable-gpu` in Terminal

Please note that compatibility may vary based on specific configurations and updates, so it's always a good idea to check for the latest information from the Hackintosh community.
