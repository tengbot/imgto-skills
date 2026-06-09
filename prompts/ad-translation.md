# Ad Translation Prompts

Prompt patterns for localizing ad scripts, captions, CTAs, and voiceover drafts.

Main site: https://aiads.im

## Localize ad script

```text
Source language: {{source_language}}
Target language: {{target_language}}
Target market: {{target_market}}
Platform: {{platform}}
Product: {{product}}
Brand voice: {{brand_voice}}

Source ad script:
{{script}}

Localize the script for the target market.
Return:
- localized hook options
- localized script
- caption lines
- CTA variants
- voiceover notes
- cultural notes
- claims to avoid

Rules:
- do not translate word for word if it sounds unnatural
- keep hooks short
- preserve the offer and selling point
- do not invent proof, awards, reviews, or certifications
```

## CTA localization

```text
Target market: {{target_market}}
Target language: {{target_language}}
Product: {{product}}
Platform: {{platform}}

CTAs:
{{ctas}}

Return localized CTAs with:
- local version
- literal meaning
- tone note
- best use case
- what to avoid
```

## Caption localization

```text
Translate and adapt these ad captions.

Captions:
{{captions}}

Target market: {{target_market}}
Platform: {{platform}}
Tone: {{tone}}

Return:
- localized captions
- shorter caption options
- on-screen text options
- voiceover-friendly variants
```
