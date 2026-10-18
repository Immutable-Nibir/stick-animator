# Stick Animator

**Make stick figure animations in your browser. One HTML file, no install, no account.**

Stick Animator is a small, free tool for frame-by-frame stick figure animation. Pose a figure, add a frame, pose it again, and press play. When you're done, export your animation as a video or PNG.

**[Open the live app](https://immutable-nibir.github.io/stick-animator/)** &nbsp;|&nbsp; Version 1.2

---

## Quick start

**Option 1: Use it online**
Open the live app link above. Nothing to download.

**Option 2: Use it offline**
1. Download `index.html` from this repository.
2. Double-click it to open it in your browser (Chrome, Edge, Firefox, or Safari).

That's it. There is no build step and no dependencies.

---

## Make your first animation

1. **Pose the figure.** Select the **Move** tool (`V`) and drag the figure's joints to set a pose.
2. **Add a frame.** Press `N` or click **Add frame**. The new frame starts as a copy of the last one.
3. **Pose again.** Make a small change. Onion skin (`O`) shows the previous frame faintly so you can keep motion smooth.
4. **Repeat** for as many frames as you need.
5. **Play.** Press `Enter` to preview. Use **Speed** to change the frames per second.
6. **Export.** Use **Save video** or **Save PNG**, or **Save project** to keep working later.

---

## Features

**Animating**
- Frame-by-frame editing with add, delete, and step-through controls
- Onion skin to see neighboring frames
- Adjustable playback speed (FPS)
- IK bones for natural posing, or rigid bones for fixed limb lengths

**Figures**
- Several preset characters
- **Build figure** to design your own, and **Import figure** to load one
- Change a figure's look, hair, and colors

**Drawing and effects**
- **Draw** tool with pen, eraser, and fill (adjustable size and tolerance)
- **Impact frame** and **Shake** effects for punchy moments

**Reference video**
- Import a video and step through it frame by frame to trace real motion
- Drag, scale, and time the video behind your animation

**Saving and exporting**
- Save and open projects (`.json` files)
- Export video or PNG
- Settings (theme, layout, shortcuts) are remembered in your browser

**Comfort**
- Works with mouse, touch, and pen
- Light and dark color themes, plus two layouts (a classic panel layout and a compact floating "Studio" layout)
- Right-click or long-press the canvas for a quick menu
- Fully customizable keyboard shortcuts

---

## Keyboard shortcuts

These are the defaults. You can change them in **Settings** (`F2`).

| Action | Key |
| --- | --- |
| Move / pose tool | `V` |
| Pen | `P` |
| Eraser | `E` |
| Pan (hand) | `H` (or hold `Space`) |
| Fill | `G` |
| Undo | `Ctrl + Z` |
| Play / pause | `Enter` |
| Previous / next frame | `←` / `→` |
| Add frame | `N` |
| Delete frame | `Delete` |
| Onion skin | `O` |
| Toggle IK | `I` |
| Zoom in / out | `+` / `-` |
| Fit to screen | `0` |
| Quick menu | `Q` |
| Save project | `Ctrl + S` |
| Open project | `Ctrl + O` |
| Settings | `F2` |

---

## Customizing the app

Everything you might want to change is in the `CUSTOMIZE HERE` block at the top of the script in `index.html`:

- App title, canvas size, and background color
- Line thickness and head size
- Default speed (FPS)
- Characters and their colors
- Export file name
- The About page (name, version, contact links)

Open the file in any text editor, edit the values, and save.

---

## Host your own copy on GitHub Pages

1. Make sure the file is named `index.html` in the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select your branch and the `/ (root)` folder.
4. Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

---

## Tips

- If the animation runs slowly on an older device, lower `CANVAS_W` and `CANVAS_H` in the customize block.
- Save your project (`Ctrl + S`) regularly. Projects are saved as files, so you can back them up or share them.
- If a reference video won't load, try converting it to MP4 or WebM.

---

## Author

Made by **Nibir** ([GitHub](https://github.com/Immutable-Nibir/)).

