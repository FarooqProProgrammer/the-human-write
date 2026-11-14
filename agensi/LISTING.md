# Agensi listing — Human Content Agent

Submit at: https://www.agensi.io/dashboard/submit  
Packaging docs: https://www.agensi.io/docs/packaging  
Submit docs: https://www.agensi.io/docs/submit-on-the-website

## Upload files

| Asset | Path |
| --- | --- |
| ZIP | `agensi/human-content-agent.zip` |
| Logo (512×512 PNG) | `agensi/human-content-agent-logo.png` |

## Name (≤ 60 characters)

```
Human Content Agent
```

## Summary (≤ 300 characters)

```
Write blogs, social posts, emails, ads, and more that sound human—not AI-generated. Picks tone, avoids slop phrases, flags unverified claims, and saves a companion reference file beside every piece. Includes AdSense-ready content guidance.
```

Character count check: paste into the form; trim if the counter warns.

## Description (Markdown)

```markdown
# Human Content Agent

Turns a plain content request into finished writing that reads like a thoughtful human wrote it—specific, natural, and usable.

## What it does

- Writes **blog posts, articles, social posts, emails, newsletters, product copy, ads, jingles**, and mixed multi-format packs
- Chooses among **formal, warm, playful, or direct** tone (defaults to warm and conversational when you don’t say)
- Strips common **AI tells** (empty hype, stock phrases, triple-list padding, vague generalities)
- On edits: **keeps your meaning and voice**; improves texture instead of rewriting everything
- Saves a **companion `*-reference.md`** next to each content file (assumptions, claims to verify, sources)
- Includes **AdSense-oriented guidance** for original, useful, policy-aware site content

## How it works

1. You ask for content (topic + format, or attach a draft).
2. The agent applies voice rules and format playbooks from bundled references.
3. You get finished copy plus a paired reference file under your project (default: `content/`).

## Where it stops

- Does **not** invent facts, stats, quotes, or sources
- Does **not** impersonate real people unless you state that purpose
- Does **not** guarantee AdSense approval (Google decides; this skill helps prep original content and flags risks)
- Does **not** replace your brand guidelines—bring those if you have them

## Best for

Creators, marketers, and publishers who use AI for drafting but want output that still sounds human—and who want a clear paper trail of assumptions and claims to check.
```

## See it in action (demo · aim for 700+ characters)

Paste from `agensi/DEMO-paste.txt` (matches the Quillbot screenshot). Short version below if the form length is tight:

```text
Request:
/human-content-agent please create 10 jingles pick any random title

Result:
Assumptions — playful tone; short radio/social jingles; fictional brand titles.

1. Copper Kettle Coffee — Wake up slow, or wake up right— / Copper Kettle, dark and bright. / One small cup, then clear your head. / Copper Kettle. Go get fed.
2. Pocket Map Shoes — Left foot, right foot, city street— / Pocket Map Shoes know your beat…
(…full set of 10 in DEMO-paste.txt…)
10. Quiet Hour Headphones — City noise can wait outside. / Quiet Hour—soft, closed tight. / Press play once. The world thins out. / Quiet Hour. That’s what we’re about.

Saved: content/ten-jingles.md + content/ten-jingles-reference.md

Screenshot: Quillbot Detect AI on this sample — 0% likely AI / 100% human-written (one scan; detectors vary).
```

**Screenshots:** attach your Quillbot SS here (not inside this text box).

## Compatibility note

```
Works with Cursor, Claude Code, Codex CLI, and other agents that load the open SKILL.md format. Needs permission to write files so it can save content and companion reference markdown. No Node/Python runtime required for the skill itself.
```

## Categories (pick up to 3 · first is primary)

1. **Writing & Content** (Create)
2. **Marketing & SEO** (Grow) — optional second
3. **Digital Products** (Grow) — optional third, or skip

## Tags

```
writing, content, copywriting, humanize, anti-slop, blog, social media, email, newsletter, ads, adsense, reference files
```

## Use cases

```
Draft human-sounding blog posts and articles
Write social posts, emails, and newsletters in a chosen tone
Lightly edit a draft while preserving the author’s voice
Create product descriptions and short ads without fake proof
Plan AdSense-oriented original content with trust-page awareness
```

## Limitations (recommended)

```
- Will not fabricate testimonials, traffic numbers, or “studies show” claims
- AdSense readiness is guidance only; approval is Google’s decision
- Music/audio production is out of scope—jingles are lyric/copy only
- Brand voice must be supplied by you for strict brand match
- AI detector scores (Quillbot, etc.) are not guaranteed; sample screenshot is one check only
```

## FAQ (recommended)

**Q: Will this make my site get AdSense approval?**  
A: No skill can promise that. It helps you write original, useful pages and flags policy risks. Google makes the decision.

**Q: Can it rewrite my draft without changing my voice?**  
A: Yes—by default it improves clarity and cuts AI-isms while preserving meaning and voice. Ask for a full rewrite only if you want one.

**Q: Why a reference file?**  
A: So every piece ships with assumptions and claims to verify, instead of buried “trust me” copy.

**Q: Which agents work?**  
A: Any agent that loads SKILL.md (Cursor, Claude Code, Codex CLI, and others listed on Agensi).

## Pricing suggestion

Set in the form after connecting payouts (paid ≥ $1; or Free). Comparable writing skills on Agensi often sit in the low one-time range—you choose.

## Submit checklist

- [ ] Upload `human-content-agent.zip`
- [ ] Upload `human-content-agent-logo.png` (512×512)
- [ ] Paste Name, Summary, Description, Demo
- [ ] Set categories, tags, use cases
- [ ] Review detected permissions
- [ ] Add limitations + FAQ
- [ ] Set price / free
- [ ] Submit for security scan + review (often 24–48h)
