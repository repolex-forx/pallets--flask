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
│   │   └── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   ├── lsp
│   │   ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│   │   └── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
│   └── repolex
│       ├── 22d924701a6ae2e4cd01e9a15bbaf3946094af65.nq.gz
│       └── 6b3e616cf905fd19c37fca93d1198cad1490567b.nq.gz
└── blob
    ├── 017ce28098014dbfea23778a53255fd7c99e175f.nq.gz
    ├── 038eb51eb634b4883ef659ca9bfa1d1a2d406893.nq.gz
    ├── 051e915aa799987320b4ff59b090ad02d3b2a82c.nq.gz
    ├── 07d027dd973f6ecf02986d98bc8bf541e174c057.nq.gz
    ├── 07e702c46a05725b89653f3cb561cef26bde322c.nq.gz
    ├── 087c50dc720b5dff47b8297f634b4dea2e0df02c.nq.gz
    ├── 0890b615f109a3685a820c8948d74f4fab6c96c0.nq.gz
    ├── 089cb914c11c70e0de4e80133676f41b69ff8a02.nq.gz
    ├── 0917c7979122ac42463219ecd00e43589a5ece3c.nq.gz
    ├── 0b0479ef8141f76e3fe83d6452021e4c5be3e55c.nq.gz
    ├── 0c74ad9260a2888dd2e61e4d8a8adada691f2c4f.nq.gz
    ├── 0cb8f43746c04b95b277d6dcb7af6d1930f09b62.nq.gz
    ├── 0d743205fd28c0a821fac05cb561cc73ef6cd94d.nq.gz
    ├── 0ddcf972d2be7735db12410fe30b2b1fffdb3c88.nq.gz
    ├── 0e25a30c75a9b2e6e164e6e65e85632ed035c5a8.nq.gz
    ├── 0e8caf3e9f3287ae6f1fbe1d18f601a8b0301ff6.nq.gz
    ├── 0e96f15b74a4ca6096c5eaa9f041be909b5e01f1.nq.gz
    ├── 0ec3ca215aa7a78c4f55e51b119883f347f4bac6.nq.gz
    ├── 0f248783cd942eb6c7da0a52fb361e052e01ab6a.nq.gz
    ├── 1174ebfcb9e9eb4ae89a8411a5e67c01127159f7.nq.gz
    ├── 12e23c16f374bfddeec3ef6081aef9478f081fe6.nq.gz
    ├── 148e50293bdd99c5d6a7f8a0a59241dd87aaab0d.nq.gz
    ├── 1561a37cd9fa0546d42262b1530b070801357a65.nq.gz
    ├── 16a0761d9bc3455179c87021d09762e642eef064.nq.gz
    ├── 1a5535cc4d39833d8053fef0c958a01ac8c51a27.nq.gz
    ├── 1aa8048f556a525896a7f8dc65e4ab9011a85086.nq.gz
    ├── 1cb779b33bd145c2341772f9676f88d8779dd502.nq.gz
    ├── 1d27396d74e0550dddccedeac3dbd897664572af.nq.gz
    ├── 1dc0aa24938cc02d3ca5c9ff52c45b95e112308c.nq.gz
    ├── 1df24293e085707f26a22f314e2e1eb28cdf37fe.nq.gz
    ├── 1e2b27dc9c2da75e976a255d3b38da6d3fc7412b.nq.gz
    ├── 1ec94be41a9c084bd3e9232da4a1cfd6c5c8d0d0.nq.gz
    ├── 1f2c07dd00b575a94a7e44912f3c897c8505ec47.nq.gz
    ├── 1fdc50cea1352b2f1e789ff07c430376924b2f2f.nq.gz
    ├── 20f9f6ddba92965dbc28bd9760ddb62bfb99e166.nq.gz
    ├── 214f52033856473522e6f9c51aa67203737a54ca.nq.gz
    ├── 2344d98ad794a2d28abb03ca602ca14a16388f80.nq.gz
    ├── 2363bf816375198cb1bc72b134f223fbc66c7caf.nq.gz
    ├── 23e8227989fe22bf1976472c7992bd6e44fb889b.nq.gz
    ├── 25bc38b2a43b220597ca8c2e4a3b87730173a95a.nq.gz
    ├── 288197c37c70e10064b120f0109bb79307110abd.nq.gz
    ├── 29075ab5b67dfc0c81883a29f546fec0711f0e84.nq.gz
    ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
    ├── 2a58efd3e750d60a39d9162ea10983f64cee7c6c.nq.gz
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
    ├── 34ef1a57217878e21daba0bc4f20ded293a33e7e.nq.gz
    ├── 381477f975c02d60fd64f5c0a0f1ecd4627a3506.nq.gz
    ├── 3945c1fab92329976f7a97867f9cf1cc17928c50.nq.gz
    ├── 395882423393d0a68f941c152836a815fb08149c.nq.gz
    ├── 3ad12879a8ce32f7dab8a92af9e13468106651a8.nq.gz
    ├── 3e95ab320c56d510376ec560b1a8219a69434139.nq.gz
    ├── 3ead05c5f6cd9672c66d57c46c46a2163bbcaaad.nq.gz
    ├── 3f2d659eef042335e5224597c7bd6779592b1d97.nq.gz
    ├── 4118b5ec67df9f2eef861c734030f3631cff0c6f.nq.gz
    ├── 444fda9987b0e77d78afdd08d74d31b5516c8642.nq.gz
    ├── 448dba71809ed755881ed56686edfb59d5641cf0.nq.gz
    ├── 45198266c6a481104f76d07778086e1df9164ead.nq.gz
    ├── 45dbb87e20ba5e0361a12bec97e11aae9d5ebb3a.nq.gz
    ├── 470bceca8dd162ac336434abd0fceb812ab3cc4b.nq.gz
    ├── 4713ec8e2d9caa49b122d009cf5303c3ab82afee.nq.gz
    ├── 47b6c3d7bd85571f0cbfb7d169f520bf4dda4b25.nq.gz
    ├── 49620ff8e5c3b4654dddf8f9cb589df2d7d82fa2.nq.gz
    ├── 4b3374e26d40d2760ef7ec947ec98fd69db79945.nq.gz
    ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
    ├── 4ea27f5e2fdf93662d7755cd78c2427560edf789.nq.gz
    ├── 4ed0f3281fcd985b26f454e093ccfcb75e677f84.nq.gz
    ├── 4eedab128e1cc41a1ffe6a7c0a55d3b2f4362942.nq.gz
    ├── 4f1846a346172e5f58744bbfb61c9d83c662d9ab.nq.gz
    ├── 4f3b71d8aed0f65b6ee2a0f9c3ae457dc03de944.nq.gz
    ├── 4f47229d6a24d5e42980c274591b1de30d7ff0d5.nq.gz
    ├── 4f912cca0565669ac6360982716b3bc19c72a5ca.nq.gz
    ├── 4ff8814b40c71c6c8452d06c211d3d34dc0b40a4.nq.gz
    ├── 50aba04d5713881541f6f4d8f4f6e743d06de7dc.nq.gz
    ├── 52c2aed416c35b7bdeef1793a6a9fb2c4482682e.nq.gz
    ├── 52d78d9efe62717d529631ab25b56494389c520a.nq.gz
    ├── 53fe976dc2ad658e761690eff40ae3e9e014e1e5.nq.gz
    ├── 542864e8bbfcf90840302dd4dd0126ca84560c07.nq.gz
    ├── 5509a9a781fc6cf75b1fa6dafa19830f8c120872.nq.gz
    ├── 55c769d8174e10790027ccdda5ed301707ff6a8f.nq.gz
    ├── 55eb12fe75457dd03345e37dd18b0075e6f578c1.nq.gz
    ├── 56d57f88cde544a3a08e2d771ec79649b077453a.nq.gz
    ├── 5817aa29cc0572c27955d159a6d097e6ae80b429.nq.gz
    ├── 58cb87306293c40ad3f6f4082ec7beb74e3885d1.nq.gz
    ├── 5932589ffa4d7d36c2f360a294bce18034cf270e.nq.gz
    ├── 59f96af759045e90ec82c5139391216379792a33.nq.gz
    ├── 5b4f6e8066957823117c5b4d1946487a3bd4b1b2.nq.gz
    ├── 5c603cc22c086a9257ee1c91277c42413e6650c4.nq.gz
    ├── 5d412c90f2bde5ab32adcf6126908330bb2880d6.nq.gz
    ├── 5deaf1b84eedf509fc1c0d853357b605880c8dfe.nq.gz
    ├── 5e685c7eea85bfd8d113bf05f524bb817ac64d0d.nq.gz
    ├── 5ec5584d2459dbd92f1536cd6922e1a138769264.nq.gz
    ├── 5f7b1f1db013739d1b3b24f5014af62cf2bd21ba.nq.gz
    ├── 602b999dfd1db503d63c3c93994264616e85abc6.nq.gz
    ├── 613da37fd2ecc73b5156c75fc3d88bcf5b6cd2b7.nq.gz
    ├── 623ac1982366d862db0a9d950fa2f50dd334d32f.nq.gz
    ├── 624988e4232da0cff6d95040bbe73f968624e8cd.nq.gz
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
    ├── 6b70c409735e07f05b31352437d715aa042fc14f.nq.gz
    ├── 6bf62f0a8fcf6f922fe43bf58fb625b7352492f4.nq.gz
    ├── 6c38b66186e00c37e10583a32f8aff111215d667.nq.gz
    ├── 6cd6e3980fbf1b5b619d2e013723368d137fafdc.nq.gz
    ├── 6d5e07e27dbb39294575e21ccd51573e32cccbeb.nq.gz
    ├── 6f8e59f44dce31bf5cefa4a1dd69bbdf8ec98ac2.nq.gz
    ├── 7092dbc28fa5eb2ff9795f68fcd598d1ac6e552e.nq.gz
    ├── 709e1791efa695c09cc8e031f91cda1a2c17de33.nq.gz
    ├── 71a2f90cf459061d9c5acf82f022351b07f5a090.nq.gz
    ├── 739bb0b548da116f315b3832bb50c9e2d9a3b885.nq.gz
    ├── 76265a657289472a8c22ca851323f7a5e21af575.nq.gz
    ├── 76db62f79d66f92e45eb3dc85b61c7a3dbdbdb57.nq.gz
    ├── 790cc41e6fa101178b5ab2867005b2a3bffe9e2e.nq.gz
    ├── 7949cca46f248f9af1b4bab4d30335d19fd29930.nq.gz
    ├── 79c5a73c6ac2c5a341a52f10e4b5f7da85a1dfc8.nq.gz
    ├── 7ac6856eacdff91f846c01c1ad09cd42c9c40699.nq.gz
    ├── 7bdd695b1b44483a7940c2090446c4bccde29f15.nq.gz
    ├── 7cc5cd825203ddb664aed55f1a655bd02269ce0e.nq.gz
    ├── 7d4181f6a41dfe2ab698c18834c8d64f5ccb1a8f.nq.gz
    ├── 7e4108d068c446a2835ed1334dd008c09068449d.nq.gz
    ├── 7e42e28515e828f8daca8cbf466111ce61235d7f.nq.gz
    ├── 8330f6e0887bd39b841be2659f17ca5b1310a71b.nq.gz
    ├── 835a87844db28da08825b0f267656a85863f9e15.nq.gz
    ├── 8368f3a251c3311de57bd564b0245ac46e8b4537.nq.gz
    ├── 8441e5a64f3bdd680c9d67e8b44c9f176d2a351b.nq.gz
    ├── 856f5f77257240322cf6715e959d675420f196e7.nq.gz
    ├── 87741165cd619e4602bc6b48f39d0e35871ef024.nq.gz
    ├── 8810d21cd3f192374172b6a7bbd9430edf67ca22.nq.gz
    ├── 8a1a306d6e76126cd141e4e6eaebae922c5dacd6.nq.gz
    ├── 8ad125de8673e338ecbe8ce4b25dfdae6ea55bee.nq.gz
    ├── 8bc271b21d1dae932498c35978f2e8c650b8ecb8.nq.gz
    ├── 8c0748a286922dec907359b0f8d5010ecf20c3c9.nq.gz
    ├── 8dc3629bf9e5e4788e3ef69e528dfd72675cc0c6.nq.gz
    ├── 8e76c409b51014a30d1652e1369dd259d6e72be5.nq.gz
    ├── 8eb6b3aca2080a00dc85a874149e3cfb7329279d.nq.gz
    ├── 90fa8a8f494fb0708580105c606385af0806146a.nq.gz
    ├── 918a75b102b100e3ef208420b3ab98a6a3646514.nq.gz
    ├── 918ad804bd7fd7b3e3135d9b4094a95f19e1e514.nq.gz
    ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
    ├── 93abf93a1a6fd2ffc620d268c7c31d7f0c74da40.nq.gz
    ├── 955deaf27bc821a6367e818f36c016892fed3d33.nq.gz
    ├── 970cca77577147de6fa43c82757c06d4845d8876.nq.gz
    ├── 9842899a938adb7f63c6b141f1fb24d0d1cb11d6.nq.gz
    ├── 98e94a1d49e4157d10548871f521e3e103e98591.nq.gz
    ├── 99cf92dc20df69d3baad4f424c83433fe65eb107.nq.gz
    ├── 9ab2058997ef29489df726230cbd7cc5cc203ecc.nq.gz
    ├── 9b68006510ba310c37f43d7f9ecd5588d2707a7e.nq.gz
    ├── 9b7ca57fd4458184428a5bfef183ac113de60cb3.nq.gz
    ├── 9bf7b72a2ce272165763c9c40da5f6a7f855048f.nq.gz
    ├── 9d227a0cc43c3268d15722b763bd94ad298645a1.nq.gz
    ├── 9f0d26c5e17e875bd2917cfd84bb748d68103c72.nq.gz
    ├── a306afbc08add2208b56b29ace2701a2f91bbf77.nq.gz
    ├── a3217f6e7d0bc2ac7181cc2ee0e46f1b3bc67db1.nq.gz
    ├── a3cc4793a58d16768a2b5e561b95def3314a0da0.nq.gz
    ├── a428950fa30de3d74e768d1ec6602ee7aa1e5392.nq.gz
    ├── a59e4e9a6166d00afa77df1b80a542cfa48c10fd.nq.gz
    ├── a5f04636c57bc034b419719192815a2cf9e67473.nq.gz
    ├── a72e6d51cbcc3c1423018a6c219a6f1283fe68bc.nq.gz
    ├── a8f9f0b75accdf25bab7952c4a05a6a24740b792.nq.gz
    ├── aa2b50f552ee094df735372fcf534a5c14d0c325.nq.gz
    ├── aa80b6fb1ad5d0bc2bfc49c1afe6e9f39a757606.nq.gz
    ├── ab2d6e9fb838edcad850874a2cb25c36f76e745c.nq.gz
    ├── ab9462953066689a594e2b7b6dcbea1891bda6f8.nq.gz
    ├── ab96e719eefbcfd0348b24b7b58e1fb7d4417a56.nq.gz
    ├── acbd83f90b38e208b211fc7e62366556e9565dd8.nq.gz
    ├── ad025545a7ff00c6366a6146d808d875c5eb6a0a.nq.gz
    ├── ad357706ff59ae07ee2c8b2a850624a33e19e220.nq.gz
    ├── ad594cf1dab44241167a111090c8ea220edb76c7.nq.gz
    ├── af8adf0182d9ae693d0481d18e66df92d5ad33ee.nq.gz
    ├── b06329eaae8360ccc7a10105370361bb451c9008.nq.gz
    ├── b197fad0530fb42b25158cff1290b7aec34cc23b.nq.gz
    ├── b1c2a8761586581f23cbf34cecd4ef8413a55e0a.nq.gz
    ├── b1d52f9a0d8962bbc8fe4d832db91a2bc6974bfa.nq.gz
    ├── b1fe4cbfc4763de3f633805f7afabaab83317da3.nq.gz
    ├── b2a56cf5d2db736907a6610694ad9f7604612ec5.nq.gz
    └── b2d073d061322997abe6e60cf028dd657c9b190d.nq.gz

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
