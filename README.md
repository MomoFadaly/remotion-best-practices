# Remotion Best Practices

> Reference guide for building video in React with Remotion — animations, audio, captions, charts, fonts, frame extraction, and more.

**Free. Apache 2.0. Bring-your-own-Claude.**

## What this is

A Claude skill bundle — a sanitized, attributed, downloadable subject-matter expert that runs inside Claude Code, Claude Desktop, or any Claude-API workflow. Drop it in, invoke it, get answers grounded in real practitioner content rather than generic LLM consensus.

Use when building video in React with Remotion. The skill ships a curated rules/ directory covering animations, audio visualization, captions, code blocks, ffmpeg integration, fonts, and more.

## Install

```bash
# Claude Code plugin install (one-line)
claude plugin install remotion-best-practices --from https://fadaly.net/downloads/skills/remotion-best-practices.zip
```

Or clone this repo into your Claude skills directory:

```bash
git clone https://github.com/MomoFadaly/remotion-best-practices.git ~/.claude/skills/remotion-best-practices
```

Or download the zip from [fadaly.net/skills/remotion-best-practices](https://fadaly.net/skills/remotion-best-practices) and extract into `~/.claude/skills/`.

## What's in the bundle

| File | Size |
|---|---|
| `rules/3d.md` | 2KB |
| `rules/animations.md` | 778B |
| `rules/assets.md` | 2KB |
| `rules/assets/charts-bar-chart.tsx` | 3KB |
| `rules/assets/text-animations-typewriter.tsx` | 2KB |
| `rules/assets/text-animations-word-highlight.tsx` | 2KB |
| `rules/audio-visualization.md` | 5KB |
| `rules/audio.md` | 4KB |
| `rules/calculate-metadata.md` | 3KB |
| `rules/can-decode.md` | 2KB |
| `rules/charts.md` | 3KB |
| `rules/compositions.md` | 4KB |
| `rules/display-captions.md` | 5KB |
| `rules/extract-frames.md` | 5KB |
| `rules/ffmpeg.md` | 998B |
| `rules/fonts.md` | 3KB |
| `rules/get-audio-duration.md` | 1KB |
| `rules/get-video-dimensions.md` | 2KB |
| `rules/get-video-duration.md` | 1KB |
| `rules/gifs.md` | 4KB |
| `rules/images.md` | 3KB |
| `rules/import-srt-captions.md` | 2KB |
| `rules/light-leaks.md` | 2KB |
| `rules/lottie.md` | 2KB |
| `rules/maps.md` | 11KB |
| `rules/measuring-dom-nodes.md` | 973B |
| `rules/measuring-text.md` | 3KB |
| `rules/parameters.md` | 2KB |
| `rules/sequencing.md` | 3KB |
| `rules/sfx.md` | 867B |
| `rules/subtitles.md` | 922B |
| `rules/tailwind.md` | 420B |
| `rules/text-animations.md` | 700B |
| `rules/timing.md` | 4KB |
| `rules/transcribe-captions.md` | 2KB |
| `rules/transitions.md` | 6KB |
| `rules/transparent-videos.md` | 2KB |
| `rules/trimming.md` | 1KB |
| `rules/videos.md` | 3KB |
| `rules/voiceover.md` | 3KB |
| `SKILL.md` | 4KB |
| `thumb.png` | 1.30MB |

Total: 1.41MB

## Sources

This SME's canon was built from these practitioners. Every claim in the canon is attributed.

- Remotion docs (remotion.dev)
- Remotion blog · Remotion community best practices

Primary sources (official documentation, peer-reviewed research) take priority over practitioner consensus, which takes priority over single-source claims. Confidence tiers are tagged inline.

## How it works

Claude reads `SKILL.md` as the system instructions for the skill. Supporting files (`canon.md`, `mental-models.md`, etc.) are loaded as reference material when the skill needs to answer off the cuff or cite a specific source.

When you ask a question this SME covers, Claude pulls the relevant canon entry, names its source, tags its confidence level, and pushes back if your question contradicts canon.

## Confidence levels

- **Verified** — primary source + practitioner corroboration. Treat as fact.
- **Confirmed** — practitioner consensus across credible voices, no primary contradiction. Defended best-practice.
- **Plausible** — single-source or thin evidence. Working hypothesis until validated.
- **Disputed** — credible voices disagree. The SME names the camps and gives you the lens to decide.
- **Stale** — once true, contradicted by current docs/data. Flagged for refresh.

## License

Apache License 2.0. See [LICENSE](LICENSE).

You are free to use, modify, redistribute, and build on this skill. Attribution to the original practitioners (named in `sources.md` or `SKILL.md`) is morally required even if not legally; their work made the canon possible.

## Built by

[Mo Fadaly](https://fadaly.net) — AI intrapreneur, runs Claude skills in production.

This is one of a series. See the [full skill catalog at fadaly.net/skills](https://fadaly.net/skills).
