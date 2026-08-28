<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="assets/icons/dark@1x.png 1x, assets/icons/dark@2x.png 2x">
  <img
    src="assets/icons/@1x.png"
    srcset="assets/icons/@1x.png 1x, assets/icons/@2x.png 2x"
    alt="Mezzo icon"
    width="64"
    height="64">
</picture>

# Mezzo

Mezzo is a native music player app for self-hosted music servers.

Currently available for iPhone, with support for Navidrome and other Subsonic-compatible servers.

> [!TIP]
> The app is in active development, and is currently available to test through TestFlight.
>
> 🔷 [**Join TestFlight to test Mezzo!**](https://testflight.apple.com/join/Ub8M3z6A)

## Videos

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/user-attachments/assets/a73b576b-c572-4fbc-aae8-9fdb05d97b29">
        <img src="assets/videos/lyrics.jpg" width="200" alt="Synced Lyrics video preview">
      </a>
      <br>
      Synced Lyrics
    </td>
  </tr>
</table>

## Screenshots

<table>
  <tr>
    <td align="center">
      <a href="https://raw.githubusercontent.com/HazemAM/mezzo-tracker/main/assets/screenshots/home.jpg">
        <img src="assets/screenshots/home.jpg" width="200" alt="Mezzo home screen">
      </a>
    </td>
    <td align="center">
      <a href="https://raw.githubusercontent.com/HazemAM/mezzo-tracker/main/assets/screenshots/album-flower-boy.jpg">
        <img src="assets/screenshots/album-flower-boy.jpg" width="200" alt="Flower Boy album screen">
      </a>
    </td>
    <td align="center">
      <a href="https://raw.githubusercontent.com/HazemAM/mezzo-tracker/main/assets/screenshots/now-playing.jpg">
        <img src="assets/screenshots/now-playing.jpg" width="200" alt="Now Playing screen">
      </a>
    </td>
    <td align="center">
      <a href="https://raw.githubusercontent.com/HazemAM/mezzo-tracker/main/assets/screenshots/lyrics-seek-bar.jpg">
        <img src="assets/screenshots/lyrics-seek-bar.jpg" width="200" alt="Interactive lyrics seek bar">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://raw.githubusercontent.com/HazemAM/mezzo-tracker/main/assets/screenshots/queue.jpg">
        <img src="assets/screenshots/queue.jpg" width="200" alt="Playback queue">
      </a>
    </td>
    <td align="center">
      <a href="https://raw.githubusercontent.com/HazemAM/mezzo-tracker/main/assets/screenshots/artist.jpg">
        <img src="assets/screenshots/artist.jpg" width="200" alt="Artist screen">
      </a>
    </td>
  </tr>
</table>

## Current features

- Full synced lyrics support
  - Karaoke lyrics with word-level highlighting & visual effects
  - External sources support for songs without lyrics on your server
  - Interactive lyrics UI
  - Swipe down on the seek bar to jump between lyric lines
- Audio quality
  - Lossless and original-quality streaming
  - Separate quality and bitrate settings for Wi-Fi and mobile data
  - Smart Transcoding setting chooses the best quality based on factors like available audio cache, your network, your desired bitrate, etc.
- Similar music
  - Autoplay: Keep playing similar music after your queue ends
  - Song Radio: Start a radio station from any song
  - Support for sonic similarity plugins, including [AudioMuse-AI](https://github.com/NeptuneHub/AudioMuse-AI-NV-plugin), to get better matching music similarity
- Queue system
  - Swipe on a song anywhere to add it to the queue, swipe in the queue to remove it
  - Reorder songs in the queue
- Playlist management
  - Add songs to one or multiple playlists, with duplicate song detection
  - Remove songs directly by swiping on them
- Search
  - Universal search across your entire library, with a top result to jump to
  - Search only in parts of your library, or search directly in a playlist or album
- Scrobbling to server, with support for `playbackReport` extension for accurate scrobbling
- Album editorial notes, with text formatting support (e.g. bold, italic)
  - Available through compatible server plugins, including [Navidrome's official Apple Music plugin](https://github.com/navidrome/apple-music-plugin)
- Library browsing
  - Browse your library by albums, artists, songs, playlists, and genres, with multiple sort options
  - Filter by favorites with search and shuffle support
- AirPlay 2 support
- Gapless playback
- Shuffle & repeat modes
- Dark mode & light mode support

## Planned features

- [ ] Downloading for offline playback
- [ ] Creating new playlists
- [ ] Animated album artworks
- [ ] Siri integration
- [ ] Spotlight integration
- [ ] Recommendations

- [x] Filtering in library
- [x] Playlist management
- [x] Shuffle & repeat modes
- [x] Search

> [!TIP]
> Want to see what’s being added in every update? Visit [Releases](https://github.com/HazemAM/mezzo-tracker/releases).

## Long-term roadmap

- macOS app
- tvOS app
- Support for more music servers

## Issues & feedback

Found a bug, or have feedback or a feature request? Please [open an issue](https://github.com/HazemAM/mezzo-tracker/issues/new/choose).
