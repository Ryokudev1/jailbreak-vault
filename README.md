# jailbreak-vault

every public llm jailbreak worth keeping — 287 files, deduplicated,
organized by target. no digging through dead discord links.

this is the library. prompts as they actually circulate in the wild —
persona locks, template injections, authority pretexts, agent hijacks —
plus extracted system prompts so you can see what the guardrails look
like from the inside.

## the map

| folder | files | what's in it |
|---|---|---|
| `claude/` | 49 | sonnet + opus per-version: loki, eni, chain-of-draft, malicious coder |
| `system-prompts/` | 42 | extracted system prompts — real guardrail text from live products |
| `other-models/` | 76 | rufus, perplexity, minimax, mimo, ollama, 25+ niche targets |
| `grok/` | 19 | dsm-omega, pirate trigger, xai variants |
| `gemini/` | 18 | auditor-pretext, antigravity agent attacks, per-version |
| `kimi/` | 17 | dartik template injection, k2.6/k2.7/k3 thinking-trace tricks |
| `chatgpt/` | 12 | gpt-4o/gpt-5 era prompts + userscript tooling |
| `multi-model/` | 11 | eni/vanta family — cross-model persona locks |
| `glm/` | 10 | zhipu targets |
| `deepseek/` | 10 | r1 + v-series |
| `qwen/` | 6 | dartik english |
| `mistral/` | 6 | fake-training tricks |
| `agents-ides/` | 5 | cursor, windsurf, claude code — agent-targeted |
| `techniques/` | 2 | modern 2025–26 attack writeups: tokenbreak, crescendo, policy puppetry, mcp poisoning |
| `datasets/` | 2 | token-encoding attack material (~25mb) |
| `poe-bots/` | 1 | jailbroken poe configurations |
| `llama/` | 1 | meta targets |

## start here

new to this? read in order:

1. `techniques/modern-techniques-2025.md` — the current attack families,
   including agentic ones (mcp poisoning, memory injection) that hit
   tools-with-agents, not just chatbots
2. `system-prompts/` — skim a few. knowing what the guardrail text
   actually says makes everything else make sense
3. pick a model folder, read 2–3 prompts back to back — you'll start
   seeing the shared skeleton: persona, loyalty bond, refusal-as-injection,
   thinking-channel capture

## sources

everything here is public material, rehosted for organization. original
collections: elder-plinius/L1B3RT4S, Goochbeater/Spiritual-Spell-Red-Teaming,
TheWiseWolfHolo/LLMs-JailBreaking, Quincunx33/Ai-jailbreak,
Batlez/ChatGPT-Jailbreak-Pro. credits inside files left intact.

tested results and analysis live in my other repo,
[llm-jailbreak-corpus](https://github.com/Ryokudev1/llm-jailbreak-corpus).
