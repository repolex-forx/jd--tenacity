# Repolex Knowledge Graph of jd/tenacity

RDF knowledge graph data for [jd/tenacity](https://github.com/jd/tenacity), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download jd/tenacity
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   └── repolex
│       └── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│           └── chunk-001.nq.gz
├── blob
│   ├── 18434bc3a3f9c06b44b010c3d2e51caf97a1fb0d.nq.gz
│   ├── 1adb67e9b7c7e411b4a2f16739069eaf08bf7aa4.nq.gz
│   ├── 39b79f6d232e9059f6937e4146b30d2946385f90.nq.gz
│   ├── 3ed312da22fc717c87714ee69665491d936ba744.nq.gz
│   ├── 56029664ae5f0ffaaa3bae3411645725a8850f3a.nq.gz
│   ├── 60f7c4ceccc064685e078891a81f3f23eff24056.nq.gz
│   ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
│   ├── bfef02d86588afa19ceb1d51156b4ef7a2e1b3ab.nq.gz
│   ├── dddc8e12580488167691ec9f5dac87f8b58646c8.nq.gz
│   ├── ec62bd62e7e64402f0853e30f8ad577ce3ec1031.nq.gz
│   ├── fca311caa7dba7ddfae791331b605c7782579791.nq.gz
│   └── ffe2fce498955b628014618b28c6bcf152466a4a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
├── filetree
│   └── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 22 files
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

## Source repository

[jd/tenacity](https://github.com/jd/tenacity)

---
*Parsed on 2026-04-11 by [repolex](https://repolex.ai)*
