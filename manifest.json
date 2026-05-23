# 🎵 Gopeed YouTube Playlist Audio Downloader
**Made by Ahmad Malik (NexusMG)**

Download full YouTube playlists as audio files directly inside Gopeed.
No API key. No account. Just paste the link.

---

## 📦 Manual Install (Step-by-Step)

### Step 1 — Find Gopeed Extensions Folder
| OS | Path |
|----|------|
| Windows | `C:\Users\<YOU>\AppData\Roaming\gopeed\extensions\` |
| Linux | `~/.config/gopeed/extensions/` |
| macOS | `~/Library/Application Support/gopeed/extensions/` |

### Step 2 — Copy the Folder
Copy this entire folder (`gopeed-yt-playlist-extension`) into the extensions directory.

### Step 3 — Enable in Gopeed
- Open Gopeed → Settings → Extensions
- You should see **"gopeed-yt-playlist-audio"** listed
- Enable it

### Step 4 — Download a Playlist
- Copy any YouTube playlist URL:
  - `https://www.youtube.com/playlist?list=PLxxxxxx`
  - `https://www.youtube.com/watch?v=xxx&list=PLxxxxxx`
- Paste it in Gopeed's "New Task" dialog
- The extension auto-resolves all songs ✅

---

## ⚙️ Configuration (edit `index.js` top lines)

| Setting | Default | Options |
|---------|---------|---------|
| `PREFERRED_QUALITY` | `"high"` | `"high"` / `"medium"` / `"low"` |
| `MAX_SONGS` | `100` | any number, `0` = unlimited |

---

## 🔧 How It Works
Uses **Invidious** (open-source YouTube frontend) public API.
- No YouTube account needed
- No API key needed
- Falls back across 5 Invidious instances if one fails
- Downloads `.m4a` or `.webm` audio (best available quality)

---

## ❗ Troubleshooting
| Problem | Fix |
|---------|-----|
| "All instances failed" | Try again later — Invidious servers are sometimes slow |
| No files appear | Playlist might be private or age-restricted |
| Missing some songs | Some videos may be unavailable in your region |

---

## 📁 Output Format
Files are saved as:
```
01 - Song Title.m4a
02 - Song Title.webm
...
```
Inside a folder named after the playlist.
