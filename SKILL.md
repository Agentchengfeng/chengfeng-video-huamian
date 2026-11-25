---
name: chengfeng-video-huamian
description: Install the chengfeng-video-huamian (成峰出画面) skill for supported Agent environments.
---

# chengfeng-video-huamian

This is the installer package for `chengfeng-video-huamian`（成峰出画面）. It now also contains the 16 code-video styles that used to be published as `chengfeng-video-styles`.

Install it with:

```sh
npx -y github:Agentchengfeng/chengfeng-video-huamian install
```

The installed skill draws explainer-video visuals as code from a shot list, times every shot to the voiceover's per-character timeline (from the Fish voiceover tool or the koubo cutting tool), renders frame by frame with headless Chrome, and outputs an mp4 with voice and subtitles. It can also render a silent preview of the opening with estimated timing before any voiceover exists. As a secondary option it carries 16 ready-made code-video styles for short silent 10-second explainers or for opening comparisons, picked by topic.
