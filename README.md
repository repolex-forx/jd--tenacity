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
│   │   ├── 24415ebbca6ecafdf870af06441656dd96149d1d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│   │   │   └── chunk-001.nq.gz
│   │   ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79
│   │   │   └── chunk-001.nq.gz
│   │   ├── 41ed2420cda8ab7650a39900451099f4730266c3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db
│   │   │   └── chunk-001.nq.gz
│   │   ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465
│   │   │   └── chunk-001.nq.gz
│   │   ├── 702014bc224240c1bb92bdaab250bda178fd938f
│   │   │   └── chunk-001.nq.gz
│   │   ├── a15fa645326ef776dbef81ee13e3833cd14bdced
│   │   │   └── chunk-001.nq.gz
│   │   ├── a44271f3d7d917d81e432ce7f85d448b437b4e41
│   │   │   └── chunk-001.nq.gz
│   │   ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── b49eb370573626abd5ddb5dc03228c503079be59
│   │   │   └── chunk-001.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│   │   │   └── chunk-001.nq.gz
│   │   ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3
│   │   │   └── chunk-001.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│   │   │   └── chunk-001.nq.gz
│   │   ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│   │   │   └── chunk-001.nq.gz
│   │   └── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 24415ebbca6ecafdf870af06441656dd96149d1d.nq.gz
│   │   ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58.nq.gz
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   │   ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372.nq.gz
│   │   ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79.nq.gz
│   │   ├── 41ed2420cda8ab7650a39900451099f4730266c3.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e.nq.gz
│   │   ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db.nq.gz
│   │   ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465.nq.gz
│   │   ├── 702014bc224240c1bb92bdaab250bda178fd938f.nq.gz
│   │   ├── a15fa645326ef776dbef81ee13e3833cd14bdced.nq.gz
│   │   ├── a44271f3d7d917d81e432ce7f85d448b437b4e41.nq.gz
│   │   ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa.nq.gz
│   │   ├── b49eb370573626abd5ddb5dc03228c503079be59.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d.nq.gz
│   │   ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe.nq.gz
│   │   ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67.nq.gz
│   │   ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a.nq.gz
│   │   └── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249.nq.gz
│   └── repolex
│       ├── 24415ebbca6ecafdf870af06441656dd96149d1d
│       │   └── chunk-001.nq.gz
│       ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58
│       │   └── chunk-001.nq.gz
│       ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437
│       │   └── chunk-001.nq.gz
│       ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f
│       │   └── chunk-001.nq.gz
│       ├── 36a09fa4dadb67b81359078c61f418a971f57372
│       │   └── chunk-001.nq.gz
│       ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79
│       │   └── chunk-001.nq.gz
│       ├── 41ed2420cda8ab7650a39900451099f4730266c3
│       │   └── chunk-001.nq.gz
│       ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e
│       │   └── chunk-001.nq.gz
│       ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0
│       │   └── chunk-001.nq.gz
│       ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db
│       │   └── chunk-001.nq.gz
│       ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2
│       │   └── chunk-001.nq.gz
│       ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465
│       │   └── chunk-001.nq.gz
│       ├── 702014bc224240c1bb92bdaab250bda178fd938f
│       │   └── chunk-001.nq.gz
│       ├── a15fa645326ef776dbef81ee13e3833cd14bdced
│       │   └── chunk-001.nq.gz
│       ├── a44271f3d7d917d81e432ce7f85d448b437b4e41
│       │   └── chunk-001.nq.gz
│       ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb
│       │   └── chunk-001.nq.gz
│       ├── a7a6a432530400a67ed33416b5e76727217738fa
│       │   └── chunk-001.nq.gz
│       ├── b49eb370573626abd5ddb5dc03228c503079be59
│       │   └── chunk-001.nq.gz
│       ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│       │   └── chunk-001.nq.gz
│       ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe
│       │   └── chunk-001.nq.gz
│       ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3
│       │   └── chunk-001.nq.gz
│       ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│       │   └── chunk-001.nq.gz
│       ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│       │   └── chunk-001.nq.gz
│       └── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249
│           └── chunk-001.nq.gz
└── blob
    ├── 00522ef940b6e75bf4a2f3e92b9f4d186ea6ed5f.nq.gz
    ├── 00f054b8ba656452c303bf769d384295e6941548.nq.gz
    ├── 02057a07c0455d666dde9b822ba0629c0dff8fe9.nq.gz
    ├── 0248d524f74fd7c23beed1fff7677c3189da0fe7.nq.gz
    ├── 0410031af6e2a3252b49caabb4236b43c6ad0c3c.nq.gz
    ├── 05fb50a7920d81121750e12ed2566ba6f50f8086.nq.gz
    ├── 06251edaeed93db8e0cb471f6a74636f270f8e54.nq.gz
    ├── 096a24f260a15216b1f0807c5d2cdbb7b8f64d01.nq.gz
    ├── 0a996e4f44898ea3dad1e4f990d1de96a9dca5aa.nq.gz
    ├── 0b74476b361ed1e6a877e5f4f2d54c52fea27caa.nq.gz
    ├── 0cb4f71681b75eabf149f59d059eb0b22d17edc9.nq.gz
    ├── 0d100f69cbd646e8189ba333fd9b100ab78fb52d.nq.gz
    ├── 0fa96fceb1ef84af55076d58fe3af93705b07c69.nq.gz
    ├── 0ffe819f7af11aef68c0ec12e935481a3d90585f.nq.gz
    ├── 13e5a1dc4b26c99331fe2cbbeed9652fac8e32ba.nq.gz
    ├── 14f8ae00733db8951d32cc6f449ff905d56d0393.nq.gz
    ├── 153edb7acbb027c110bf140412ef671e3fb82dca.nq.gz
    ├── 15cfd3cd9ac3c9b3ec6ab388a123c90508183102.nq.gz
    ├── 1620fe087b95747de0b93e269acf39ac9279379c.nq.gz
    ├── 18434bc3a3f9c06b44b010c3d2e51caf97a1fb0d.nq.gz
    ├── 186fa00c8a8e78d21b7cbcc281cd206eb9a03142.nq.gz
    ├── 188dc8da3e7f3e8ae229975186225fff5523990f.nq.gz
    ├── 1adb67e9b7c7e411b4a2f16739069eaf08bf7aa4.nq.gz
    ├── 1cc17ea20427645e07e24ac4d0fa08fe8bc15013.nq.gz
    ├── 1ce0b71b81a2ac737abb9cce772680bd9290cf95.nq.gz
    ├── 1cf7dc75bc67250dfdaaa614ac07f4762471dd93.nq.gz
    ├── 1f90ccd0dff0bea719dd5413b1d9190e07ef6b75.nq.gz
    ├── 22cbc6f9a9d3ac92ddb8f2ff079ff203f061ccd0.nq.gz
    ├── 230b115460b2e39d56bc3b6e3a19f079f4df5b7b.nq.gz
    ├── 23380170683dd1bc359794cce5baca7861cc8323.nq.gz
    ├── 24858cff10a81e8a1bd292012902d98badedcd07.nq.gz
    ├── 24cf6ed723c871f5a9a5e814d0f247b25f3513b9.nq.gz
    ├── 278df6caa16af26c8f1420db3edb6b5a481bd507.nq.gz
    ├── 279a21eb5bc2280dccf250f33c5044dd622eb796.nq.gz
    ├── 2951be41b5c1237ec2ef055928805728dd3baba3.nq.gz
    ├── 2cacb7744a216d0db9b5a56c8bbf31533f0d7aab.nq.gz
    ├── 2d3e30126506d545aae293d9fa9ab1a6fcaf5d81.nq.gz
    ├── 2ff52b9b97439f94d06a281a34a695b409889e7d.nq.gz
    ├── 31be83501e56d05dd358dc0d482e6afcddfd931f.nq.gz
    ├── 3360ecabf733e8aebce69e7b75119627c86bb45d.nq.gz
    ├── 34efd1c2cbd353ac445f6ff2f6d741d65320aecd.nq.gz
    ├── 35e475d0cd4105228e93db1b092dd938d7a081aa.nq.gz
    ├── 366235af6af5b9261c94184521ea6c63759a2b38.nq.gz
    ├── 368d8e49df52e78dd93596dedf349654a2441473.nq.gz
    ├── 381ddc4a4d0e7b54ffe84837274d429f2a6f250c.nq.gz
    ├── 38b76c7e85ae305ffd3098d4a66d92e746e88855.nq.gz
    ├── 39b79f6d232e9059f6937e4146b30d2946385f90.nq.gz
    ├── 3addbb9c4a2e4641d0541c7ffb5d61c693384e33.nq.gz
    ├── 3b560c3b0f947ff337136068213c0b751305c05c.nq.gz
    ├── 3c222360ec92b01ea02f38e09a34b5a6bd5ba49e.nq.gz
    ├── 3c7ac8a67abf6412e6c5fc18d83513d1d52f8a76.nq.gz
    ├── 3d224b2748c81054de712016885ce2410c5bdf6f.nq.gz
    ├── 3d5e37eba01fd384017698b41d58452e9f727ded.nq.gz
    ├── 3ed312da22fc717c87714ee69665491d936ba744.nq.gz
    ├── 3eec60a3a98049d6143c3abe456e131ca6a7a04a.nq.gz
    ├── 3f57bf23c5c52e2a49a134602fa4575b2785f1a0.nq.gz
    ├── 405c4b725f7f60826ba01ed805b2eb267b7bc988.nq.gz
    ├── 41ffe7267c770292705a0862c60e3d861f01edad.nq.gz
    ├── 42b794e64e911ccd3f43a7ddd10f3a49f0f33f38.nq.gz
    ├── 42bf3e1f4cd0131ace6ceccff5612155674e6ba4.nq.gz
    ├── 43b4caf9541c35abbcc4d13d304504e19258f73e.nq.gz
    ├── 43c9000707c911f8830279560a4ca3e7fe992e10.nq.gz
    ├── 44323e40dab2f2617723c085818610ef21243852.nq.gz
    ├── 4803ca403a793c3bea781365d2ed4279aedc76f3.nq.gz
    ├── 4972b726a8fe00d400130483259c9128bc1715c2.nq.gz
    ├── 4de06d775ba7a0847af7db8118c0264139f07c1e.nq.gz
    ├── 4e34115e0e44f98cfd7b7e1b322bed5fbaee6a4d.nq.gz
    ├── 4e37fe9c8808418715f0f053443b558ddbb912ba.nq.gz
    ├── 4e7c59c0945ba6a288ddbd6fd3085ea1523e5527.nq.gz
    ├── 50fc439baa964cf7b10f704dde28a9bcc78c6820.nq.gz
    ├── 511a5b571cc03823ce5fe99bbe6abf2ab1863298.nq.gz
    ├── 54259dddff86ba9cad56b78c436b899e3ff7e217.nq.gz
    ├── 55522c99b6ad7d7ec87c53414390a02a91a6ca8c.nq.gz
    ├── 55d09ac781b27d120de52232bcf2843504f0ca44.nq.gz
    ├── 56029664ae5f0ffaaa3bae3411645725a8850f3a.nq.gz
    ├── 57c4c76284130fd05ed07754edcee07046a41472.nq.gz
    ├── 5aa6225a40f9a4a09bd01ae12d4088e8fd148cf6.nq.gz
    ├── 5cda59ab21727eae5de4c60a0622314103f8e973.nq.gz
    ├── 5ce64d32ff266abb8e2e14a07fb061bead08f89d.nq.gz
    ├── 5d9aa24ec51e01d72dd4a42b37c420c8a283ef6d.nq.gz
    ├── 5da03fc3c7832289d3abd53284101e20b0429e49.nq.gz
    ├── 60f7c4ceccc064685e078891a81f3f23eff24056.nq.gz
    ├── 617953cfb6be727375eb998f69d7923f731ce14d.nq.gz
    ├── 647a7b3cd72f56fb1177ff365c36c31ff005d33f.nq.gz
    ├── 65dd208bdfeb542f29e7fcb1111577d16983bea4.nq.gz
    ├── 66096bebf60db4a056ce59129090ce9cc56f62a5.nq.gz
    ├── 6703bd9c903327c114e8d84a91cd3efefb4b4d30.nq.gz
    ├── 673128090a8527f71421cbb37ba74c21c61c0342.nq.gz
    ├── 688cabe4a17e9d1737d17e30d622204beefcff5d.nq.gz
    ├── 69375119cd0a683f9a6ce421c5a8208070689db3.nq.gz
    ├── 6a5b66bb947d7c6a6bf918ff11db736401f9e7ba.nq.gz
    ├── 6a5c81c9851afc1c961aef00c29d0e801686cc9d.nq.gz
    ├── 6d0d1ab8f01474d642e53d07adb4e5c17c9b2be9.nq.gz
    ├── 6d63ebcfabae0737f9c15a9c3a11171241115d36.nq.gz
    ├── 6d7db45a7e9b117f73d99c1993cac978503cd1a9.nq.gz
    ├── 6deddd338ee06fbb5a49c43c65f977fdd6649e0f.nq.gz
    ├── 70d2f465d1712fe10d170467b6b8f59b27b05314.nq.gz
    ├── 72aa5bfd4b60d8e6ef6ed0cf2ae4f763d12195cc.nq.gz
    ├── 73a58aa820c4b4e98d75a2b9b2e1fc0da80747d5.nq.gz
    ├── 7489ad7c88c60d4771e9bddc0cd82a0cd09c11ae.nq.gz
    ├── 765b6fe14a315e98fc170fc1248ea559b4fc46d1.nq.gz
    ├── 7793b8f95c4f4101dfcbec421f9cffa9c8be171f.nq.gz
    ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
    ├── 7a793b2090910b5b3468b3b73561b04538d4f21c.nq.gz
    ├── 7a80c4e7187860b081fe91c8b593f8a7f45f8580.nq.gz
    ├── 7a92c1b510a7bbb0eec07bcab73a9747a32ce459.nq.gz
    ├── 7de36d43457072666577da49fb49dcaa3ebade6b.nq.gz
    ├── 7df6b1cfaa807fc458783963de91df6ef35e9ea7.nq.gz
    ├── 7e6f59480c7373ae5d80347da99801ad540b7334.nq.gz
    ├── 7eeace46a8b0a2b0a4ca86523a449aaf3c92835f.nq.gz
    ├── 7ff47d162793a93ff30dfcdbddd001c433b50484.nq.gz
    ├── 80352027800924b320e20d4093a609907aada4e2.nq.gz
    ├── 82806a69cf15b296450785edce9ae07650736c11.nq.gz
    ├── 83182ac42f78f44f73dc2aeab28fba07bdd350c9.nq.gz
    ├── 85be6b0635a286e884886dbdb4bf5632927895a8.nq.gz
    ├── 85df4c3d4d085ba7879119d0bd39bf8f0ec92848.nq.gz
    ├── 8697723852400eb5976499ec2434a2c92f52bff1.nq.gz
    ├── 870380ca0f5316e1c34163b5a58773e586a6b927.nq.gz
    ├── 871652998a7248da5d0ab0b4416c7d720967d19b.nq.gz
    ├── 888233ce0cb12bf049cb872b8917796dc2ac4a25.nq.gz
    ├── 8b5a420fe8b4abcea5b5fd0a872048fd57ffe6cc.nq.gz
    ├── 8c1aa55824aa97c9a6fded48a75dc52f6d4c7aae.nq.gz
    ├── 8e4fab322cbc892e7c99ecf6cfbb60aa2927f606.nq.gz
    ├── 9211631bd8c58157cd827f065004c6c2996e0814.nq.gz
    ├── 9284f7ae5b9c6e879dbe667e7ebde22a0f2c64dd.nq.gz
    ├── 928ddd99b915bc191af607db788859f07dc52664.nq.gz
    ├── 933f759e21b33af6984657643d6dfc939c0d8a4f.nq.gz
    └── 94b8b15428b9cdd85607e79ebb089af0fb70dd1b.nq.gz

54 directories, 200 files
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
