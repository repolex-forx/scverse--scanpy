# Repolex Knowledge Graph of scverse/scanpy

RDF knowledge graph data for [scverse/scanpy](https://github.com/scverse/scanpy), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/scanpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ed52d9dad906c260e52405380ed4ed1e353d4e7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ed52d9dad906c260e52405380ed4ed1e353d4e7
│           └── chunk-001.nq.gz
└── blob
    ├── 021af0a0cb16a099a49bc6752ea1ae9880614601.nq.gz
    ├── 029327f6bd179f8aeeba6bc77fa9def69f9a0bb9.nq.gz
    ├── 03312b214e91050da3cf147dc52c6edd2b9b8217.nq.gz
    ├── 03de5baf440132a29dad37d230f9770ff317a8fd.nq.gz
    ├── 052c608840502bc1130b2b0d6231630aa3652889.nq.gz
    ├── 0585e09d490234dd6b856fff35bf61dcac70697f.nq.gz
    ├── 05fe80da7daadf6a428588a38e2c2871a4d9ac4e.nq.gz
    ├── 06154ebe030e66f1ccce1f3ca2f721432c9b027e.nq.gz
    ├── 066fba45a02a74994ce0f87d44b8152f268abb87.nq.gz
    ├── 0722d80c6fe03935e8686458fbfc4a471882fa20.nq.gz
    ├── 075adcae7ec222e908d9bf6d398139c042ebcbd6.nq.gz
    ├── 0760ded9137aa797adc83a6ae5038fb3916e4283.nq.gz
    ├── 07b58089b4352d18ef11181cb26bdf10dbc429ba.nq.gz
    ├── 0846d8e0d73ea29e687d52fbd1a648ed6cb0dd09.nq.gz
    ├── 084c9fff27aa116c76b1817d5eae6d57d57d1371.nq.gz
    ├── 08571d88a90ef95ba44068759f2cf74c89c0e4eb.nq.gz
    ├── 08e7e3cd4a60db76eafdd100494ae3ef37e1dec3.nq.gz
    ├── 09347158551c96844b015e5cac83bca6099cdc90.nq.gz
    ├── 093acaa44926e37e55a3502cfbd8638769c3f67c.nq.gz
    ├── 0a1329e4791d8a2d42b799c42e79357bf2caf33a.nq.gz
    ├── 0aaba0fbd063df43726b2bfecbf8b1d720982315.nq.gz
    ├── 0b76a01105ec57b7e7a25d540ed4b5b850fcea1f.nq.gz
    ├── 0bbda8ca491a2ec7948f5657633301a467068a7d.nq.gz
    ├── 0c4eb0761f85691d3fc705c8a8ab07f60c8d24e3.nq.gz
    ├── 0cb544a743c095990db447c3721c99694701fd42.nq.gz
    ├── 0ddd02eb907362ca6d4b20a92992491908e7b38a.nq.gz
    ├── 0df3d2e51d61551aa6afa7a37f9ca92a47335a88.nq.gz
    ├── 0e50a331814e2b0ce3ccdf330ddbcec5f7488260.nq.gz
    ├── 10294d98c849ac9f0fa2ea4442843faf61d43add.nq.gz
    ├── 10641e730d268f6d231969bdd5ae49132d19f75c.nq.gz
    ├── 10e6b7fe8013c04c6f8a63ec6c6f22d2e8bd38dd.nq.gz
    ├── 118a971e2d0e58ab935b7786d99491c6e6f1d0ce.nq.gz
    ├── 133a5d5f896885b182a033d1822a8aed772478c7.nq.gz
    ├── 148e38603c2d1cec1886e2aea0e84f600b5015fb.nq.gz
    ├── 1511a39598fa45fc29f7006f6438439bf37df5f3.nq.gz
    ├── 1522f168b52d313c0635e6262e38b8725d4091ea.nq.gz
    ├── 153acf1e8a78560f0b2199154e54bb31b6b52c79.nq.gz
    ├── 15de9b1eb5d69255d93fdd4c22aa1d8c6475eb93.nq.gz
    ├── 16b76341e07af36ce53a1a4b32a5f8417c463ddf.nq.gz
    ├── 16c13c2743b9b3606068c6aff7b2e26c33c13a2f.nq.gz
    ├── 17670d47a8285def854aaa081486ef1a54966c7c.nq.gz
    ├── 183244e66fba188b318d9c6890a094f9af220f84.nq.gz
    ├── 18ecd20ca492e7e344c3deb58b9461cc3ce0e891.nq.gz
    ├── 18fa22a4ca0920ec5adf3a18267d8aabb10cae13.nq.gz
    ├── 19675fe0e3e8d3c5c83355094e058ff5f094e476.nq.gz
    ├── 1980275a1c5c5a09b905cc82ea385ba3d1b883f6.nq.gz
    ├── 1a146a7208dba5b4b2d2f336e5f1794f5a3af1b6.nq.gz
    ├── 1a26215470f91aad21a7bfa936c3743b52123d3b.nq.gz
    ├── 1a816238e8b77c820bfff180c3c0ec3f117bd94a.nq.gz
    ├── 1cadbe8ad7a22ec5155661c09406433f1dd29358.nq.gz
    ├── 1d2657a56b260670fa8c606fa9dca18338d88250.nq.gz
    ├── 1df4b95ff29b5ec5ee094de121b2b19493af1041.nq.gz
    ├── 1e6779c62265cfb7e2145fa6434998d7142a20b8.nq.gz
    ├── 1ea897a13ae8bfac6bc3b792cba2444aee1d3427.nq.gz
    ├── 1fe0f8d85b111eff190c0f0b1447997c92852b09.nq.gz
    ├── 2019bcbbbb85bdac23adb0a84bb8d25a800b4b98.nq.gz
    ├── 20b8f9708739dbe9d30d2a498f8f4b9f6f5df743.nq.gz
    ├── 20f69b33578933b7394edd1dad4664df2ef14a10.nq.gz
    ├── 21687d35280ff416bd29aa1c0d0f40b7ad7bf144.nq.gz
    ├── 22fcc1429621db4d1f2f6e5da0e0170623e32ffe.nq.gz
    ├── 23f398a2e0322c168d074f22ef7a22996c44fd90.nq.gz
    ├── 2404e0d695111840efc1d2bd9b48ebc22bc4de9e.nq.gz
    ├── 242bce6be9b2c9b64ba16475f68638c91aad0568.nq.gz
    ├── 248aab23bf8a8674d8655f5ce34e76762e910cd4.nq.gz
    ├── 24c66502bda54dc4ae517fb3404f6f7402f423e0.nq.gz
    ├── 24d399c1d577a352586fee2a2f5d43d2d339092b.nq.gz
    ├── 25003fc60b73a3fb402b290ad6665d0cc651f079.nq.gz
    ├── 2562cd58f1632d292c2bb1a17fcc0323e3c71d0e.nq.gz
    ├── 2609a53567e96d603c53f09bde0b205ccbfb8633.nq.gz
    ├── 26af76bb5a7699a4801d7940e9a560408874f3c1.nq.gz
    ├── 26bdaf51eb93dc40fcf9acb179e9090e45840adb.nq.gz
    ├── 273b3521bc70baeed4c8aba8cb32c7e7cb14b09c.nq.gz
    ├── 285e6248d1d40cefb87225d76a31c1cd5f73b39b.nq.gz
    ├── 286f332dc90921b857cfaa474c0eef11453c0383.nq.gz
    ├── 29324b98b7528ad338388a2bb7a7bf37f48c75e6.nq.gz
    ├── 2b676b13d6a76868b1337ee071e5ad115063f26f.nq.gz
    ├── 2be9e84fd1f8ba5dfb1d22271b55c635b548c4d2.nq.gz
    ├── 2c25ba8bc88b5bfe0e13f43b2fbc6e5d585ecaa2.nq.gz
    ├── 2c4cd0b1751f5da5679ca4fc16bc3cf1a3a5b62c.nq.gz
    ├── 2d0e33192caa9c1b1ea7ac002ca61d6732cb49e7.nq.gz
    ├── 2d80e596264c7f75c740732b10ccb941dcbd8dd4.nq.gz
    ├── 2de9da3f41e4ef456f9526a7a67df4c7a4ea26e3.nq.gz
    ├── 2e81f228fd4a9407cdbb30794c0391120f807578.nq.gz
    ├── 2e9fde87aa26ca8de738edbbdfb609ccc7014df3.nq.gz
    ├── 2ea16c184c016df0a44514bd0581a9f6c6e7642a.nq.gz
    ├── 2f48520d2352a5990ac5599245ba89c11e3a369c.nq.gz
    ├── 3027a811074ebd673e3dd3cb125820dacd766651.nq.gz
    ├── 3073ea26c49c2fcc6179490183690c8b8e6f41d7.nq.gz
    ├── 30c96fde2511571b05c165095029d0fe2e35d372.nq.gz
    ├── 327153089ff64258b70ccad09c10392c37c53e48.nq.gz
    ├── 32a468be3a5c14c14615b59fae1dd827ee7edb39.nq.gz
    ├── 3300fa26bb670500c40d59bb1dbee8baf7b191be.nq.gz
    ├── 331108d690672f8bff6c14be981592f3017914d8.nq.gz
    ├── 3319e3928ca3f020d5cbd2eb954269b7f13b7e3b.nq.gz
    ├── 336903ba77382709f89a5b2ab5a50f3a99ec8e11.nq.gz
    ├── 336f438f518abb304b786246a3b2c29aea717e32.nq.gz
    ├── 3382528c680f7f44a0d0ae97d4c077781ca26ed0.nq.gz
    ├── 345637d79c4afd1e535087c9170b195f963b2df4.nq.gz
    ├── 34d3fa794a116dda14e3bd8f4475a963db32fa33.nq.gz
    ├── 34d79529b1fd4d4b7417348b3f02e01dd19d4745.nq.gz
    ├── 34d7fdd638672c1f40e34ce1fcdd0347dbd85d70.nq.gz
    ├── 35978dae8cde46b627d319cb2c184bb5c9959854.nq.gz
    ├── 361aa44060fcf87cf10d50993527c9b47b712422.nq.gz
    ├── 368f43ecc5acd366ae735857cddc4663ffb0d707.nq.gz
    ├── 3696ba3d28c8381876a1181a12fd6d8502194a7b.nq.gz
    ├── 3725521ca8a19b3f631fbcf4a793348f9af213ab.nq.gz
    ├── 385480e6c00e29927a4ba22df93205e8da4700fb.nq.gz
    ├── 399a766412e7972fdae44a5bb0ffce848ff8da8a.nq.gz
    ├── 3aa23a2d8560f6f8df24779d24a5c6147918e010.nq.gz
    ├── 3ac14e950683d7b269a5809e16933cc4e380b79b.nq.gz
    ├── 3aeb2fcb863ee7cfc212c50ad7ee01f8d8969cca.nq.gz
    ├── 3b7daf227c1687f28bc23b69f183e27ce9a475c1.nq.gz
    ├── 3b95c6d906ef1238f9830ed28c6b88b488e5cab5.nq.gz
    ├── 3c51b7fcee9c729ac4b8797ad39b6a3c57007337.nq.gz
    ├── 3c7df19874e9448b80784ed5e3d2b042218a350c.nq.gz
    ├── 3deca7a364f8e54c9cd505f462a7d523b0d28fc6.nq.gz
    ├── 3e0cf8c43f43113164b0565bfeb5050ff80b6da3.nq.gz
    ├── 3e27cd6a2565b062e1576a69f2509e47beb02e23.nq.gz
    ├── 3e6cc18b018c135539517c6de2cc9cf7460be5ec.nq.gz
    ├── 3ee7e452f290edfeb448c4f7922674a65be968d6.nq.gz
    ├── 3f320b6d33d9205bf7a3a213117ab7f2cb2d820e.nq.gz
    ├── 3f7ab6acdf324bc1445dd0e32f92607f3df256cd.nq.gz
    ├── 3ff620ee3b7f40e083bd32e7f2f24be009d0e0df.nq.gz
    ├── 4056e71f57970b471113dc44c3b7c6fcf666fffe.nq.gz
    ├── 40913f2c35a57bbbb3768cc83b6bbc77b2061c07.nq.gz
    ├── 40ee716504c882e543fc7e2d6f2412d441639a0a.nq.gz
    ├── 419d60b395c902e86b3f7f6760e386381d08f5b8.nq.gz
    ├── 41a6cdc5cc6c88d1cea01977736ed6a792ac80b2.nq.gz
    ├── 441c385bc8509f015e49a4482cfe369dd8c9f278.nq.gz
    ├── 44799b57abf9688caac008a21978318984726a22.nq.gz
    ├── 448ce0c95a1eddf711431e89d391bf43454c2e35.nq.gz
    ├── 44a475ad5dae8fdeef40925e17e71e748a6b481b.nq.gz
    ├── 451b0f092effa5ea77ac3e7838a18e25210267f8.nq.gz
    ├── 457824dc8a1a8b95ca2e496c6fe0901d7f128c0c.nq.gz
    ├── 45d0f603d9098cb107c4f87f00f7a18dd3e4fe0b.nq.gz
    ├── 45f2f5d867d0741b9aaf7bbf468f07c541357157.nq.gz
    ├── 45fe31af5cc571f409647adee155a6126ebfda34.nq.gz
    ├── 46c03a1f72f70ab53ed9d88adcd89f5b5d4aabf9.nq.gz
    ├── 487d9adbde4b6db543c161630d311cf312be91a9.nq.gz
    ├── 48f8b3454949dee60e97e221677ba227133be5be.nq.gz
    ├── 499960f52378f51ad6dede22cfd66d93f998918d.nq.gz
    ├── 4a15aff0879620139638441bae4fc086107e9d02.nq.gz
    ├── 4b943bcd27462b662fc7b8b69ccaf27a07a74392.nq.gz
    ├── 4bbef044d3ed67b34e568f1831a5c31df44ea440.nq.gz
    ├── 4d4153c6f0c0800dfec779da81bf550c573f8089.nq.gz
    ├── 4dbc9a0b867ea458533765f182f7a12fb3546c72.nq.gz
    ├── 4e0f083a17ad5036845ac2b113a16a3501e6a195.nq.gz
    ├── 4e7b8ba88d92973a50cfc9147a36b9633176a350.nq.gz
    ├── 4ea646b75cd22c7de477882683dd6fb75c976e03.nq.gz
    ├── 4ebe8392f6d87b805fbab7ed0016cb10df7cc6fe.nq.gz
    ├── 50861e1cef5ffbcf0700fb52d88c8bc538655422.nq.gz
    ├── 511f238ec874609f7e481102f43526a471fde7c5.nq.gz
    ├── 51dd07a1756f742b7065833192650831bc6128d2.nq.gz
    ├── 51f957a97f95cdf9fe9611180d51edcef24181ff.nq.gz
    ├── 51fa863d9ef6e619923759a12b8b3190244fa178.nq.gz
    ├── 52022e7a570739843a21d0d9aa12486bfedcdc70.nq.gz
    ├── 522f894c85267262883a349a77073076cb912f85.nq.gz
    ├── 523c5493e6f871b73debe46c4bcab2286829f240.nq.gz
    ├── 542ecd8fa64fc5f1ad6b0914bf3bac19e71fa2b7.nq.gz
    ├── 5479b589c0669667e3ddab4fea9d94b715c4061c.nq.gz
    ├── 5674762ffaf69301cfe9f466496cc377684dce2b.nq.gz
    ├── 567864d7916cb6a8b921d49c129db6d1d854e6ce.nq.gz
    ├── 5686942fe411165b07094fe1667b5815fbdba66d.nq.gz
    ├── 56f72ef0cb2570a3bc1770a800f88ae10670b805.nq.gz
    ├── 577e6e2b88946ebcbbf4fedd3b021835ab1105f4.nq.gz
    ├── 57d110d3cb1ca0d986a31fafe371ab7072393561.nq.gz
    ├── 587c3ea8395ca799a3e971c2076ae32b4128c369.nq.gz
    ├── 58990e2526363224f2691b3eeb3279cd2db50422.nq.gz
    ├── 58e09f3939bfab4ebc6afaf172f4f61bbebd1672.nq.gz
    ├── 59a3fc0fd3979b38d992db0684e343a07f807d83.nq.gz
    ├── 5a1a6754b9ea56c460fa09c55457b09bb3a8b1f7.nq.gz
    ├── 5a590fb35f33916c28e2122cfd1a6f11a4854e28.nq.gz
    ├── 5aa77008f195689ea058666d067fc3d1d03f59d9.nq.gz
    ├── 5ab37496ea1bfdb31c151349de44a2d2f83c7f67.nq.gz
    ├── 5ab7f0984202fbcdf7cb69d6092d20180c94f278.nq.gz
    ├── 5d849dd860d63e65ead32fcbee57b71adbe0e710.nq.gz
    ├── 5faa53961da7b64ef36ef616f7bf26fca8cfeca4.nq.gz
    ├── 5fde09be3b477b21dc0c5a4cacf4617a94f730e3.nq.gz
    ├── 6151987f32e0f8689d59c9fa75ba252442a453c9.nq.gz
    ├── 6164715609eeaeabbdcbe137d80288c45ebea4ef.nq.gz
    ├── 6168a9518a4c272b5de71792a7ffad993948b19e.nq.gz
    ├── 61b80cb2881a35b4743a86312b396fe36d44a777.nq.gz
    ├── 61c9eaa266282c9dd80b367ebcb1067b7e684736.nq.gz
    ├── 622a88dc2408aa47ead1c0a5ad4a0348e9c694c7.nq.gz
    ├── 624f5a1235d8ac0b96882abd487424dd738b4ae7.nq.gz
    ├── 62dde6990d33f8cd4f191c21a91310f474d6fc39.nq.gz
    ├── 6325c1298fa6a7e6b7102ee43ca99ab28ab6c5f9.nq.gz
    ├── 636b77dad7e58d5f5fbbd313335d01295fa5e834.nq.gz
    ├── 6381481c950f774ed69ee10a5505ad0ecf93780d.nq.gz
    ├── 638d109bd43b7132e9e1c00427908919aa47e7ea.nq.gz
    ├── 64bd1669f722224eeb0fd5b306782286c0a0c1c2.nq.gz
    ├── 64c068a06eeb8ea4aff55ffbcdb4363ccd3f049f.nq.gz
    ├── 64d80850ec9e30d325c995db069dc42aec34e30f.nq.gz
    ├── 64fc799702cda4d119e2987f803db7b8fee39831.nq.gz
    ├── 652b2da94672d3d1e9a25fd9ed6961f4e0c7b03f.nq.gz
    ├── 67a95bbfd01f567ca68511bf627a627dc56d7843.nq.gz
    ├── 687f83796732230e97221f5d3760fa3bcd81cd04.nq.gz
    └── 6897effa018b95e9d32bbdf3a2e7be31c61b1a4c.nq.gz

7 directories, 200 files
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

[scverse/scanpy](https://github.com/scverse/scanpy)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
