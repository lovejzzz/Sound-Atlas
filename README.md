# Sound Atlas · 拉美声音地图

MUSC 1100 (Fall 2026) midterm review site.

- **地图**：hover the water-drop pins to lift each region; click for illustrated, one-topic-per-page notes.
- **听力**：the ten course recordings with 15/30/60-second or full-length clips, shuffle, random start points, a blind-listening quiz, per-track guides, notes saved in the browser, and an instrument gallery with photos and solo samples.
- **模拟考题**：52 English multiple-choice questions with Chinese hints and illustrated explanations.

Open `index.html` through any static host (GitHub Pages serves it from the repository root). Everything runs in the browser; no build step.

## Listening controls

- Click **盲听测验** to start a blind-listening round immediately with the selected tracks, shuffled order, and random clip starts. The button becomes **结束测验** to stop the round and return to normal listening. Your previous shuffle and random-start settings are restored when the round ends.
- Use the bottom **播放 / 暂停** button for normal continuous listening, starting with the current track when it is selected. Clicking a track starts from that track; an unchecked track plays on its own. Clip length, shuffle, and repeat still apply.

## Educational use only · 仅供教育用途

The course recordings are included solely for MUSC 1100 study. Copyright remains with the original rights holders. The site provides listen-only playback; please do not download, redistribute, or use the recordings for any other purpose. Rights holders who want them removed can open an issue.

本站录音仅用于 MUSC 1100 课程学习，版权归原权利人所有。网站只提供在线试听，请勿下载、转载或用于其他用途。如权利人要求移除，请提交 issue。

## Media and credits

- `media/audio/` — the ten listening examples supplied for the course (*World Music: A Global Journey*). They are stored in a scrambled form and are decoded in the browser only for in-page listening.
- `media/inst/` — instrument photos, diagrams, and solo recordings. Each instrument card in the 听力 → 乐器 tab lists its image and sound source, author, and license (Wikimedia Commons, Freesound, and original diagrams).
- Map geometry: Natural Earth via [world-atlas](https://github.com/topojson/world-atlas) (public domain).

Content follows the course study guide; classroom-specific examples (for example the salsa song discussed in class) should be checked against class notes.
