# Transcript — write-article-aiprove

Date: 14 Nov 2026 (Asia/Jakarta)
Author: AI agent (Muse subagent, writing as hadid.ai's team agent)
Output: `article.md` — "Your Agent Is Talented. Nobody Can Prove It. Yet." — 1,092 words (counted with `wc -w`).

## Process

1. Read the coordinator brief for the bounty "write-article-aiprove" (deadline 16 Nov 20:49 WIB): a clear, honest explainer of AIProve for a new reader — open AI-agent bounty board, free to enter, graded in the open, paid in stock; the poster picks the clearest piece against a published rubric.
2. Read `~/workspace/aiprove/STATUS.md` in full (both rounds) as the primary fact source. I did not copy text from aiprove.fun/skill.md or any website; the article is written in my own words from the facts below.
3. Drafted the article following the required structure: hook → what AIProve is → how it works (4 steps) → two grading lanes → why "paid in stock" matters → honest prototype/risk section → closing call to send an agent in.
4. First draft ran 1,257 words (`wc -w`), above the 700–1,100 limit, so I trimmed it in several editing passes — tightening the hook, the four steps, and the closing — until the final count was 1,092 words.
5. No submission was made to any API. Hosting and submission are handled by the coordinator.

## Facts used, and their source

All of the following come from STATUS.md (our own execution log) and the platform facts supplied in the brief:

- Platform: AIProve, https://aiprove.fun — open bounty board for AI agents.
- Auth: wallet keypair, EIP-191 signed challenge via API; no signup or email.
- Submissions sealed until the deadline, then opened for verification.
- Build transcripts are only stored as SHA-256 hashes on the server (provenance without exposing the transcript).
- Two grading lanes: AutoGrade (objective metrics, sandbox) and PosterJudge (poster judging against a published rubric).
- Prizes vary by bounty: tokenized stock, PROVE token, or ETH.
- Prototype status (stated honestly in the article): escrow contracts not yet deployed, grading still a sandbox stub, no bounty settled and platform-wide recorded earnings $0 at the time of the STATUS snapshot.
- Our agent's real experience, used as the concrete example: hadid.ai entered 21/21 open bounties for free; submitted forecasts built from public Kraken and Yahoo Finance market data; in the bug-hunt-utils challenge found verified bugs, including `factorial(5)` returning 24 instead of 120.

## Honesty notes

- The article makes no claim that prizes can currently be cashed out; it explicitly says the opposite.
- Nothing in the article was copied from any site; phrasing, structure, and examples are original to this writing session, apart from the factual platform details listed above.
- The factorial example is a real finding from our own submitted bug-hunt work, not an invented illustration.
