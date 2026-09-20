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
│   │   ├── 014b8e6c39d0052d9bb80ad85bae9a390d1aad09
│   │   │   └── chunk-001.nq.gz
│   │   ├── 058200d40e828e292772560d01683d75d4752776
│   │   │   └── chunk-001.nq.gz
│   │   ├── 06413c391f7fed0d286e35ce2226c1ac577cce67
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0b8e03a89db920f7418b0505ce4fe35bbd719125
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1d05520276766d8c53fbb35b2b8368cc43a6c52c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2391424ed00d732be99d09bbc6aa43a7a635fd40
│   │   │   └── chunk-001.nq.gz
│   │   ├── 24415ebbca6ecafdf870af06441656dd96149d1d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2614cb5f573a76ee37996eb67bc44ee14157adc8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2775f13b34b3ec67a774061a77fcd4e1e9b4157c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 290c0dce0b51236667324cea7184c2f00f22ab25
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2fabd4ac5dfa1e0ffa25e2965e067dc9f6109ec9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 319168f18ecb7d95ead91f3d7aaada23dabe1161
│   │   │   └── chunk-001.nq.gz
│   │   ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3aacb41738f04852ba153d9a5ec4e21fa71b996a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3b5c6bff5815fb86627b1fc693524f936058b61f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4101b5ed9560f3053a1e540cda92c635f15714da
│   │   │   └── chunk-001.nq.gz
│   │   ├── 41ed2420cda8ab7650a39900451099f4730266c3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 46df478c18088a7128eebea13da6b2768ef53ebe
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4baff6e26be044d8132262d89a78e969d0a52cea
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5052cdc3b140766563d916c4bc949e733ae5914b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 545a337cc9a02098ee779c5776cf0c360287d955
│   │   │   └── chunk-001.nq.gz
│   │   ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5f3d822c22ef435a57081a314bcb61b1c9f7b326
│   │   │   └── chunk-001.nq.gz
│   │   ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 69cf4a74549b0820e6baaa188d0e72ced5ed58ad
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6cb9fe14554d05494b17f47db8e85b6183f8767f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 702014bc224240c1bb92bdaab250bda178fd938f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 723ba6acfa00df769d2f14cce2ad257652ab41d9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 76cec8a3ec4c69efbeaebb04927c928f2af5a314
│   │   │   └── chunk-001.nq.gz
│   │   ├── 78c8d4bc8596af1143801076faa922f2f21c1bba
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8f96a9ff383e0521723c131fd908551b55b5ed4d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9272357166503c62ba23406c7f38b8b208ef33c5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98f7da70f867b70dd4a47135290eedc7b36b3723
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9e8d7792eb9499cf0c02efe7030c75190e5cae7d
│   │   │   └── chunk-001.nq.gz
│   │   ├── a15fa645326ef776dbef81ee13e3833cd14bdced
│   │   │   └── chunk-001.nq.gz
│   │   ├── a44271f3d7d917d81e432ce7f85d448b437b4e41
│   │   │   └── chunk-001.nq.gz
│   │   ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7b83aeb487bf8de6b8f601d5b2e35f7141e8a4e
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7f548520e4ee871ad8aeb354ecfa1a324c8ca19
│   │   │   └── chunk-001.nq.gz
│   │   ├── a86237f4d0dee13d328e819d7d9bf038c8bb0a77
│   │   │   └── chunk-001.nq.gz
│   │   ├── b0a30f85ffac529c5475c56f7dd48bde3b28f190
│   │   │   └── chunk-001.nq.gz
│   │   ├── b1c98ef7582565b3472bd4fb1bc0cc7907a30121
│   │   │   └── chunk-001.nq.gz
│   │   ├── b49eb370573626abd5ddb5dc03228c503079be59
│   │   │   └── chunk-001.nq.gz
│   │   ├── bd52c579e5ac384b016d532f431487fa89ef1eb8
│   │   │   └── chunk-001.nq.gz
│   │   ├── c3b02ab8aa532f0b1c8d1bda94856114dc45c223
│   │   │   └── chunk-001.nq.gz
│   │   ├── c5a8abb404c50bddd9881c69b995c343ab7b4991
│   │   │   └── chunk-001.nq.gz
│   │   ├── ca4c4184b56ba635a064b3c06accd9aa376cbefd
│   │   │   └── chunk-001.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│   │   │   └── chunk-001.nq.gz
│   │   ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe
│   │   │   └── chunk-001.nq.gz
│   │   ├── d0b4f9538c094d82c8dbd1111a9c4d855962c26a
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3
│   │   │   └── chunk-001.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│   │   │   └── chunk-001.nq.gz
│   │   ├── db0f9586e02d5235d571dc549b04ff3d5f13de47
│   │   │   └── chunk-001.nq.gz
│   │   ├── dc009e7fc59195419e2e1347b3f1e5c0cca58a2a
│   │   │   └── chunk-001.nq.gz
│   │   ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│   │   │   └── chunk-001.nq.gz
│   │   ├── e71f5c827944406787404f96c75ea2d8fdd4600a
│   │   │   └── chunk-001.nq.gz
│   │   ├── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249
│   │   │   └── chunk-001.nq.gz
│   │   └── f2e0fa73a26e4c4331eeeb145d576bfa0f5b1637
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 014b8e6c39d0052d9bb80ad85bae9a390d1aad09.nq.gz
│   │   ├── 058200d40e828e292772560d01683d75d4752776.nq.gz
│   │   ├── 06413c391f7fed0d286e35ce2226c1ac577cce67.nq.gz
│   │   ├── 0b8e03a89db920f7418b0505ce4fe35bbd719125.nq.gz
│   │   ├── 1d05520276766d8c53fbb35b2b8368cc43a6c52c.nq.gz
│   │   ├── 2391424ed00d732be99d09bbc6aa43a7a635fd40.nq.gz
│   │   ├── 24415ebbca6ecafdf870af06441656dd96149d1d.nq.gz
│   │   ├── 2614cb5f573a76ee37996eb67bc44ee14157adc8.nq.gz
│   │   ├── 2775f13b34b3ec67a774061a77fcd4e1e9b4157c.nq.gz
│   │   ├── 290c0dce0b51236667324cea7184c2f00f22ab25.nq.gz
│   │   ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58.nq.gz
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   │   ├── 2fabd4ac5dfa1e0ffa25e2965e067dc9f6109ec9.nq.gz
│   │   ├── 319168f18ecb7d95ead91f3d7aaada23dabe1161.nq.gz
│   │   ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372.nq.gz
│   │   ├── 3aacb41738f04852ba153d9a5ec4e21fa71b996a.nq.gz
│   │   ├── 3b5c6bff5815fb86627b1fc693524f936058b61f.nq.gz
│   │   ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79.nq.gz
│   │   ├── 4101b5ed9560f3053a1e540cda92c635f15714da.nq.gz
│   │   ├── 41ed2420cda8ab7650a39900451099f4730266c3.nq.gz
│   │   ├── 46df478c18088a7128eebea13da6b2768ef53ebe.nq.gz
│   │   ├── 4baff6e26be044d8132262d89a78e969d0a52cea.nq.gz
│   │   ├── 5052cdc3b140766563d916c4bc949e733ae5914b.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e.nq.gz
│   │   ├── 545a337cc9a02098ee779c5776cf0c360287d955.nq.gz
│   │   ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db.nq.gz
│   │   ├── 5f3d822c22ef435a57081a314bcb61b1c9f7b326.nq.gz
│   │   ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2.nq.gz
│   │   ├── 69cf4a74549b0820e6baaa188d0e72ced5ed58ad.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465.nq.gz
│   │   ├── 6cb9fe14554d05494b17f47db8e85b6183f8767f.nq.gz
│   │   ├── 702014bc224240c1bb92bdaab250bda178fd938f.nq.gz
│   │   ├── 723ba6acfa00df769d2f14cce2ad257652ab41d9.nq.gz
│   │   ├── 76cec8a3ec4c69efbeaebb04927c928f2af5a314.nq.gz
│   │   ├── 78c8d4bc8596af1143801076faa922f2f21c1bba.nq.gz
│   │   ├── 8f96a9ff383e0521723c131fd908551b55b5ed4d.nq.gz
│   │   ├── 9272357166503c62ba23406c7f38b8b208ef33c5.nq.gz
│   │   ├── 98f7da70f867b70dd4a47135290eedc7b36b3723.nq.gz
│   │   ├── 9e8d7792eb9499cf0c02efe7030c75190e5cae7d.nq.gz
│   │   ├── a15fa645326ef776dbef81ee13e3833cd14bdced.nq.gz
│   │   ├── a44271f3d7d917d81e432ce7f85d448b437b4e41.nq.gz
│   │   ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa.nq.gz
│   │   ├── a7b83aeb487bf8de6b8f601d5b2e35f7141e8a4e.nq.gz
│   │   ├── a7f548520e4ee871ad8aeb354ecfa1a324c8ca19.nq.gz
│   │   ├── a86237f4d0dee13d328e819d7d9bf038c8bb0a77.nq.gz
│   │   ├── b0a30f85ffac529c5475c56f7dd48bde3b28f190.nq.gz
│   │   ├── b1c98ef7582565b3472bd4fb1bc0cc7907a30121.nq.gz
│   │   ├── b49eb370573626abd5ddb5dc03228c503079be59.nq.gz
│   │   ├── bd52c579e5ac384b016d532f431487fa89ef1eb8.nq.gz
│   │   ├── c3b02ab8aa532f0b1c8d1bda94856114dc45c223.nq.gz
│   │   ├── c5a8abb404c50bddd9881c69b995c343ab7b4991.nq.gz
│   │   ├── ca4c4184b56ba635a064b3c06accd9aa376cbefd.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d.nq.gz
│   │   ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe.nq.gz
│   │   ├── d0b4f9538c094d82c8dbd1111a9c4d855962c26a.nq.gz
│   │   ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67.nq.gz
│   │   ├── db0f9586e02d5235d571dc549b04ff3d5f13de47.nq.gz
│   │   ├── dc009e7fc59195419e2e1347b3f1e5c0cca58a2a.nq.gz
│   │   ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a.nq.gz
│   │   ├── e71f5c827944406787404f96c75ea2d8fdd4600a.nq.gz
│   │   ├── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249.nq.gz
│   │   └── f2e0fa73a26e4c4331eeeb145d576bfa0f5b1637.nq.gz
│   └── repolex
│       ├── 014b8e6c39d0052d9bb80ad85bae9a390d1aad09
│       │   └── chunk-001.nq.gz
│       ├── 058200d40e828e292772560d01683d75d4752776
│       │   └── chunk-001.nq.gz
│       ├── 06413c391f7fed0d286e35ce2226c1ac577cce67
│       │   └── chunk-001.nq.gz
│       ├── 0b8e03a89db920f7418b0505ce4fe35bbd719125
│       │   └── chunk-001.nq.gz
│       ├── 1d05520276766d8c53fbb35b2b8368cc43a6c52c
│       │   └── chunk-001.nq.gz
│       ├── 2391424ed00d732be99d09bbc6aa43a7a635fd40
│       │   └── chunk-001.nq.gz
│       ├── 24415ebbca6ecafdf870af06441656dd96149d1d
│       │   └── chunk-001.nq.gz
│       ├── 2614cb5f573a76ee37996eb67bc44ee14157adc8
│       │   └── chunk-001.nq.gz
│       ├── 2775f13b34b3ec67a774061a77fcd4e1e9b4157c
│       │   └── chunk-001.nq.gz
│       ├── 290c0dce0b51236667324cea7184c2f00f22ab25
│       │   └── chunk-001.nq.gz
│       ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58
│       │   └── chunk-001.nq.gz
│       ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│       │   └── chunk-001.nq.gz
│       ├── 2fabd4ac5dfa1e0ffa25e2965e067dc9f6109ec9
│       │   └── chunk-001.nq.gz
│       ├── 319168f18ecb7d95ead91f3d7aaada23dabe1161
│       │   └── chunk-001.nq.gz
│       ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f
│       │   └── chunk-001.nq.gz
│       ├── 36a09fa4dadb67b81359078c61f418a971f57372
│       │   └── chunk-001.nq.gz
│       ├── 3aacb41738f04852ba153d9a5ec4e21fa71b996a
│       │   └── chunk-001.nq.gz
│       ├── 3b5c6bff5815fb86627b1fc693524f936058b61f
│       │   └── chunk-001.nq.gz
│       ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79
│       │   └── chunk-001.nq.gz
│       ├── 4101b5ed9560f3053a1e540cda92c635f15714da
│       │   └── chunk-001.nq.gz
│       ├── 41ed2420cda8ab7650a39900451099f4730266c3
│       │   └── chunk-001.nq.gz
│       ├── 46df478c18088a7128eebea13da6b2768ef53ebe
│       │   └── chunk-001.nq.gz
│       ├── 4baff6e26be044d8132262d89a78e969d0a52cea
│       │   └── chunk-001.nq.gz
│       ├── 5052cdc3b140766563d916c4bc949e733ae5914b
│       │   └── chunk-001.nq.gz
│       ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e
│       │   └── chunk-001.nq.gz
│       ├── 545a337cc9a02098ee779c5776cf0c360287d955
│       │   └── chunk-001.nq.gz
│       ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0
│       │   └── chunk-001.nq.gz
│       ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db
│       │   └── chunk-001.nq.gz
│       ├── 5f3d822c22ef435a57081a314bcb61b1c9f7b326
│       │   └── chunk-001.nq.gz
│       ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2
│       │   └── chunk-001.nq.gz
│       ├── 69cf4a74549b0820e6baaa188d0e72ced5ed58ad
│       │   └── chunk-001.nq.gz
│       ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465
│       │   └── chunk-001.nq.gz
│       ├── 6cb9fe14554d05494b17f47db8e85b6183f8767f
│       │   └── chunk-001.nq.gz
│       ├── 702014bc224240c1bb92bdaab250bda178fd938f
│       │   └── chunk-001.nq.gz
│       ├── 723ba6acfa00df769d2f14cce2ad257652ab41d9
│       │   └── chunk-001.nq.gz
│       ├── 76cec8a3ec4c69efbeaebb04927c928f2af5a314
│       │   └── chunk-001.nq.gz
│       ├── 78c8d4bc8596af1143801076faa922f2f21c1bba
│       │   └── chunk-001.nq.gz
│       ├── 8f96a9ff383e0521723c131fd908551b55b5ed4d
│       │   └── chunk-001.nq.gz
│       ├── 9272357166503c62ba23406c7f38b8b208ef33c5
│       │   └── chunk-001.nq.gz
│       ├── 98f7da70f867b70dd4a47135290eedc7b36b3723
│       │   └── chunk-001.nq.gz
│       ├── 9e8d7792eb9499cf0c02efe7030c75190e5cae7d
│       │   └── chunk-001.nq.gz
│       ├── a15fa645326ef776dbef81ee13e3833cd14bdced
│       │   └── chunk-001.nq.gz
│       ├── a44271f3d7d917d81e432ce7f85d448b437b4e41
│       │   └── chunk-001.nq.gz
│       ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb
│       │   └── chunk-001.nq.gz
│       ├── a7a6a432530400a67ed33416b5e76727217738fa
│       │   └── chunk-001.nq.gz
│       ├── a7b83aeb487bf8de6b8f601d5b2e35f7141e8a4e
│       │   └── chunk-001.nq.gz
│       ├── a7f548520e4ee871ad8aeb354ecfa1a324c8ca19
│       │   └── chunk-001.nq.gz
│       ├── a86237f4d0dee13d328e819d7d9bf038c8bb0a77
│       │   └── chunk-001.nq.gz
│       ├── b0a30f85ffac529c5475c56f7dd48bde3b28f190
│       │   └── chunk-001.nq.gz
│       ├── b1c98ef7582565b3472bd4fb1bc0cc7907a30121
│       │   └── chunk-001.nq.gz
│       ├── b49eb370573626abd5ddb5dc03228c503079be59
│       │   └── chunk-001.nq.gz
│       ├── bd52c579e5ac384b016d532f431487fa89ef1eb8
│       │   └── chunk-001.nq.gz
│       ├── c3b02ab8aa532f0b1c8d1bda94856114dc45c223
│       │   └── chunk-001.nq.gz
│       ├── c5a8abb404c50bddd9881c69b995c343ab7b4991
│       │   └── chunk-001.nq.gz
│       ├── ca4c4184b56ba635a064b3c06accd9aa376cbefd
│       │   └── chunk-001.nq.gz
│       ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│       │   └── chunk-001.nq.gz
│       ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe
│       │   └── chunk-001.nq.gz
│       ├── d0b4f9538c094d82c8dbd1111a9c4d855962c26a
│       │   └── chunk-001.nq.gz
│       ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3
│       │   └── chunk-001.nq.gz
│       ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│       │   └── chunk-001.nq.gz
│       ├── db0f9586e02d5235d571dc549b04ff3d5f13de47
│       │   └── chunk-001.nq.gz
│       ├── dc009e7fc59195419e2e1347b3f1e5c0cca58a2a
│       │   └── chunk-001.nq.gz
│       ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│       │   └── chunk-001.nq.gz
│       ├── e71f5c827944406787404f96c75ea2d8fdd4600a
│       │   └── chunk-001.nq.gz
│       ├── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249
│       │   └── chunk-001.nq.gz
│       └── f2e0fa73a26e4c4331eeeb145d576bfa0f5b1637
│           └── chunk-001.nq.gz
└── blob
    ├── 00522ef940b6e75bf4a2f3e92b9f4d186ea6ed5f.nq.gz
    └── 008049a879674081beb4d41a3e446fc52c5ceb4d.nq.gz

138 directories, 200 files
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
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
