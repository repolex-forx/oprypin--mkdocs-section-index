# Repolex Knowledge Graph of oprypin/mkdocs-section-index

RDF knowledge graph data for [oprypin/mkdocs-section-index](https://github.com/oprypin/mkdocs-section-index), parsed by [repolex](https://repolex.ai).

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
rlex download oprypin/mkdocs-section-index
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5b710e75cbe5f81846fb8dc79211d7a06b2d090b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5b710e75cbe5f81846fb8dc79211d7a06b2d090b
│           └── chunk-001.nq.gz
├── blob
│   ├── 03319a92e0f0a38085d615c81937f87b4c3c70e7.nq.gz
│   ├── 12c1dd1cfda6c84ddb64ba0e8c8f753965bfc5a0.nq.gz
│   ├── 19463235140f970c1aff3acbfa1b67bc81b61595.nq.gz
│   ├── 1f11ffc1949046a37f8d7cacd0f13ea7bd559047.nq.gz
│   ├── 255f3d4bfa620772412006ae4de925ef1345b0e9.nq.gz
│   ├── 257cc5642cb1a054f08cc83f2d943e56fd3ebe99.nq.gz
│   ├── 2bfb7ecb1dadb6a9867853235b8fc78a2c7836c2.nq.gz
│   ├── 2c7ffd4b190bfdb2573ff56849632ffcb93d7ea8.nq.gz
│   ├── 3e182441c4ed84cac8154bbb1a0957361d9f066e.nq.gz
│   ├── 43b1e975849722e4a73b5eba9ae454b03629d591.nq.gz
│   ├── 5b0a998d29dd162fe7f56512e28466807830b938.nq.gz
│   ├── 612c7a5e0d17657e51018285d9850b8fa8e76174.nq.gz
│   ├── 61bcd64c4e1389fa2f19656340ecf22673354d49.nq.gz
│   ├── 66a71ea55c4617079a3d84bc3aa96397148cdf3b.nq.gz
│   ├── 67cdd4cb2bb59c84d99f96ac71a49ef612314f50.nq.gz
│   ├── 748c28a5b96cdd8b5fbb58b91c97177cdb5c34ef.nq.gz
│   ├── 76018072e09c5d31c8c6e3113b8aa0fe625195ca.nq.gz
│   ├── 7f095bb03cddff053969b4116c1a0120b6864dc0.nq.gz
│   ├── 943fb721bf1c1483a7b674f4226613b0ba7ac030.nq.gz
│   ├── 9a4c65827cff01e8aa4f13d855a44b3878ffffcb.nq.gz
│   ├── 9eab69073d0021feb5544e8b35a6c8401e14ae9c.nq.gz
│   ├── a28405267943a31d95b5917aa17dea7dc7fa9e95.nq.gz
│   ├── b1a0a02549f91996f426ed53b9fdc75c2e48c23e.nq.gz
│   ├── b351b187fb53c4e9d62b07d354e15b82f32a7294.nq.gz
│   ├── b384790b546b1c9314cdb51b333df7bf41740a8f.nq.gz
│   ├── c194f2e3610d3a4c2d0ee0cb3d3ccec47714d8c8.nq.gz
│   ├── c6b42965ef142ea704715feab82725bbcbe25ccc.nq.gz
│   ├── d0d23352ea08c8e31b465da4e9f270458d6d52bf.nq.gz
│   ├── d11cd80280ab293b9501162c17e61952dd41596e.nq.gz
│   ├── d745acfe554d3278aaabaed9fb3513fea5eb5dfb.nq.gz
│   ├── e5a0c275d0e8050bdffbd5f21e0ed24868cf3a21.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e764db4cd372946cd8f6149ad16b0a2e2d747131.nq.gz
│   ├── e9b500a922783518b4a3e47ada98b8236b8ed9f2.nq.gz
│   ├── ec9eeaa9841534a0719b66de494c06946983a69c.nq.gz
│   ├── f39da24d63e5c6cfde6c2dad7215bca2b4f34dc8.nq.gz
│   ├── f738281a3a4cbe42501b526f26da0a41380baf76.nq.gz
│   ├── f958d832241973fd6be05f413efc4a31c7fa1aae.nq.gz
│   ├── fa7367201ead6678fc64fbed416337a473a3fb1e.nq.gz
│   └── fde455f4ae811f64049b7b34683636e29df0bed9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5b710e75cbe5f81846fb8dc79211d7a06b2d090b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 48 files
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

[oprypin/mkdocs-section-index](https://github.com/oprypin/mkdocs-section-index)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
