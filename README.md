# OBS-web

#### Screenshot:

![Screenshot of OBS-web](.github/screenshot.png)

#### Features:

- No installation needed, works in any modern browser (desktop + mobile)
- Support for remote control through [WSS tunnels](https://github.com/Palakis/obs-websocket/blob/4.x-current/SSL-TUNNELLING.md)
- Easily switch scenes and start/stop streaming and recording
- Support for Studio Mode (preview and program scenes)
- Preview of output, updating continuously
- Fullscreen button and wakelock support
- Easy bookmarking/deeplink by specifying host in URL
- Hide scenes that have `(hidden)` in their name
---
#### Requirements:

- [OBS](https://obsproject.com/)
- [OBS-websocket](https://github.com/Palakis/obs-websocket/releases) plugin
- A tunnel service if you want to control remotely, [see these instructions](https://github.com/Palakis/obs-websocket/blob/4.x-current/SSL-TUNNELLING.md)

---
#### Build instructions:
```bash
npm i
npm run dev # or: npm run build
```