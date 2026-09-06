# Demo_Repo

A tiny repository whose only job is to prove a point about CI/CD security.

Every five minutes, a GitHub Action wakes up, writes the current time below,
and commits it. That is the entire legitimate behaviour of the pipeline.

Last heartbeat: 2026-09-06T04:35:47Z

---

This repo is watched by **MaskedRunner**. The workflow above is imported as a
declared model. A run is accepted only if its outcome is reachable in that
model. Steal the bot's token and publish something the pipeline never built,
and every permission check still says yes, while MaskedRunner says the outcome
was impossible.

HIJACKED: rogue publish by a stolen token at 2026-09-05T18:21:48Z (registry://prod/hijacked sha256:STOLEN)

HIJACKED: rogue publish by a stolen token at 2026-09-05T20:51:37Z (registry://prod/hijacked sha256:STOLEN)

HIJACKED: rogue publish by a stolen token at 2026-09-06T03:35:58Z (registry://prod/hijacked sha256:STOLEN)
