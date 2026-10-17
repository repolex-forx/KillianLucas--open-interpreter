# Repolex Knowledge Graph of KillianLucas/open-interpreter

RDF knowledge graph data for [KillianLucas/open-interpreter](https://github.com/KillianLucas/open-interpreter), parsed by [repolex](https://repolex.ai).

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
rlex download KillianLucas/open-interpreter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ac1fcc8fe57aba51fcc3c79afd57a0883237fe87
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ac1fcc8fe57aba51fcc3c79afd57a0883237fe87
│           └── chunk-001.nq.gz
└── blob
    ├── 00e6d928ea530e8e3786b95ef15d54cd478ac27b.nq.gz
    ├── 0136fc14422a2c6155da92e92b714dc838f42238.nq.gz
    ├── 0208b8e73cacbb7dc994dcf950a8fcd9a23184e4.nq.gz
    ├── 03fef87ad4b4918d319b6cc67ae78bf072be86f3.nq.gz
    ├── 043c10b883bf23b9815832763ca11b96b5133d18.nq.gz
    ├── 043fc30435b37d6bad2e332ca158693f8c32326c.nq.gz
    ├── 04c0946750cef8bdd029f3cfe7a05408bbc34562.nq.gz
    ├── 04e05693d96b667c34d9e622edf58d9111df1a7b.nq.gz
    ├── 0501f1c782d6906656a81ee6be3047c7b5313347.nq.gz
    ├── 0527de0f905577decc7ab02ee4d483c2f93a7f00.nq.gz
    ├── 0544fd09c83b8ec08e70c1604e7fa8af48e159fc.nq.gz
    ├── 0615d9f33c6ee19ddeae4f56d7cc92e2749975c6.nq.gz
    ├── 06565c097b28d3bf2ad592943cc30c776b45e236.nq.gz
    ├── 068d363b7615de35d853f04e18049a5d8406802a.nq.gz
    ├── 076651d5227baa047d95a42e9e8795c65dc0bc52.nq.gz
    ├── 081fe4bd9cf7f9dfef8e4869875314a3fd9cf693.nq.gz
    ├── 086dd52a4858aa97f6409dd0c9d29e7ea9a1fc25.nq.gz
    ├── 0b5eeed1af04e532ca8e96ddcfb77f389990a1dc.nq.gz
    ├── 0c82049c285dc65eb88c02e0aae627c7dab468e7.nq.gz
    ├── 0e53a71957c78a99e6dd2607c4bcd332da353e2e.nq.gz
    ├── 0e5ecdf78de0d777f16e02708dfe23844c107cdc.nq.gz
    ├── 0eebd85565a0154bcd2f5c4c0a5cc4450145a31c.nq.gz
    ├── 0f2be753aa65f18cec7d6a4fabeec8a0fa6d253c.nq.gz
    ├── 0f37d454b8c3015f06dc6ed3df3b93fd6ab9fed7.nq.gz
    ├── 1351377e5d7777f54a6bc20a9515492aff9c854c.nq.gz
    ├── 13557c6377650d0ea074168d3d068ed2dc4398e5.nq.gz
    ├── 15921aced426d692553d6e4d942ae1489daa0cc0.nq.gz
    ├── 15c50c51e472f1fb21f6590b5eabfd276bc005f2.nq.gz
    ├── 16353fd7169a665ef015a3f8ea1636bf05ca459c.nq.gz
    ├── 16511aee2c80b8c042d4afc9989bfafbdc2d6f4a.nq.gz
    ├── 17b92359ccb3d4515a29196554e60888816b062f.nq.gz
    ├── 1840f23fae6abae549a8dd06de1a9b66903a7fce.nq.gz
    ├── 186cafefc0c6175bb74769550fdcb2052ed63b64.nq.gz
    ├── 18722e278f7c574a89115e70cbade1e63844b1aa.nq.gz
    ├── 19a9a6fc5b08354fad82817971937bb1ee06dbdf.nq.gz
    ├── 19ef149e4278bd182f0c9e2528aa12e6a0a1e675.nq.gz
    ├── 1a7a719d50d149b2ada5a351dde7c533a9b5eef8.nq.gz
    ├── 1aba4f274c41d198facb3e2e54dd6720be77253b.nq.gz
    ├── 1aead727731475bc9590ac90efb37c2ae7adef64.nq.gz
    ├── 1b20f8462d2864f946fe156068259137e13079bd.nq.gz
    ├── 1bb4970bb41e5278eefb1347f757d83cc7a3b130.nq.gz
    ├── 1be43deac2c0edff12f17b01e1d487113dbae50d.nq.gz
    ├── 1cb11fba7b49db0d4b3df0152822c8d07ebfb29a.nq.gz
    ├── 1d03fd89cf56655111df8c6e76feb2921aa434cb.nq.gz
    ├── 1d11e11dec21b6e6cf0047632e20448daca08a1f.nq.gz
    ├── 1d219422daa90071c321476b328b3b5cb739ecef.nq.gz
    ├── 1dcd5586ef5f73c28a6d028a59172b8c7b003d47.nq.gz
    ├── 1dd51e001030cb6b260114da3461cbe9d77ba944.nq.gz
    ├── 1e0d5d83e8e0e1f64bf1fcf31b9439a3458ed1e0.nq.gz
    ├── 1e33c0809f5fafc1ae9c5cb7c4d054ebb3a04f19.nq.gz
    ├── 1e48f22769f5c6c0ba40373f2b68782e9ae27e01.nq.gz
    ├── 1e73a237ebc17f689cbfb2d22e96fc4b0c77fe80.nq.gz
    ├── 1f6bf6b92d682e9fe3ff6d3b1be1bc560f0a121c.nq.gz
    ├── 20706d1bfe5d315f05b7173512ef6c4f9a0a00de.nq.gz
    ├── 212b63d34635401775963ceb80e25bb3c541c6bc.nq.gz
    ├── 21793fc95778e085127231f5bdb945cf61fb46d5.nq.gz
    ├── 219fd3b3159b029374af834b969bfeb8e282688e.nq.gz
    ├── 225867d8c72283b57540a38c97d6c44106eef33e.nq.gz
    ├── 2266b3d0c6b06648f8db157e1f5d169487dd9c3d.nq.gz
    ├── 227042c5961c7839142d618920dd5b85e95a0ba1.nq.gz
    ├── 2296c73621cebf44fd41ab1def26dbaa11177208.nq.gz
    ├── 23ed93a5eced7aed00b705109cf4b409ccf70be7.nq.gz
    ├── 24582c9507adc780459df92ca0c6d7e250f81236.nq.gz
    ├── 245bdb0d54fb8c8d8bd32c97429c232e8ea4ac1c.nq.gz
    ├── 264c76833ae5393674519cf3b6f587d8db002da1.nq.gz
    ├── 26b12f28868c0dca58d8163ebd3112bcd081616b.nq.gz
    ├── 271fae177685fa2439a68b1801870317556d276d.nq.gz
    ├── 2738c8a8afea0466ece3c14d0d53ec0d9f80e84f.nq.gz
    ├── 27622583be3a22911f21ed34a9e51286094e87cd.nq.gz
    ├── 2904ff2986e4e26604b667246e4bc800f6b404c8.nq.gz
    ├── 2908a504fdd6e534ed7891626a10a7afe64cbb28.nq.gz
    ├── 2957f3e2b1df4936523202281f4c63892054c570.nq.gz
    ├── 29a1ceea148f5a5d12d5a5c436c767443b585d80.nq.gz
    ├── 2ab952c240600522d7202cb9f4bff3cf65806a57.nq.gz
    ├── 2c00fc166c2d1fe562c54325fd4ea606d614344c.nq.gz
    ├── 2c17b1fd2ad989bda8a38e80dee1c5380f887c03.nq.gz
    ├── 2c6a1bce212567c6f1c05e73989118a31ea7807d.nq.gz
    ├── 2ca9e12a8a9e8e2dc2904177c742a536aadb53eb.nq.gz
    ├── 2cb25a6b17dd23e845768ad44a1f3ba22034e9dd.nq.gz
    ├── 2da49eeb64095a2ebd7b77fa993e32702152f375.nq.gz
    ├── 2dbd73c38036718d101064e41d7290754acddd0f.nq.gz
    ├── 2ddc146aec081652200c7a03aa0244c0766d09c9.nq.gz
    ├── 2ec986ec52f13a7e9719d454859d505e7b9398e9.nq.gz
    ├── 2fce42cc26b726d04286e3bf34ced8b916decc0b.nq.gz
    ├── 304349b8a17c3709673fa15143cebd4c3a011669.nq.gz
    ├── 3091a0b52c59fa770a63103da33ae7af1eaefa54.nq.gz
    ├── 30e6cda1734e3c7c991b3b6b7990d0c42e8b6b85.nq.gz
    ├── 31e70b773b203421c784d5f2d629bdae98e3bcf5.nq.gz
    ├── 32256d3a88b9d77d8c8cb02c2e7f46f222c188bf.nq.gz
    ├── 3268643cd663d455e0a65fce736fa9bf9a664120.nq.gz
    ├── 334ef4563160e96e55e61e50879cdb5793a68422.nq.gz
    ├── 33585b561b704cb28fe47765583d3d2a260c88a3.nq.gz
    ├── 33bd720c94fe0bfa62226ca2e14fb11945034abd.nq.gz
    ├── 33e6edf55e2b32228b0ee3f2fde6257b99e29880.nq.gz
    ├── 3410f6e176b1d5315a7bfda64a885e31cbd9be7a.nq.gz
    ├── 3549cb228c7db842c84ade6fe3fe5320951ea646.nq.gz
    ├── 355352c9cc10325c69cb3035ed671ac615790007.nq.gz
    ├── 35d6fb98bf26a6fb18938b5a322a1d54023857c6.nq.gz
    ├── 366d7486b6d66f723989263520a6445f79e57d32.nq.gz
    ├── 36c40c2c594598ef339ea508bb4cd492cb73e98d.nq.gz
    ├── 370a4ed8c566e15560b9c1983690d640bdea0d28.nq.gz
    ├── 3883de031e5e4ef4d14161ea08456fb39ce248c6.nq.gz
    ├── 39ebdfddd64d2695065ccd945974bee440a4f66a.nq.gz
    ├── 3ae7b9d624443dc37b03de8963919e9006aeaa73.nq.gz
    ├── 3afc65beead99ede0cb731c2349e193815e6f70d.nq.gz
    ├── 3b7ab6db21c8c6386d9f8bcf3fc7407ddbab82f0.nq.gz
    ├── 3c406946cf01ecf0212746c2c37626b54e4401fd.nq.gz
    ├── 3c5d97f2d1bd600bf3117ec189d1a3b211ed4ba2.nq.gz
    ├── 3c91ff76758ecd6053ae1961d41104a30d8a7f67.nq.gz
    ├── 3dc5ceca8f255db93fe4a2e5b87278ba7c8a6f24.nq.gz
    ├── 3e250ca77fe6ede7252713a25957966a6df90fec.nq.gz
    ├── 3e61f3a2eae8c7434124b9659c59c216a9b8bf29.nq.gz
    ├── 3e6665f4733f1a53ca0b6347af513b4586032faa.nq.gz
    ├── 3e6f0556a12f470d354871d75f523afc73003893.nq.gz
    ├── 3e757656cf36eca53338e520d134963a44f793f8.nq.gz
    ├── 3ea3a5f8180c877ca37ee7dc9943e62f55fab588.nq.gz
    ├── 3f6c958ec0db06ce12afa1a1c6ba836be4562279.nq.gz
    ├── 3fe3d7575ea3743934a005a3710fc637babf59c7.nq.gz
    ├── 4109b8965eb233b25f08ecb19c1299c679bfaaa7.nq.gz
    ├── 4156fcfc39c90b37423f6fbf836da8df34ae8bba.nq.gz
    ├── 4176a55996f01d2383a89803d54198beb7490d33.nq.gz
    ├── 418edb74a82a4b3157e1d44dc266afe2052b7ceb.nq.gz
    ├── 420eeee0c5f20663d0d877d0edbbee2e43135198.nq.gz
    ├── 42ca76a2ed029bf0c71eba93e74a562da1c457f6.nq.gz
    ├── 4342f1b45bc132e1da11ba38c6f54a9414451091.nq.gz
    ├── 43ace4f7a78ecab1153e548a1205b77b93d60349.nq.gz
    ├── 43dc3ccc5923224ca93472d19b8f4111992793c6.nq.gz
    ├── 448b0338a44d6ba62381d62977195b040b479fe9.nq.gz
    ├── 452834c96b733d980910288e7612eb92f16b1c72.nq.gz
    ├── 454418ad882114c4dd98cc52b804d75d3524c7f9.nq.gz
    ├── 45afa12172c031833dfe28969d87c459e2cf1405.nq.gz
    ├── 4638d46b8c0dde7e252cd947f8727ca00cf28de1.nq.gz
    ├── 46f9710b4c58f63e6acba1d96049eb1cab818d5a.nq.gz
    ├── 473e50cf4e21c176db53a6b9e096c2cb7a1cc512.nq.gz
    ├── 47504740bb32684606d1f7d63b9f72dab7645812.nq.gz
    ├── 478f044f1e81f74e2e38dc06dd0daa15ff1ece23.nq.gz
    ├── 47b28c8c25351d2582f9bffe4594e7b4126460b0.nq.gz
    ├── 480853d92fc94b6c9c70a93cc8ce1bb1fc6b4ba7.nq.gz
    ├── 48245c47162a85f07ccf7ee039d9d37f4f1f1737.nq.gz
    ├── 486b7a9480be6d76057298957c27affbfff3678c.nq.gz
    ├── 48cfbe1d1421b540b3097c214375063caacfa35f.nq.gz
    ├── 490ccc6c3e0015eb982bb5c108c2df083be2c6c2.nq.gz
    ├── 49e4551bb5b9ab12ba3954811f7097606db9aba0.nq.gz
    ├── 4a3d76e0acd514e1a7f7db22311025a6bc41e5d7.nq.gz
    ├── 4abe2d17c200967d40d9bdbb9eb129f320ca4625.nq.gz
    ├── 4b41740f893b168c3ec421fe11ee762d0cd0500e.nq.gz
    ├── 4b6474c9c2e78cf13c75ab63325efdeb2d437950.nq.gz
    ├── 4bdd425236c9f107cc7f092b2ebe5e94e626564e.nq.gz
    ├── 4beebb0d3f2d1b5cdc60cf013c65b0930f9df6f4.nq.gz
    ├── 4c300e0bccee542e5e5e4f32772efa8aab2801c5.nq.gz
    ├── 4cf1871af66ff5d9503caeb2a5ea4a183f85569b.nq.gz
    ├── 4d039577456e36d226675a58e1f4ac2182b7ced0.nq.gz
    ├── 4d0e252494307d5bf2fa467abf56a33306a3ddcd.nq.gz
    ├── 4d649b0f5bfb32f77939e20c24ec70517356108f.nq.gz
    ├── 4e131c62b6634aac2cf4034be547b163b21289a9.nq.gz
    ├── 4e5092e4d0ca72345d785aab8b30e4a482800c4e.nq.gz
    ├── 4e5b3a1e9fd55d8682047afd0a3325536be9f39f.nq.gz
    ├── 4f3d6d82fa78fbdce97af3c17f6a25c683aa3290.nq.gz
    ├── 4f8f9072d0a0744d1fef23847400ec52c79efa78.nq.gz
    ├── 5280d7a013670807a0c6dec2f8531f8a59aa3809.nq.gz
    ├── 52ad1e4271159903bab42efe75904e5cb7c48dad.nq.gz
    ├── 53d4630412e7f4e766f4b23de23a7ba84d70c045.nq.gz
    ├── 5425272c30ec0d75a6a211476957745aea2af1e2.nq.gz
    ├── 55035cbbc28b9c6743d4ba0bd029b998293ed26a.nq.gz
    ├── 5575701ff2d7924e431df7b86d57947d650f2989.nq.gz
    ├── 55ca34c3905a91c448b2233cd964f13a35ff7ff4.nq.gz
    ├── 561176b3edb4a8daaee2fc9c887faefd3de85886.nq.gz
    ├── 562a66a08f37ea715832fa1c915c6b9e51252a46.nq.gz
    ├── 56442718de8e6264d60561993c110c755aafe3c3.nq.gz
    ├── 566fa227807bbf158f396540598d360b9fb7614b.nq.gz
    ├── 567bed646144749944388401af1420da464d46d0.nq.gz
    ├── 569b1d2c126f83848e89482d18cf1d4f336da11b.nq.gz
    ├── 57a28696c8fc2148525480511551b256b35d8b02.nq.gz
    ├── 583698ff670ac3e3b488b7f46d180069f4612faa.nq.gz
    ├── 591dd279f47c3a94a6c4d7812980083c3c9f6d6c.nq.gz
    ├── 597a75e9ec067c93b2769fec05ca6bafe09959cd.nq.gz
    ├── 5a21d75d90bcb9ea362e9f6ed2d58330a437603f.nq.gz
    ├── 5a4ef82f0a45bacb35669b22f44246dfc96c8d36.nq.gz
    ├── 5a60a34b8e5d435daba06b0a089523f3226b441c.nq.gz
    ├── 5a9f34ead3c1b6f4d25964c9c3e5a232718e193d.nq.gz
    ├── 5b98f9bbc888748b8f95a9b44c49c32f9591f8cf.nq.gz
    ├── 5c841f56a9d2f04ca8fc8ae2f23ef506bd1297d2.nq.gz
    ├── 5cea3967e7b2f989e421178a511663acaf7baae0.nq.gz
    ├── 5e0e9182621df1fe6d1ae98a138f1688b878c8a0.nq.gz
    ├── 5e9a7649bb7743f85645b08d9878569292e4acb7.nq.gz
    ├── 5fa494c76a7bf6fe8e14923954423e3f283ff9a1.nq.gz
    ├── 5fad1f50fa580d7df58ec673caa9e9ee7b374a26.nq.gz
    ├── 60063c10fa3db85dd609b3715ec22d44324f16ac.nq.gz
    ├── 6107caf8f167d1df58b54d26e4865b5a869304ca.nq.gz
    ├── 620c31b36eabcb23f342966cb6de1564987ab378.nq.gz
    ├── 628dbfc5a58a2f8936ddae9b05e9c4978085064c.nq.gz
    ├── 631e06a99060adcaf48b36da45c76392c70e8fa1.nq.gz
    ├── 6329e4342224620dfa22dd5d466e162ffa63093c.nq.gz
    ├── 63a6ebcadc9be99acffee301772b5cb60488fb31.nq.gz
    ├── 63bc1d9d4a6b4b5bf74718b8395a8d2a0e041d2b.nq.gz
    ├── 64eff30ee6ab19671ff31b83c992ac19e9829430.nq.gz
    ├── 655c89fe204a6045ac36a6ddc64af1604e51d822.nq.gz
    └── 65871028260351989130b3c95cba47bf1f9c606e.nq.gz

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

[KillianLucas/open-interpreter](https://github.com/KillianLucas/open-interpreter)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
