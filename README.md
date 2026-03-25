# rewrite

An agent skill that rewrites text for clarity. Turns corporate jargon, buried leads, and wordy drafts into something a real person would actually read.

## What it does

- Rewrites emails, Slack messages, reports, slide copy, and product announcements
- Strips corporate jargon and replaces it with plain English
- Puts the most important thing first (no more buried leads)
- Cuts aggressively. Aims for 50%+ shorter than the original
- Outputs clean copy you can paste directly. No commentary, no preamble

## How it works

Invoke `/rewrite`, then paste your text. You get back the rewritten version and nothing else.

The skill stays active for the rest of the session, so you can keep pasting text without re-invoking.

## Install

### Claude Code

```bash
/install-skill https://github.com/howardmann/rewrite
```

### Claude Desktop / claude.ai

1. Download the ZIP from [GitHub](https://github.com/howardmann/rewrite)
2. Go to Settings > Customize > Skills
3. Upload the ZIP file

### Other AI clients

Download or clone this repo. Point your AI agent at the directory containing `SKILL.md`. The skill follows the [Agent Skills](https://agentskills.io) open standard and works with any client that supports it.

## Example

**Before:**

> It is important to note that, in light of recent developments pertaining to our customer satisfaction metrics, we have observed a meaningful year-over-year deceleration in growth across our core product lines, which may necessitate a comprehensive review of our go-to-market strategy.

**After:**

> Customer satisfaction is dropping and growth is slowing down. We need to rethink how we sell our core products.

## Attribution

- Plain English Campaign, [*How to Write in Plain English*](https://www.plainenglish.co.uk/free-guides)
- Cole Nussbaumer Knaflic, [*Storytelling with You*](https://www.storytellingwithyou.com)

## License

[MIT](LICENSE)
