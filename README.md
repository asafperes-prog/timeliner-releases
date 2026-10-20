# Top40 Theory Timeliner

A free app for mapping songs, for Windows and Mac. Load a track, mark its sections
and techniques as bubbles on a timeline, tap in the melody's rhythm, type its scale
degrees to draw the contour, and export the whole timeline as a graphic you can edit
in Canva. Made by [Top40 Theory](https://top40theory.com).

## Download

**[Get the latest version →](https://github.com/asafperes-prog/timeliner-releases/releases/latest)**

On that page, under **Assets**, download the file for your computer:

| Computer | File | How to install |
|---|---|---|
| Windows | `Top40-Theory-Timeliner-Setup.exe` | Double-click it and follow the steps. |
| Mac | `Top40-Theory-Timeliner.dmg` | Double-click it, then drag the app into your Applications folder. |

The manual (PDF) is on the same page. To check that your computer can run the app, see
[What do I need to run it?](#what-do-i-need-to-run-it)

### A note for Windows

Windows may show a blue box saying **"Windows protected your PC"**. The installer
is signed by Top40 Theory, LLC; Windows shows this box for apps it hasn't seen
installed many times yet. Click **More info**, check that the publisher says
**Top40 Theory, LLC**, then click **Run anyway**.

## Updating

The app checks for new versions once a day and shows a notice at the bottom of
its window when one is out (you can also use **Help > Check for Updates**).
To update, download the new version and install it over the old one. Your
projects and settings stay as they are.

## FAQ

### Is it really free?

Yes. The Timeliner is free to download and use, on Windows and Mac.

### Is it a plugin? Does it work in my DAW?

No. It's a standalone app for studying songs. You load audio files into it (a mix,
a reference track, a bounce of your own song), map the song, and export the result.
It never changes the audio.

### What do I need to run it?

- **Windows:** Windows 10 (version 1809 or later) or Windows 11, 64-bit.
- **Mac:** a Mac with Apple silicon (M1 or later) running macOS Sonoma (14.4) or later.
  Intel Macs aren't supported.

### What audio can I load?

WAV, MP3, FLAC, OGG and AIFF files on your computer. Songs on streaming services
can't be loaded, and neither can M4A or AAC files (the format of many Apple Music
and iTunes purchases): convert those to WAV or MP3 first.

You can load two versions of the same song, such as the vocal and the instrumental,
and press **T** to switch between them while it plays.

### How do I get a timeline into Canva?

Choose **File > Export as PDF / SVG** (Ctrl+E, or Cmd+E on a Mac) and pick
**PDF (best for Canva)**. In Canva, upload the PDF, go to **Uploads > Designs**,
click it and choose **Add as new page**. Everything arrives editable.

To move it onto another page, select everything (Ctrl+A or Cmd+A), group it, cut it
and paste it there. Dragging it from one page to another loses the text.

### My taps land early or late

Every computer adds a little delay between a key press and the app, and the app can
measure yours. With the beat grid set and lined up with the song, choose
**Edit > Tap timing...**, click **Calibrate** and tap **K** on eight beats. From then
on, that amount is taken off every K tap.

After each tapping pass, the app also checks whether your notes leaned early or late.
If they did, it slides the pass onto the beat grid and updates the amount. Cuts made
with **B** while the song plays have their own amount in the same box.

### Can I open my Variations Audio Timeliner (.v2t) files?

Yes. Choose **File > Import Variations / Audio Timeliner file**, or drag the .v2t
(or .tim) file onto the window. The bubbles come in with their annotations as bubble
notes. If the song doesn't come in with them, add it with **File > Add audio track**.
The Timeliner isn't made by or affiliated with Variations.

### Can I share a project with someone?

Yes. Send them the project file (.t40t) along with the audio. A project remembers
where the audio was on your computer, so on theirs the app will say it couldn't load
the audio. They drag the song onto the window and choose **Add to this project as a
track**. You should both be on the latest version (**Help > Check for Updates**).

### Does it use AI?

No. Nothing on a timeline is generated: every bubble, note and label is one you put
there. The one thing the app works out from the audio is the tempo for the beat grid,
using standard signal processing (the kind a DAW uses to detect tempo), and you can
adjust whatever it finds.

### What are FuelCore, Phrase Syncopation and the other technique labels?

They're songwriting techniques taught by Top40 Theory, the channel and course behind
the Timeliner. See [FuelCore explained on YouTube](FUELCORE_VIDEO_LINK) and the
[Melodic Math course](https://www.top40theory.com/melodic-math-course).

### Something isn't working, or I have an idea

Please use this short form. It takes a couple of minutes and you don't need an account:
**[Report a problem or suggest a feature](https://forms.gle/xsDs8D3yF8WASQak8)**

If the app crashed or showed an error, the details are in a file called
`crash-log.txt`. **Help > Show Crash Log** opens its folder with the file selected:
email it to support@top40theory.com. If your taps are landing oddly, send
`tap-timing-log.txt` from the same folder too.

If the app won't open at all, go to that folder yourself (it's hidden from normal
browsing):

- **Windows:** click in File Explorer's address bar, paste `%APPDATA%\Bubble Timeliner`
  and press Enter.
- **Mac:** in the Finder, choose **Go > Go to Folder** (Cmd+Shift+G), paste
  `~/Library/Application Support/Bubble Timeliner` and press Return.
