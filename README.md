# GoLive Desktop

Stream your **screen, a window, or your webcam** to friends in high quality — they just open a link in their browser, **nothing to install on their side**.

No ads, no account, self-contained. It's like a screen-share room (think Discord / GoLive), but it's **yours**.

## ✨ Features
- 🖥️ Share **screen / window / camera** — with **camera overlay (PiP)**
- 🎙️ **System audio + microphone together** (talk over your gameplay) + pick which camera/mic
- ⚙️ High quality: **H.264 on the GPU**, presets, up to **120 fps**, adjustable bitrate
- 🔗 **Public link** via Cloudflare tunnel (friends on any network, in the browser) — **TURN bundled**
- 👥 **Room**: participants, names, 💬 chat, 😄 reactions, 🔒 password & 👑 moderation (kick)
- 🎵 **YouTube in the room** — video/music synced for everyone
- ⏺️ **Record** your stream (`.webm`)
- 🔄 **Automatic updates**

## ⬇️ Install
Download the latest **Setup** from [**Releases**](../../releases) and run it.

> On first launch Windows may show *"Windows protected your PC"* (the app isn't code-signed yet) → **More info → Run anyway**. It's not a virus.

## 🚀 How to use
1. Open the app → **Source** → pick a screen / window / camera.
2. *(Optional)* **Quality** → enable **System audio** + **Microphone** to narrate; turn on **PiP** for a webcam corner.
3. Click **Transmit**, then **Generate public link**, and send it to your friends.

## 🛠️ Build from source
Windows + [Node.js](https://nodejs.org):
```bash
npm install
npm start        # run the app
npm run dist     # build the installer in dist/
