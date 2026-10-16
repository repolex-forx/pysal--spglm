# Repolex Knowledge Graph of pysal/spglm

RDF knowledge graph data for [pysal/spglm](https://github.com/pysal/spglm), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/spglm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 69a720d51ea3fa714b4a8e31f0463a2b4bba7323
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 69a720d51ea3fa714b4a8e31f0463a2b4bba7323
│           └── chunk-001.nq.gz
├── blob
│   ├── 0594f99b314e94fb9e51fd8a0a3468700e4e0a39.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 132152ba2a1b1e6c5156197cbf61eb5861decc8a.nq.gz
│   ├── 1ddcdc6c8b284888713aca20e0cc1d7b8936a68b.nq.gz
│   ├── 3573cccbbb90c774f14aa9533587cd0e3f83ba46.nq.gz
│   ├── 36814ac269f9ca40f09183885c00f69de09f14de.nq.gz
│   ├── 39e0101f18f9eaacef9eb5a0f00dd2755e2d002c.nq.gz
│   ├── 3cc6b14ee3a8b76fc0da2c3dc2a1ca4ef38a9f50.nq.gz
│   ├── 457848bcfe0044d48fe9ca6c5aedd7354daf511f.nq.gz
│   ├── 458034d590b71af9d1e6ceefff9bdebc0ab70c72.nq.gz
│   ├── 4590e8df01e88e1e4177d82e51b666bb1781bb0c.nq.gz
│   ├── 45d5f87fe9c47473df1de10ea9b797319ee90c3b.nq.gz
│   ├── 470fba43792cefa6124ce50a63fc468e9ce96e07.nq.gz
│   ├── 4f6fc36f2af02c4bc0aeef8b21974b4b6bc45486.nq.gz
│   ├── 500eeaee914d4fcef7c73136f5037e0592dbbe8b.nq.gz
│   ├── 505388de586f4e0e6c8bbd7624ac4ca8e95c4bfb.nq.gz
│   ├── 5a5af4e6e70c0d0bef50a3ed87994341f9d0879a.nq.gz
│   ├── 5bb5e1d9ae26fa4be96fac2a42ce4287111595ea.nq.gz
│   ├── 63178ab96476297dd478e0bf42417c43b22990f6.nq.gz
│   ├── 6e0980aec45da1ae2df789399bba6906ce5a69f5.nq.gz
│   ├── 7640976c1be2c65f90503131b26c49a7916ce784.nq.gz
│   ├── 7b9821f28da17b03e1225aa73da915e725b18c98.nq.gz
│   ├── 889919c0b2b6df7c1c18441e4e778c27fbaa2d64.nq.gz
│   ├── 8cc0c56b59de4913e1b0b99b1c0b7b7177e49d1c.nq.gz
│   ├── a05dae9acf383ab57b0e7f1422b37a4372954d07.nq.gz
│   ├── a1d18c549b24a057a7959918ed9b305365cd5eb3.nq.gz
│   ├── a221e6fdcd05e4d41e7b3e23923acdaee0ba5cdb.nq.gz
│   ├── a6a32dcb874354b686342fde87c68e91c6491c29.nq.gz
│   ├── a7be72b2754f0ec9952d2411161c401a61cc37e1.nq.gz
│   ├── b07f6b931edc3ac6b2c3794ae30fbc6c5a749b72.nq.gz
│   ├── b15eccca66a8a2cb29b9d50b06b289078dfbfc94.nq.gz
│   ├── ba3f53d06e8920d815026e2e3d8fb0c94433d68a.nq.gz
│   ├── cb4c93727c7bb41af643d7611bb235dc561f7f0c.nq.gz
│   ├── ce72652ca102a51c3a43a52aad924a51fb5bdea4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6aac71768a52df200f13c65ac0cd3bde479f897.nq.gz
│   ├── f00d45e87605fd374bdd8068273259ae65b3106c.nq.gz
│   ├── f3cd89bb225bac8212f1534175b176f9b2e2756d.nq.gz
│   ├── f54354496e0c4488ad7b8721987907d94374858f.nq.gz
│   ├── f9499b13a9a900b446174fd2c4f15a09f3ca24f6.nq.gz
│   ├── fdf32ad7946daa2221fcc286bf1a3470244c2c80.nq.gz
│   └── fec5d65968677cbac84727211b55f011dacaf8d6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 69a720d51ea3fa714b4a8e31f0463a2b4bba7323.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[pysal/spglm](https://github.com/pysal/spglm)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
