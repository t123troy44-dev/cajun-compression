# CAJUN Compression

**A causal compression algorithm — reconstruct, don't just store.**

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![Ratio](https://img.shields.io/badge/Ratio-up%20to%2057%3A1-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

> Built by **Troy Thompson** — [fridaysovereign.com](https://fridaysovereign.com)

---

## Overview

CAJUN is a causal compression algorithm: instead of storing data verbatim, it stores a compact causal "seed" plus the rules to regenerate the original from it — an approach closer to describing *how to rebuild* something than to zipping bytes. On suitable inputs it reaches compression ratios up to **57:1**.

The core idea is Kolmogorov-flavored: the shortest description of structured data is often a small generator, not the data itself. CAJUN builds that generator and reconstructs on demand. It's the compression work underneath several of the FRIDAY patent filings.

---

## Tech Stack

- **Language:** Python
- **Approach:** causal seed + reconstruction rules
- **Domain:** structured / self-similar data

---

## Features

- **Causal reconstruction** — store a generator, not raw bytes
- **Up to 57:1** compression on suitable inputs
- **Seed-based** representation (hierarchical causal seeds)
- Foundation for the CAJUN patent family

---

## Related

- [friday-patent-portfolio](https://github.com/t123troy44-dev/friday-patent-portfolio) — the filings this underpins
- [friday-consciousness](https://github.com/t123troy44-dev/friday-consciousness) — uses causal representations
- Portfolio: [fridaysovereign.com](https://fridaysovereign.com)

---

*Built entirely through AI pair-programming — 600+ documented sessions.*
