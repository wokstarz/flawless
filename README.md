# 🌊 Flawless Music Player

Hey there! Welcome to **Flawless Music Player**. 

If you're tired of clunky, outdated music players and want something that actually looks and feels like it belongs in the modern era, you're in the right place. Built with Tauri, React, and Zustand, Flawless isn't just a music player—it's an experience. We designed it from the ground up to give you that buttery-smooth "Liquid Glass" aesthetic, all while packing some seriously powerful audio tools under the hood. 

Whether you're jamming to your local FLAC files or streaming from your own private server, we've got you covered.

---

## 📖 What's Inside?
1. [The Cool Stuff (Features)](#-the-cool-stuff)
2. [Let's Get Started](#-lets-get-started)
3. [Finding Your Way Around](#-finding-your-way-around)
4. [Make It Yours (Customization)](#-make-it-yours)
5. [Integrations & Connections](#-integrations--connections)
6. [Keyboard Shortcuts](#-keyboard-shortcuts)

---

## ✨ The Cool Stuff

### 🎵 Your Music, Your Way
* **Local Library Magic**: Just point Flawless to your music folders. We'll scan them, pull all the metadata, grab the cover art, and even read your embedded lyrics. Easy peasy.
* **Server Hopping**: Got a self-hosted **Navidrome** (Subsonic API) or **Samply** setup? Just log in, and your remote albums will blend perfectly with your local library.
* **Pro Audio Engine**: We take sound seriously. Powered by the WebAudio API, we included a built-in **10-band Equalizer** so you can tune your sound exactly how you like it.
* **Plays Nice with Windows**: Full support for your keyboard's media keys and Windows media controls.
* **Discord Rich Presence**: Let your friends know what you're vibing to on Discord, complete with the album art.

### 🎨 Eye Candy
* **Liquid Glass UI**: Everything is gorgeous, translucent, and blurred just right. It feels alive.
* **Chameleon Colors**: Play a track, and watch the whole app shift its accent colors and glow effects to match the album art. It’s pretty mesmerizing.
* **Immersive & Fullscreen**: Press **F11** and say goodbye to distractions. The UI melts away, leaving you with massive, scrolling lyrics over a cinematic blur of your album art.

### 🎤 Sing Along
* **Karaoke-style Lyrics**: Fully synchronized LRC lyrics that scroll as you listen.
* **Smart Fetching**: Don't have lyrics embedded in your MP3s? No sweat. Flawless will quietly ask **LRCLIB** for them in the background. It's completely free, anonymous, and requires zero effort from you.

---

## 🚀 Let's Get Started

### 1. Feeding the Player
When you first open Flawless, it’ll be a bit lonely in there. Let's fix that:
1. Click the **Settings** gear icon in the sidebar.
2. Scroll down to the **Folders** section.
3. Click **Add Folder** and pick where you hoard your music.
4. Grab a coffee! The app will scan everything and build your library automatically.

### 2. Connecting the Cloud (Optional)
Prefer streaming your own collection?
1. Head over to **Settings**.
2. **Navidrome users**: Punch in your Server URL, Username, and Password, then hit Connect.
3. **Samply users**: Just paste your token and click Connect.
Boom! All your remote tracks are now mixed right into your library.

---

## 🖥️ Finding Your Way Around

### The Sidebar
* **Library**: The home page. See what you've recently added or played.
* **Playlists**: Your personal mixtapes.
* **Folders**: For those who prefer browsing by raw directories.
* **Albums**: The classic grid view (or list view, if you prefer that in the settings).
* **Artists**: Click an artist to see their dedicated page, complete with a fancy "Verified Artist" badge and a beautiful banner.
* **Search**: Instantly hunt down any song, artist, or album across both your hard drive and remote servers.

### The Now Playing Bar
Hanging out at the bottom of the screen, this is your command center:
* Standard **Play/Pause, Next/Prev, Shuffle, and Repeat** buttons.
* A smooth **Seekbar** to jump to your favorite solo.
* **Volume & EQ**: Click the EQ icon to pull up the 10-band equalizer.
* **Lyrics**: Pop open the side panel to sing along.
* *Pro tip:* Want it to look sleeker? Go to Settings and change the Now Playing bar style to "Minimal" for a floating pill design.

### Entering the Zone
* Click the tiny album art in the Now Playing bar to pop into **Immersive View**.
* Want the ultimate experience? Hit **F11** for **Fullscreen Mode**. Dim the lights and enjoy the scrolling lyrics.

---

## ⚙️ Make It Yours

Flawless is *your* player. Go to Settings and tweak it until it feels just right:

### Looks & Feel
* **Accent Color**: Not a fan of the dynamic chameleon colors? Pick your own permanent hex color.
* **Language**: English, Italiano, or Español.
* **Fonts**: We love our default font, but you can click the Upload icon to import any `.ttf`, `.otf`, or `.woff` file straight from your PC.
* **Scaling**: Adjust the text size, overall UI scale, and how many albums load per page.
* **Glass Blur**: Slide it from 0px (sharp) to 40px (super dreamy).
* **Animations**: Playing on a potato PC? You can toggle off the fancy transitions for extra performance.

---

## 🔗 Integrations

### Last.fm (Track Your Obsessions)
If you're a data nerd who loves tracking listening habits:
1. Hit **Connect** under Last.fm in the Settings.
2. **Scrobble Percentage**: You decide when a song counts as "played" (e.g., halfway through, or only if you finish 90% of it).
3. **Now Playing Delay**: Set a tiny delay so you don't spam Last.fm while rapidly skipping through tracks looking for that one specific song.

### LRCLIB
As mentioned earlier, this is the magic behind the automatic lyrics. It just works in the background. No accounts, no hassle.

---

## ⌨️ Keyboard Shortcuts

Because who wants to use a mouse anyway?

| Shortcut | What it does |
|----------|--------------|
| `Space` | Play / Pause |
| `F11` | Enter / Exit Fullscreen Mode |
| `Esc` | Exit Fullscreen Mode |
| `Media Keys` | Next, Previous, Play/Pause via your keyboard |

---

*Made with ❤️ by x2loreeh (guide made using ai). Enjoy!*
