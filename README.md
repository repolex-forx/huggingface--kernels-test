# Repolex Knowledge Graph of huggingface/kernels-test

RDF knowledge graph data for [huggingface/kernels-test](https://github.com/huggingface/kernels-test), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download huggingface/kernels-test
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 143c28350821f99104a5cc9757e4c65ca7dc2995
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 143c28350821f99104a5cc9757e4c65ca7dc2995
│           └── chunk-001.nq.gz
├── blob
│   ├── 08ff0970c5434d7afbe3ea0d3e8ba0d0d617bc28.nq.gz
│   ├── 103c610f4a529f98b5ec95433ca279a21e85720a.nq.gz
│   ├── 1361c138aa1d0234d29aedd09003b385be989f96.nq.gz
│   ├── 141f8212544823ea3a463952801af57b0bb9a82b.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1b7f728a9a93e0948d0ec86e1dc484aff6727ea6.nq.gz
│   ├── 2f22f76a96965d33c78648e51bb1b028816e37b3.nq.gz
│   ├── 32a745f1702757895c9a25084632a74e690a55c3.nq.gz
│   ├── 3ae7a1c8297b7a0698ea4c5d0041f7faff75444a.nq.gz
│   ├── 3c9ac203ee7c192801c801f55198ea923be065bd.nq.gz
│   ├── 3cff04d76637723d8cf3345cccf91a145a7fd30f.nq.gz
│   ├── 45a90a97bffe2f2359bb33bf31d385f7be19e2cd.nq.gz
│   ├── 4bd5a477d4d2dc202c8e68cbf462d451143657fe.nq.gz
│   ├── 4cd0dcfa3801d6a577ec2c59351c38adf9a61904.nq.gz
│   ├── 4dcaf8670ba9e8733abc0cbc616322cae8eb4029.nq.gz
│   ├── 4e239a0c46820f9cc5416b378988c46574b47f3a.nq.gz
│   ├── 5ed3a4fabc00bfa651db5bfc65327de171af76ac.nq.gz
│   ├── 66f8ceea474e33fc7f9a74962d0dcdfac3c02726.nq.gz
│   ├── 677bca5ff431398c3a250f3173cc40f43c21ba46.nq.gz
│   ├── 6fcaafa3ea40354b7ae18fd91e80f26347466000.nq.gz
│   ├── 70cfcbc8a0bcba26c2d52fedd3428b1c19e5e76a.nq.gz
│   ├── 749e9df22bb8dceafb2abaec44bc357b948d87a7.nq.gz
│   ├── 77eda797e7b1e6aba69608d0c63168ba0720cfeb.nq.gz
│   ├── 7800a2ef74dd10edb3ad0a3b8e429772d00ed2bf.nq.gz
│   ├── 7ca099984268a392e81caa53648468467f6ce670.nq.gz
│   ├── 8409908f5dd6217b7e53b8a8ed532d2c5e4c025a.nq.gz
│   ├── 882d98106934cd6df6e6d743e77606ac09e332c9.nq.gz
│   ├── 88d440b2365d9455ef07c2e93254f9f1ee210e5e.nq.gz
│   ├── 896102b5c0a86876bb564c50b777ee517a99633a.nq.gz
│   ├── 8c40ca53cd4448760afd64b80f47df57d3f7519e.nq.gz
│   ├── 927ad93fd78d6941348bc80a85d4a95044f05f89.nq.gz
│   ├── 92ecc33da0bc2dc87a58053dc021008db9ef0127.nq.gz
│   ├── 9d27631deba1b96e33cb7f146caf38bd0c2b2a95.nq.gz
│   ├── 9dfd44e6fa8b95aa5402e69639277d6cd03adc33.nq.gz
│   ├── 9f52e73f9875f63447e3e1e3d33c2d34ea40468c.nq.gz
│   ├── a51fee218ae77b3736b81f62f993ffa0c6d25402.nq.gz
│   ├── af986e61b7285b97ce36fd755daf1305265ca6e6.nq.gz
│   ├── b0f9a926c28da506d1715e2d015fa8d6dd1ccf3c.nq.gz
│   ├── b8f691d6e6a7f83400d61cadda6d16a10e7cf304.nq.gz
│   ├── b970ce415b73e6c564a1ac810172a41b1894a06c.nq.gz
│   ├── c345642b623da3fdab0e7fb85c26e6551a4b7e67.nq.gz
│   ├── c728f7ee51ce659957089168f82a3398cb23692c.nq.gz
│   ├── cc921c56978eef90338b4e0b5197217e411b4cd3.nq.gz
│   ├── cd2261bb3204e10e26cf228b68af30a2dc10b4d9.nq.gz
│   ├── d2a204aecc4e6db9c61ecdddbf07a7b2520b450f.nq.gz
│   ├── d69753565c028820867dfb6134101113c7c07620.nq.gz
│   ├── d6c7ed2cb329ebf098be31188b8b263a6e11bce8.nq.gz
│   ├── d76c87491e1f033d7bb6898ac1d3ea15f136ee7c.nq.gz
│   ├── daf642797c96ea5f55dc52ac8d65863d0b949fcb.nq.gz
│   ├── df435cd106d10443083befffdef10aa742f224f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c37f02442eb3288ece6a68e700ca086609e595.nq.gz
│   ├── eb7b21cd9d00114787f52463af119cb39b479f80.nq.gz
│   └── ec4bfff27d73458e5d50378a9784afe4c1dd0720.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 143c28350821f99104a5cc9757e4c65ca7dc2995.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 61 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[huggingface/kernels-test](https://github.com/huggingface/kernels-test)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
