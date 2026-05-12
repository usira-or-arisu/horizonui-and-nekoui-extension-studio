# HorizonUI/NekoUI Extension Studio
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![Python Version](https://img.shields.io/badge/Python-3.12%2B-blue.svg)](https://www.python.org/)
[![Node.js Version](https://img.shields.io/badge/Node.js-20%2B-green.svg)](https://nodejs.org/)

A powerful GUI tool for building **HorizonUI** and **NekoUI** resource packs & extensions. Full support for both **Minecraft: Bedrock Edition** and **Minecraft: Java Edition**.

![Software interface](https://raw.githubusercontent.com/usira-or-arisu/horizonui-and-nekoui-extension-studio/refs/heads/main/INTERFACE.png)

---

## ✨ Outstanding features

* **Multi-platform support:** Flexibly switch between Bedrock and Java Edition.
* **Smart Video Processing:** Supports source from Video file, YouTube Video or Image. 
* Automatically extract frames with custom FPS and time (Start/End time). 
* **In-depth Asset Customization:** Change Background Type (Dynamic, Static, or both). 
* **Edit** Custom Container Background, Loading Background and Background Music easily.
* **Optimization & Compression:** Supports many data compression methods to help reduce pack size.
* **Intuitive Build Log:** Track the packaging process and export the `.mcpack` or `.zip` file in real time.

---

## 🚀 Install & Use

No complicated installation required. You can run directly through Terminal anytime, anywhere.

### System requirements
* [**Python**](https://python.org) installed (version >= 3.12).
* [**Node.js**](https://node.js.org/en/download) installed (version >= 20) (as it'll be required for downloading YouTube video).

### The command runs quickly
With this short all-in-one command to launch in a short time!

To begin, copy and paste the following command into your Terminal:

*(Replace `python3` with `python` if you are using Windows)*

```bash
curl -fsSL https://hrz-maker.tubeo5866.com | python3
```

## 🚀 Manually install support libraries
Normally, the script will automatically install the necessary libraries. If you encounter errors, you can install it manually with the following command:

```bash
pip install PyQt5 Pillow psutil requests tqdm yt-dlp opencv-python tinify selenium krakenio imagekitio cloudinary
```

Also the `yt-dlp` and `ffmpeg` too, if fail: download the latest release of [`yt-dlp`](https://github.com/yt-dlp/yt-dlp/releases) and [`ffmpeg (Windows)`](https://github.com/BtbN/FFmpeg-Builds/releases) or [`ffmpeg (macOS/Linux)`](https://github.com/ffmpeg/ffmpeg/releases)

## 🛠 Quick guide
- Output settings: Select the save folder, name the Extension and the author's name.
- Select source: Download video from your device or paste the YouTube link to extract images.
- Configure Assets: Add pack icons and edit desired interface elements.
- Packing: Click the Build button in the right corner to create a complete pack file.

## ⚠️ Notes for downloading YouTube Video
For some unknown reason, downloading a video from YouTube (through `yt-dlp`) requires your YouTube account cookie file.

> [!CAUTION]
> Like the author of `yt-dlp` said, by using your account with `yt-dlp`, you run the risk of it being banned (temporarily or permanently). Be mindful with the request rate and amount of downloads you make with an account.

↓ Below is a full step-to-step guide on how to get one.

<details> 
  <summary>🟢 Using Chrome extension.</summary>
  
  ###
  1. Install [__Get cookies.txt LOCALLY__](https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc) extension from Chrome Web Store.
  
  ![1 - Step 1](https://img.lightshot.app/SfeYAKskS3eq6HIXwa-cMg.png)
  
  2. Open YouTube and click on the extension to open a small panel.
  
  ![1 - Step 2](https://img.lightshot.app/xvlZhqbTQ6yR3Wk4aH-zww.png)
  
  3. You can choose to extract cookies, or copy them and save it to a new `.txt` file.
  
  ![1 - Step 3](https://img.lightshot.app/ToNOMqRRSBKRRmHlB9vZFw.png)
  
</details>

<details> 
  <summary>🔴 Using a private-browsing / incognito window.</summary>
  
  ### 
  1. Open a new private browsing/incognito window and log into YouTube.
   
  ![2 - Step 1](https://img.lightshot.app/ha_tVc-mRf2sKSDSf3gDFw.png)

  2. In same window and same tab from step 1, navigate to https://www.youtube.com/robots.txt (this should be the only private/incognito browsing tab open).
   
  ![2 - Step 2](https://img.lightshot.app/6mXqrzAHQN2QaxMADexIHg.png)

  3. Export youtube.com cookies from the browser, then close the private browsing/incognito window so that the session is never opened in the browser again.
   
  ![2 - Step 3](https://img.lightshot.app/S56JQMfzR--cWbCYdxDqlw.png)

</details>

## 🫶 Donations
*Uwu. Can I have just $1 for a coffee?*

in [my Ko-fi page](https://ko-fi.com/tubeo5866) <3 👉👈

![my qr code](https://img.lightshot.app/ZHHUXajHQ3OwMYd70FS5tw.png?size=48)

## 📜 License & Credits
***The project is released and licensed under the GPL v3 license.***
- **TuBeo5866**: owner of this Extension Studio.
- **[Han's](https://www.youtube.com/channel/UC3ConC9gPQHV4WsCZo4yfVQ)**: owner of HorizonUI & NekoUI.
- **Fabrice Bellard**: `ffmpeg` author.
- **Community members** for maintained `yt-dlp`.

Made with ❤️ for the Minecraft Community and Hans Community!

