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
│   │   ├── 06413c391f7fed0d286e35ce2226c1ac577cce67
│   │   │   └── chunk-001.nq.gz
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
│   │   ├── 3b5c6bff5815fb86627b1fc693524f936058b61f
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
│   │   ├── 78c8d4bc8596af1143801076faa922f2f21c1bba
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98f7da70f867b70dd4a47135290eedc7b36b3723
│   │   │   └── chunk-001.nq.gz
│   │   ├── a15fa645326ef776dbef81ee13e3833cd14bdced
│   │   │   └── chunk-001.nq.gz
│   │   ├── a44271f3d7d917d81e432ce7f85d448b437b4e41
│   │   │   └── chunk-001.nq.gz
│   │   ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── a7f548520e4ee871ad8aeb354ecfa1a324c8ca19
│   │   │   └── chunk-001.nq.gz
│   │   ├── b49eb370573626abd5ddb5dc03228c503079be59
│   │   │   └── chunk-001.nq.gz
│   │   ├── c5a8abb404c50bddd9881c69b995c343ab7b4991
│   │   │   └── chunk-001.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│   │   │   └── chunk-001.nq.gz
│   │   ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3
│   │   │   └── chunk-001.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│   │   │   └── chunk-001.nq.gz
│   │   ├── db0f9586e02d5235d571dc549b04ff3d5f13de47
│   │   │   └── chunk-001.nq.gz
│   │   ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│   │   │   └── chunk-001.nq.gz
│   │   └── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 014b8e6c39d0052d9bb80ad85bae9a390d1aad09.nq.gz
│   │   ├── 06413c391f7fed0d286e35ce2226c1ac577cce67.nq.gz
│   │   ├── 24415ebbca6ecafdf870af06441656dd96149d1d.nq.gz
│   │   ├── 2b173a1039009773dbf5d377f95cc8aabe83bf58.nq.gz
│   │   ├── 2cd062edcb522b37c49e5b693e69d5fa8d6d2437.nq.gz
│   │   ├── 31fe2d0cf2505bffd0cf1ffda8c7e30450ce709f.nq.gz
│   │   ├── 36a09fa4dadb67b81359078c61f418a971f57372.nq.gz
│   │   ├── 3b5c6bff5815fb86627b1fc693524f936058b61f.nq.gz
│   │   ├── 3cd734c7aed08b33ae08a5c96e8af7037e006b79.nq.gz
│   │   ├── 41ed2420cda8ab7650a39900451099f4730266c3.nq.gz
│   │   ├── 52ebba0af2d1782e74524a90b0309a4b95b3581e.nq.gz
│   │   ├── 548c5d490187af6f339cbffdd0add38aecc3ecb0.nq.gz
│   │   ├── 5ac66cf291fa6d017d28a56355cc50f476cc08db.nq.gz
│   │   ├── 62787c34bb052d28d814bc07e5c3caed22cd73a2.nq.gz
│   │   ├── 6bc111fd90786a8f137b4b1d44a76bd9e9b4d465.nq.gz
│   │   ├── 702014bc224240c1bb92bdaab250bda178fd938f.nq.gz
│   │   ├── 78c8d4bc8596af1143801076faa922f2f21c1bba.nq.gz
│   │   ├── 98f7da70f867b70dd4a47135290eedc7b36b3723.nq.gz
│   │   ├── a15fa645326ef776dbef81ee13e3833cd14bdced.nq.gz
│   │   ├── a44271f3d7d917d81e432ce7f85d448b437b4e41.nq.gz
│   │   ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb.nq.gz
│   │   ├── a7a6a432530400a67ed33416b5e76727217738fa.nq.gz
│   │   ├── a7f548520e4ee871ad8aeb354ecfa1a324c8ca19.nq.gz
│   │   ├── b49eb370573626abd5ddb5dc03228c503079be59.nq.gz
│   │   ├── c5a8abb404c50bddd9881c69b995c343ab7b4991.nq.gz
│   │   ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d.nq.gz
│   │   ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe.nq.gz
│   │   ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3.nq.gz
│   │   ├── d59d44624ac7b9afa9ecc949873fd29266dfde67.nq.gz
│   │   ├── db0f9586e02d5235d571dc549b04ff3d5f13de47.nq.gz
│   │   ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a.nq.gz
│   │   └── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249.nq.gz
│   └── repolex
│       ├── 014b8e6c39d0052d9bb80ad85bae9a390d1aad09
│       │   └── chunk-001.nq.gz
│       ├── 06413c391f7fed0d286e35ce2226c1ac577cce67
│       │   └── chunk-001.nq.gz
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
│       ├── 3b5c6bff5815fb86627b1fc693524f936058b61f
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
│       ├── 78c8d4bc8596af1143801076faa922f2f21c1bba
│       │   └── chunk-001.nq.gz
│       ├── 98f7da70f867b70dd4a47135290eedc7b36b3723
│       │   └── chunk-001.nq.gz
│       ├── a15fa645326ef776dbef81ee13e3833cd14bdced
│       │   └── chunk-001.nq.gz
│       ├── a44271f3d7d917d81e432ce7f85d448b437b4e41
│       │   └── chunk-001.nq.gz
│       ├── a662bbb487cd6d34541824589f8e8c7a1f7791bb
│       │   └── chunk-001.nq.gz
│       ├── a7a6a432530400a67ed33416b5e76727217738fa
│       │   └── chunk-001.nq.gz
│       ├── a7f548520e4ee871ad8aeb354ecfa1a324c8ca19
│       │   └── chunk-001.nq.gz
│       ├── b49eb370573626abd5ddb5dc03228c503079be59
│       │   └── chunk-001.nq.gz
│       ├── c5a8abb404c50bddd9881c69b995c343ab7b4991
│       │   └── chunk-001.nq.gz
│       ├── cab083eb5791615fadbc0c98ad77a70d64b77d0d
│       │   └── chunk-001.nq.gz
│       ├── cb15300d9b4358d9bdb6cfd33d433368700b3abe
│       │   └── chunk-001.nq.gz
│       ├── d4e868d6b8368c00b5a1fad54de36c2c8c3a0fb3
│       │   └── chunk-001.nq.gz
│       ├── d59d44624ac7b9afa9ecc949873fd29266dfde67
│       │   └── chunk-001.nq.gz
│       ├── db0f9586e02d5235d571dc549b04ff3d5f13de47
│       │   └── chunk-001.nq.gz
│       ├── e0ebef9d2b3571be4f788e9d7fa02561d8ecaa8a
│       │   └── chunk-001.nq.gz
│       └── ee6a8f7a76654d712fd44604d3b6d4f9af6b2249
│           └── chunk-001.nq.gz
└── blob
    ├── 00522ef940b6e75bf4a2f3e92b9f4d186ea6ed5f.nq.gz
    ├── 008049a879674081beb4d41a3e446fc52c5ceb4d.nq.gz
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
    ├── 0e4fda13f7bcd512113c1bf9d4cec38abf8413d1.nq.gz
    ├── 0f48511e8f50b495d417d5fc7998201074fa7e28.nq.gz
    ├── 0fa96fceb1ef84af55076d58fe3af93705b07c69.nq.gz
    ├── 0ffe819f7af11aef68c0ec12e935481a3d90585f.nq.gz
    ├── 1305d3f07584e73e27657ab62083728310b77d10.nq.gz
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
    ├── 1d876728d7ae1d6e5d1c6d31bb8008dd330b9613.nq.gz
    ├── 1e3ff86593f63c74065e1876df8c660414c2de52.nq.gz
    ├── 1f26ecddcea9f8a6e6822164d7b71437e86cd96a.nq.gz
    ├── 1f72148c19bb60f0ddcb0895a6d3000f5849081b.nq.gz
    ├── 1f90ccd0dff0bea719dd5413b1d9190e07ef6b75.nq.gz
    ├── 2057fd2d7821000ef4c9c1535dfedbbee98cb73d.nq.gz
    ├── 20f3b12ad6c02eba1424fbf6740dac525b731e35.nq.gz
    ├── 22cbc6f9a9d3ac92ddb8f2ff079ff203f061ccd0.nq.gz
    ├── 230b115460b2e39d56bc3b6e3a19f079f4df5b7b.nq.gz
    ├── 23380170683dd1bc359794cce5baca7861cc8323.nq.gz
    ├── 23856bc59e3b94d8df0382255cee396a9ff72515.nq.gz
    ├── 243cf5deabe9772ab2bb2aecc01fa0571985bcef.nq.gz
    ├── 24858cff10a81e8a1bd292012902d98badedcd07.nq.gz
    ├── 24cf6ed723c871f5a9a5e814d0f247b25f3513b9.nq.gz
    ├── 278df6caa16af26c8f1420db3edb6b5a481bd507.nq.gz
    ├── 279a21eb5bc2280dccf250f33c5044dd622eb796.nq.gz
    ├── 27dd349a19acfc57b730970029acbdd1deaaf118.nq.gz
    ├── 283e6202572940b39de62a68c442b9a0f95f18e1.nq.gz
    ├── 2951be41b5c1237ec2ef055928805728dd3baba3.nq.gz
    ├── 2cacb7744a216d0db9b5a56c8bbf31533f0d7aab.nq.gz
    ├── 2d3e30126506d545aae293d9fa9ab1a6fcaf5d81.nq.gz
    ├── 2e5febd8046b5fbe361f7c4f08cb05993531f54e.nq.gz
    ├── 2f025ef1471674767d4d73d94d35d38a374a34fb.nq.gz
    ├── 2f981c89d12f3cd8c4b3b0ee3319e64cc91b76bd.nq.gz
    ├── 2ff52b9b97439f94d06a281a34a695b409889e7d.nq.gz
    ├── 31be83501e56d05dd358dc0d482e6afcddfd931f.nq.gz
    ├── 3360ecabf733e8aebce69e7b75119627c86bb45d.nq.gz
    ├── 336f4f65a23987dfac167b52f165ef87304d44d7.nq.gz
    ├── 33caefaa0aafac86638674633840e631d33e02ac.nq.gz
    ├── 34efd1c2cbd353ac445f6ff2f6d741d65320aecd.nq.gz
    ├── 35072244fca159a18435e816016947d8e73f25ff.nq.gz
    ├── 35e475d0cd4105228e93db1b092dd938d7a081aa.nq.gz
    ├── 366235af6af5b9261c94184521ea6c63759a2b38.nq.gz
    ├── 368d8e49df52e78dd93596dedf349654a2441473.nq.gz
    ├── 374ef20615614b97b5c7f7e032a657cb19d3a4b9.nq.gz
    ├── 381ddc4a4d0e7b54ffe84837274d429f2a6f250c.nq.gz
    ├── 38b76c7e85ae305ffd3098d4a66d92e746e88855.nq.gz
    ├── 39b79f6d232e9059f6937e4146b30d2946385f90.nq.gz
    ├── 3addbb9c4a2e4641d0541c7ffb5d61c693384e33.nq.gz
    ├── 3b560c3b0f947ff337136068213c0b751305c05c.nq.gz
    ├── 3c222360ec92b01ea02f38e09a34b5a6bd5ba49e.nq.gz
    ├── 3c7ac8a67abf6412e6c5fc18d83513d1d52f8a76.nq.gz
    ├── 3d224b2748c81054de712016885ce2410c5bdf6f.nq.gz
    ├── 3d5e37eba01fd384017698b41d58452e9f727ded.nq.gz
    ├── 3e3b33b1474b27b4d9afd6fe903154d8e0c2f347.nq.gz
    ├── 3e4fbee23546f63607f9cc7cb0f6b95021f0866b.nq.gz
    ├── 3ed312da22fc717c87714ee69665491d936ba744.nq.gz
    ├── 3eec60a3a98049d6143c3abe456e131ca6a7a04a.nq.gz
    ├── 3f57bf23c5c52e2a49a134602fa4575b2785f1a0.nq.gz
    ├── 405c4b725f7f60826ba01ed805b2eb267b7bc988.nq.gz
    ├── 418db0c330dce0daacb33fcdf83a72e47da74cf4.nq.gz
    ├── 41ffe7267c770292705a0862c60e3d861f01edad.nq.gz
    ├── 42b794e64e911ccd3f43a7ddd10f3a49f0f33f38.nq.gz
    ├── 42bf3e1f4cd0131ace6ceccff5612155674e6ba4.nq.gz
    ├── 43a8a4eddf5e49e31004a69c894b54005d839542.nq.gz
    ├── 43b4caf9541c35abbcc4d13d304504e19258f73e.nq.gz
    ├── 43c9000707c911f8830279560a4ca3e7fe992e10.nq.gz
    ├── 44323e40dab2f2617723c085818610ef21243852.nq.gz
    ├── 44b9f70ea6b7be1e1db43ed3153e69e6e180e288.nq.gz
    ├── 4803ca403a793c3bea781365d2ed4279aedc76f3.nq.gz
    ├── 4972b726a8fe00d400130483259c9128bc1715c2.nq.gz
    ├── 4de06d775ba7a0847af7db8118c0264139f07c1e.nq.gz
    ├── 4e34115e0e44f98cfd7b7e1b322bed5fbaee6a4d.nq.gz
    ├── 4e37fe9c8808418715f0f053443b558ddbb912ba.nq.gz
    ├── 4e7c59c0945ba6a288ddbd6fd3085ea1523e5527.nq.gz
    ├── 4fbed6e670c8e7787e41c13a0be8cef395c65d36.nq.gz
    ├── 50fc439baa964cf7b10f704dde28a9bcc78c6820.nq.gz
    ├── 511a5b571cc03823ce5fe99bbe6abf2ab1863298.nq.gz
    ├── 54259dddff86ba9cad56b78c436b899e3ff7e217.nq.gz
    ├── 55522c99b6ad7d7ec87c53414390a02a91a6ca8c.nq.gz
    ├── 55d09ac781b27d120de52232bcf2843504f0ca44.nq.gz
    ├── 56029664ae5f0ffaaa3bae3411645725a8850f3a.nq.gz
    ├── 57c4c76284130fd05ed07754edcee07046a41472.nq.gz
    └── 5aa6225a40f9a4a09bd01ae12d4088e8fd148cf6.nq.gz

70 directories, 200 files
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
