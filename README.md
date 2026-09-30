# Claude Opus 5.5 week — 10 GitHub repos

Curated list from [Muhammad Ayan / @socialwithaayan](https://x.com/socialwithaayan/status/2105271130215064056) (30 Sep 2026).

Theme: **video and games as code**. Claude Opus 5.5 writes HTML, Canvas, p5.js, Three.js or raw WebGPU. A headless browser + ffmpeg turns time-parameterised frames into an MP4. This is not a text-to-video model stack.

Star counts below are the figures printed in the original X post, not live counts.

## The 10 repos

| # | Repo | Stars in post | What it is |
|---|---|---|---|
| 1 | [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | 1.5k | Source for the Opus 5.5 music video *I'm Upping My P(doom)*. Every frame painted in p5.js / p5.brush, rendered in headless Chrome + ffmpeg. |
| 2 | [yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) | 1k | 475 viral Opus 5.5 videos with the creator prompts. Motion graphics, explainers, 3D, games. Remakes on Skillry. |
| 3 | [dgreenheck/tidewater](https://github.com/dgreenheck/tidewater) | 988 | Browser island fishing game on raw WebGPU + WGSL. [Play it](https://dgreenheck.github.io/tidewater/). |
| 4 | [riba2534/claude-opus-5-5-demo](https://github.com/riba2534/claude-opus-5-5-demo) | 937 | Three 3D web games, one prompt each (pelican bike, transport ship, QQ Speed). |
| 5 | [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 650 | 43 film styles, each a short film made entirely in code. [Gallery](https://lemomo-ai.github.io/lemo-opuscar/). Claude Code plugin. |
| 6 | [JohnHeibel/ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | 606 | Starter kit from PDoomVideo: Clawd character, 31 emotions, `ANIMATION_GUIDE.md`, headless renderer. |
| 7 | [athemeroy/awesome-opus-5-5-videos](https://github.com/athemeroy/awesome-opus-5-5-videos) | 360 | Independent source-linked guide to 1,000+ Opus 5.5 videos. Different project from #2. |
| 8 | [diggerhq/shipvideo](https://github.com/diggerhq/shipvideo) | 223 | Paste a URL or prompt. Opus 5.5 writes one HTML film. Serverless agent renders it. Live: [launchvideo.io](https://launchvideo.io). |
| 9 | [makevoid/motion-graphics-music-video-skill](https://github.com/makevoid/motion-graphics-music-video-skill) | 71 | Claude Code plugin: song + prompt in, motion-graphics music video out. |
| 10 | [tuzhechen2005/opus-video-skills](https://github.com/tuzhechen2005/opus-video-skills) | 36 | One Claude Code skill per style (painted-animation, kinetic-reel). Frames generated in code. |

## How to use this list

1. Clone or star the original repo you want to study.
2. For skills (#5, #6, #9, #10), install the plugin or skill in Claude Code and give it a short brief.
3. Watch dependencies. Several of these pull Node, Chrome, ffmpeg, or paid APIs (Fal.ai on #9).

```bash
# example — animation starter kit
git clone https://github.com/JohnHeibel/ClaudeAnimationBase.git
cd ClaudeAnimationBase
# then open in Claude Code and ask it to read ANIMATION_GUIDE.md
```

## Source

- X post: https://x.com/socialwithaayan/status/2105271130215064056
- Quoted article: https://x.com/i/article/2104519423780687872
- Extracted 30 Sep 2026. This repo only links out. It does not copy their source trees.

## License

This list file is CC0. Each linked repository keeps its own license. Read that license before you fork or ship from it.
