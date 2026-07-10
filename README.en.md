# Hi there 👋

**Non-IT job. No college degree. Zero coding experience. A low-spec laptop. And I still built a patent-application-level system through "vibe coding" — in my mid-40s.**

I can't write code. I have no engineering background.
Yet using nothing but conversations with AI, I've made it all the way through actual patent application prep — drafting the filing documents and answering questions from a patent attorney.

---

## 🧑‍💻 My "specs" (no exaggeration here)

| Item | Detail |
|---|---|
| Job | Non-IT field |
| Education | No college degree |
| Coding skill | None (I didn't even know the difference between a variable and a function at the start) |
| Dev machine | Core i5-7200U / 8GB RAM (not exactly a powerhouse) |
| Age | Mid-40s |
| Tools | Persistence and conversations with AI — that's it |

This started as a personal commitment: I didn't want "I don't have the environment or the specs" to be an excuse.

---

## 🔬 What I built: Prime Source (patent application in progress)

**Prime Source** is a system that compares and analyzes primary sources against secondary information.

- Comparing primary sources against online news coverage
- Re-analyzing Claim Review fact-check data
- Built with a fixed priority order: **hallucination resistance > robustness > low latency**

Starting from a place where I couldn't write a single line of code, I worked through spec design, logic verification, and an accumulating set of test cases entirely through dialogue with AI — and moved all the way into actual patent application prep, including drafting the filing documents and answering questions from a patent attorney.

> I can't share detailed design or implementation yet due to the ongoing filing process, but **I plan to write it up in full once the application is complete**.

---

## 🧭 What came out of that process: the CGP method (Core Growth Prompting)

While building Prime Source, I kept asking myself: how does someone who can't code work with AI without the design falling apart? Working through that question led to a general-purpose design process I call **CGP (Core Growth Prompting)**.

### Core principles of CGP

- **One persona, multiple intelligences**: keep a single conversational interface with the user; treat backend analysis modules as functions that return structured output, not autonomous agents
- **Fixed priority order**: hallucination resistance > robustness > low latency — never compromised, even for proposals that would trade verification steps for speed
- **Never trust the LLM's self-report**: confidence or self-assessed consistency isn't verification. Verification has to be deterministic — string matching, calculations, rule-based checks
- **Pseudocode isn't enough**: never settle for "this should work" in prose. Always turn it into real code and run it against real data
- **Record decisions as they happen**: reconstructing a decision log after the fact tends to produce a plausible-sounding but inaccurate account. Log each decision right when it's finalized

Building on this personal-use version, I've also developed a derivative aimed at **high-stakes public contexts where values genuinely conflict** — privacy vs. transparency being a typical example. Its core shifts to "structure the conflict, don't erase it": AI is limited to detecting, organizing, and logging tensions, never making the final call on which side wins.

---

## 💡 What I want this to show

"Vibe coding" tends to get dismissed as something that only produces toy-level prototypes.
I wanted to show, in a concrete and verifiable way, that even starting from non-IT, no degree, and a low-spec laptop, it's possible to reach a real-world milestone like patent application prep — working alongside AI the whole way.

I don't think the value here is technical skill. I think it's in *how* you talk to AI, how you verify what it produces, and how you record decisions along the way. CGP is my attempt to turn that process into something others can reproduce.

### 📖 CGP Method Primers

- [`Primer/cgp-primer-parsonal.en.md`](./Primer/cgp-primer-parsonal.en.md) — Personal-use primer (English)
- [`Primer/cgp-primer-public.en.md`](./Primer/cgp-primer-public.en.md) — Primer for high-publicness cases (English)

---

📫 Feel free to reach out with questions or collaboration ideas.
