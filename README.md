# Repolex Knowledge Graph of pallets/flask

RDF knowledge graph data for [pallets/flask](https://github.com/pallets/flask), parsed by [repolex](https://repolex.ai).

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
lexq download pallets/flask
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 187d7179f605d28c3d24e9f4d65d3295fb099afe.nq.gz
│   │   ├── 191710cbda616a53533d5e794a787f24c453ac5a.nq.gz
│   │   ├── 19def9606ac50bd308ea283e283cbcf62498d6c7.nq.gz
│   │   ├── 1ca199f9b38b70a4e97cb47a4252ffd7fccc008c.nq.gz
│   │   ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│   │   ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│   │   ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   │   ├── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│   │   └── d1d82ca8ce7262ad9d27245ce44f86571287810e.nq.gz
│   ├── lsp
│   │   ├── 187d7179f605d28c3d24e9f4d65d3295fb099afe.nq.gz
│   │   ├── 191710cbda616a53533d5e794a787f24c453ac5a.nq.gz
│   │   ├── 19def9606ac50bd308ea283e283cbcf62498d6c7.nq.gz
│   │   ├── 1ca199f9b38b70a4e97cb47a4252ffd7fccc008c.nq.gz
│   │   ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│   │   ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│   │   ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   │   ├── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│   │   └── d1d82ca8ce7262ad9d27245ce44f86571287810e.nq.gz
│   └── repolex
│       ├── 187d7179f605d28c3d24e9f4d65d3295fb099afe.nq.gz
│       ├── 191710cbda616a53533d5e794a787f24c453ac5a.nq.gz
│       ├── 19def9606ac50bd308ea283e283cbcf62498d6c7.nq.gz
│       ├── 1ca199f9b38b70a4e97cb47a4252ffd7fccc008c.nq.gz
│       ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│       ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│       ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│       ├── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│       └── d1d82ca8ce7262ad9d27245ce44f86571287810e.nq.gz
└── blob
    ├── 00f56f0911fc935a561fe6c6d5bd1d58c88da79a.nq.gz
    ├── 014d579fef8878c35e39e33a2f0e68fa02860376.nq.gz
    ├── 01584d36c5c25331a17068bbf487255867b000b0.nq.gz
    ├── 015e7b613b49d8aa15db4bd0295ce654f1c765bd.nq.gz
    ├── 017ce28098014dbfea23778a53255fd7c99e175f.nq.gz
    ├── 01bf7976e7a496069ee00e7f2b7c292fa86daf42.nq.gz
    ├── 0249b88e7b79dfeb3bca9f2686d9e673d08dfda2.nq.gz
    ├── 033a5149f3d65384dae9289791b55cd554d377d4.nq.gz
    ├── 034ab5be0743e919cb44bb33323a316ccdfd0d25.nq.gz
    ├── 038eb51eb634b4883ef659ca9bfa1d1a2d406893.nq.gz
    ├── 03f62ed121ad80928e68f67766e9ecd0be5410ae.nq.gz
    ├── 0407f86fefdca40ce4487ad006a4e65bee0d1ee6.nq.gz
    ├── 043beb07757e8fb50c041bf74f2328137764fdf0.nq.gz
    ├── 051e915aa799987320b4ff59b090ad02d3b2a82c.nq.gz
    ├── 051f44ac4051aa73ef23be0bf8a8873dec5aa4f6.nq.gz
    ├── 052d36e10810367c4e1fd37373c0e68d551601bd.nq.gz
    ├── 053148f848642cb6c79ecb61968f0a9d3fea8bb4.nq.gz
    ├── 053f08044dc9e9e758057cefdd08d87c76095c88.nq.gz
    ├── 056ecc7d5239741889705b42723f70dd6a54582f.nq.gz
    ├── 066cf107c1e5305790c1376c791173b22752677a.nq.gz
    ├── 068b2d98ed479b952eded5de98abd18398a9c651.nq.gz
    ├── 06a29fccc19345d52b4541ec4673512f1e0633d4.nq.gz
    ├── 071628fc1148e435b70084d31216605631c2d2e7.nq.gz
    ├── 0754669fa67f80449d5b80edd66e3eaa95abd068.nq.gz
    ├── 077cb4329832983e7a605b2478da36d1a4661491.nq.gz
    ├── 07bbc048864e2ce40981643cf28cd90d16be8468.nq.gz
    ├── 07d027dd973f6ecf02986d98bc8bf541e174c057.nq.gz
    ├── 07e702c46a05725b89653f3cb561cef26bde322c.nq.gz
    ├── 084f13f4dcbebaf805d10dec45128e6a8706f80a.nq.gz
    ├── 087c50dc720b5dff47b8297f634b4dea2e0df02c.nq.gz
    ├── 0890b615f109a3685a820c8948d74f4fab6c96c0.nq.gz
    ├── 089cb914c11c70e0de4e80133676f41b69ff8a02.nq.gz
    ├── 08fc42ab0cb504469472f618d74036e82a6da2bd.nq.gz
    ├── 0912b7a1d5cb7d688b45f9ff665b30be243012f9.nq.gz
    ├── 0917c7979122ac42463219ecd00e43589a5ece3c.nq.gz
    ├── 0ac278b5e42d54dc49ef1906c467b65bcad7c7a4.nq.gz
    ├── 0b0479ef8141f76e3fe83d6452021e4c5be3e55c.nq.gz
    ├── 0b5d887cd96d9223ac3df595b589ed77d19f7ec0.nq.gz
    ├── 0b6ff5048bc45a6a34a8593a913c9d6eb76e8127.nq.gz
    ├── 0b70a3ef925bee137b93933517c1aa0e268bbbfd.nq.gz
    ├── 0ba3d5b8cfec31c56f69f14d222660fdeb010111.nq.gz
    ├── 0ba46c13d58b3af799808d8963c7d65349a7989e.nq.gz
    ├── 0c3a7d0fe561a82c462efd92275417e9d8082ec1.nq.gz
    ├── 0c5e846efdfe3d15ec188cfd89f8c007548093b6.nq.gz
    ├── 0c74ad9260a2888dd2e61e4d8a8adada691f2c4f.nq.gz
    ├── 0cb8f43746c04b95b277d6dcb7af6d1930f09b62.nq.gz
    ├── 0cd39ddc703c1ce2b8e75d4d52687f03d3663512.nq.gz
    ├── 0d0028e25f81b8228a2c0f66b601d60445e263ab.nq.gz
    ├── 0d02e465583b2e5d71bab01b40a161228ab8d21a.nq.gz
    ├── 0d1d9eea7d41ca9b79094a4f761d73124c586d49.nq.gz
    ├── 0d4b656131e62229005770d748d412dc2632503c.nq.gz
    ├── 0d743205fd28c0a821fac05cb561cc73ef6cd94d.nq.gz
    ├── 0d7ad3f695d3db68cb04eae14ef871596cad6d6a.nq.gz
    ├── 0ddcf972d2be7735db12410fe30b2b1fffdb3c88.nq.gz
    ├── 0e215252255879d6731feb1e54f1fecf1ce6cece.nq.gz
    ├── 0e25a30c75a9b2e6e164e6e65e85632ed035c5a8.nq.gz
    ├── 0e8caf3e9f3287ae6f1fbe1d18f601a8b0301ff6.nq.gz
    ├── 0e96f15b74a4ca6096c5eaa9f041be909b5e01f1.nq.gz
    ├── 0ec3ca215aa7a78c4f55e51b119883f347f4bac6.nq.gz
    ├── 0edd3d58d7d9ca85e5fc216b24da0eacc16d47ec.nq.gz
    ├── 0f1b97e3aa6905e6929f39df5c1dadf95d2b1eb7.nq.gz
    ├── 0f248783cd942eb6c7da0a52fb361e052e01ab6a.nq.gz
    ├── 0f2a98276c15461e82cfb7e62bee7a4780144a42.nq.gz
    ├── 0f99a7e8c98d90d746732f55e52b1c3d890abc6f.nq.gz
    ├── 0facbfee9062771fe95a8ed1d2b36045f097a46b.nq.gz
    ├── 1032097e509b73af68bcf9cc312d68570b13043f.nq.gz
    ├── 10b886bf05bcfc267110515f5ccd0b83bbec3419.nq.gz
    ├── 114873e29b9d9194d82380c43379e8fa9ab09147.nq.gz
    ├── 116774338dede8bf9542aa86a10c908bd325378e.nq.gz
    ├── 1174ebfcb9e9eb4ae89a8411a5e67c01127159f7.nq.gz
    ├── 11cb9fb0e549e10fe86095432f75e4f4c673c1fa.nq.gz
    ├── 11d6684d2e091ddd9325302eb0344539a1acbac5.nq.gz
    ├── 12336fb1b4546540f3a7881c095139262e51fc07.nq.gz
    ├── 12e23c16f374bfddeec3ef6081aef9478f081fe6.nq.gz
    ├── 134ffcf4d2534251b6fbcc8f95319fc6de369208.nq.gz
    ├── 1387d4a614ceba324b2251d2a3ce15702996e0ac.nq.gz
    ├── 13ac34837b43a24cf956996f3b7614feb782b880.nq.gz
    ├── 13b61eeeebf19956c9141008785272546a18da42.nq.gz
    ├── 13db5e6691714b405adaffaea7f8594f54a6667c.nq.gz
    ├── 1404e17e74820a5909d4e0663a9889f814c82ed3.nq.gz
    ├── 147f49d05ea3199c5d9d4e7eb451d8b9c5b7544c.nq.gz
    ├── 148e50293bdd99c5d6a7f8a0a59241dd87aaab0d.nq.gz
    ├── 1561a37cd9fa0546d42262b1530b070801357a65.nq.gz
    ├── 15911b4ca4587c59a64fd689a8640eb76c1bd449.nq.gz
    ├── 16580d16d2e7222b6ed7e44ecb5319bd8f47e91f.nq.gz
    ├── 166c5aa3769ab66c252c2c9136c932f1c275afe7.nq.gz
    ├── 16a0761d9bc3455179c87021d09762e642eef064.nq.gz
    ├── 16d7e6709f7cd7385ffaeadf9566e1513f6cdfbf.nq.gz
    ├── 172f6a01b32b2cfee5df94b8bef7b5862475b62b.nq.gz
    ├── 1733f0a3b629259c0c5ffe70ef42da42d4b5cd1b.nq.gz
    ├── 17ff2f3db7e2fbcb857f0395dcfe7882d40423f9.nq.gz
    ├── 183bdb69fa34408a7b3ea024d294c353f0cf9ea3.nq.gz
    ├── 18eac19389474433d970dd3693bf4958f6f5b991.nq.gz
    ├── 18f5c9b3a9f93e8db0ec4de17f34d2d427183333.nq.gz
    ├── 1918bd999d24096470be1c766363e897f9b302b3.nq.gz
    ├── 1928219a233944646a83a809be6c09f71b72bb49.nq.gz
    ├── 196545d0e0052553238b6c1cdc489563b7c1ca4b.nq.gz
    ├── 1a43fdc1530c1de8ac5f40b649bd0b7ab9e37102.nq.gz
    ├── 1a478917be8677edb26d739e94ac42248318f842.nq.gz
    ├── 1a5535cc4d39833d8053fef0c958a01ac8c51a27.nq.gz
    ├── 1aa8048f556a525896a7f8dc65e4ab9011a85086.nq.gz
    ├── 1b17086ce787e05e767e67e16a4842b5a3bd1284.nq.gz
    ├── 1bca80c38ef3a7e628ae2fd88141df81b8cfe14e.nq.gz
    ├── 1bf1815c3580c5816558bea2826e95e6c4c511ef.nq.gz
    ├── 1c4f466c5a3b7eb9b680b6d495a8d3930f65da43.nq.gz
    ├── 1cb779b33bd145c2341772f9676f88d8779dd502.nq.gz
    ├── 1cd7797420f6a3456afaaeee824a272b304c7335.nq.gz
    ├── 1d27396d74e0550dddccedeac3dbd897664572af.nq.gz
    ├── 1d86049396f8ae57391c7558ed121311a45d334f.nq.gz
    ├── 1d9d41f979da96ba12f2e42d53a64092a4b595b2.nq.gz
    ├── 1da25f3d4f823842616a758e1d5b263df260fe62.nq.gz
    ├── 1dc0aa24938cc02d3ca5c9ff52c45b95e112308c.nq.gz
    ├── 1dd560c62bf65b1f9ec4a7f13fb9350f2595917a.nq.gz
    ├── 1df24293e085707f26a22f314e2e1eb28cdf37fe.nq.gz
    ├── 1e00fe80e299256dc6a92c41d5885916648c07b7.nq.gz
    ├── 1e05fdce1ab693016bca3548f4cd17dd36d96f1c.nq.gz
    ├── 1e0732b31a49a44c5e7c624e7c5dd50d34ce0c01.nq.gz
    ├── 1e2b27dc9c2da75e976a255d3b38da6d3fc7412b.nq.gz
    ├── 1e5802167f293dc5f22c810258c807423e20861c.nq.gz
    ├── 1e8feb023a26fb4eb0292c2033e68d3922363a18.nq.gz
    ├── 1ec94be41a9c084bd3e9232da4a1cfd6c5c8d0d0.nq.gz
    ├── 1f2c07dd00b575a94a7e44912f3c897c8505ec47.nq.gz
    ├── 1f391b8c5fac6e969262315807cd706ae216d26a.nq.gz
    ├── 1f9d5eca00b2ee88483ccbf744caa423d131ff7e.nq.gz
    ├── 1f9e3671aa6cad7c4cd9d637061bac9d6e269a25.nq.gz
    ├── 1fdc50cea1352b2f1e789ff07c430376924b2f2f.nq.gz
    ├── 20a0186e2e2edd02fa725f421676fb64e2da6931.nq.gz
    ├── 20e71762a6c5bdba45729a2cd9e0c6a33ab65e1f.nq.gz
    ├── 20f9f6ddba92965dbc28bd9760ddb62bfb99e166.nq.gz
    ├── 214f52033856473522e6f9c51aa67203737a54ca.nq.gz
    ├── 21735af1267d6181e8fed4c11642b71095ed45ea.nq.gz
    ├── 218fe3339b3c747d3f7d208d34ad005095ff0ea3.nq.gz
    ├── 21ea767fac97de4c1425d2e7445afb6d64c7c38e.nq.gz
    ├── 21f3a56293243d4a97596b582e261dd1eade66d1.nq.gz
    ├── 22447c7c5af25c706502926e6c60d6c8fc53a500.nq.gz
    ├── 228a04a8aad6f133ccb1313b443019cdce68c1ca.nq.gz
    ├── 22e333f8fa0ab502914cfd19270029aa93e85696.nq.gz
    ├── 2344d98ad794a2d28abb03ca602ca14a16388f80.nq.gz
    ├── 2363bf816375198cb1bc72b134f223fbc66c7caf.nq.gz
    ├── 237b0ba7997b9b6edd8c1eed00df36d88eec1be4.nq.gz
    ├── 23cfee4cb354b129b8f215d5753a25ff223c372e.nq.gz
    ├── 23e8227989fe22bf1976472c7992bd6e44fb889b.nq.gz
    ├── 2426e920e83f68bb0511e0cf59214b0acb08fd3c.nq.gz
    ├── 243be5ebb30dcf3b397d8fbcbfca184c56a616e3.nq.gz
    ├── 2487e8b707d166bac49303211c6a179458dca532.nq.gz
    ├── 24c42a9104191d1465a96ecc26aa823becfd625a.nq.gz
    ├── 2583cc2c117a00fc8185454ae7126b402170abb7.nq.gz
    ├── 25b2cadd1d9ff5981a22e9e9ba2b6c56a036a813.nq.gz
    ├── 25bc38b2a43b220597ca8c2e4a3b87730173a95a.nq.gz
    ├── 25ced1870cfa10148d798a2ce44f5f3e648cc50c.nq.gz
    ├── 26781dbd01feb02054454909e5c348c2d7dcd2c5.nq.gz
    ├── 26922dd7f65a99646c82cc9ff7f1d781457e3dd0.nq.gz
    ├── 269402407a32ba97c40f1109ace6004c1cd3894c.nq.gz
    ├── 269e8df1b14826f22d286cfc351fd7c6f9bc1446.nq.gz
    ├── 26ad56b7d11869adeaf2b4463b22dd898dd0c475.nq.gz
    ├── 27182a8458df46d1d38b36b5c20b4bf1dcd5e0d2.nq.gz
    ├── 27630de681732680a1bbbabd1c54b5b7d496e2d2.nq.gz
    ├── 2795bb1fbb248fe9d9895d6439dc4301bc471a06.nq.gz
    ├── 27b5ddbea9c03da17403c421c12d9c36668865a1.nq.gz
    ├── 27cbe0ee657780a9a463fdd235d3bcd0e5328b72.nq.gz
    ├── 27d378c24a4642a5c9a37f501af6ea41e5543d63.nq.gz
    ├── 28476a40b6dadf876b26e3e1d3fa2515b1c3d714.nq.gz
    ├── 284c36965b527553d55dcf058c51110483061134.nq.gz
    ├── 288197c37c70e10064b120f0109bb79307110abd.nq.gz
    ├── 28b272d716ce572bb983449c3e610ac52a364531.nq.gz
    ├── 29075ab5b67dfc0c81883a29f546fec0711f0e84.nq.gz
    ├── 29caadce4d375fb6796b54b8c7456392cb1adb97.nq.gz
    ├── 29fd35f8557158826f728f846f4c631a18469400.nq.gz
    ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
    ├── 2a58efd3e750d60a39d9162ea10983f64cee7c6c.nq.gz
    ├── 2a6190ea7719a4afa35cbb68c29c2be4810f7223.nq.gz
    ├── 2a841236a7f6ef77eb3dbdc02cec7aba5d32c59b.nq.gz
    └── 2aad7b5731e29560761b7e3c9c6d52dba5fc5846.nq.gz

6 directories, 200 files
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

[pallets/flask](https://github.com/pallets/flask)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
