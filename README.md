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
│   │   ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│   │   ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│   │   ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   │   └── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│   ├── lsp
│   │   ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│   │   ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│   │   ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   │   └── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
│   └── repolex
│       ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│       ├── 3f5db33ece48bd22b77fcc62553998ea9a6cfdfc.nq.gz
│       ├── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│       └── 774b7f768214f5b0c125a1b80daa97247a0ac1a6.nq.gz
└── blob
    ├── 017ce28098014dbfea23778a53255fd7c99e175f.nq.gz
    ├── 038eb51eb634b4883ef659ca9bfa1d1a2d406893.nq.gz
    ├── 03f62ed121ad80928e68f67766e9ecd0be5410ae.nq.gz
    ├── 051e915aa799987320b4ff59b090ad02d3b2a82c.nq.gz
    ├── 07d027dd973f6ecf02986d98bc8bf541e174c057.nq.gz
    ├── 07e702c46a05725b89653f3cb561cef26bde322c.nq.gz
    ├── 087c50dc720b5dff47b8297f634b4dea2e0df02c.nq.gz
    ├── 0890b615f109a3685a820c8948d74f4fab6c96c0.nq.gz
    ├── 089cb914c11c70e0de4e80133676f41b69ff8a02.nq.gz
    ├── 0917c7979122ac42463219ecd00e43589a5ece3c.nq.gz
    ├── 0b0479ef8141f76e3fe83d6452021e4c5be3e55c.nq.gz
    ├── 0b5d887cd96d9223ac3df595b589ed77d19f7ec0.nq.gz
    ├── 0c3a7d0fe561a82c462efd92275417e9d8082ec1.nq.gz
    ├── 0c74ad9260a2888dd2e61e4d8a8adada691f2c4f.nq.gz
    ├── 0cb8f43746c04b95b277d6dcb7af6d1930f09b62.nq.gz
    ├── 0d743205fd28c0a821fac05cb561cc73ef6cd94d.nq.gz
    ├── 0ddcf972d2be7735db12410fe30b2b1fffdb3c88.nq.gz
    ├── 0e25a30c75a9b2e6e164e6e65e85632ed035c5a8.nq.gz
    ├── 0e8caf3e9f3287ae6f1fbe1d18f601a8b0301ff6.nq.gz
    ├── 0e96f15b74a4ca6096c5eaa9f041be909b5e01f1.nq.gz
    ├── 0ec3ca215aa7a78c4f55e51b119883f347f4bac6.nq.gz
    ├── 0f1b97e3aa6905e6929f39df5c1dadf95d2b1eb7.nq.gz
    ├── 0f248783cd942eb6c7da0a52fb361e052e01ab6a.nq.gz
    ├── 0f2a98276c15461e82cfb7e62bee7a4780144a42.nq.gz
    ├── 1032097e509b73af68bcf9cc312d68570b13043f.nq.gz
    ├── 1174ebfcb9e9eb4ae89a8411a5e67c01127159f7.nq.gz
    ├── 11cb9fb0e549e10fe86095432f75e4f4c673c1fa.nq.gz
    ├── 12e23c16f374bfddeec3ef6081aef9478f081fe6.nq.gz
    ├── 134ffcf4d2534251b6fbcc8f95319fc6de369208.nq.gz
    ├── 1387d4a614ceba324b2251d2a3ce15702996e0ac.nq.gz
    ├── 13db5e6691714b405adaffaea7f8594f54a6667c.nq.gz
    ├── 147f49d05ea3199c5d9d4e7eb451d8b9c5b7544c.nq.gz
    ├── 148e50293bdd99c5d6a7f8a0a59241dd87aaab0d.nq.gz
    ├── 1561a37cd9fa0546d42262b1530b070801357a65.nq.gz
    ├── 15911b4ca4587c59a64fd689a8640eb76c1bd449.nq.gz
    ├── 16a0761d9bc3455179c87021d09762e642eef064.nq.gz
    ├── 1a5535cc4d39833d8053fef0c958a01ac8c51a27.nq.gz
    ├── 1aa8048f556a525896a7f8dc65e4ab9011a85086.nq.gz
    ├── 1b17086ce787e05e767e67e16a4842b5a3bd1284.nq.gz
    ├── 1cb779b33bd145c2341772f9676f88d8779dd502.nq.gz
    ├── 1d27396d74e0550dddccedeac3dbd897664572af.nq.gz
    ├── 1d86049396f8ae57391c7558ed121311a45d334f.nq.gz
    ├── 1d9d41f979da96ba12f2e42d53a64092a4b595b2.nq.gz
    ├── 1da25f3d4f823842616a758e1d5b263df260fe62.nq.gz
    ├── 1dc0aa24938cc02d3ca5c9ff52c45b95e112308c.nq.gz
    ├── 1df24293e085707f26a22f314e2e1eb28cdf37fe.nq.gz
    ├── 1e2b27dc9c2da75e976a255d3b38da6d3fc7412b.nq.gz
    ├── 1ec94be41a9c084bd3e9232da4a1cfd6c5c8d0d0.nq.gz
    ├── 1f2c07dd00b575a94a7e44912f3c897c8505ec47.nq.gz
    ├── 1f391b8c5fac6e969262315807cd706ae216d26a.nq.gz
    ├── 1fdc50cea1352b2f1e789ff07c430376924b2f2f.nq.gz
    ├── 20a0186e2e2edd02fa725f421676fb64e2da6931.nq.gz
    ├── 20f9f6ddba92965dbc28bd9760ddb62bfb99e166.nq.gz
    ├── 214f52033856473522e6f9c51aa67203737a54ca.nq.gz
    ├── 21f3a56293243d4a97596b582e261dd1eade66d1.nq.gz
    ├── 22447c7c5af25c706502926e6c60d6c8fc53a500.nq.gz
    ├── 2344d98ad794a2d28abb03ca602ca14a16388f80.nq.gz
    ├── 2363bf816375198cb1bc72b134f223fbc66c7caf.nq.gz
    ├── 23e8227989fe22bf1976472c7992bd6e44fb889b.nq.gz
    ├── 2487e8b707d166bac49303211c6a179458dca532.nq.gz
    ├── 2583cc2c117a00fc8185454ae7126b402170abb7.nq.gz
    ├── 25bc38b2a43b220597ca8c2e4a3b87730173a95a.nq.gz
    ├── 288197c37c70e10064b120f0109bb79307110abd.nq.gz
    ├── 29075ab5b67dfc0c81883a29f546fec0711f0e84.nq.gz
    ├── 29caadce4d375fb6796b54b8c7456392cb1adb97.nq.gz
    ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
    ├── 2a58efd3e750d60a39d9162ea10983f64cee7c6c.nq.gz
    ├── 2a6190ea7719a4afa35cbb68c29c2be4810f7223.nq.gz
    ├── 2a841236a7f6ef77eb3dbdc02cec7aba5d32c59b.nq.gz
    ├── 2c125e118170d18327eb5ff54ab19bdc7df13671.nq.gz
    ├── 2c8634f9195cf38242e9ff5e971cb2963ec4169f.nq.gz
    ├── 2c8c4c483677d2233f34baf82263d747f882d561.nq.gz
    ├── 2c96c9b4d96713cbc6247534cebac3239f5b98d2.nq.gz
    ├── 2d74c58f248790e34e482eb07e20ec6c753c9d2d.nq.gz
    ├── 2e9a43a731f7b6a360eb8b32f7d8dc8f4ec12248.nq.gz
    ├── 2f1f4d0c3c57c4916577e3acc4b9d3f1d1e6f23c.nq.gz
    ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
    ├── 304f57dcff8edc56f0bf01abdf814fa8263a0dbc.nq.gz
    ├── 31c40023908f23c36ebf3771daffefb89781efd0.nq.gz
    ├── 32ab333e6322b948bf856efed7931f5e14b26e01.nq.gz
    ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
    ├── 34c03a204f03fdfb339640b788044174e7487eb7.nq.gz
    ├── 34edd79116eb246be11fb1b6b07be11e0128bd88.nq.gz
    ├── 34ef1a57217878e21daba0bc4f20ded293a33e7e.nq.gz
    ├── 35e82d4ef4d49785aa34c3af635ba146f1224411.nq.gz
    ├── 361c1aee513e24aae1de1a1b116cda303792450b.nq.gz
    ├── 381477f975c02d60fd64f5c0a0f1ecd4627a3506.nq.gz
    ├── 38777e6662be20bd6e83f28cdacf89687792ce02.nq.gz
    ├── 390361a64fe4a46fb95f3fba4c4dc8dd78701b7f.nq.gz
    ├── 3945c1fab92329976f7a97867f9cf1cc17928c50.nq.gz
    ├── 395882423393d0a68f941c152836a815fb08149c.nq.gz
    ├── 3a7521d4404aabbbad1f888fee13165b38fe7bc3.nq.gz
    ├── 3ad12879a8ce32f7dab8a92af9e13468106651a8.nq.gz
    ├── 3b4a33817aa6ecec3b1920bd220f238ebd9159ab.nq.gz
    ├── 3be35fb658f2be01fa0f9156b4dddf013dc2fe69.nq.gz
    ├── 3c5e3583ce3cccd788278bdf6ab471f95cbec142.nq.gz
    ├── 3cc3a7f09397bc0122f72c17343f3875e5bd9e6b.nq.gz
    ├── 3e95ab320c56d510376ec560b1a8219a69434139.nq.gz
    ├── 3ea43b97aeb75eb464954b3e5bd1c845e2904d9a.nq.gz
    ├── 3ead05c5f6cd9672c66d57c46c46a2163bbcaaad.nq.gz
    ├── 3f2d659eef042335e5224597c7bd6779592b1d97.nq.gz
    ├── 3fef8b5b77e9da852a55e696929b534f216faca4.nq.gz
    ├── 4027d8cea1d67d85764c4e271e838ba99be02551.nq.gz
    ├── 4118b5ec67df9f2eef861c734030f3631cff0c6f.nq.gz
    ├── 413ea84d445105ed1e2b588396d49efced3c5b76.nq.gz
    ├── 4233808bdeca88d52cd6a842ff5119434c5260b7.nq.gz
    ├── 444fda9987b0e77d78afdd08d74d31b5516c8642.nq.gz
    ├── 44633b331c83bdb653f8ff749b1b5df2205ab95c.nq.gz
    ├── 448dba71809ed755881ed56686edfb59d5641cf0.nq.gz
    ├── 45198266c6a481104f76d07778086e1df9164ead.nq.gz
    ├── 45dbb87e20ba5e0361a12bec97e11aae9d5ebb3a.nq.gz
    ├── 45fff0ca21a84eb545b1617e348573ed0ddd4da5.nq.gz
    ├── 470bceca8dd162ac336434abd0fceb812ab3cc4b.nq.gz
    ├── 4713ec8e2d9caa49b122d009cf5303c3ab82afee.nq.gz
    ├── 47b6c3d7bd85571f0cbfb7d169f520bf4dda4b25.nq.gz
    ├── 49620ff8e5c3b4654dddf8f9cb589df2d7d82fa2.nq.gz
    ├── 4ac1083d91123945ba3ff2f545fa1c8efd00d688.nq.gz
    ├── 4b3374e26d40d2760ef7ec947ec98fd69db79945.nq.gz
    ├── 4cd9dd27abcfee301850bac388e8ccb139c98138.nq.gz
    ├── 4db03b75b604b47db3d2ac2db5ac3e0a6ac09329.nq.gz
    ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
    ├── 4ea27f5e2fdf93662d7755cd78c2427560edf789.nq.gz
    ├── 4ed0f3281fcd985b26f454e093ccfcb75e677f84.nq.gz
    ├── 4eedab128e1cc41a1ffe6a7c0a55d3b2f4362942.nq.gz
    ├── 4eedf68fd092a1268951022295f3af0738f7f8b4.nq.gz
    ├── 4f1846a346172e5f58744bbfb61c9d83c662d9ab.nq.gz
    ├── 4f3b71d8aed0f65b6ee2a0f9c3ae457dc03de944.nq.gz
    ├── 4f47229d6a24d5e42980c274591b1de30d7ff0d5.nq.gz
    ├── 4f912cca0565669ac6360982716b3bc19c72a5ca.nq.gz
    ├── 4ff8814b40c71c6c8452d06c211d3d34dc0b40a4.nq.gz
    ├── 50aba04d5713881541f6f4d8f4f6e743d06de7dc.nq.gz
    ├── 50ad6fa8d8b8ba9b571f683f434b6b9031ffa287.nq.gz
    ├── 52c2aed416c35b7bdeef1793a6a9fb2c4482682e.nq.gz
    ├── 52d78d9efe62717d529631ab25b56494389c520a.nq.gz
    ├── 53fe976dc2ad658e761690eff40ae3e9e014e1e5.nq.gz
    ├── 542864e8bbfcf90840302dd4dd0126ca84560c07.nq.gz
    ├── 5509a9a781fc6cf75b1fa6dafa19830f8c120872.nq.gz
    ├── 55c769d8174e10790027ccdda5ed301707ff6a8f.nq.gz
    ├── 55eb12fe75457dd03345e37dd18b0075e6f578c1.nq.gz
    ├── 56d57f88cde544a3a08e2d771ec79649b077453a.nq.gz
    ├── 574cb75d9803044d56e755c9ecd4d377d514c848.nq.gz
    ├── 5817aa29cc0572c27955d159a6d097e6ae80b429.nq.gz
    ├── 58cb87306293c40ad3f6f4082ec7beb74e3885d1.nq.gz
    ├── 5932589ffa4d7d36c2f360a294bce18034cf270e.nq.gz
    ├── 59f96af759045e90ec82c5139391216379792a33.nq.gz
    ├── 5a33d1f6b8d4343f50225922f00f4f55c40fdde6.nq.gz
    ├── 5b19f1d52f05419a521c4583f09dac4b9438e47b.nq.gz
    ├── 5b4202ad6bfbf8c1e8f8e8f4e857b0eed9bf861d.nq.gz
    ├── 5b4f6e8066957823117c5b4d1946487a3bd4b1b2.nq.gz
    ├── 5c012aaaf298ca817e7ad4cb21b8f1e55e58083c.nq.gz
    ├── 5c603cc22c086a9257ee1c91277c42413e6650c4.nq.gz
    ├── 5d2693890dddc34129973f5613afd88767213b24.nq.gz
    ├── 5d412c90f2bde5ab32adcf6126908330bb2880d6.nq.gz
    ├── 5deaf1b84eedf509fc1c0d853357b605880c8dfe.nq.gz
    ├── 5e685c7eea85bfd8d113bf05f524bb817ac64d0d.nq.gz
    ├── 5eaaf9c5511f2b77d16c18923e66acca9e5aeeba.nq.gz
    ├── 5ec5584d2459dbd92f1536cd6922e1a138769264.nq.gz
    ├── 5f7b1f1db013739d1b3b24f5014af62cf2bd21ba.nq.gz
    ├── 602b999dfd1db503d63c3c93994264616e85abc6.nq.gz
    ├── 61080932a8927fe51d8706a2fadfca1648f28527.nq.gz
    ├── 613da37fd2ecc73b5156c75fc3d88bcf5b6cd2b7.nq.gz
    ├── 616c298b4df0b61a8c23ced30a69e8259afa7a94.nq.gz
    ├── 61b3cbc4212f32a30d5a6593ad7cd216f0039919.nq.gz
    ├── 61b9dc0532f8f3e4ac3d92bf8f0157c8491e49b9.nq.gz
    ├── 623ac1982366d862db0a9d950fa2f50dd334d32f.nq.gz
    ├── 624988e4232da0cff6d95040bbe73f968624e8cd.nq.gz
    ├── 62e5c75ea859f270ceec52e689023a4c6998d5d0.nq.gz
    ├── 6312a345f63e627758e7282283dfd253437dbed8.nq.gz
    ├── 64acdbdd09c0f7a831738fa7201d4e7ded63ae47.nq.gz
    ├── 64f56cac4f9d60020a39b9c2f803b1846796cf6d.nq.gz
    ├── 653c216729dd4f9aac68ee375f52587d69981645.nq.gz
    ├── 65678a1585822aa07320b3e5962e11510bfa30f6.nq.gz
    ├── 658a1cd43c890251140d69db7b938368c245ca26.nq.gz
    ├── 677160a6367e6dfb540bbfda5c4ef92331a99427.nq.gz
    ├── 697d20779c1503ad276be4d3fc92e5120b24ac54.nq.gz
    ├── 6a8df19e1ceabd262f31532cf0475d20fbae5192.nq.gz
    ├── 6b25c073e8406294ebad12474afd30693b627ff3.nq.gz
    ├── 6b407b3452021088a514d2f98f3e64f9dbdbc90d.nq.gz
    ├── 6b70c409735e07f05b31352437d715aa042fc14f.nq.gz
    ├── 6bf62f0a8fcf6f922fe43bf58fb625b7352492f4.nq.gz
    ├── 6c38b66186e00c37e10583a32f8aff111215d667.nq.gz
    ├── 6c95c6e258f2fb904026706fbf538c594815c1cc.nq.gz
    ├── 6cd6e3980fbf1b5b619d2e013723368d137fafdc.nq.gz
    ├── 6d5e07e27dbb39294575e21ccd51573e32cccbeb.nq.gz
    ├── 6ee8b441efc1fc9a24d43e8c193d2889cee0844f.nq.gz
    ├── 6f37373137ca51076f3e47b052260e8504755cda.nq.gz
    ├── 6f3e5cc6a00105433cbc995e493d7afb673090a6.nq.gz
    └── 6f8e59f44dce31bf5cefa4a1dd69bbdf8ec98ac2.nq.gz

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
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
