# Repolex Knowledge Graph of jazzband/django-admin2

RDF knowledge graph data for [jazzband/django-admin2](https://github.com/jazzband/django-admin2), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-admin2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7770da8a4931db60326f87d9fa7a15b1ef704c4c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7770da8a4931db60326f87d9fa7a15b1ef704c4c
│           └── chunk-001.nq.gz
└── blob
    ├── 0056c05038ec40272d35dbf18a262ed7d3cd6845.nq.gz
    ├── 0085be0c82e0fb09e7aa2fd167b0285383602d78.nq.gz
    ├── 03dfd667bcc3f76a08677c864d1b054aab4e968c.nq.gz
    ├── 0595cb195c385856eb33c65adaa42b868975f223.nq.gz
    ├── 06847e31babf09bc999a4cd713869a46418c77f5.nq.gz
    ├── 0f5696467ac03fd60a8c7feb7e218453afcbc48e.nq.gz
    ├── 111cf767a5ab924de01a787c84c0a2f641cb02c0.nq.gz
    ├── 138f94c3d5d67988b989eb8bc5a68c0257376ad9.nq.gz
    ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
    ├── 148211dd280a7465c93f6a98be3b0b6d0ee25fef.nq.gz
    ├── 163e05269de8bbe4d462bc719c7498a18aa122ad.nq.gz
    ├── 16d69d97c8498ba496c6c6bca1744fe2299f8082.nq.gz
    ├── 179d9fbae2ea5d68807ef0ecdd74a503f6cee5c9.nq.gz
    ├── 181f9ffeb90b0e863b329d6cffbc866aa19fa299.nq.gz
    ├── 1ade7cc512abfc3373ce0cd15c24cea936a75f28.nq.gz
    ├── 1bebfde4e5291289ed1c0547c6bf4dcaafa258fa.nq.gz
    ├── 1c0c2dde28d84f5677c355d23e326a433c392c8c.nq.gz
    ├── 1c2b51911e77a7775a6df86a249d684a6e284c92.nq.gz
    ├── 1d62da8eb39f388206f9f996f7e456fc5eefd9f2.nq.gz
    ├── 22f0fc98ce91ab89896c2eed19ddcfaee9b4bfcb.nq.gz
    ├── 22ffe3342982a226366193d1c8ec0fdf65db0f84.nq.gz
    ├── 250010603f03c54d895227a1a412700d05eb7446.nq.gz
    ├── 257c4174f5c342b9b94abe666616179d48f9f1af.nq.gz
    ├── 26dea7951a73079223b50653c455c5adf46a4648.nq.gz
    ├── 282d0a0851ad42eb29b9e5ee6dae969b7db97b91.nq.gz
    ├── 283bf14277615cc0e517de31acc00e2fdde44004.nq.gz
    ├── 2969ca4e48db8350d0c24977f12fc7988f3edb7f.nq.gz
    ├── 2ed9ed8df1e0c54b576168f92fcc0fdef9b43e33.nq.gz
    ├── 2f2c221898b24fa770c5725519b9b37b9aaa5020.nq.gz
    ├── 2fc3d7e9715fa9f173439016d6a265a9e2772b5c.nq.gz
    ├── 3169cbf1018ee4f6b3feebb31117d6530e5d929a.nq.gz
    ├── 322e5648adebe61f389e9923057358ddea602351.nq.gz
    ├── 3633baf1f531db4191ff8e5b382aeca305e28b9e.nq.gz
    ├── 389b0a23d6fe8560b615f259f45681c6805fcd74.nq.gz
    ├── 3c2469fbec20ec29bd2691f8601b787b6ee37a06.nq.gz
    ├── 3cc1fbc5c7eb6ca9e8767811b24b80c3312afa10.nq.gz
    ├── 3ec8243dfef6cd8dceb3b55d9d671d4c703a59fb.nq.gz
    ├── 3ed7f8b48ad9bfab52eb03822fefcd6b77d2e680.nq.gz
    ├── 3fa435922bf49399af90767cf0a07da8c913fda3.nq.gz
    ├── 409fabf72215b6ff9fdc44a9b1e8b207fb95e6e9.nq.gz
    ├── 45c87e574cbd930d153f4912c44a99e9eb6309ca.nq.gz
    ├── 46072c53b76db5b0099120cf1e9d4aab2836c5da.nq.gz
    ├── 47e29885dd766629bab51689a22eb3eaaed31260.nq.gz
    ├── 49ab64f97395c0cb5c764e13a2672907eebb4626.nq.gz
    ├── 49ae9f81669e20aeb046543b5b3867f1a67f5774.nq.gz
    ├── 4c28f00b1e60ff967b233bdd5e17b610c7fa300d.nq.gz
    ├── 4d219366dfeeed5dbf92c43c2fc289b4e86ccc40.nq.gz
    ├── 4dbbe4b9494e0ecdb406b732cde9c86f7a4ff26c.nq.gz
    ├── 4e50bf5bca1388a5b62abd89cef6d08b821c230a.nq.gz
    ├── 4e9853c3153c0a6b4c1c980ae8eccb517ee53547.nq.gz
    ├── 4f0b37b56186b322671ce22d9046cca492187707.nq.gz
    ├── 500e5172534171f678e01f7569d66f9257036a09.nq.gz
    ├── 5025895432d5239fa7e55381e2172fac40ce17dc.nq.gz
    ├── 50a11060137dccaf18707e5df72d2dc6141128a5.nq.gz
    ├── 52e8547d5326e0b4b2450f6029a79ccd9270c194.nq.gz
    ├── 532c5ff1d7178d447639c423519127cd4a9e3c83.nq.gz
    ├── 5369fb4b60ebeeb9f14b3043deb2e366965761ae.nq.gz
    ├── 536d0785c7cab4b7ffd8008bedc0d22bcdef8766.nq.gz
    ├── 53d459af8ec730c402f6b9dddd20fe63d0d5b5e3.nq.gz
    ├── 54b87bd20cbc733ce5347f9a87df18e7eb3cdc94.nq.gz
    ├── 54ba0f3e66678d0b1d964525b2094fb845019c60.nq.gz
    ├── 557db03de997c86a4a028e1ebd3a1ceb225be238.nq.gz
    ├── 570cb9654de2b3d7cbea484d8534efbe7c824d51.nq.gz
    ├── 58ed54ba36faa0da9cc53c60452bcd93446685ea.nq.gz
    ├── 59604434638bde486ede9d640df17189857fa883.nq.gz
    ├── 5a485c4408d48b463390e3e90bd9bba5ba6c60e8.nq.gz
    ├── 5b11403b3e7a9665dc9f61f263705b963a400430.nq.gz
    ├── 5b3fb02c1f0981325f76b6e549c556ac28ba8a7e.nq.gz
    ├── 5dbd4da30cfb9b500ab67655911b1d420c6e920a.nq.gz
    ├── 5dd3bdb108266d2087e5f5d08a9b73d0f352efad.nq.gz
    ├── 5eafa3e82e0779cbf5e07fe1123aa7f5b2aba059.nq.gz
    ├── 5ffc9300b99aad1c31b580f58757a78c0b17a5a2.nq.gz
    ├── 604b965debc1da348da2f52b3c5d4367c61960ed.nq.gz
    ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
    ├── 6168aacd5ed78801973b1b5fb4e43599096dc258.nq.gz
    ├── 62e9e5e4f360de364a05c34fdb045ba8582394da.nq.gz
    ├── 6319e3acc1269157def115ffe50120a3c6e3a1c0.nq.gz
    ├── 63bfe0d7aae3f08362f91e75d4a82394bf2f36b3.nq.gz
    ├── 64539b54c3751a6d9adb44c8e3a45ba5a73b77f0.nq.gz
    ├── 64bbaa202d98b5a5017d671fa2ada437471f5610.nq.gz
    ├── 64f0d9b1c703191c5231b6127f10c0d07d21c2c3.nq.gz
    ├── 65340072fc93f1210f92c5aedce6cacdf211616c.nq.gz
    ├── 68f8c9d48f9a757785420d9722d15ceb7817594e.nq.gz
    ├── 6a09ddd050037c242de81f1cbd5456528648903d.nq.gz
    ├── 6ad6f9eaad8a1ce1a12eca140513a1c65b4eb612.nq.gz
    ├── 6ce9dba020550715b8dac64b1cd7e7257e1df459.nq.gz
    ├── 716af0609a2b731cbb9b48b1bdf10f7c9c60fc9e.nq.gz
    ├── 71ad316e50f96b060fa3df8a160d43b17c47d641.nq.gz
    ├── 72ca89dd57afa6f0ca2126d2a0805c5f9c316b35.nq.gz
    ├── 743aafd641b8c9fbf31e2691ff0fc05dd7132b09.nq.gz
    ├── 775e6ca4b4292e9f2ab055ef377dd09ca7dedbc5.nq.gz
    ├── 77c46d9ed4a91e92b1918e5189a35bdb5fec4608.nq.gz
    ├── 79357eb89a379b72c9e9a90594b85ecfc523daa0.nq.gz
    ├── 79a1a0b4e76238ab9f23d7eae150ee19827569d9.nq.gz
    ├── 7d53a23d6c2577b5b76f232790d97bcfef4b7667.nq.gz
    ├── 7e8b74e1a019432f63168507719fc9808e238ba5.nq.gz
    ├── 7ef76efba339f110916b92917616f5b7faf12207.nq.gz
    ├── 7fd99451398d9ba360c0d6fd9ecddfbd320274dd.nq.gz
    ├── 8206be9e5a29c91ee82efab9883e5a809a7634a8.nq.gz
    ├── 829acf5ce606660963bfe22ff24ce8b65dead1a6.nq.gz
    ├── 841743263af065d10b8710c2150cff9e4047e492.nq.gz
    ├── 86084e60340bd2ec9da8949e59eb4b95dc10b923.nq.gz
    ├── 89ac5d98edc540293db338630851df0b33997636.nq.gz
    ├── 8f8d0454c9010f7be9359e6e58b345c4baefdcf7.nq.gz
    ├── 90601fd4ba0451c449c927ef702b40aa9aaebc86.nq.gz
    ├── 90f7633eb748895e76cc5ff334898169186193b0.nq.gz
    ├── 9163b04788e85b44cbb526f17828f1b47074122e.nq.gz
    ├── 9276ca386aadac26d96f9e6382b3689bebdadb44.nq.gz
    ├── 935bd6c7aa62803750cc999934f54c9f22d5d9db.nq.gz
    ├── 94a7ad2216059385dc315274f3b536e84f511250.nq.gz
    ├── 94e688cb4f302af1d92b99e71f881699751e3e4b.nq.gz
    ├── 94fb5490a2ed10b2c69a4a567a4fd2e4f706d841.nq.gz
    ├── 95f43099a6c52b67e9a19871203ac8bb106d57c6.nq.gz
    ├── 97bfbe60f5f4fdd2fcad738ca363e38b14b7be44.nq.gz
    ├── 97dfdb42d4696f9d30d8ad3d28cd09cef9e876db.nq.gz
    ├── 986fc4243040ea126b92f98428e0259dec45e8ff.nq.gz
    ├── 98713c302a5db41df2d2e4a46a09ff9a63a6a767.nq.gz
    ├── 9977cf51b7846040282ec4d769ed727b2efa492e.nq.gz
    ├── 9a10b0b84946e245595c44c5b3c4da8504a52955.nq.gz
    ├── 9a5da1e8ab4f71cce955560e5cc4be16842aeeed.nq.gz
    ├── 9a6fc52e1944ff003e4c9d4dd648ebf5248f4ea7.nq.gz
    ├── 9b6afaedc0fd7aaf927a07f82da9c11022251b8b.nq.gz
    ├── 9d658704ce74f5921c28663a5db0de5ccc9d8224.nq.gz
    ├── 9d9c38023db62eb9410ff0d7c46511727f0c5163.nq.gz
    ├── 9dbd09369d62fe14de12f726f7f730fd33ebb901.nq.gz
    ├── 9e5f4f6ac4ea49164228f331ea1b59664981599a.nq.gz
    ├── 9e612858f802245ddcbf59788a0db942224bab35.nq.gz
    ├── 9f802ea08f50e60f76b89a19a08cf3178fdd1ab8.nq.gz
    ├── a0851fe3971e9016eac72ac40aa118eff37036e0.nq.gz
    ├── a10eecd9352408ad0baf2765d36c06c703196717.nq.gz
    ├── a21c26c8ac8c52e02d8ab08d59e0a48a98af6115.nq.gz
    ├── a2427b015ae0342d1af6a00ab2db3201ab7f5e92.nq.gz
    ├── a33fcf24743b84e9f12f34cc7ee03789abca7e6f.nq.gz
    ├── a58f862e1328f80102ba8a66fb593fe340e77504.nq.gz
    ├── a5ad3953b8e9a4a4dfc7fb42cb3dae7a0f415ee5.nq.gz
    ├── a610fde9f8f255b0c50363a2c40e85a9dd2f9a99.nq.gz
    ├── a878cc5d57731713c6be89e315ccc6cb01994c99.nq.gz
    ├── aa20ae736d7cefe7b656c2db6ea1beb82570b015.nq.gz
    ├── aa72eab58b5ed7682ee861fb3324eab8c6086df4.nq.gz
    ├── abefd20a61651333fb183960540ba486c2c4e2de.nq.gz
    ├── ac7b7828d57c8ad1efa7be3fb1e0ef6166982380.nq.gz
    ├── addd21fff73f12fde4965d397f415f84ca83812c.nq.gz
    ├── af5f94eeb5e421658dfcfff2376fb8c534032a8b.nq.gz
    ├── af7e1f8521fd90f252651647a2965cfabe47bd89.nq.gz
    ├── af81449515318796626d957793b63dc85ac6ce8e.nq.gz
    ├── b3084142bcaa31d4b5240a7c4b8f01ddca29d319.nq.gz
    ├── b5084db0009ce0e4f33e7317ba8b6630b0203046.nq.gz
    ├── b5cb073ec39a7fdb6c47c109ad97af7bdd8e7638.nq.gz
    ├── b8091e6114b2210f250aceffbaebbf9b191c1ed0.nq.gz
    ├── b8e946bcbde41852ba54101072b089e1c68651cc.nq.gz
    ├── b93a4953fff68df523aa7656497ee339d6026d64.nq.gz
    ├── b94961be5b8eb337e2ebfdbb55644d45e032665d.nq.gz
    ├── bb69696aca44e31a7f522fd4242e97563aad0eda.nq.gz
    ├── bc9c223ef001225fa84fe6a8868a6da899694a47.nq.gz
    ├── bdf0b0432af81c44b68498a11174236828683bcc.nq.gz
    ├── c0ca401d0d6cadcfb9b34060676f1cacca85212f.nq.gz
    ├── c4eb62417e8b7f614b97be35a810b8e40db741a2.nq.gz
    ├── c52c119dcef498c58747d71e6f633e33d60c6d38.nq.gz
    ├── c56a41fbf3c102067f1c57366389163056e735f5.nq.gz
    ├── c570996c0ecfd653a4bfc578f529ea58a4d0fdb6.nq.gz
    ├── c6c83541e066af0964f02089c782feea79c96ef1.nq.gz
    ├── c8a667e605bd08ac27b859b9776e6142e3e62c35.nq.gz
    ├── cea11189ede49bb7c48e1abdd35cff3d6b5ddd56.nq.gz
    ├── d027ee6aad6965722ae478cb398976c4d106b187.nq.gz
    ├── d05688e9e28e1bee95662f3b668f410d37dfa214.nq.gz
    ├── d07b83cb30f167401d400bb424e27d050f7b1b4b.nq.gz
    ├── d1b82ea74573c5d915e1cb41b383ebf7ca8f9765.nq.gz
    ├── d283dbd66d17d2971f3104bac0e6d95b6f31940d.nq.gz
    ├── d2cc5f14beaa661a688cf1cb3f080cbf60317516.nq.gz
    ├── d86ccdc47ffadb93aa1adcd98e56178ff0160798.nq.gz
    ├── da187c900d5673a345c7f78ac0a0bd40f87d9d4f.nq.gz
    ├── db3c211af92426c5c777e21ef91e27a1c3458909.nq.gz
    ├── dc35ce3c2cf688c89b0bd0d4a82bc4be82b14c40.nq.gz
    ├── dc37df38a221842af0352555a7c50c8d482982e6.nq.gz
    ├── dcdbb7f2f97d015fd296e4a7675155265f05d1ea.nq.gz
    ├── dceeea7c437c11ae9bf78d1540f33871d0f8be55.nq.gz
    ├── e099dc18dba9367b2af52ef9c89590a7dc144031.nq.gz
    ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
    ├── e1fc4211d34536c118b32bfdb55e26903a45bbf4.nq.gz
    ├── e27140661f0c7dfead97ee83aac26d2bb758a1e9.nq.gz
    ├── e284f72e1826845b77a8d88635247cc92d707f54.nq.gz
    ├── e35be7326c541269295f7e0853155deb96d81d70.nq.gz
    ├── e3c1c7a74f0e77061d3d7431ff64430bac4179d9.nq.gz
    ├── e48cba3ba74b73a8d4ef4dcea51bc3e6d10d960c.nq.gz
    ├── e4b2fd7c0dae7462054ac3a032233c733c7c69a8.nq.gz
    ├── e4f726a54e2b38236f2ed63502635a2aa38e1e12.nq.gz
    ├── e58c84d4236303f4516b25ecf0f900995aa2e1e4.nq.gz
    ├── e5b2288b7f9216938520cfed31ad256be7becb0b.nq.gz
    ├── e620ad7f56abe9ca422c0ce33f52e1b050500e5d.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7582c62cffe4a4b66e2fabf8b52d8d929927d3c.nq.gz
    ├── e76c170f35d6f910a36d1f7e822407337f954193.nq.gz
    ├── e808e3081a2375b18899047d892d023b98d261d7.nq.gz
    ├── e82da597eb11b9c55f67e274ae09b45c29b36e59.nq.gz
    ├── ea0692b7eee27a0f048cef2935b7d54ab0d02523.nq.gz
    ├── ea762c39fd2735dc361c1845b6cf0062084accac.nq.gz
    ├── eb42c75fcb9e4fda04c170005f4f9264685ddb72.nq.gz
    └── eb7d93f42da20f92b118114c7badbf893095c8a0.nq.gz

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

[jazzband/django-admin2](https://github.com/jazzband/django-admin2)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
