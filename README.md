# CCXT

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-cryptocurrency-lightgrey)

> Anticloud-hardened packaging of the upstream project `CCXT` in category **CRYPTOCURRENCY**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CRYPTOCURRENCY · **Upstream:** https://github.com/ccxt/ccxt · **Upstream pin:** `f0aca06eb7482f083bed8406fadfcc0c05e45b1c` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# CCXT – CryptoCurrency eXchange Trading Library

[![NPM Downloads](https://img.shields.io/npm/dy/ccxt.svg)](https://www.npmjs.com/package/ccxt) [![npm](https://img.shields.io/npm/v/ccxt.svg)](https://npmjs.com/package/ccxt) [![PyPI](https://img.shields.io/pypi/v/ccxt.svg)](https://pypi.python.org/pypi/ccxt) [![NuGet version](https://img.shields.io/nuget/v/ccxt)](https://www.nuget.org/packages/ccxt) [![GoDoc](https://img.shields.io/github/v/tag/ccxt/ccxt?label=go)](https://godoc.org/github.com/ccxt/ccxt/go/v4) [![Mvn](https://badges.mvnrepository.com/badge/io.github.ccxt/ccxt/badge.svg?label=mvn)](https://mvnrepository.com/artifact/io.github.ccxt/ccxt) [![Packagist](https://img.shields.io/packagist/v/ccxt/ccxt)](https://packagist.org/packages/ccxt/ccxt) [![Crates.io](https://img.shields.io/crates/v/ccxt.svg)](https://crates.io/crates/ccxt) [![Supported Exchanges](https://img.shields.io/badge/exchanges-104-blue.svg)](https://github.com/ccxt/ccxt/wiki/Exchange-Markets) [![CCXT Chat in Telegram](https://telegram-badge.vercel.app/api/telegram-badge?channelId=@ccxt_chat&label=chat)](https://t.me/ccxt_chat) [![CCXT Discord Server](https://img.shields.io/discord/690203284119617602?logo=discord&logoColor=white)](https://discord.gg/ccxt) [![Follow CCXT at x.com](https://img.shields.io/twitter/follow/ccxt_official.svg?style=social&label=CCXT)](https://x.com/ccxt_official)

A crypto trading API with more than 100 exchanges and prediction markets in JavaScript / TypeScript / Python / C# / PHP / Go / Java / Rust.

### [Install](#install) · [Usage](#usage) · [Manual](https://github.com/ccxt/ccxt/wiki) · [FAQ](https://github.com/ccxt/ccxt/wiki/FAQ) · [Examples](https://github.com/ccxt/ccxt/tree/master/examples) · [Contributing](https://github.com/ccxt/ccxt/blob/master/CONTRIBUTING.md) · [Disclaimer](#disclaimer) · [Social](#social)

The **CCXT** library is used to connect and trade with cryptocurrency exchanges worldwide. It provides quick access to market data for storage, analysis, visualization, indicator development, algorithmic trading, strategy backtesting, bot programming, and related software engineering.

It is intended to be used by **coders, developers, technically-skilled traders, data-scientists and financial analysts** for building trading algorithms.

Current feature list:
- supports 100+ cryptocurrency exchanges and prediction markets:
  - Polymarket
  - Kalshi
  - Hyperliquid
  - Limitless
  - Myriad
  - more coming soon!
- implements public and private APIs, both REST and WebSocket
- optionally normalizes data for cross-exchange analytics and arbitrage
- has an out of the box unified API that is extremely easy to integrate
- ideal for AI agents, LLMs and vibe coding
- works in Node 18+, Python 3, PHP 8.1+, netstandard2.0/2.1, Go 1.20+, Java 21+ and web browsers

## CCXT Terminal

[![CCXT Terminal: One App. Every Market. High-performance trading with real-time sync](https://github.com/user-attachments/assets/11f1ead4-24bb-49d5-bb67-cd8f4be35ad6)](https://terminal.ccxt.com/?utm_source=github&utm_medium=referral&utm_campaign=web_terminal_launch&utm_content=readme_banner)

[**CCXT Terminal**](https://terminal.ccxt.com/?utm_source=github&utm_medium=referral&utm_campaign=web_terminal_launch&utm_content=readme_text_link) is a non-custodial trading platform built on the same open-source CCXT library you already use. It takes you from market analysis to order execution in one place, pairing a scalper DOM and real-time liquidity visualization with low-latency order routing across multiple exchanges.

## See Also

- <sub>[![Freqtrade](https://user-images.githubusercontent.com/1294454/114340585-8e35fa80-9b60-11eb-860f-4379125e2db6.png)](https://www.freqtrade.io)</sub> **[Freqtrade](https://www.freqtrade.io)** – leading opensource cryptocurrency algorithmic trading software!
- <sub>[![OctoBot](https://user-images.githubusercontent.com/1294454/132113722-007fc092-7530-4b41-b929-b8ed380b7b2e.png)](https://www.octobot.online)</sub> **[OctoBot](https://www.octobot.online)** – cryptocurrency trading bot with an advanced web interface.
- <sub>[![TokenBot](https://user-images.githubusercontent.com/1294454/152720975-0522b803-70f0-4f18-a305-3c99b37cd990.png)](https://tokenbot.com/?utm_source=github&utm_medium=ccxt&utm_campaign=algodevs)</sub> **[TokenBot](https://tokenbot.com/?utm_source=github&utm_medium=ccxt&utm_campaign=algodevs)** – discover and copy the best algorithmic traders in the world.

## Certified Cryptocurrency Exchanges

|logo                                                                                                                                                                         |id             |name                                                                                     |ver                                                                                                                                  |type                                                                                                    |certified                                                                                                                    |pro                                                                                                |discount                                                                                                                                                                                                      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|-----------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------:|--------------------------------------------------------------------------------------------------------|-------------------------

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, package-lock.json; scanned in UPSTREAM_CLONE)
- Top-level source layout: `build/`, `cli/`, `cs/`, `dist/`, `examples/`, `go/`, `java/`, `js/`, `mcp/`, `php/`, `python/`, `rust/`
- Snapshot size: **9081 files**, **5839293 lines of code** (measured; see Benchmarks)
- Primary languages: `.ts` (1396), `.md` (1353), `.py` (1013), `.cs` (956), `.php` (956), `.js` (758)
- Upstream commit pinned for this packaging: `f0aca06eb7482f083bed8406fadfcc0c05e45b1c`

---

## Installation

The **CCXT** library is used to connect and trade with cryptocurrency exchanges worldwide. It provides quick access to market data for storage, analysis, visualization, indicator development, algorithmic trading, strategy backtesting, bot programming, and related software engineering.

It is intended to be used by **coders, developers, technically-skilled traders, data-scientists and financial analysts** for building trading algorithms.

Current feature list:
- supports 100+ cryptocurrency exchanges and prediction markets:
  - Polymarket
  - Kalshi
  - Hyperliquid
  - Limitless
  - Myriad
  - more coming soon!
- implements public and private APIs, both REST and WebSocket
- optionally normalizes data for cross-exchange analytics and arbitrage
- has an out of the box unified API that is extremely easy to integrate
- ideal for AI agents, LLMs and vibe coding
- works in Node 18+, Python 3, PHP 8.1+, netstandard2.0/2.1, Go 1.20+, Java 21+ and web browsers

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

The **CCXT** library is used to connect and trade with cryptocurrency exchanges worldwide. It provides quick access to market data for storage, analysis, visualization, indicator development, algorithmic trading, strategy backtesting, bot programming, and related software engineering.

It is intended to be used by **coders, developers, technically-skilled traders, data-scientists and financial analysts** for building trading algorithms.

Current feature list:
- supports 100+ cryptocurrency exchanges and prediction markets:
  - Polymarket
  - Kalshi
  - Hyperliquid
  - Limitless
  - Myriad
  - more coming soon!
- implements public and private APIs, both REST and WebSocket
- optionally normalizes data for cross-exchange analytics and arbitrage
- has an out of the box unified API that is extremely easy to integrate
- ideal for AI agents, LLMs and vibe coding
- works in Node 18+, Python 3, PHP 8.1+, netstandard2.0/2.1, Go 1.20+, Java 21+ and web browsers

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

A crypto trading API with more than 100 exchanges and prediction markets in JavaScript / TypeScript / Python / C# / PHP / Go / Java / Rust.

### [Install](#install) · [Usage](#usage) · [Manual](https://github.com/ccxt/ccxt/wiki) · [FAQ](https://github.com/ccxt/ccxt/wiki/FAQ) · [Examples](https://github.com/ccxt/ccxt/tree/master/examples) · [Contributing](https://github.com/ccxt/ccxt/blob/master/CONTRIBUTING.md) · [Disclaimer](#disclaimer) · [Social](#social)

The **CCXT** library is used to connect and trade with cryptocurrency exchanges worldwide. It provides quick access to market data for storage, analysis, visualization, indicator development, algorithmic trading, strategy backtesting, bot programming, and related software engineering.

It is intended to be used by **coders, developers, technically-skilled traders, data-scientists and financial analysts** for building trading algorithms.

Current feature list:
- supports 100+ cryptocurrency exchanges and prediction markets:
  - Polymarket
  - Kalshi
  - Hyperliquid
  - Limitless
  - Myriad
  - more coming soon!
- implements public and private APIs, both REST and WebSocket
- optionally normalizes data for cross-exchange analytics and arbitrage
- has an out of the box unified API that is extremely easy to integrate
- ideal for AI agents, LLMs and vibe coding
- works in Node 18+, Python 3, PHP 8.1+, netstandard2.0/2.1, Go 1.20+, Java 21+ and web browsers

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, package-lock.json |
| Files in snapshot | 9081 |
| Lines of code | 5839293 |
| Dependency references | 467 |
| Dependencies by ecosystem | cargo: 160, go: 123, npm: 164, pypi: 20 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @noble/curves | 2.2.0 | package.json |
| npm | @noble/hashes | 2.2.0 | package.json |
| npm | @scure/base | 2.2.0 | package.json |
| npm | @scure/starknet | 2.2.0 | package.json |
| npm | undici | 7.29.1 | package.json |
| npm | ws | 8.21.0 | package.json |
| npm | @eslint/js | ^9.39.4 | package.json |
| npm | @rollup/plugin-commonjs | ^21.0.3 | package.json |
| npm | @rollup/plugin-json | ^4.1.0 | package.json |
| npm | @rollup/plugin-node-resolve | ^15.2.3 | package.json |
| npm | @rspack/cli | ^2.0.8 | package.json |
| npm | @rspack/core | ^2.0.8 | package.json |
| npm | @types/node | ^25.9.3 | package.json |
| npm | @typescript-eslint/eslint-plugin | ^8.61.0 | package.json |
| npm | @typescript-eslint/parser | ^8.61.0 | package.json |
| ... | (452 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `Dockerfile`
- `docker-compose.yml`
- `exchanges.cfg`
- `package.json`
- `pyproject.toml`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing To The CCXT Library

- [How To Submit A Question Or Issue](#how-to-submit-an-issue)
- [How To Contribute Code](#how-to-contribute-code)
  - [What You Need To Have](#what-you-need-to-have)
  - [What You Need To Know](#what-you-need-to-know)

## How To Submit An Issue

Read the notes when opening a [new issue on github](https://github.com/ccxt/ccxt/issues/new/choose) and provide the requested details, so we can assist you better. You can also read the [Troubleshooting](https://github.com/ccxt/ccxt/wiki/Manual#troubleshooting) section.

### Reporting Vulnerabilities And Critical Issues

If you found a security issue or a critical vulnerability and reporting it in public would impose risk – please feel free to send us a message to <a href="mailto:info@ccxt.trade">info@ccxt.trade</a>.

## How To Contribute Code

- **[MAKE SURE YOUR CODE IS UNIFIED](https://github.com/ccxt/ccxt/blob/master/CONTRIBUTING.md#derived-exchange-classes)!**

  **↑ This is the most important rule of all!!!**

- **BEFORE ANY PUSH MAKE SURE YOU RUN THIS COMMAND LOCALLY: `git config core.hooksPath .git-templates/hooks`**

- **PLEASE, DO NOT COMMIT THE FOLLOWING FILES IN PULL REQUESTS:**

  - `/build/*` (these are generated automatically)
  - `/js/*` (these are compiled from the typescript version)
  - `/php/*` (except for base classes)
  - `/python/*` (except for base classes)
  - `/cs/*` (except for base classes)
  - `/ccxt.js`
  - `/README.md` (exchange lists are generated automatically)
  - `/package.json`
  - `/package.lock`
  - `/wiki/*` (except for real edits, exchange lists are generated automatically)
  - `/dist/ccxt.browser.js` (this is also browserified automatically)

  These files are generated ([explained below](https://github.com/ccxt/ccxt/blob/master/CONTRIBUTING.md#multilanguage-support)) and will be overwritten upon build. Please don't commit them to avoid bloating the project which is already quite large. Most often, you have to commit just one single source file to submit an edit to the implementation of an exchange.

- **PLEASE, SUBMIT ATOMIC EDITS, ONE PULL REQUEST PER ONE EXCHANGE, DO NOT MIX THEM**
- **MAKE SURE YOUR CODE PASSES ALL SYNTAX CHECKS BY RUNNING `npm run build`**

## Pending Tasks

Below is a list of functionality we would like to have implemented and fully **unified** in the library in the first place at this time. Most of these tasks are already in progress, implemented for some exchanges, but not all of them:

- Margin trading
- Lev

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright © 2024 Igor Kroitor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `CCXT` (category: CRYPTOCURRENCY)
- **Upstream URL:** https://github.com/ccxt/ccxt
- **Pinned commit (SHA):** `f0aca06eb7482f083bed8406fadfcc0c05e45b1c`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`049a676c1377efb1fec458be4cb919ab6caadff83804010a787a419fc51d47d9`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

