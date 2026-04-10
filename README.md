# Repolex Knowledge Graph of TypeStrong/ts-node

RDF knowledge graph data for [TypeStrong/ts-node](https://github.com/TypeStrong/ts-node), parsed by [repolex](https://repolex.ai).

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
lexq download TypeStrong/ts-node
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 057ac1beb118f9c42d21e876a17320ad73ea6be2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 057ac1beb118f9c42d21e876a17320ad73ea6be2.nq.gz
│   └── repolex
│       └── 057ac1beb118f9c42d21e876a17320ad73ea6be2
│           └── chunk-001.nq.gz
└── blob
    ├── 00872cb2b8f845cba3eec395edb2c730e02472e6.nq.gz
    ├── 00dbc5efd74c0bd972e8f97026bf3b152dbea207.nq.gz
    ├── 0313bb4d095f1a67911995d2b1d5d2fe4e385daf.nq.gz
    ├── 03e0c3c5d785f3fbd533283ecfbde2dd2d8ab127.nq.gz
    ├── 04e93e5c79815356ec773f01190628b99422441b.nq.gz
    ├── 0550170bf715fd5baff2d424c5f3698d4c64bc32.nq.gz
    ├── 0744dc4d37614472462bd2775942e0201ec37ae5.nq.gz
    ├── 0843cf3491f6aa0a13cca47cc8476e2e8366d884.nq.gz
    ├── 084c8b3966afcf4c5767c274e668cab0f93924b5.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 098594e5f5c24a845f5a852ebcfc48fde7a26b7d.nq.gz
    ├── 0b1738d5ef9b5fad6e4271b7231713631c996dfa.nq.gz
    ├── 0b879a9423eff01de3dce5e2595b49c6b73c7dda.nq.gz
    ├── 0c59f203babac6bcb498a08cbaf79bf29603ecf8.nq.gz
    ├── 0db2c96acaedb81cc3d4d6ff699a6966e9f1b955.nq.gz
    ├── 0f343de39016f812fa2006bf5cd77f3d16044ca1.nq.gz
    ├── 0f95d97e454515f23ea681b220d08e2e259c0ac9.nq.gz
    ├── 0fb0d7e85e13a3cef1b1396eda0374d2dbf871f8.nq.gz
    ├── 0ff9a8a62e51e2fd3de34ce6c5409770383f4b9c.nq.gz
    ├── 101c0b51faea3d826fe92e67ba43715bb3ffda2d.nq.gz
    ├── 1229526994c20895e173faeea27a047250da8491.nq.gz
    ├── 12737b62ff0d06106eaaf002c48129dd043589f5.nq.gz
    ├── 12797e9c67ea9264d3e3d25202d7fba79eb485b9.nq.gz
    ├── 12f1bfe6dcbe1021c0fdf2e609c0c57376ac4b01.nq.gz
    ├── 13d90bee223dc558f421b467a47698ec50aa2ff1.nq.gz
    ├── 14c5e0cec90e47aecfae432e411da043c5bb5293.nq.gz
    ├── 154e9bf5820a7b886fd4fc4697ed3f5882e1f44c.nq.gz
    ├── 15eca36b3a71e762e5e474bae38a809d767f5bb4.nq.gz
    ├── 17ab824fb5dfdc1a4d8767d35cfe6d531523b73c.nq.gz
    ├── 182e845b3a1f21e142caea211e93e136d7c6e044.nq.gz
    ├── 185a3dbf381dcb76907bdf7b3fcc6bb4d6067f4e.nq.gz
    ├── 189ad05cacc9ca122e1bf6cbd97176006fbc3a18.nq.gz
    ├── 1902166b8c181498dddc266c590eb841cd0ad6f1.nq.gz
    ├── 19a7e2161066fa7b0971d34b6671dc51047407a7.nq.gz
    ├── 19a9e8361836290e96cf41a4f65f5431d2e4c0d6.nq.gz
    ├── 1a80ab281983dab52b860fac5b8217630ae0bc11.nq.gz
    ├── 1a8879db2e893254de2c1c56088f7e5c6a7379b0.nq.gz
    ├── 1ac61592bb05c0f9e86e71fecae87f6017128ef4.nq.gz
    ├── 1d64186a01c082c2a12a6f269efe29462811af58.nq.gz
    ├── 1d83a99769a4ca974fc307302958f44fa9e7102b.nq.gz
    ├── 1db06d541b8aa34eb82c34240efb9ee87a90b46d.nq.gz
    ├── 1e3113acc21ec7bfab2a423141b0dd1aa61fce57.nq.gz
    ├── 1e9f32136e56c638dfd9057517ac697b40f1f286.nq.gz
    ├── 1ec416b419280edb87a05184c39d34d466be6e04.nq.gz
    ├── 21230f9d821116e50e67a4a1eaecdaf29693e957.nq.gz
    ├── 22722755d06efb5b7748a39fb1d171f867d409bb.nq.gz
    ├── 230f5ea098225a91b84e1b296ec6f686db0d33a3.nq.gz
    ├── 25707df94e32bbebbf4e200c9ab8d289ce8faba7.nq.gz
    ├── 25a7642af76dd4863aa79713ffd07bcae402168d.nq.gz
    ├── 26a0cb044846c1a5ff1b9fff31aa5e6810e18e34.nq.gz
    ├── 276f399ea82f7f37c11e99c39d7af9261c8f9fdc.nq.gz
    ├── 287da82dce2e99f14a0d06233f8afef32fb20834.nq.gz
    ├── 28900bb1b5837a59cdf7f9186563964956d82094.nq.gz
    ├── 2919795de035f4519f2b77e938689d0b99c3e20c.nq.gz
    ├── 2925ccbbab669328fa353e9f4f6a77087cc466c9.nq.gz
    ├── 29827a78a46d33deacf68f701bf989f8adaba44d.nq.gz
    ├── 2a03b0ac672d6b1c400d16b389d92bbcd6d9de90.nq.gz
    ├── 2abffe738710db76e5f527965a7a798119a03f5f.nq.gz
    ├── 2c248faf74c945267a38252760e643800331d4a4.nq.gz
    ├── 2d59e0aab07f1d083b8e809de7a77b6dd9a0be3e.nq.gz
    ├── 2e154da09748c211a42a82b65e1ac3d1b2022d3a.nq.gz
    ├── 2efb42bb28f3c13b1e9dee2c75a9936b4482aa3c.nq.gz
    ├── 2f1444fb5a63bd918339c4b0f68a2f6450a68136.nq.gz
    ├── 2f30a06f2ee0fc4603ee49c049e9be0342af2fec.nq.gz
    ├── 2f93f853cd050d803b45fbc3714afbfd933563e3.nq.gz
    ├── 2f98042715ab97ef1c420552b4bc4e228365eb45.nq.gz
    ├── 2fbd832e1422cea1fb26fb8d480df5b914b14cc8.nq.gz
    ├── 3137daa496af3f47ddc813834d728a373776e75d.nq.gz
    ├── 31f1b5805b86cf1fef536a5ec7103f1f31b67cd7.nq.gz
    ├── 31f702b87d0fee37804e660efb59a8100eb18cfb.nq.gz
    ├── 32cbeee7a145e5d315dc8ad0dcbaab5bcac4af3f.nq.gz
    ├── 33ac13eacc76ea837eb592922a30759bf30bad39.nq.gz
    ├── 33f6996f12aa29948c2946de76092ef8abf628ce.nq.gz
    ├── 34a4fba5c203fa0cbca5160bf1e90936abbf7949.nq.gz
    ├── 35ff402ef8dca182061a5a55fe659dc34e659205.nq.gz
    ├── 375012a76360d42f5d48667676a69b488f39d3a5.nq.gz
    ├── 377a86016baf7a2dd9f02d802d1409214eb87df5.nq.gz
    ├── 388cf246038bef3c4ec1676be8205ccaff53cd26.nq.gz
    ├── 39c4cc2944e68740e35192ed6a8a7be92d5ab710.nq.gz
    ├── 39d28b1cada41df113a80800a4c370099a6f5b72.nq.gz
    ├── 3a6697657dcdc927662927eeafa3c98b3dd21e65.nq.gz
    ├── 3a850c17c5ddd7b732c75b58c46dceec92d67549.nq.gz
    ├── 3bc6bbbd2c7b7685ebce8038e6305653541b959b.nq.gz
    ├── 3d3c60b5b3cc110f6e2aa88de56b18dee6c28996.nq.gz
    ├── 3d56b028e583103bf97c82f23b27c9a251df6a6a.nq.gz
    ├── 3dbc1ca591c0557e35b6004aeba250e6a70b56e3.nq.gz
    ├── 3def33246b437460cea757d48139d4e5c6c9c138.nq.gz
    ├── 3dffdd3401654fe162c777996eb010acc1a957cc.nq.gz
    ├── 3f248317e1d147415952fc4d54006557d2fd20db.nq.gz
    ├── 3f47424010cfb28527d7eabe55db417eefa1db5e.nq.gz
    ├── 3fcf217d5fa34205bb0bfc4ba7b4d11bb49c6f6f.nq.gz
    ├── 4114d5ab030f83cf741345ae7818a88dc7931dce.nq.gz
    ├── 419f16664e07512fc2b3a32a5efab03f7ebd9391.nq.gz
    ├── 431cef2f7fece86b135fe8fa5bae5b4ff168d9e9.nq.gz
    ├── 4371a864c27c5e6cfc5e1e7622533e1764b87de7.nq.gz
    ├── 43d65e0f714dbd93cfd59fb556d9657eee29108b.nq.gz
    ├── 4417afe883ec5bc55a0c42aa817906d15d027107.nq.gz
    ├── 446f0c5017b39a49ad4f70e14e9b4b17661be007.nq.gz
    ├── 45691176057494fd24377323a099c45929e0aa13.nq.gz
    ├── 45dd9d2490bbf3de1b25273a3d99a53f0c4b29f0.nq.gz
    ├── 45ff8afd7a4cdfa50b4a216eb9125ebc39cf6278.nq.gz
    ├── 466e7df0810ab60f0746cb6b8cd1c1326c2c0d76.nq.gz
    ├── 468972685ae5399962eac2577a5c69ac2551476a.nq.gz
    ├── 480a40bbc16a66d1ff6eae148a55fbd22cc7ceb5.nq.gz
    ├── 484405d0e8b824f8fdbef4b7a43565c7f341523e.nq.gz
    ├── 496d3df738373966ef6779eaba1eda01e889c940.nq.gz
    ├── 4aaa7bb839351f859bf3afb8f224f422e3d2ddd5.nq.gz
    ├── 4aad23730cb32efd98b5e973510796d043186bb7.nq.gz
    ├── 4ab0a7ccffd875f00e137311baeda9acc4094125.nq.gz
    ├── 4ad6e1a8905c7e9354d4ed430742279c695fc91b.nq.gz
    ├── 4afde82d28e8945859940a8e078ecbc161c9e083.nq.gz
    ├── 4b267821c490c6bca434afe650846edd5d099566.nq.gz
    ├── 4bc22c6f723af2435a6165f91751bb1311945a82.nq.gz
    ├── 4c526989b938108360f17382446f62bcc9e1668e.nq.gz
    ├── 4dce851c9e475ba35a1b637e47ba787e23bec418.nq.gz
    ├── 4fbc518705c059e2873282b83795c01e8b0f57b4.nq.gz
    ├── 501e2ea594ddbb3059cc6c4c7fe4a647b801e95a.nq.gz
    ├── 50ec742463edbd8a879a87e4f418181680f4b0ee.nq.gz
    ├── 5197f72f94c2068ebdf3354596f13b7c59288cc9.nq.gz
    ├── 51bd1a03e3df2625798d6dc20df5f146d933bb7a.nq.gz
    ├── 530b7e33d92c469a0cfd7c9290bd7b768fdeb36c.nq.gz
    ├── 5342c08edb81e7de564f846cb3a1b81479b350b0.nq.gz
    ├── 53599c9eda2e8c9e8fc28658145d6bba429e17f1.nq.gz
    ├── 541434b495d0f834b73fbf71c3b3a246ae6cec0f.nq.gz
    ├── 55f49cb688ee144a46e949183deeb37b890d7ba5.nq.gz
    ├── 5788979df85eb36e03aa7c20fbe2fdc6526c594c.nq.gz
    ├── 59478d315b2e1a7bf3a0b6790e6970bb037cf334.nq.gz
    ├── 595a0c7032921acdb2483307f0d19c1f4e3e3a6c.nq.gz
    ├── 5b03f0704c7385f566936fb01452b0f384a03285.nq.gz
    ├── 5ee399b580529207ac1a41908b9bea406bbf1d5a.nq.gz
    ├── 618b8190ac6094ff49f640d82da59c48f59be315.nq.gz
    ├── 618fe17794a535cf539ac48b130cb5f31e98d794.nq.gz
    ├── 61a4cf65bbecd3571de7a2fa5c52a642aec21c75.nq.gz
    ├── 6204474193f4990fe66a94aa07b115551fb21166.nq.gz
    ├── 622c5e16141820a2737025bcd0f267eee62eff9d.nq.gz
    ├── 62d968e8238e568d588b5f7b065b16e5649b97b3.nq.gz
    ├── 635b5b8725d02e6f258dc285ab27b3c30e91bc08.nq.gz
    ├── 635f08a5587d8c3010fb34ded955f79ef8bdb0e3.nq.gz
    ├── 63625d5ee0e1b66a0b374a220ef2df612317e43e.nq.gz
    ├── 6363a288043086846567067fe0e2496e736f5378.nq.gz
    ├── 63be1fdcafae4981fad51d4a9cb5247985e4a092.nq.gz
    ├── 64af4bda5959f474d424182e20bf8ba60d5278b4.nq.gz
    ├── 665235754643e0a828aed7ac40095a152b2e9a39.nq.gz
    ├── 674b908e2de016a7a88c644b6417074d033a107f.nq.gz
    ├── 684e08e609622ddc3a1901c5444dfe59275c1e6b.nq.gz
    ├── 6c0688e148a2c9a6faece6543ee40a333a8c8526.nq.gz
    ├── 6d42f4a42a7b1aa3c1ecbca358bca1427a0938fb.nq.gz
    ├── 6e5de11ec39937bf9488ee7a125dcb3d88b4607d.nq.gz
    ├── 6ef592ac51253e73244bf16dd94abb829cc5ca96.nq.gz
    ├── 6ffbeefb63ae28dcf234445d055ff3e07589750e.nq.gz
    ├── 7079f3adb5e83dbb0eaa628aef637fa3858fc968.nq.gz
    ├── 70faf491e5105c02bbdb3c8def001f249d8534e4.nq.gz
    ├── 71b749ed05c663bdad028344a242f25bc38793db.nq.gz
    ├── 721e6d03240a2d85c6709b591cc112837b522941.nq.gz
    ├── 7280d9dc879aa9308d863eb6f4a0a2b098a802cf.nq.gz
    ├── 731778e971e775210c1646efd5fbb0700bb380bf.nq.gz
    ├── 743c1fe8a15ab34c1396dbaf0cdf54aeaa99c2a6.nq.gz
    ├── 746acaafbc72abbfc1c4b4d141cc903570f4f058.nq.gz
    ├── 76603f1cd67013ff5a96cdea1f9a1908ca7f79fc.nq.gz
    ├── 77f8fe380032dfcac8ca81d0248c5b62fde4fc0f.nq.gz
    ├── 780979e88e719caaf7cb501c230381e51ae691de.nq.gz
    ├── 782a13dc2b04c23990bc3f95a982ee89b275741b.nq.gz
    ├── 78c35a9cacd0e047d37131a7df36a56c17f80779.nq.gz
    ├── 79a6f98f87132983475fa280bbde5aa720ef2eb7.nq.gz
    ├── 7a37a1fadf48ba1380e338c4aa78128c082c6698.nq.gz
    ├── 7a3d2442908ce2fe2dad72857854fbe8a64bb867.nq.gz
    ├── 7a4ee038d511e091b804e6fe5e76ae9c9cf81ec7.nq.gz
    ├── 7ac50831709a952044ddef8a0597f92cdf987439.nq.gz
    ├── 7ac5a99d2c73712b5c349b80462f25003cf428a1.nq.gz
    ├── 7b76389d93e13f7b3c880a5d6a9fcdd237a575ea.nq.gz
    ├── 7b909fb4ab6aae6b62748e7660fb39d9ab255d1f.nq.gz
    ├── 7c28aa1f2f2e048bf86152b212b9484494c15c95.nq.gz
    ├── 7cf79b13c3eaf78058b176a5c615dc6540d606cc.nq.gz
    ├── 7d0895211bfb73d2fe717938cfa48bf95498414e.nq.gz
    ├── 7ebb3fd4c91c65d5e22cc8d1a76bd92229c342f9.nq.gz
    ├── 7ed392e4f5745cc0aac6184fad57aa19881a065f.nq.gz
    ├── 7eed9e3503a48e234cb22fae1ce466f48b4ef463.nq.gz
    ├── 81442b7761fd98f5dbcab2aee3d95131a65f5d50.nq.gz
    ├── 816f921ff2f3da29e1209b178803225647027e3c.nq.gz
    ├── 81afa3157c18b0093ea76e6faae703945254f2d7.nq.gz
    ├── 820d10b2e5316233d91d6ebb667c34b5d329ac0c.nq.gz
    ├── 824a8494e6cb1ffc4d5dd0db74e81f967c41c0e4.nq.gz
    ├── 82ee4b1848cc28b5c7f3129adc11a28b31ad0faf.nq.gz
    ├── 83568669c84070200ea63f058711bf85c63af5fa.nq.gz
    ├── 83eda74464fb0be81bc394e8a23069b9ab98f432.nq.gz
    ├── 85504b3e90a5ff884c6ccb7a18510f5e7400612d.nq.gz
    ├── 85bff2de16aa6cb6bdedd36e35daabfcd887abdd.nq.gz
    ├── 863b6c4f3c6b4bbcfb83eebe845d9f87f9c908d2.nq.gz
    ├── 866503d04b9c9915eb968480e1a900dfdc26d0dd.nq.gz
    ├── 8757b0806eec9c0719b6e7493850c29b55b6c4fb.nq.gz
    ├── 886dfba9dd3715fb9ced0f0483fdfc50c10fe313.nq.gz
    ├── 88a3bd61a0c3bbc633969155368794fbeddd026a.nq.gz
    ├── 894724791926f9b2e133d24bfe21aead245687e3.nq.gz
    ├── 8960fa2afa3b4a8451348c6cb5e71ba96c712f77.nq.gz
    ├── 89ce02c9a7e384a0bfb1c7e3d2e38e03e67f1d2f.nq.gz
    ├── 89efb1cf99ee54ed55d38de3ff0f12144c2c3a72.nq.gz
    └── 8a496b8a88b4f5b569ba790814aa8625295a438e.nq.gz

8 directories, 200 files
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

[TypeStrong/ts-node](https://github.com/TypeStrong/ts-node)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
