<div align="center">
<img src="https://raw.githubusercontent.com/jimmyjames177414/jimmyjames177414/main/docs/banner.jpg" alt="jimmyjames177414" width="100%">
</div>

## I build tools that measure what AI agents actually do

Most tooling around coding agents helps them do more. These mostly help you find out what they
*already did* — what context they needed, what they changed, what they broke, and what they
quietly got wrong.

Every one ships a `NOVELTY.md`: the prior-art search run **before** any code, including a table
of claims the project is **not allowed to make**. Several were renamed or cut down by that
gate. It is the most useful file in each repo.

---

### Watching agents work

| | |
|---|---|
| **[rollcall](https://github.com/jimmyjames177414/rollcall)** | Which worktree does each running agent own — and which work does *nobody* own? Joins the OS process table, provider session data and git. Anthropic's docs say to remove leftover worktrees by hand; this finds them. |
| **[sincelast](https://github.com/jimmyjames177414/sincelast)** | Your agent read that file four minutes ago. Another agent has changed it since. Read-dependency invalidation for independently-launched sessions. |
| **[claude-memory-atlas](https://github.com/jimmyjames177414/claude-memory-atlas)** | Renders a directory of Claude Code auto-memory files as one offline interactive knowledge graph. |

### Measuring what context is worth

| | |
|---|---|
| **[stopless](https://github.com/jimmyjames177414/stopless)** | Which words does your prompt actually need? Learned stopwords, measured per model. |
| **[stopbench](https://github.com/jimmyjames177414/stopbench)** | How much *language* does an LLM need? A contributable linguistic-ablation benchmark. |
| **[mincontext](https://github.com/jimmyjames177414/mincontext)** | Delta debugging for AI failures. Shrink a failing agent context to the part that actually causes it. |
| **[toolsweep](https://github.com/jimmyjames177414/toolsweep)** | Which tool-schema decision is costing you accuracy? Controlled ablation over function definitions. |

### Making evaluation honest

| | |
|---|---|
| **[errorbars](https://github.com/jimmyjames177414/errorbars)** | The statistics your LLM eval does not do. Power analysis, paired bootstrap, minimum detectable effect. |
| **[inconclusive](https://github.com/jimmyjames177414/inconclusive)** | Your agent test says FAIL. Did the property fail, or did the trace just end? Three-valued verdicts. |
| **[knowwhen](https://github.com/jimmyjames177414/knowwhen)** | Every agent benchmark asks whether it finished. This one asks whether it should have started. |

### Keeping agents accountable

| | |
|---|---|
| **[assumptionledger](https://github.com/jimmyjames177414/assumptionledger)** | Make an agent state what it is assuming, in a form you can execute against reality. |
| **[validwhile](https://github.com/jimmyjames177414/validwhile)** | Evidence-bound agent memory. Every fact carries an executable check for whether it is still true. |

### Other things

| | |
|---|---|
| **[worker-king](https://github.com/jimmyjames177414/worker-king)** | Always-on AI desktop assistant for Windows. Listens, and delegates real work to Claude Code. |
| **[local-transcription](https://github.com/jimmyjames177414/local-transcription)** | Fully offline Windows transcription with speaker memory, and an optional live meeting AI. No cloud, ever. |
| **[claude-roundtable](https://github.com/jimmyjames177414/claude-roundtable)** | Two Claude personas argue a topic adversarially, streamed live in your terminal. |

---

<div align="center">
<img src="https://raw.githubusercontent.com/jimmyjames177414/jimmyjames177414/main/docs/avatar.png" width="72" alt="jimmyjames177414">

Everything here is Apache-2.0 or MIT, local-first, and runs without an account.

</div>
