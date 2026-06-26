# Entrolution

Open-source tools at the intersection of documents, AI, and scientific computing.

## Documents & Publishing

| Project | Description |
|---------|-------------|
| [CDX Format Spec](https://github.com/Entrolution/cdx-file-format-spec) | Open specification for a modern document format with semantic content, cryptographic integrity, and verifiable provenance. |
| [cdx-core](https://github.com/Entrolution/cdx-core) | Rust reference implementation for reading, writing, and validating CDX (.cdx) files. |
| [cdx-pandoc](https://github.com/Entrolution/cdx-pandoc) | Pandoc writer/reader for converting documents to and from CDX format. |

## Scientific Computing

| Project | Description |
|---------|-------------|
| [Echidna](https://github.com/Entrolution/echidna) | High-performance automatic differentiation library for Rust. Forward and reverse mode with generic scalar types. |
| [Bilby](https://github.com/Entrolution/bilby) | High-performance numerical quadrature (integration) library for Rust. Gaussian rules, adaptive methods, cubature, sparse grids. |
| [Thylacine](https://github.com/Entrolution/thylacine) | Functional Bayesian inference framework for sampling, integration, and posterior analysis with automatic differentiation and STM-based concurrency. |

## Concurrency

| Project | Description |
|---------|-------------|
| [Bengal STM](https://github.com/Entrolution/bengal-stm) | Software Transactional Memory for Cats Effect with intelligent scheduling via static analysis of transaction variable domains. |

## Developer Tools

| Project | Description |
|---------|-------------|
| [quotaline](https://github.com/Entrolution/quotaline) | Claude Code status line for your account-wide usage limits — the 5-hour and weekly windows — with a live burn rate and cap warnings. Reads only Claude Code's stdin: no token, no API calls. |
| [vastline](https://github.com/Entrolution/vastline) | Claude Code status line for vast.ai GPU usage — running/total instances, running-compute vs stopped-storage burn, account balance, and runway. Sits under any existing status line; cached off the render path with a read-only key. |
| [machineline](https://github.com/Entrolution/machineline) | Claude Code status line for local-machine health — CPU speed-limit/throttle, load, utilisation, memory pressure, swap, temperature, the hottest process, and power. Stacks under any existing status line; reads the OS off the render path. macOS. |
