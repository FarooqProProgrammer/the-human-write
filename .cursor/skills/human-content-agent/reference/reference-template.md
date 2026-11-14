# Companion reference file template

For every content piece, create a file named `{content-basename}-reference.md` in the **same folder** as the content. Fill every section; use `None` when empty.

```markdown
# Reference: [content title or filename]

## Pairing
- Content file: [exact filename]
- Format: [blog | social | email | newsletter | product | ad | mixed]
- Tone used: [formal | warm | playful | direct]
- Audience: [who it’s for]
- Date: [YYYY-MM-DD]

## Assumptions
- [Assumption that shaped the draft]
- [Or: None]

## Claims to verify
| Claim (quote or paraphrase) | Why it needs checking | Suggested check |
| --- | --- | --- |
| … | … | … |
| Or one row: None | — | — |

## Sources to verify / add
- [URL, paper, doc, or “needs primary source for X”]
- [Or: None provided; no external citations used]

## Placeholders left in content
- `[verify: …]` — [what to replace it with when known]
- [Or: None]

## Edit notes (if improving a user draft)
- Preserved: [what stayed]
- Changed: [texture / clarity / AI-tell cuts only]
- [Or: N/A — original draft]
```

## Naming rules

- Match the content basename exactly: `my-post.md` → `my-post-reference.md`
- Same directory as the content file—never a separate `/refs` tree unless the user asks
- Mixed pack in one file: one reference covering all sections, or one reference per saved file if split
