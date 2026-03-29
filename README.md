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
│   │   ├── 298334fffc8288b5a9a45ef4150e3c4292e45318.nq.gz
│   │   ├── 3205b53c7cf69d17fee49cac6b84978175b7dd73.nq.gz
│   │   ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│   │   ├── 47af817c8fe01045c641b97f8fb784c7ad864eee.nq.gz
│   │   ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   │   ├── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│   │   ├── c12a5d874c5a014495eb2db8a73f40037bc813ac.nq.gz
│   │   ├── d1d82ca8ce7262ad9d27245ce44f86571287810e.nq.gz
│   │   └── ef557b3ff2602b9956a2f3ac02c6e134c529fccc.nq.gz
│   ├── lsp
│   │   ├── 187d7179f605d28c3d24e9f4d65d3295fb099afe.nq.gz
│   │   ├── 191710cbda616a53533d5e794a787f24c453ac5a.nq.gz
│   │   ├── 19def9606ac50bd308ea283e283cbcf62498d6c7.nq.gz
│   │   ├── 1ca199f9b38b70a4e97cb47a4252ffd7fccc008c.nq.gz
│   │   ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│   │   ├── 298334fffc8288b5a9a45ef4150e3c4292e45318.nq.gz
│   │   ├── 3205b53c7cf69d17fee49cac6b84978175b7dd73.nq.gz
│   │   ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│   │   ├── 47af817c8fe01045c641b97f8fb784c7ad864eee.nq.gz
│   │   ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   │   ├── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│   │   ├── c12a5d874c5a014495eb2db8a73f40037bc813ac.nq.gz
│   │   ├── d1d82ca8ce7262ad9d27245ce44f86571287810e.nq.gz
│   │   └── ef557b3ff2602b9956a2f3ac02c6e134c529fccc.nq.gz
│   └── repolex
│       ├── 187d7179f605d28c3d24e9f4d65d3295fb099afe.nq.gz
│       ├── 191710cbda616a53533d5e794a787f24c453ac5a.nq.gz
│       ├── 19def9606ac50bd308ea283e283cbcf62498d6c7.nq.gz
│       ├── 1ca199f9b38b70a4e97cb47a4252ffd7fccc008c.nq.gz
│       ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│       ├── 298334fffc8288b5a9a45ef4150e3c4292e45318.nq.gz
│       ├── 3205b53c7cf69d17fee49cac6b84978175b7dd73.nq.gz
│       ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│       ├── 47af817c8fe01045c641b97f8fb784c7ad864eee.nq.gz
│       ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│       ├── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│       ├── c12a5d874c5a014495eb2db8a73f40037bc813ac.nq.gz
│       ├── d1d82ca8ce7262ad9d27245ce44f86571287810e.nq.gz
│       └── ef557b3ff2602b9956a2f3ac02c6e134c529fccc.nq.gz
└── blob
    ├── 00f56f0911fc935a561fe6c6d5bd1d58c88da79a.nq.gz
    ├── 014d579fef8878c35e39e33a2f0e68fa02860376.nq.gz
    ├── 01584d36c5c25331a17068bbf487255867b000b0.nq.gz
    ├── 015e7b613b49d8aa15db4bd0295ce654f1c765bd.nq.gz
    ├── 017ce28098014dbfea23778a53255fd7c99e175f.nq.gz
    ├── 0188cc5446be509870888ecbd6db385bf96d45ac.nq.gz
    ├── 01bf7976e7a496069ee00e7f2b7c292fa86daf42.nq.gz
    ├── 01fd5dbfaefe3f79a137957639e4df8a6c057501.nq.gz
    ├── 0249b88e7b79dfeb3bca9f2686d9e673d08dfda2.nq.gz
    ├── 033a5149f3d65384dae9289791b55cd554d377d4.nq.gz
    ├── 034ab5be0743e919cb44bb33323a316ccdfd0d25.nq.gz
    ├── 036ec176a91759a7318d718d2f2070b9ba752fcb.nq.gz
    ├── 038eb51eb634b4883ef659ca9bfa1d1a2d406893.nq.gz
    ├── 03bd3b3c98c71ab8a39247985a0ea1d784483342.nq.gz
    ├── 03f62ed121ad80928e68f67766e9ecd0be5410ae.nq.gz
    ├── 0407f86fefdca40ce4487ad006a4e65bee0d1ee6.nq.gz
    ├── 043beb07757e8fb50c041bf74f2328137764fdf0.nq.gz
    ├── 050fd7e0f36eef116876ed9a849d2a8aceb3d1e6.nq.gz
    ├── 051e915aa799987320b4ff59b090ad02d3b2a82c.nq.gz
    ├── 051f44ac4051aa73ef23be0bf8a8873dec5aa4f6.nq.gz
    ├── 052d36e10810367c4e1fd37373c0e68d551601bd.nq.gz
    ├── 053148f848642cb6c79ecb61968f0a9d3fea8bb4.nq.gz
    ├── 05316607aa9462abd54e60febaa250484df34dbf.nq.gz
    ├── 053f08044dc9e9e758057cefdd08d87c76095c88.nq.gz
    ├── 056ecc7d5239741889705b42723f70dd6a54582f.nq.gz
    ├── 05b8758c0f7e88b22a02f16aec551c16eb6cc673.nq.gz
    ├── 05d4f2f352c3d6f78ccfc4403453030ab13b5b46.nq.gz
    ├── 062711083595e71f4eed43f41c6da45220c4ed83.nq.gz
    ├── 066cf107c1e5305790c1376c791173b22752677a.nq.gz
    ├── 068b2d98ed479b952eded5de98abd18398a9c651.nq.gz
    ├── 06a29fccc19345d52b4541ec4673512f1e0633d4.nq.gz
    ├── 06c265ba9df6f45d6f022810c860b523f47bd41d.nq.gz
    ├── 071628fc1148e435b70084d31216605631c2d2e7.nq.gz
    ├── 0754669fa67f80449d5b80edd66e3eaa95abd068.nq.gz
    ├── 077cb4329832983e7a605b2478da36d1a4661491.nq.gz
    ├── 07a762d88b35b72d0ee6c708947b024c80fb6f74.nq.gz
    ├── 07bbc048864e2ce40981643cf28cd90d16be8468.nq.gz
    ├── 07ca5c6542a4da7e150850ef8a4cf1d500db1fbc.nq.gz
    ├── 07d027dd973f6ecf02986d98bc8bf541e174c057.nq.gz
    ├── 07e702c46a05725b89653f3cb561cef26bde322c.nq.gz
    ├── 082c7065d554e3234c70836302be0baa6cff5d45.nq.gz
    ├── 084f13f4dcbebaf805d10dec45128e6a8706f80a.nq.gz
    ├── 087c50dc720b5dff47b8297f634b4dea2e0df02c.nq.gz
    ├── 0890b615f109a3685a820c8948d74f4fab6c96c0.nq.gz
    ├── 089cb914c11c70e0de4e80133676f41b69ff8a02.nq.gz
    ├── 08ba4800175cd6aabaee4db3b1776031740fbd64.nq.gz
    ├── 08fc42ab0cb504469472f618d74036e82a6da2bd.nq.gz
    ├── 0912b7a1d5cb7d688b45f9ff665b30be243012f9.nq.gz
    ├── 0917c7979122ac42463219ecd00e43589a5ece3c.nq.gz
    ├── 09752974bc5f1aeba5d7d49d24a26a7c14bd0d13.nq.gz
    ├── 09995488cc2dc3710b9c944713abbee79ec28ea6.nq.gz
    ├── 09bf2d2c861eb4cafae385b2738a090a9e0556e3.nq.gz
    ├── 0a75bb71a5bcd8caa7d5ee559a60681d3663328e.nq.gz
    ├── 0ac278b5e42d54dc49ef1906c467b65bcad7c7a4.nq.gz
    ├── 0b0479ef8141f76e3fe83d6452021e4c5be3e55c.nq.gz
    ├── 0b5d887cd96d9223ac3df595b589ed77d19f7ec0.nq.gz
    ├── 0b6ff5048bc45a6a34a8593a913c9d6eb76e8127.nq.gz
    ├── 0b70a3ef925bee137b93933517c1aa0e268bbbfd.nq.gz
    ├── 0b86674d88577ab6d8353cc0e2502a1d5d7efde1.nq.gz
    ├── 0ba3d5b8cfec31c56f69f14d222660fdeb010111.nq.gz
    ├── 0ba46c13d58b3af799808d8963c7d65349a7989e.nq.gz
    ├── 0bc0a9dbec1dc2c5a8874c90db86b11e9131ae3f.nq.gz
    ├── 0c3a7d0fe561a82c462efd92275417e9d8082ec1.nq.gz
    ├── 0c5e846efdfe3d15ec188cfd89f8c007548093b6.nq.gz
    ├── 0c74ad9260a2888dd2e61e4d8a8adada691f2c4f.nq.gz
    ├── 0cb8f43746c04b95b277d6dcb7af6d1930f09b62.nq.gz
    ├── 0cd39ddc703c1ce2b8e75d4d52687f03d3663512.nq.gz
    ├── 0d0028e25f81b8228a2c0f66b601d60445e263ab.nq.gz
    ├── 0d02e465583b2e5d71bab01b40a161228ab8d21a.nq.gz
    ├── 0d1d9eea7d41ca9b79094a4f761d73124c586d49.nq.gz
    ├── 0d4b656131e62229005770d748d412dc2632503c.nq.gz
    ├── 0d5e126fe1b977f1fb60fb00a0aa2ef319cc3180.nq.gz
    ├── 0d743205fd28c0a821fac05cb561cc73ef6cd94d.nq.gz
    ├── 0d7ad3f695d3db68cb04eae14ef871596cad6d6a.nq.gz
    ├── 0d9625b114eb94c8f8ddb945ffec2379351c0f35.nq.gz
    ├── 0ddcf972d2be7735db12410fe30b2b1fffdb3c88.nq.gz
    ├── 0e215252255879d6731feb1e54f1fecf1ce6cece.nq.gz
    ├── 0e25a30c75a9b2e6e164e6e65e85632ed035c5a8.nq.gz
    ├── 0e6a8856f3db78425f0796f46ec4ec948752886d.nq.gz
    ├── 0e8caf3e9f3287ae6f1fbe1d18f601a8b0301ff6.nq.gz
    ├── 0e96f15b74a4ca6096c5eaa9f041be909b5e01f1.nq.gz
    ├── 0ec3ca215aa7a78c4f55e51b119883f347f4bac6.nq.gz
    ├── 0ec631d2c5044d6a9cb02bb2922320c1a66eee80.nq.gz
    ├── 0ed495591672e9e0a68988dafefbebf9044adc24.nq.gz
    ├── 0edd3d58d7d9ca85e5fc216b24da0eacc16d47ec.nq.gz
    ├── 0f1b97e3aa6905e6929f39df5c1dadf95d2b1eb7.nq.gz
    ├── 0f248783cd942eb6c7da0a52fb361e052e01ab6a.nq.gz
    ├── 0f2a98276c15461e82cfb7e62bee7a4780144a42.nq.gz
    ├── 0f99a7e8c98d90d746732f55e52b1c3d890abc6f.nq.gz
    ├── 0facbfee9062771fe95a8ed1d2b36045f097a46b.nq.gz
    ├── 1032097e509b73af68bcf9cc312d68570b13043f.nq.gz
    ├── 10718760112b52ab1bf74f8fb1eafacd23d87bcb.nq.gz
    ├── 10b886bf05bcfc267110515f5ccd0b83bbec3419.nq.gz
    ├── 114873e29b9d9194d82380c43379e8fa9ab09147.nq.gz
    ├── 116774338dede8bf9542aa86a10c908bd325378e.nq.gz
    ├── 11700458b4bd7e829521eaff535708fcd3be52d7.nq.gz
    ├── 1174ebfcb9e9eb4ae89a8411a5e67c01127159f7.nq.gz
    ├── 11cb9fb0e549e10fe86095432f75e4f4c673c1fa.nq.gz
    ├── 11d6684d2e091ddd9325302eb0344539a1acbac5.nq.gz
    ├── 11e976bc7387072f10e7b6d20607c965381b178a.nq.gz
    ├── 12336fb1b4546540f3a7881c095139262e51fc07.nq.gz
    ├── 1241193a73406271ac37652253c9802348128a33.nq.gz
    ├── 1292f26e214ba5ef3e6f3b98da1bbc3aac1fcef2.nq.gz
    ├── 12e23c16f374bfddeec3ef6081aef9478f081fe6.nq.gz
    ├── 1339a6257b0853212596e1eb9610fca2b253b84d.nq.gz
    ├── 134ffcf4d2534251b6fbcc8f95319fc6de369208.nq.gz
    ├── 1387d4a614ceba324b2251d2a3ce15702996e0ac.nq.gz
    ├── 13ac34837b43a24cf956996f3b7614feb782b880.nq.gz
    ├── 13b61eeeebf19956c9141008785272546a18da42.nq.gz
    ├── 13db5e6691714b405adaffaea7f8594f54a6667c.nq.gz
    ├── 1404e17e74820a5909d4e0663a9889f814c82ed3.nq.gz
    ├── 143d6924869035709f6fe46a2a641e06416629d0.nq.gz
    ├── 147f49d05ea3199c5d9d4e7eb451d8b9c5b7544c.nq.gz
    ├── 148e50293bdd99c5d6a7f8a0a59241dd87aaab0d.nq.gz
    ├── 14c5ade0bfe6fdc70cb2fbce4116e2fd26b02cdb.nq.gz
    ├── 155afa2fbf1af9b1357b8f7876d4aa36d4dba1b1.nq.gz
    ├── 1561a37cd9fa0546d42262b1530b070801357a65.nq.gz
    ├── 15911b4ca4587c59a64fd689a8640eb76c1bd449.nq.gz
    ├── 16580d16d2e7222b6ed7e44ecb5319bd8f47e91f.nq.gz
    ├── 166c5aa3769ab66c252c2c9136c932f1c275afe7.nq.gz
    ├── 1677663fd5fc90973cff5528a18449e71e29a73f.nq.gz
    ├── 167f2f413c3de9bf84a802f67be383f594c161bc.nq.gz
    ├── 16a0761d9bc3455179c87021d09762e642eef064.nq.gz
    ├── 16d7e6709f7cd7385ffaeadf9566e1513f6cdfbf.nq.gz
    ├── 172f6a01b32b2cfee5df94b8bef7b5862475b62b.nq.gz
    ├── 1733f0a3b629259c0c5ffe70ef42da42d4b5cd1b.nq.gz
    ├── 17e79500ae2d5d72724e030b7763ff4b0230eec0.nq.gz
    ├── 17ff2f3db7e2fbcb857f0395dcfe7882d40423f9.nq.gz
    ├── 183bdb69fa34408a7b3ea024d294c353f0cf9ea3.nq.gz
    ├── 18b4fa7d205b20070df3fc5fd0aad1250bd01aec.nq.gz
    ├── 18eac19389474433d970dd3693bf4958f6f5b991.nq.gz
    ├── 18f5c9b3a9f93e8db0ec4de17f34d2d427183333.nq.gz
    ├── 1918bd999d24096470be1c766363e897f9b302b3.nq.gz
    ├── 1928219a233944646a83a809be6c09f71b72bb49.nq.gz
    ├── 196545d0e0052553238b6c1cdc489563b7c1ca4b.nq.gz
    ├── 19993402ffe9b947c62cd579cf5dfe63b30499de.nq.gz
    ├── 19d4675a15a71bf2eeb056defcf26aa5d9cae669.nq.gz
    ├── 1a17824ae0f6ed84fdc4edde36a791915d66e456.nq.gz
    ├── 1a43fdc1530c1de8ac5f40b649bd0b7ab9e37102.nq.gz
    ├── 1a478917be8677edb26d739e94ac42248318f842.nq.gz
    ├── 1a5535cc4d39833d8053fef0c958a01ac8c51a27.nq.gz
    ├── 1a87f8d446a79906356fc923c48e4df5ea06200d.nq.gz
    ├── 1a89ffe5962fabbcf427be1da2241b3b6fafcbc8.nq.gz
    ├── 1aa8048f556a525896a7f8dc65e4ab9011a85086.nq.gz
    ├── 1afb1ebd133f20a75e77a66e568e15143fba6a1f.nq.gz
    ├── 1b17086ce787e05e767e67e16a4842b5a3bd1284.nq.gz
    ├── 1b35cc7a0bf29766350f4b7fb68de77f9990e04a.nq.gz
    ├── 1bbc778da2a4bead8e877d8a7503ac35e203b331.nq.gz
    ├── 1bca80c38ef3a7e628ae2fd88141df81b8cfe14e.nq.gz
    ├── 1bd5c68b06c7dc424789d354d77fbb9acdc5cc62.nq.gz
    ├── 1bf130f52baa3bec808907c61f57e947741b249b.nq.gz
    ├── 1bf1815c3580c5816558bea2826e95e6c4c511ef.nq.gz
    ├── 1bf466378d4d6142799fe3b0dee00a219ecee357.nq.gz
    ├── 1c1c7b816b2124d97b6394f391f8b76e31d71b52.nq.gz
    ├── 1c4f466c5a3b7eb9b680b6d495a8d3930f65da43.nq.gz
    ├── 1c745078bc0abf9ae2c9417a80aeabd63be61d1a.nq.gz
    ├── 1c7f9bd0896782bdc0d194b4312c695abbe4dd7f.nq.gz
    └── 1cb779b33bd145c2341772f9676f88d8779dd502.nq.gz

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
*Parsed on 2026-03-29 by [repolex](https://repolex.ai)*
