# Repolex Knowledge Graph of jupyterlab/jupyter-collaboration

RDF knowledge graph data for [jupyterlab/jupyter-collaboration](https://github.com/jupyterlab/jupyter-collaboration), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterlab/jupyter-collaboration
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 455f8218038137d5ea60371d9f6ece093620f11d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 455f8218038137d5ea60371d9f6ece093620f11d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0054164c1aebc51db0af4877df63a341e620fbe9.nq.gz
│   ├── 00fe02e2ebd3426ab8748f53eb60abc890dc7112.nq.gz
│   ├── 013bb6c0b49fc6b835b0c5ac528f754579ddc4ac.nq.gz
│   ├── 018d8fbd4d8d9006ef9f131e025c04b781001778.nq.gz
│   ├── 04fa5dac9df986a3793407dd637fb38cd0830fbc.nq.gz
│   ├── 0559a09e0c2db88f256ca5190f5a29b3f122634c.nq.gz
│   ├── 097344fca216d428d2c61222cd073307a025d51b.nq.gz
│   ├── 0f80c418034307abeae806be0322db386c5bf0e4.nq.gz
│   ├── 0ffb5093e9f56c9602c59aa15c4bf4e6e250d4e4.nq.gz
│   ├── 10b47a09f166be9cbabfa6232c519eb658caa0ad.nq.gz
│   ├── 1130cc2f4f4d838fa24bac8e2166325e9fa0198b.nq.gz
│   ├── 11ca8451285c16816c8a057d64c0a1ac87bbbd83.nq.gz
│   ├── 11e4391bae37facf686cd7a6b0edf86c5fba8e61.nq.gz
│   ├── 11fb509986aae64603ee6d827c7eb1e471b360d8.nq.gz
│   ├── 121faaf64c54a642df5a31c36a87f37482c50d24.nq.gz
│   ├── 122f7a8fe225a3fcb9dd35324fb9c44a1f317974.nq.gz
│   ├── 12bcac94409fdb64a92119ddec349cb6950f8adf.nq.gz
│   ├── 131485a28af2c54207824ebc2d825a0c80e7fd3f.nq.gz
│   ├── 14c03e9ed21e67858a24b033fe0f3595722758a7.nq.gz
│   ├── 195e300a65b1d92512da141c090117054754d49f.nq.gz
│   ├── 196b75c0824ee5ec867a1ca58d84cda9781fc893.nq.gz
│   ├── 1a6801bda888338bd95112f59bacacd3605f04d1.nq.gz
│   ├── 1aaa288080c8d48e73eaf2740738a10ee809c218.nq.gz
│   ├── 1b84f4f6d3b33859c13cb6b96106613324816328.nq.gz
│   ├── 1bf51feb7df0329e0028b85b19ce2ed7496839c3.nq.gz
│   ├── 1bff7903f63610068596b1070845375584d45097.nq.gz
│   ├── 1c0a9cbeb13e3fab439ce491681e7673f7619774.nq.gz
│   ├── 1cd1542490c8944c2f2528bb6376ca426e288f7e.nq.gz
│   ├── 1d4c8248861f76eba8336af33eb002b0fb678fcb.nq.gz
│   ├── 1e55c9069f4d9ba12609ab47c407ca0762ef5461.nq.gz
│   ├── 241de1dafe2412f02e83911d3561c9fb6ee3ef06.nq.gz
│   ├── 243a107489102ad7765401fbcac0192dbcb71fac.nq.gz
│   ├── 24ec0042072587772e5cd0b43018f5bc88709795.nq.gz
│   ├── 25989cbae0834f2d01c7d3dc0d3c013c93002124.nq.gz
│   ├── 25bda0e7227bfe89b95b9055e5afb7a7345d07bd.nq.gz
│   ├── 2660af2fc3473f0865f74987591e68f1551edeca.nq.gz
│   ├── 27ac7ce07f3e35d4840a1edc91fcb017b2aaaa1d.nq.gz
│   ├── 284f321ced6bc59917dc1e31cad247a437646aee.nq.gz
│   ├── 29aa83db856df28946a9ced9c2ec63408a515f6f.nq.gz
│   ├── 2a76f6ef4ba13ff75fc57cbdb3785d9af481219f.nq.gz
│   ├── 2becd46d31f7ae1c385809380f3da5ae9132158f.nq.gz
│   ├── 2bf6af117d5b48ceeefb41a1d06fee8b0ac1f675.nq.gz
│   ├── 2dc2b6036fbfbe6ed8fdca026879391862d395cc.nq.gz
│   ├── 3001f23a3de7d93160b469c84cfb8804353ecad4.nq.gz
│   ├── 31fb5ab39e1d4d879345977f76802d084ba88888.nq.gz
│   ├── 33c0ab7cfad65a5388f9d0f6be05b14d688696bd.nq.gz
│   ├── 345d6568aae36b90930a1a7a46fa776fdf730e2d.nq.gz
│   ├── 355c43f4f95cc2cb8ce91e5a512013cbca27643d.nq.gz
│   ├── 35b805c0194ddd7d18fb07ec7a00cdddcff6f41a.nq.gz
│   ├── 3815ccdbb1012921a10f4a4b3fad94592ee7623c.nq.gz
│   ├── 39137e785527679f0eaf14ff2020031f074e898a.nq.gz
│   ├── 392d2dba5dfd1baa6883faf8bf09473ba8ff663f.nq.gz
│   ├── 396330bb9729d2ec595617aef79fb28600d86bd7.nq.gz
│   ├── 3a373dc7d1320f139a45d3ba08ba737cfb55459d.nq.gz
│   ├── 3c3629e647f5ddf82548912e337bea9826b434af.nq.gz
│   ├── 3c50a2f17c685a3d1ae447574f18e0a2a1af4d34.nq.gz
│   ├── 3dfb55ede056df4ae4b9bf577cb81c5962c4680a.nq.gz
│   ├── 3e0a3e32448720af3b067e5088f7ba67040351f9.nq.gz
│   ├── 408a3d435c5b45e7fca1f14ef89e57b0618f1e8c.nq.gz
│   ├── 4376db13691a0de8163079b0fc3c3d3a5c903fac.nq.gz
│   ├── 46ae573da07e5b6d7868bcaa29979856cd2d03a2.nq.gz
│   ├── 4957a9dccf0807a7352588fac11fb14d2db30009.nq.gz
│   ├── 4abca77c30866fe2053b0a30a57e80ff26dda6f8.nq.gz
│   ├── 50183242e8862f461af0d243a3d1fcbbb23c0d11.nq.gz
│   ├── 50493532a8e7bfd1962bedcf8e3c55579d24590c.nq.gz
│   ├── 51f9a2dd2fd2c7f5dacf4df391141ff4d3fcda2c.nq.gz
│   ├── 5535d8c54cbcb2ba72f56d81d79ae799d671112a.nq.gz
│   ├── 56195132911037a7018224123d443f07537fe784.nq.gz
│   ├── 59dffb45f98d663151f4a75d3af7a4002ecee161.nq.gz
│   ├── 5ad2daec39987c4c99fcd33054534479111c1051.nq.gz
│   ├── 5bb3f406ca12c07a4ccdad7a00744cdc1d8ff070.nq.gz
│   ├── 5c5120daa3d46a7703f56a29c112ceea9df308d2.nq.gz
│   ├── 6042b46f28e23f30d6ba43956e8a5e0729d38f1e.nq.gz
│   ├── 609708caf4479e8e888efa99fe25dd15d2c3e6c3.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 60d6ee831f271c73e3d2bfe2867e262494050f53.nq.gz
│   ├── 60fbeefedb20bf9f3651a607e91ce51fdb022a22.nq.gz
│   ├── 62a5e41910d902bb3f3ce9324033a64f380c5499.nq.gz
│   ├── 63ad1aec0095843a8c2b4af07eef369d8b590e3a.nq.gz
│   ├── 65f7ecaf2d024aa551bdb6bb5670c4bf32802336.nq.gz
│   ├── 674659c773a284d2d4a2227d8a8fc018e57c8836.nq.gz
│   ├── 692ba210289c24702e1e0bb04fa40782930cbf1e.nq.gz
│   ├── 6a51faf67f551c5f8c511ac4e915f1b65de8f9bb.nq.gz
│   ├── 6ef25e8d12b7ea6b1981be23cfa7b7dbf233916d.nq.gz
│   ├── 714dc3eb4a2a20290f31a6f3f8c58b57039914c9.nq.gz
│   ├── 71f8e0a615b79962066c44824a3eb3a5e869364f.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 73304a0eaf910f84b510e1b11c56f88790480c51.nq.gz
│   ├── 744a8a6aacc7af4da85e106041290a7a326ff085.nq.gz
│   ├── 756dc0c31f0a19accb86db39349063ac07f896ff.nq.gz
│   ├── 75d7c9a8779da55bd2a4e6e0bf13c4d16512af18.nq.gz
│   ├── 774b34ed3442f6fd0215f86ae75ec6458b5b5d2a.nq.gz
│   ├── 79edaf9580b2d0daa76e253af0b3ba976004b320.nq.gz
│   ├── 8069ff24aaeb297a766d67152c39c77a02c8b299.nq.gz
│   ├── 809e012b38cccabad00dce56fb95ddbe614f6764.nq.gz
│   ├── 817929367c651be9470623aae549c6f72db2e463.nq.gz
│   ├── 820f5648426b3b0687d7adbbd635c4e6d454b5ba.nq.gz
│   ├── 84a313f1dbee7361c5db5e9fe586573ded636dc8.nq.gz
│   ├── 85588a33572c9bd86bc471e8560df71e1deb5c45.nq.gz
│   ├── 87e9cd29b58fdb1d83807bac61659dbaf58e1370.nq.gz
│   ├── 8847465cb087c13f8b65b3f1ffd6e4113d627ede.nq.gz
│   ├── 8b130ad01610acbd482dd677a220e12d14118cb9.nq.gz
│   ├── 8c36f402b9f84dbbf00ad8a8bb8f3a2352927c85.nq.gz
│   ├── 8c5a1a08f63bf3b2df3b8d116c8cb9d0fdaff982.nq.gz
│   ├── 8caf51f4356c206d112eb94e69d630ffd055b645.nq.gz
│   ├── 8e10cb462a9e21d6a216e606428d76f24bde44b6.nq.gz
│   ├── 8f4b9f964b9bf7470a96c59e8f4fbe01f8926196.nq.gz
│   ├── 908f9be358a56ce227cf35bb691968c058d1dc87.nq.gz
│   ├── 90ba46d8e42f1e711f3cf485d37cf7ae84d1c6b1.nq.gz
│   ├── 91c168eaf87381df8d21535cf0aa5e8c5b804d71.nq.gz
│   ├── 93c1a579c1d0acc753285bd5008bfb33837aa748.nq.gz
│   ├── 94f5c254e79da87ccfcc481788d47223213db9a9.nq.gz
│   ├── 95a2eecf60825a4851800242d05590f9c7f622a5.nq.gz
│   ├── 974aa9de50d40eccd313612119407c12382a3ee8.nq.gz
│   ├── 999d80d9eb6153f3d6dd7024c7f5436f2bc2e2ab.nq.gz
│   ├── 9bf6bfb34bba09d6433b6a40c74ab52a3d583b0a.nq.gz
│   ├── 9f054691fd5e30fc42a880b2d151c43174b04e1e.nq.gz
│   ├── 9fa76909de674d3635c3d48547b43932da1928ba.nq.gz
│   ├── a139763cb2260bc9adea5d2aee90d0da5a710b6e.nq.gz
│   ├── a161ace12414c686c1b89aa0c5fc93ca508f800a.nq.gz
│   ├── a1c28df82dbf82180acad70651917d03877b0edc.nq.gz
│   ├── a3d6832414c6bf535928f2789ea45c0f0ec7c307.nq.gz
│   ├── a426680eb9297dcbef568b81bf0cdd46127e9db0.nq.gz
│   ├── a65b84f94cfbc4e44e84f8d511cfd1c29ab5008f.nq.gz
│   ├── a69c36b3ec284eafd561080ee3ca57db6dabd802.nq.gz
│   ├── a88f01c5e973a52853e0c5496b11825ef5211571.nq.gz
│   ├── a8a47bf6e54c34105122800455df88af631b2547.nq.gz
│   ├── abb0cd9116d79eea3303752e105222e1e6833021.nq.gz
│   ├── acc8b6052fcfda3cf9b6cc39d69b5eb140d55f1d.nq.gz
│   ├── af29f3407ed55594fdf7512e91a586b6ce5d32de.nq.gz
│   ├── b04428bd5b8c06b2d0df5bce4a5176ed53f742f8.nq.gz
│   ├── b0696477f5d6c54884980e6f88be216154c2025e.nq.gz
│   ├── b1ca86c83f051593d32f657628ae2d8314b7fa50.nq.gz
│   ├── b3d38191711a739c67fea6b91da0305bf5342120.nq.gz
│   ├── b508d225bc907c3ddd29ff3150205ac9d412ba4c.nq.gz
│   ├── b85d1f4b5587c2050c3ab64f35e3023d5fe2808a.nq.gz
│   ├── b95721c156e306791e64da7a128e7be17ab78c01.nq.gz
│   ├── baf70e9a28dee575a83ce7333c0fb706e598c26b.nq.gz
│   ├── bd5dad3a37ff42936ad8e38f9381e1f663b8178d.nq.gz
│   ├── bd933dfa251ee3f0327fb13c5748fb03a1da1b3b.nq.gz
│   ├── c0f689c306b98b78c4dcbbc7ab202911f6a77e7a.nq.gz
│   ├── c1463008fe10057d5339c9611053564131449401.nq.gz
│   ├── c1881060de286b6e65824cf42d336f09ad37ce7e.nq.gz
│   ├── c247b2f92335188e0cc1a2cb933ba173dd4d97b1.nq.gz
│   ├── c58c744afdf3785684f5b17091b25cec9a25e250.nq.gz
│   ├── c5cb4388a200a07069e8bf16a75e71a9e944a64a.nq.gz
│   ├── c8aeb64764506bde1ceb2415ffafcfc640b5a013.nq.gz
│   ├── c9286f66ac5389b42ba128979eabf3f4e3a29b7f.nq.gz
│   ├── caa846b0cf00affb1f2480b1875a7ff7d79123bd.nq.gz
│   ├── caf04647959b58ba727b7e06dd61420bf804402a.nq.gz
│   ├── cd3594e071050ed6d34bd3f899b22a8637173d90.nq.gz
│   ├── cda8f022a9498ce708cd0ef9cc9d2bff77aa66fd.nq.gz
│   ├── d0824a69c143d80f2a5ef9fb11a7cb2e9611eb61.nq.gz
│   ├── d1bcad7651a0c256c994c34b977000eba06d64ed.nq.gz
│   ├── d373048613159f3b72cf5cbeaf17cfa038244dda.nq.gz
│   ├── d379711facb855ef1557abc25f9024bad656cf3c.nq.gz
│   ├── d4ca3f081c4152c0d41a89bb312b22333b7ed4d6.nq.gz
│   ├── d6bbdef38c44a96104317de6cac086fbce8f2632.nq.gz
│   ├── dd33d7324166ebabfda4e5c34129ce84b1d4dac8.nq.gz
│   ├── dd91a80c39939b4916cd4fd80ef991d53fb1226c.nq.gz
│   ├── de21a138c803fa95cdfb96e6d25673f3b03792c3.nq.gz
│   ├── decbb34db2f004fab27085d66194b1ef6b1e85c8.nq.gz
│   ├── ded1b53d737d12fdcd359884de71ceac5b171dd9.nq.gz
│   ├── e2d733ed18179020be8c1ee2f6adcc2750a43452.nq.gz
│   ├── e3663b2e7e3a4e2b88374f9f28c6b89d7ef55b4a.nq.gz
│   ├── e388b39b5a3ce74d564544c22092f2a9938179a3.nq.gz
│   ├── e5cb76ba0299435338509f23cab9d18e49480cda.nq.gz
│   ├── e6b281c4f44afcdb1dc945e2081501299f1c674d.nq.gz
│   ├── e6fa86c1238b7d568bba7b31ff61b69e0a097118.nq.gz
│   ├── e713e073de9d79e3ddbe96d778ba1919ab36188a.nq.gz
│   ├── e77d3dafb238a83c712c7572d938d51923fb485a.nq.gz
│   ├── e7fe1667b1ffab5d04506380b3749c49b55f47b0.nq.gz
│   ├── e8c7dc51796e3585523f0d5ac327d711c4d01d1d.nq.gz
│   ├── ea1f0c5b6b146dcb25f4dbd05867ac5b6361d959.nq.gz
│   ├── ea32c5e149ae5a16066fc2e9e47277df03e80ecb.nq.gz
│   ├── eb2198a956e70fe4505623df825e962b546da933.nq.gz
│   ├── eb9b9dff30c6d06d708d9191a6ccad70bcd3c789.nq.gz
│   ├── ed8160652a494e99d0a5cb539bbace1f86f6bb2c.nq.gz
│   ├── f01cc5ec49b6e6836244d215200dc28840dfcfdd.nq.gz
│   ├── f2498dec9476a6898ef7306a14a22dafbf28e08e.nq.gz
│   ├── f495407d0d96d0ca94472a76fe604dd9c61698c8.nq.gz
│   ├── f51f3999188d8a722bae104f32f6f564fa1736ea.nq.gz
│   ├── f660ff9f2d8240dcb756007b31f633a4c6c19c21.nq.gz
│   ├── f7ede13531018b7c09a9543c954211594ecdc818.nq.gz
│   ├── f807423700bb2b73537ddce2d72549eda5b927c4.nq.gz
│   ├── f9762711e3ec8b455b310d1d4d4754363d6866dd.nq.gz
│   ├── fb1df89614649c8db889a636af3fe72002181d84.nq.gz
│   ├── fbbade5955c6b3c2777b54844d3ae3b4f24779c9.nq.gz
│   ├── ff94cfb02c11550543f3845af7247937273b0861.nq.gz
│   └── ffb4d9b0a6e5c341d80f0ef715a797a234f1ab07.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 455f8218038137d5ea60371d9f6ece093620f11d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 198 files
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

[jupyterlab/jupyter-collaboration](https://github.com/jupyterlab/jupyter-collaboration)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
