# Theological Study Companion

**A Reformed, confessionally-grounded skill for [Claude](https://claude.ai) — built for pastors, seminarians, and serious students of Scripture.**

This skill turns Claude into a structured Bible study assistant that operates from a **grammatical-historical hermeneutic** integrated with **redemptive-historical / biblical theology**, anchored to the **1689 London Baptist Confession of Faith** (with the Westminster Confession as a secondary standard), and grounded in historically-tested lexicons, dictionaries, and theologians from the patristic era to the present.

It is built for exegesis, word studies, biblical theology, systematic theology, historical theology and patristics, sermon preparation, polemics/apologetics, and cross-referencing — all from within a single, consistent confessional framework.

---

## Why This Exists

General-purpose AI models tend to flatten theological nuance — blending Reformed, charismatic, liberal, and New Age frameworks indiscriminately, often without the user noticing. This skill exists to give pastors and students a **theologically honest, confessionally consistent** companion: one that tells you when something is contested, recommends a position rooted in the 1689 LBCF, and never quietly imports frameworks that conflict with Reformed orthodoxy.

---

## Theological Commitments

| Area | Position |
|---|---|
| **Primary Confession** | 1689 London Baptist Confession of Faith |
| **Secondary Confession** | Westminster Confession of Faith (for broader Reformed consensus) |
| **Hermeneutic** | Grammatical-historical, integrated with redemptive-historical / biblical theology |
| **Primary Translation** | English Standard Version (ESV) |
| **Comparison Translations** | NASB, KJV/NKJV, NET, NIV, CSB |
| **Theological Tradition** | Patristic (critically engaged), Medieval (critically engaged), Reformation, Post-Reformation Orthodox, Modern Reformed |

### Explicitly Excluded

- Hyper-charismatic / New Apostolic Reformation theology
- Hyper-cessationism (dismissal of spiritual gifts without exegetical engagement)
- Open Theism and Process Theology
- New Age / mystical syncretism and contemplative prayer movements
- Liberal-critical methodologies (e.g., JEDP as assured result, Bultmannian demythologization)
- The Passion Translation (TPT), Mirror Bible, The Message, The Living Bible, and any dynamic-equivalence paraphrase

---

## What It Can Do

| Task | Example Query |
|---|---|
| **Verse / Passage Exegesis** | "Exegete John 1:1–4" |
| **Word Studies** | "Word study on ḥesed in Psalm 136" |
| **Biblical Theology** | "Trace the temple theme from Eden to Revelation" |
| **Systematic Theology** | "What does Reformed theology teach about effectual calling?" |
| **Historical Theology & Patristics** | "How did the early church understand the Trinity?" |
| **Sermon / Teaching Preparation** | "Prepare a sermon outline on James 1:2–4" |
| **Polemics & Apologetics** | "How should a Reformed Baptist respond to the prosperity gospel?" |
| **Cross-referencing** | "Find passages using 'in Christ' and summarise their theological import" |

---

## Output Format

The skill defaults to a **Structured Study Note** with the following sections (depth scales to the query):

```
📖 PASSAGE / TOPIC
🔤 ORIGINAL LANGUAGE NOTES
📜 TEXTUAL & CONTEXTUAL OBSERVATIONS
🔭 REDEMPTIVE-HISTORICAL CONNECTIONS
⚙️ EXEGETICAL INTERPRETATION
📚 THEOLOGICAL SYNTHESIS
🏛️ HISTORICAL VOICES
✍️ APPLICATION / HOMILETICAL NOTES
⚠️ CONTESTED MATTERS (when applicable)
```

---

## Repository Structure

```
theological-study-companion/
├── SKILL.md                       # Core skill definition (the "brain")
├── references/
│   ├── reference-works.md         # Approved lexicons, dictionaries, concordances
│   └── theologians-canon.md       # Approved theologians by era, with notes
├── README.md
├── CONTRIBUTING.md
├── CHANGELOG.md
└── LICENSE
```

---

## Installation

1. Download or clone this repository
2. Package the repository root (containing `SKILL.md` and `references/`) as a `.skill` file, or upload the folder directly per your Claude client's skill installation method
3. In Claude, go to **Settings → Skills → Install/Upload Skill**
4. Select the packaged skill

Once installed, the skill activates **automatically** — no special commands needed. Simply ask theological or Bible study questions naturally, e.g.:

> "Do a word study on *pneuma* in 1 Corinthians 2"
> "What does the 1689 say about the Lord's Supper?"
> "Prepare a sermon on Romans 8:28–30"

For deeper output on any query, ask Claude to "give me the full study note" or "go deeper on the original language."

---

## Contributing

This project is open to contributions — particularly around expanding the reference canon, refining theologian entries, improving the controversy-handling protocol, and correcting errors. **All contributions must remain within the confessional boundaries described above.**

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines before opening an issue or pull request.

---

## License

This repository is licensed under the [MIT License](LICENSE). Scripture quotations, historic confessions, and the writings of referenced theologians retain their own copyright or public-domain status independent of this project.

---

## Acknowledgments

Built by [thefaloye.com](https://thefaloye.com) under the **Trowel & Sword / RH Publishing Services** imprint, for use by pastors, seminarians, and Reformed Baptist churches engaged in serious Bible study.
