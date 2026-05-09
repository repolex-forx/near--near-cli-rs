# Repolex Knowledge Graph of near/near-cli-rs

RDF knowledge graph data for [near/near-cli-rs](https://github.com/near/near-cli-rs), parsed by [repolex](https://repolex.ai).

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
lexq download near/near-cli-rs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 76394205f079e1d6d907ba6c193b6fd632e7ab26
│   │   │   └── chunk-001.nq.gz
│   │   ├── de007e43effb520e79c7ea88f89bf8742bb486c2
│   │   │   └── chunk-001.nq.gz
│   │   └── fd0d64ce56880ef39f868ec28e48f7d31a0557e4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 76394205f079e1d6d907ba6c193b6fd632e7ab26.nq.gz
│   │   ├── de007e43effb520e79c7ea88f89bf8742bb486c2.nq.gz
│   │   └── fd0d64ce56880ef39f868ec28e48f7d31a0557e4.nq.gz
│   └── repolex
│       └── fd0d64ce56880ef39f868ec28e48f7d31a0557e4
│           └── chunk-001.nq.gz
└── blob
    ├── 019bb59539b2325f9f79c70b1d844493f87c9104.nq.gz
    ├── 01a678e1a4cd2417347e65c0f50dcf41a7da1b4a.nq.gz
    ├── 01b984ce0e6f6965274f6f4f4823255a22cc2cb6.nq.gz
    ├── 01db8e077e100009d94128e64944d79796caae36.nq.gz
    ├── 02f3849a71beab180dfb827a987fbf3fc936bde4.nq.gz
    ├── 02fe69879bbdc808855849717e38d06d83d2f118.nq.gz
    ├── 041c243cac9fd9e87502eca248ae0392aea40df4.nq.gz
    ├── 0502a28e538005f6d59ae1675f6ca8d7b4c84f83.nq.gz
    ├── 056ddedd9466daf2efe212c5ec189f357d3da032.nq.gz
    ├── 07235d8cdd2a26649d233634e69c1faeb585d4a6.nq.gz
    ├── 07c25dd9443d63d798506a7b48f7119ca3d3287b.nq.gz
    ├── 07f35e8a6167b4f560e258e4fb4c16eb3f86b24a.nq.gz
    ├── 09c0daed42be253aef85b18c7a7877dcfe8e1719.nq.gz
    ├── 0a06de710f7f6c6dafb8e70ebdd2dae7551e8d05.nq.gz
    ├── 0a9d05767aebcc1591ca083444a5db92ac1862d2.nq.gz
    ├── 0aef6d894cc282079c2fec259a81f23154b33fbf.nq.gz
    ├── 0b1e28181e1cb8ce4fa993e2b14041734475d609.nq.gz
    ├── 0b418adfdf4ec6984ad78e09593ee7e3abc137e2.nq.gz
    ├── 0bbad69bc8ebce1c62300d8dbcdb73cd2a02b164.nq.gz
    ├── 0c5548be978bbbf981c7eb3df41c0992b5944c9e.nq.gz
    ├── 0d5126698e19578daea86fca7a9455c0fbe0b009.nq.gz
    ├── 0fcc54d775da53f5f43d261a07d07addded489a1.nq.gz
    ├── 0fdd1c32469486c31de4c4fee391c50ce08fa43b.nq.gz
    ├── 10643f3592a9d10b0219e0532cb8d98a7aef229b.nq.gz
    ├── 1082abc473624ee7cd3bfbadeb14b972846ae4a1.nq.gz
    ├── 1142c42890aab429b37991b1ae725527f4d3f99a.nq.gz
    ├── 11f61ca5b53228e54b27a0900aab2374de209f4f.nq.gz
    ├── 12a1ea300b9688c0d709ee9b7065b8b6d0f3bbc3.nq.gz
    ├── 12d30ab6f725a783865f24e725576020d143c553.nq.gz
    ├── 132c394073b8855609d82d6bfde9307c79637174.nq.gz
    ├── 133ca786a3e1574fe03ad0d89435dad505790160.nq.gz
    ├── 13db64bbc90f2331d74fd9dbc6a1e2820ef44666.nq.gz
    ├── 1460293a07c330d7213ee37c9810ddb09c8bfb74.nq.gz
    ├── 155035357bd770f377b8d86288698fc602e99a11.nq.gz
    ├── 1584a7e7afba63aba79154e9b340f82c7911a3d8.nq.gz
    ├── 15881549d7f13b8dced06630e3be5f86c9661bea.nq.gz
    ├── 15d21044219c8761846daa2b839ffff360d1757a.nq.gz
    ├── 1666476352692831d8e4d313ae9d0b34333f5e39.nq.gz
    ├── 17cd364cd2bb73d32ded48adcec2208c4245b21f.nq.gz
    ├── 18a2d0cc8e81bd52ca2056744e7b9f8fbcb741db.nq.gz
    ├── 194399d8621fec88ec668e2b01a35fdf8a9b357c.nq.gz
    ├── 1a83d22798aa4cabb9e563041aae0d6ee4372b22.nq.gz
    ├── 1c5d91a7a747b6a16ec8db961a94157f2b1f01de.nq.gz
    ├── 1dcd080136364d6f6d7fe5d0ba548fa7fba58e6f.nq.gz
    ├── 1e1af6db2528266634c96487f93a3004bf40cd2f.nq.gz
    ├── 1e370187ae8fcd596aeb9b4059da31c95ffcb253.nq.gz
    ├── 2019f16fb114e277084964f204cd837bd6baa940.nq.gz
    ├── 2028ac5de625a20028fe1046cdb7a920e6133fea.nq.gz
    ├── 2038d5f276d66d34238f5c93584e407cb5708e6d.nq.gz
    ├── 21266b65c23b9c73a8548c065ac988c2fae57712.nq.gz
    ├── 217a74e23112a904a21c079eca32f89c680dbacd.nq.gz
    ├── 23e5a32251e3d7bf1f51b42e04f64f0c73c702ce.nq.gz
    ├── 2429d97ff9cdad553f94facbe3c0eefddfae8cb4.nq.gz
    ├── 244985817c6819a064f2eaaa00dbae3733a37cc0.nq.gz
    ├── 251eba0ba34e806391c9de591eba5a29e469a30f.nq.gz
    ├── 259c08fa69305129eee01e88cbc2e3e92db48efd.nq.gz
    ├── 2661675b03653c4d0734166fc5c170fe8c7b2da3.nq.gz
    ├── 2668ba1341411ba5a804ef3b18cdf28a0e401b31.nq.gz
    ├── 267d79f85f36fb9f9f67d772b78960babe24aeaf.nq.gz
    ├── 26d81c4eefb851e01ef244a4191007b031aa455d.nq.gz
    ├── 2a47185fbe421df605d05a94b19870b0541b471c.nq.gz
    ├── 2ad4debfe9b24f72326cc01e608c0c5c86d1e50c.nq.gz
    ├── 2b11574fd23bcf0ef46081b70b20493b4530eabd.nq.gz
    ├── 2b40b1a7d0a470c457da29682501bcfc95ae4d13.nq.gz
    ├── 2bf5ad0447d3370461c6f32a0a5bc8a3177376aa.nq.gz
    ├── 2cb5603ecb4fe74f4836e6970e2b1594081c36e5.nq.gz
    ├── 2d0b67d327ff3e18f56f1a0d0b04e8016d0893fc.nq.gz
    ├── 2d77a44ac4baa1a734b6410d9806884f6a3acadf.nq.gz
    ├── 2e3a3f2b28d6934c726325a0b50fcb4e7bae6a4a.nq.gz
    ├── 2ed67c38c3b00fc2ac21d976b79170b01567a24f.nq.gz
    ├── 2f0246fb0ed1a70da838b83ba216895a2d731f01.nq.gz
    ├── 2fae67211a195673c373d5f27f773dcc4a4ecfc8.nq.gz
    ├── 328671c099d17ba99041e4bcf782c0209d97da72.nq.gz
    ├── 348311b5a1dd56ae0d75bf938b611f906d04465b.nq.gz
    ├── 34f2139ea8fb9038fd85111ad73b2b65445d952b.nq.gz
    ├── 362ed7062c940ed07c211f02a714f729749a0da2.nq.gz
    ├── 368952df9cd185efe64810b1e438abad1e32a9d3.nq.gz
    ├── 368ac01a844e8a1baf5261aea1bf4510001cb175.nq.gz
    ├── 36c74329a6730045cc9c8f8d3c71d6d4813541c2.nq.gz
    ├── 375206befbd1115b517c478901d016f8d81ef589.nq.gz
    ├── 39d400ff45103f89b77b154ebee6092963e2d151.nq.gz
    ├── 3a12e14b9f2b08cf16e5f219ef57d7511b0ba5b5.nq.gz
    ├── 3a5d0ec80b57a48942a864a2083b32c06d70e8f2.nq.gz
    ├── 3af2270e72f9bd9433f039ac94d4b688e4e36f8b.nq.gz
    ├── 3b67a92e47f2a78a890b2bc28538d04118d4d1f9.nq.gz
    ├── 3ea198b1ddf3b04e93dc54d202b432fb840f64f0.nq.gz
    ├── 3ea82f692851e813a6b5ad7a2585d70fb5942a44.nq.gz
    ├── 3f09b6624d3e36b39af7d8e8637b71ace9ced9bb.nq.gz
    ├── 3f820caa5626c64f8287af29014ff415d242d395.nq.gz
    ├── 405b043b671bfaa98081ac2f4e1b94776b6a9c0e.nq.gz
    ├── 407b0ee87901d0771d7267af6181626c8c30e227.nq.gz
    ├── 416da730f5e5b3e2761cd289680a29178040274a.nq.gz
    ├── 41735f8a2476cb86782cd5978ae6b83b04d9f1df.nq.gz
    ├── 42c170c7b5a53631c0ee08f83582bbb3c6fcbf1d.nq.gz
    ├── 4346136c45f123241b0574b3b68fe78edeea6631.nq.gz
    ├── 442879477d3061a2a2c7eee6f7a00e0a0bf5421d.nq.gz
    ├── 44524aa04cb53efa6ff66da1a2b9bd78748fc972.nq.gz
    ├── 448b0e72773bf3cb567a8962e406044690e8edf5.nq.gz
    ├── 45ba343bf808dbac3ebf5c06c006fc6cf7f07e28.nq.gz
    ├── 45e414e63acf07ff0c1591004e1802ffd354412c.nq.gz
    ├── 46c6ff7df9365d32465b3e238b85833313c715eb.nq.gz
    ├── 4764c9332e05cf44c658d3fa6fff45e79913e10d.nq.gz
    ├── 489f0579b91cdc9cb6b796c0f3edc7c20c7ce0ad.nq.gz
    ├── 48af4ea5314293ed8f489ccf3e7f638d472470f5.nq.gz
    ├── 4982542a215d90483aa2e698ce8d3d02baa721e0.nq.gz
    ├── 49d5f189a69a71ab0d8975fe03518bea692d290a.nq.gz
    ├── 4a4d02a5c42224a5d9c5ef39834dc4007d88ae70.nq.gz
    ├── 4b2a303b1028d60179ac19bfe234e1dd116cf47e.nq.gz
    ├── 4bfb80de16402487b28d8f89ccac50beefc40718.nq.gz
    ├── 4cca29b2ba762f22b1ae7cd4e3c0a7d5c7512b78.nq.gz
    ├── 4d00243e76731bd95feda82b930ba1ae76a57e1e.nq.gz
    ├── 4d4c199af9e286523b439f66b38010a5ad9ff709.nq.gz
    ├── 4d90f88d2f820c5aec23f3df29fa7161f449987a.nq.gz
    ├── 4e2b59ea9f11ac7237f54b1432c95b637fce62be.nq.gz
    ├── 4f225cfc4f9ed0eca86454bcf7f50da0f72c69b3.nq.gz
    ├── 4f355b7b3511f3d4783eef0224186823af0c0f75.nq.gz
    ├── 508f380b0feb024dd09ead829bed4b00e6247e76.nq.gz
    ├── 5095e0f565f543d5854835b6fd566b678cebe213.nq.gz
    ├── 50b6c3ed130dfb0158d6067b31ef655d9416e297.nq.gz
    ├── 5343f06de7efd548a3a3bb7147096a842df9af25.nq.gz
    ├── 534d5ac0c63f401a19c136dd0caef561c7a8a24a.nq.gz
    ├── 54323c7adc267390bc346891d904f204dcaab48c.nq.gz
    ├── 55ba6db59ef2e8add991314e7dcadc24f40481f5.nq.gz
    ├── 561ca0322deef67ed960b805b9109239ae111636.nq.gz
    ├── 56b76c826e81672b6dde0217c000b24c3cc7a683.nq.gz
    ├── 57db67debc066bc550944ddca40401230f8aa4bc.nq.gz
    ├── 590c6a2581196bf3c20ec5fdc73e15ae9fe37c52.nq.gz
    ├── 59f983ea4ce5e543c4500ee0fc5b2cb3457e6bfd.nq.gz
    ├── 5c40f0728eb6e0a02942849b1d4409816c5eeba6.nq.gz
    ├── 5c86d0dbf42e8d4a0602fd4eadf4185372e94acd.nq.gz
    ├── 5cbdce43a5f134f4d72e7c11abd87145521a4b25.nq.gz
    ├── 5d950514e4aa0ace47f209ecaf6478a16da84f22.nq.gz
    ├── 5dab65e04e4016f625c50eb58ffc811a009aafc5.nq.gz
    ├── 5eafda9bcb4edf840cc740be63e6e41aa7c95be4.nq.gz
    ├── 5f2c2731b8264a842ef80f441eb5f4398f406e5d.nq.gz
    ├── 6050716381a76f35e216abdae72df2791064e8fd.nq.gz
    ├── 607485625888a42eb5e4adfc9c8d361d28fa7370.nq.gz
    ├── 609bc8df280123a446f0c0db4e5e1a9bc7e41dcd.nq.gz
    ├── 613a4360b3ca55fc10f1eb3caaa40aa06331edae.nq.gz
    ├── 6201b6028647bf1bd15170cb92c510c1356be106.nq.gz
    ├── 6216b0594da34af2886b6c7329996675226befd0.nq.gz
    ├── 629af4ef3829badecbcc1310cc7b4d8634cb7123.nq.gz
    ├── 62e79f1fbf2429fd7bd3d89873b1a40973274103.nq.gz
    ├── 6495c5e33294caf1d4697a68a3f5c2122a5a0455.nq.gz
    ├── 64a872284838d9ed11d1b74126418467b4bee190.nq.gz
    ├── 66563ad8f082cfb7f912fc3e15089665a5abf2d0.nq.gz
    ├── 668a42ac6b224b7aea88a4147b958e522695ff73.nq.gz
    ├── 669c20cd4bcaaf1557084868ddf35764e8be479d.nq.gz
    ├── 6716fd4973593b0763f59996367119e1ae3fb0d9.nq.gz
    ├── 6807871cccf9fc7e9fd3f9f0b5cc0a17cdfea077.nq.gz
    ├── 684c9fa38d546d2d738d8d12fd253196293ac30b.nq.gz
    ├── 6856f2dca5ae637de179a2820313bd305a984b2a.nq.gz
    ├── 686b3293e018b2b835879e5f936d3ebed601b5ba.nq.gz
    ├── 691d9d76589823cf52a02d96f6f2d656b8093f90.nq.gz
    ├── 698bc3a4e0d33925ffec0457748775485e38fe92.nq.gz
    ├── 699561caecc4a71f204bbe66ee931650795e95b0.nq.gz
    ├── 69b6a1821724cb5e91ac60337403e5ab77fc8611.nq.gz
    ├── 69b89e8a82fa98156d01f4d5e61aaf3286328416.nq.gz
    ├── 69f817c92f6875f3548e34e3c4217371446e1d57.nq.gz
    ├── 6a54c53b3482248b2d67f789ac3a8ab7abe66b87.nq.gz
    ├── 6abbc459c724a77bbc47ce713a9bf120bfb8086d.nq.gz
    ├── 6b469a04a7068b90ff63e8fb8a1326ea24b55cf2.nq.gz
    ├── 6b485a7ab240829f3455e766e13fa84a01e17bfa.nq.gz
    ├── 6c18048d4e6335a622f006666102b76cbcff14c4.nq.gz
    ├── 6c1cc15300fae7b8798dc4e9b7459579198c0785.nq.gz
    ├── 6c8b29d402a42229b44359606035bf90460fe6d6.nq.gz
    ├── 6f527fc4b29e8123ebc41d71d90c6db87b400a95.nq.gz
    ├── 70d19b9fefd134903a59e84e266ba76821a300d6.nq.gz
    ├── 7176b9327951a537a05c736da87f9aabdb93d4f5.nq.gz
    ├── 71c02d69b8fbb20c13f431bee8ddcdbce2443b14.nq.gz
    ├── 71d226c78bd7de8f118f933d6d28bcc2ed821607.nq.gz
    ├── 71eb8eaee3abd3d51a3d0f52ae76a456930737d8.nq.gz
    ├── 73bae455b35ce2b7a69d13877c0b469ec5965f58.nq.gz
    ├── 745ec7b8c5c3944aa8133d596e6ca9c83d320315.nq.gz
    ├── 74b4699d5fbeb96c6a8f605e8fc8d5e2e6620364.nq.gz
    ├── 751c42070a5803963b9cd61cb06a9821367106f2.nq.gz
    ├── 77441ac9391ccfcc400714bf958d5e6fdbae9a20.nq.gz
    ├── 77a2eca7ff00ad690db9ca5a4d756c95ea8cc177.nq.gz
    ├── 78798b5259beba225bbefc82dbab517247933d80.nq.gz
    ├── 7893b6171735a5d52e991606c0e7a6f785ed25c0.nq.gz
    ├── 7900ddc3debf00f1218ade8cd3b014d4cedad04f.nq.gz
    ├── 79b80e9963c5a5debe348fe0eaefd13b325c0f8b.nq.gz
    ├── 7a0ad2c4ecd9f9721f90afbf0ab15a8ccd7f6d52.nq.gz
    ├── 7a14d61af00b1211b0c7513c0e1c4450f4073f7b.nq.gz
    ├── 7b43d1ec692ac1313af7541e1cb186139ee0280e.nq.gz
    ├── 7bbf0fbe9e2056fd896ff0543a6a7b3532ab17e3.nq.gz
    ├── 7c463982f3373c7fde511de58bff49ef6d241577.nq.gz
    ├── 7f519d77e6ded599fefc4a445f5b9c734b8bbb94.nq.gz
    ├── 7f5d61136a7a2849cf778293d45b5514675d761d.nq.gz
    ├── 7f6e21aeba6e1b425a41a01bef1cdb6a0443255d.nq.gz
    ├── 8013ec9aec683f44d1da7ea6c1af73a5c0f6d9b7.nq.gz
    ├── 8144561f426991c7a2a21a9ca559ec1a32fca9b1.nq.gz
    └── 8159e749e291aca80f90378d1a2d313599fe7341.nq.gz

10 directories, 200 files
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

[near/near-cli-rs](https://github.com/near/near-cli-rs)

---
*Parsed on 2026-05-09 by [repolex](https://repolex.ai)*
