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
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│   │   │   └── chunk-001.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372
│   │   │   └── chunk-001.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│   │   │   └── chunk-001.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│   │   │   └── chunk-001.nq.gz
│   │   └── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67.nq.gz
│   │   └── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a.nq.gz
│   └── repolex
│       ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│       │   └── chunk-001.nq.gz
│       ├── 36a09fa4dadb67b81359078c61f418a971f57372
│       │   └── chunk-001.nq.gz
│       ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e
│       │   └── chunk-001.nq.gz
│       ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db
│       │   └── chunk-001.nq.gz
│       ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465
│       │   └── chunk-001.nq.gz
│       ├── a7a6a432530400a67ed33416b5e76727217738fa
│       │   └── chunk-001.nq.gz
│       ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│       │   └── chunk-001.nq.gz
│       ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│       │   └── chunk-001.nq.gz
│       └── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00522ef940b6e75bf4a2f3e92b9f4d186ea6ed5f.nq.gz
│   ├── 00f054b8ba656452c303bf769d384295e6941548.nq.gz
│   ├── 0248d524f74fd7c23beed1fff7677c3189da0fe7.nq.gz
│   ├── 0d100f69cbd646e8189ba333fd9b100ab78fb52d.nq.gz
│   ├── 18434bc3a3f9c06b44b010c3d2e51caf97a1fb0d.nq.gz
│   ├── 1adb67e9b7c7e411b4a2f16739069eaf08bf7aa4.nq.gz
│   ├── 2cacb7744a216d0db9b5a56c8bbf31533f0d7aab.nq.gz
│   ├── 368d8e49df52e78dd93596dedf349654a2441473.nq.gz
│   ├── 39b79f6d232e9059f6937e4146b30d2946385f90.nq.gz
│   ├── 3d224b2748c81054de712016885ce2410c5bdf6f.nq.gz
│   ├── 3ed312da22fc717c87714ee69665491d936ba744.nq.gz
│   ├── 42bf3e1f4cd0131ace6ceccff5612155674e6ba4.nq.gz
│   ├── 43c9000707c911f8830279560a4ca3e7fe992e10.nq.gz
│   ├── 4803ca403a793c3bea781365d2ed4279aedc76f3.nq.gz
│   ├── 4de06d775ba7a0847af7db8118c0264139f07c1e.nq.gz
│   ├── 50fc439baa964cf7b10f704dde28a9bcc78c6820.nq.gz
│   ├── 55d09ac781b27d120de52232bcf2843504f0ca44.nq.gz
│   ├── 56029664ae5f0ffaaa3bae3411645725a8850f3a.nq.gz
│   ├── 5aa6225a40f9a4a09bd01ae12d4088e8fd148cf6.nq.gz
│   ├── 5ce64d32ff266abb8e2e14a07fb061bead08f89d.nq.gz
│   ├── 60f7c4ceccc064685e078891a81f3f23eff24056.nq.gz
│   ├── 6deddd338ee06fbb5a49c43c65f977fdd6649e0f.nq.gz
│   ├── 7793b8f95c4f4101dfcbec421f9cffa9c8be171f.nq.gz
│   ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
│   ├── 7df6b1cfaa807fc458783963de91df6ef35e9ea7.nq.gz
│   ├── 7ff47d162793a93ff30dfcdbddd001c433b50484.nq.gz
│   ├── 85be6b0635a286e884886dbdb4bf5632927895a8.nq.gz
│   ├── 8c1aa55824aa97c9a6fded48a75dc52f6d4c7aae.nq.gz
│   ├── 9598a58add6cc46b6120a38756fb6c7911bbeba0.nq.gz
│   ├── 987b65c6362c5998b1acfae105be092c5483cb9c.nq.gz
│   ├── 9f0a2a0a7b3e3900e992db2e22eed1b95aba9727.nq.gz
│   ├── a4e4ed171e7559ef1edb9941a58401a75839de36.nq.gz
│   ├── b048e7e25b607fde4873d42563eaf457a501d0d6.nq.gz
│   ├── b3377442caa33b928e15a1d51c3aa7bd25eb5ead.nq.gz
│   ├── b8ca6e8a7d22319b5dc99ba06bad7fefa2f495cf.nq.gz
│   ├── ba89481fe6158954ae0695a31adbbd38fbffabf4.nq.gz
│   ├── bfef02d86588afa19ceb1d51156b4ef7a2e1b3ab.nq.gz
│   ├── c163c419bd5224d3b51d826bfb80957568eb017a.nq.gz
│   ├── c624d09296c2d9d818a8d4ac463f7d2213434d43.nq.gz
│   ├── c95a8017ed0d1b9d868cc8917bb7bfe14a7a4f21.nq.gz
│   ├── c971b0b1d48e1d9267881c994864f998524c57eb.nq.gz
│   ├── cb2aa5b124632cba17a4b45677dfb34ff790fb56.nq.gz
│   ├── ccf9668f11056f178354e42e505a7a7361aa4b06.nq.gz
│   ├── d56ea172eaeeed3e0c0e4054de65bc895e36bfb0.nq.gz
│   ├── d9bd4ed5050ef646a23ecdb367313c81b23d65e0.nq.gz
│   ├── da440b0fcb03e7e936687e7aee01b1e3ab4754db.nq.gz
│   ├── dddc8e12580488167691ec9f5dac87f8b58646c8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec62bd62e7e64402f0853e30f8ad577ce3ec1031.nq.gz
│   ├── f87576ac80d7ba4cc8c83ff82665f25bcee8c078.nq.gz
│   ├── fca311caa7dba7ddfae791331b605c7782579791.nq.gz
│   └── ffe2fce498955b628014618b28c6bcf152466a4a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   ├── 36a09fa4dadb67b81359078c61f418a971f57372.nq.gz
│   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e.nq.gz
│   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db.nq.gz
│   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465.nq.gz
│   ├── a7a6a432530400a67ed33416b5e76727217738fa.nq.gz
│   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d.nq.gz
│   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67.nq.gz
│   └── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a.nq.gz
├── filetree
│   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   ├── 36a09fa4dadb67b81359078c61f418a971f57372.nq.gz
│   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e.nq.gz
│   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db.nq.gz
│   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465.nq.gz
│   ├── a7a6a432530400a67ed33416b5e76727217738fa.nq.gz
│   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d.nq.gz
│   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67.nq.gz
│   └── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

31 directories, 102 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
