# Dear English Radio — companion site

Public, crawlable companion pages for
[Dear English Radio](https://www.youtube.com/@dearenglishradio). Each released
episode can publish a reviewed transcript, a direct answer, CEFR level, useful
words, Q&A, and sources on one stable page.

- **Live site:** https://wenchangyue.github.io/dear-english-radio/
- **Built with:** Jekyll on GitHub Pages, using custom lightweight layouts.
- **Discovery policy:** search crawlers are allowed; `GPTBot` is disallowed so
  search discovery and model-training permission remain separate.

## Add an episode page

1. Copy `TEMPLATE-episode.md` to `_episodes/<slug>.md`.
2. Fill the title, direct answer, CEFR level, topic, FAQ, sources, and the
   human-reviewed transcript.
3. Keep `youtube_url` and `video_id` empty while the YouTube upload is private.
4. After the video is public or unlisted, add its URL, video ID, upload date,
   duration, and thumbnail URL.
5. Commit and push. GitHub Pages rebuilds automatically.
6. Link the companion page from the YouTube description and project metadata.

Do not publish API keys, OAuth files, voice-account exports, licensed production
assets, or unreviewed factual claims in this repository.

Local path: `~/dear-english-radio`

