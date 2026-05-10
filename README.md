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
│   │   ├── b067abdefa0306a13395e512f5453dda4b3579d4
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9cda7bcb76d513c212e347a76ddacdb941ed755
│   │   │   └── chunk-001.nq.gz
│   │   ├── de007e43effb520e79c7ea88f89bf8742bb486c2
│   │   │   └── chunk-001.nq.gz
│   │   └── fd0d64ce56880ef39f868ec28e48f7d31a0557e4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 76394205f079e1d6d907ba6c193b6fd632e7ab26.nq.gz
│   │   ├── c9cda7bcb76d513c212e347a76ddacdb941ed755.nq.gz
│   │   ├── de007e43effb520e79c7ea88f89bf8742bb486c2.nq.gz
│   │   └── fd0d64ce56880ef39f868ec28e48f7d31a0557e4.nq.gz
│   └── repolex
│       ├── c9cda7bcb76d513c212e347a76ddacdb941ed755
│       │   └── chunk-001.nq.gz
│       └── fd0d64ce56880ef39f868ec28e48f7d31a0557e4
│           └── chunk-001.nq.gz
└── blob
    ├── 00b41cca8b24a45abb78ae15483f1a6cffca4332.nq.gz
    ├── 019bb59539b2325f9f79c70b1d844493f87c9104.nq.gz
    ├── 01a678e1a4cd2417347e65c0f50dcf41a7da1b4a.nq.gz
    ├── 01b984ce0e6f6965274f6f4f4823255a22cc2cb6.nq.gz
    ├── 01db8e077e100009d94128e64944d79796caae36.nq.gz
    ├── 02f3849a71beab180dfb827a987fbf3fc936bde4.nq.gz
    ├── 02fe69879bbdc808855849717e38d06d83d2f118.nq.gz
    ├── 041c243cac9fd9e87502eca248ae0392aea40df4.nq.gz
    ├── 045da08a8d32e90a01ddb7be256bac01510bbdf9.nq.gz
    ├── 0502a28e538005f6d59ae1675f6ca8d7b4c84f83.nq.gz
    ├── 056ddedd9466daf2efe212c5ec189f357d3da032.nq.gz
    ├── 0615188f4a5cbc95b34141099c54f3699dc5fac6.nq.gz
    ├── 07235d8cdd2a26649d233634e69c1faeb585d4a6.nq.gz
    ├── 0781baa3d946e00a9f302f9857a68efc8ee00e28.nq.gz
    ├── 07c25dd9443d63d798506a7b48f7119ca3d3287b.nq.gz
    ├── 07f35e8a6167b4f560e258e4fb4c16eb3f86b24a.nq.gz
    ├── 09c0daed42be253aef85b18c7a7877dcfe8e1719.nq.gz
    ├── 0a06de710f7f6c6dafb8e70ebdd2dae7551e8d05.nq.gz
    ├── 0a27036fcf9723d7c80757b47c94a6493095117d.nq.gz
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
    ├── 108c8dc5778c38c3fc14c7445ecdebf44ef37604.nq.gz
    ├── 1142c42890aab429b37991b1ae725527f4d3f99a.nq.gz
    ├── 11f61ca5b53228e54b27a0900aab2374de209f4f.nq.gz
    ├── 12a1ea300b9688c0d709ee9b7065b8b6d0f3bbc3.nq.gz
    ├── 12d30ab6f725a783865f24e725576020d143c553.nq.gz
    ├── 132c394073b8855609d82d6bfde9307c79637174.nq.gz
    ├── 133ca786a3e1574fe03ad0d89435dad505790160.nq.gz
    ├── 139d5239754ce55a871967615051dc7dc1a955f5.nq.gz
    ├── 13db64bbc90f2331d74fd9dbc6a1e2820ef44666.nq.gz
    ├── 1460293a07c330d7213ee37c9810ddb09c8bfb74.nq.gz
    ├── 155035357bd770f377b8d86288698fc602e99a11.nq.gz
    ├── 1584a7e7afba63aba79154e9b340f82c7911a3d8.nq.gz
    ├── 15881549d7f13b8dced06630e3be5f86c9661bea.nq.gz
    ├── 15d21044219c8761846daa2b839ffff360d1757a.nq.gz
    ├── 1666476352692831d8e4d313ae9d0b34333f5e39.nq.gz
    ├── 17cd364cd2bb73d32ded48adcec2208c4245b21f.nq.gz
    ├── 186313da14533f2b24bf1a68f68268e36f990ad9.nq.gz
    ├── 1899df196b34cda6b6ac07de52a01d099089029d.nq.gz
    ├── 18a2d0cc8e81bd52ca2056744e7b9f8fbcb741db.nq.gz
    ├── 194399d8621fec88ec668e2b01a35fdf8a9b357c.nq.gz
    ├── 1a83d22798aa4cabb9e563041aae0d6ee4372b22.nq.gz
    ├── 1b9eef6a19d867fda0bf5163b6335376304b3d28.nq.gz
    ├── 1c0beb6a0ac029ceef4f9ca47e7ed2d2e4d32c73.nq.gz
    ├── 1c5d91a7a747b6a16ec8db961a94157f2b1f01de.nq.gz
    ├── 1d12daa93b92ed3e1ba49fbfd2ee969c4ad935f8.nq.gz
    ├── 1dcd080136364d6f6d7fe5d0ba548fa7fba58e6f.nq.gz
    ├── 1e1af6db2528266634c96487f93a3004bf40cd2f.nq.gz
    ├── 1e370187ae8fcd596aeb9b4059da31c95ffcb253.nq.gz
    ├── 1e5f9feaf9754e68243c854d7a43cec96dd28fae.nq.gz
    ├── 2019f16fb114e277084964f204cd837bd6baa940.nq.gz
    ├── 2028ac5de625a20028fe1046cdb7a920e6133fea.nq.gz
    ├── 2038d5f276d66d34238f5c93584e407cb5708e6d.nq.gz
    ├── 206d879eb93e856a268124bd6bfafc67db388006.nq.gz
    ├── 21266b65c23b9c73a8548c065ac988c2fae57712.nq.gz
    ├── 217a74e23112a904a21c079eca32f89c680dbacd.nq.gz
    ├── 230ad1c4fcd060807a7a9c8061e0ef96a61000ea.nq.gz
    ├── 23e5a32251e3d7bf1f51b42e04f64f0c73c702ce.nq.gz
    ├── 2429d97ff9cdad553f94facbe3c0eefddfae8cb4.nq.gz
    ├── 244985817c6819a064f2eaaa00dbae3733a37cc0.nq.gz
    ├── 251eba0ba34e806391c9de591eba5a29e469a30f.nq.gz
    ├── 259c08fa69305129eee01e88cbc2e3e92db48efd.nq.gz
    ├── 2661675b03653c4d0734166fc5c170fe8c7b2da3.nq.gz
    ├── 2668ba1341411ba5a804ef3b18cdf28a0e401b31.nq.gz
    ├── 267d79f85f36fb9f9f67d772b78960babe24aeaf.nq.gz
    ├── 26d81c4eefb851e01ef244a4191007b031aa455d.nq.gz
    ├── 28a11918ea03e789e7af2e039fdebb908adabbf7.nq.gz
    ├── 2a47185fbe421df605d05a94b19870b0541b471c.nq.gz
    ├── 2ad4debfe9b24f72326cc01e608c0c5c86d1e50c.nq.gz
    ├── 2b11574fd23bcf0ef46081b70b20493b4530eabd.nq.gz
    ├── 2b40b1a7d0a470c457da29682501bcfc95ae4d13.nq.gz
    ├── 2bf5ad0447d3370461c6f32a0a5bc8a3177376aa.nq.gz
    ├── 2c903e2afe08aa77be413ceed5ce46cb3e49279c.nq.gz
    ├── 2c990726c5d01feb5eea7162b9319197e64c47ce.nq.gz
    ├── 2cb5603ecb4fe74f4836e6970e2b1594081c36e5.nq.gz
    ├── 2d0b67d327ff3e18f56f1a0d0b04e8016d0893fc.nq.gz
    ├── 2d372cbbc84c7e80382af0c2675718d570e26442.nq.gz
    ├── 2d77a44ac4baa1a734b6410d9806884f6a3acadf.nq.gz
    ├── 2e242f1b32fb76e650c2118f83195130402a188b.nq.gz
    ├── 2e3a3f2b28d6934c726325a0b50fcb4e7bae6a4a.nq.gz
    ├── 2e6c75b425f30ccec1fcf0fd3173a393deb029ec.nq.gz
    ├── 2ed67c38c3b00fc2ac21d976b79170b01567a24f.nq.gz
    ├── 2f0246fb0ed1a70da838b83ba216895a2d731f01.nq.gz
    ├── 2fae67211a195673c373d5f27f773dcc4a4ecfc8.nq.gz
    ├── 2fcdaa8b1524d74c56d4e521270af0c6f13428e0.nq.gz
    ├── 3122b0409f77bef1dd7c751755b14076983878f7.nq.gz
    ├── 31c1cb109d500fb7a52294e6c84ad3d00646884d.nq.gz
    ├── 328671c099d17ba99041e4bcf782c0209d97da72.nq.gz
    ├── 348311b5a1dd56ae0d75bf938b611f906d04465b.nq.gz
    ├── 34f2139ea8fb9038fd85111ad73b2b65445d952b.nq.gz
    ├── 362ed7062c940ed07c211f02a714f729749a0da2.nq.gz
    ├── 3655b45f9a8f9a0bbc760045565042cacc346f39.nq.gz
    ├── 368952df9cd185efe64810b1e438abad1e32a9d3.nq.gz
    ├── 368ac01a844e8a1baf5261aea1bf4510001cb175.nq.gz
    ├── 36c74329a6730045cc9c8f8d3c71d6d4813541c2.nq.gz
    ├── 375206befbd1115b517c478901d016f8d81ef589.nq.gz
    ├── 378b468c2dfe103112cf63a5c22699ac28691eb2.nq.gz
    ├── 38e5498784b779e20c53512b37733bc1844d4e44.nq.gz
    ├── 39d400ff45103f89b77b154ebee6092963e2d151.nq.gz
    ├── 3a12e14b9f2b08cf16e5f219ef57d7511b0ba5b5.nq.gz
    ├── 3a5d0ec80b57a48942a864a2083b32c06d70e8f2.nq.gz
    ├── 3af2270e72f9bd9433f039ac94d4b688e4e36f8b.nq.gz
    ├── 3b110c60ba19e5958ff2a4f8e1dddb034aa5f093.nq.gz
    ├── 3b67a92e47f2a78a890b2bc28538d04118d4d1f9.nq.gz
    ├── 3e36812e158eccb3ee2b8b56246a5800191e81fd.nq.gz
    ├── 3ea198b1ddf3b04e93dc54d202b432fb840f64f0.nq.gz
    ├── 3ea82f692851e813a6b5ad7a2585d70fb5942a44.nq.gz
    ├── 3f09b6624d3e36b39af7d8e8637b71ace9ced9bb.nq.gz
    ├── 3f820caa5626c64f8287af29014ff415d242d395.nq.gz
    ├── 3ffe1d6dee728d52c40c63fcee8d0b2055e76a52.nq.gz
    ├── 402581612bb93d451ccf66d90dfc74f5d23969f1.nq.gz
    ├── 405b043b671bfaa98081ac2f4e1b94776b6a9c0e.nq.gz
    ├── 40609c0a7eac54d81b6e3fe244010b31cd5baf56.nq.gz
    ├── 407b0ee87901d0771d7267af6181626c8c30e227.nq.gz
    ├── 415742e8631ef1422772459177e8b827098edaf5.nq.gz
    ├── 416da730f5e5b3e2761cd289680a29178040274a.nq.gz
    ├── 41735f8a2476cb86782cd5978ae6b83b04d9f1df.nq.gz
    ├── 420495380001a9bbedd97df3cc954957b4258853.nq.gz
    ├── 42c170c7b5a53631c0ee08f83582bbb3c6fcbf1d.nq.gz
    ├── 4346136c45f123241b0574b3b68fe78edeea6631.nq.gz
    ├── 442879477d3061a2a2c7eee6f7a00e0a0bf5421d.nq.gz
    ├── 44524aa04cb53efa6ff66da1a2b9bd78748fc972.nq.gz
    ├── 448b0e72773bf3cb567a8962e406044690e8edf5.nq.gz
    ├── 45ba343bf808dbac3ebf5c06c006fc6cf7f07e28.nq.gz
    ├── 45c7930a00c49d7b012603ec2280e85a4dd769a6.nq.gz
    ├── 45e414e63acf07ff0c1591004e1802ffd354412c.nq.gz
    ├── 46c6ff7df9365d32465b3e238b85833313c715eb.nq.gz
    ├── 4764c9332e05cf44c658d3fa6fff45e79913e10d.nq.gz
    ├── 489f0579b91cdc9cb6b796c0f3edc7c20c7ce0ad.nq.gz
    ├── 48af4ea5314293ed8f489ccf3e7f638d472470f5.nq.gz
    ├── 4982542a215d90483aa2e698ce8d3d02baa721e0.nq.gz
    ├── 49d5f189a69a71ab0d8975fe03518bea692d290a.nq.gz
    ├── 4a4d02a5c42224a5d9c5ef39834dc4007d88ae70.nq.gz
    ├── 4a79a767182623f8683db95d4a37e033221b4a7d.nq.gz
    ├── 4ad41c021fb9f7b13f067a3156ecca5bbe13eef6.nq.gz
    ├── 4b2a303b1028d60179ac19bfe234e1dd116cf47e.nq.gz
    ├── 4bfb80de16402487b28d8f89ccac50beefc40718.nq.gz
    ├── 4cca29b2ba762f22b1ae7cd4e3c0a7d5c7512b78.nq.gz
    ├── 4d00243e76731bd95feda82b930ba1ae76a57e1e.nq.gz
    ├── 4d2648cf5321f45c31c6b9e379479387ae1ac36b.nq.gz
    ├── 4d4c199af9e286523b439f66b38010a5ad9ff709.nq.gz
    ├── 4d90f88d2f820c5aec23f3df29fa7161f449987a.nq.gz
    ├── 4e2b59ea9f11ac7237f54b1432c95b637fce62be.nq.gz
    ├── 4f0f4c9073770d374984670f1f547714261bfd78.nq.gz
    ├── 4f225cfc4f9ed0eca86454bcf7f50da0f72c69b3.nq.gz
    ├── 4f355b7b3511f3d4783eef0224186823af0c0f75.nq.gz
    ├── 508f380b0feb024dd09ead829bed4b00e6247e76.nq.gz
    ├── 5095e0f565f543d5854835b6fd566b678cebe213.nq.gz
    ├── 50b6c3ed130dfb0158d6067b31ef655d9416e297.nq.gz
    ├── 520ae748adff54cd09e46c38818063488546c575.nq.gz
    ├── 520b7548544213fe56c671e11f08ad660f18a15f.nq.gz
    ├── 5343f06de7efd548a3a3bb7147096a842df9af25.nq.gz
    ├── 534d5ac0c63f401a19c136dd0caef561c7a8a24a.nq.gz
    ├── 54323c7adc267390bc346891d904f204dcaab48c.nq.gz
    ├── 553253f29d1a0a246e1555878bac5de236f6f480.nq.gz
    ├── 559fb6df3244e8095b6c7d42914e4baa2bf64aaa.nq.gz
    ├── 55ba6db59ef2e8add991314e7dcadc24f40481f5.nq.gz
    ├── 561ca0322deef67ed960b805b9109239ae111636.nq.gz
    ├── 56b76c826e81672b6dde0217c000b24c3cc7a683.nq.gz
    ├── 575537a9b3a25e36c09aa3dfb6e3e73985ae6a93.nq.gz
    ├── 57db67debc066bc550944ddca40401230f8aa4bc.nq.gz
    ├── 590c6a2581196bf3c20ec5fdc73e15ae9fe37c52.nq.gz
    ├── 59f983ea4ce5e543c4500ee0fc5b2cb3457e6bfd.nq.gz
    ├── 5c40f0728eb6e0a02942849b1d4409816c5eeba6.nq.gz
    ├── 5c4990560305c82ddee6ea581d5997dfb1fe1f71.nq.gz
    ├── 5c86d0dbf42e8d4a0602fd4eadf4185372e94acd.nq.gz
    ├── 5cbdce43a5f134f4d72e7c11abd87145521a4b25.nq.gz
    ├── 5d950514e4aa0ace47f209ecaf6478a16da84f22.nq.gz
    ├── 5dab65e04e4016f625c50eb58ffc811a009aafc5.nq.gz
    ├── 5eafda9bcb4edf840cc740be63e6e41aa7c95be4.nq.gz
    ├── 5f1eb9c7362534f730f16b948530bab674969d14.nq.gz
    ├── 5f2c2731b8264a842ef80f441eb5f4398f406e5d.nq.gz
    ├── 6038ae9938078b9d61a3262ab77d191f6fd46702.nq.gz
    ├── 60398a72728706c4ef0160842a236feb5d6f1bbd.nq.gz
    ├── 6050716381a76f35e216abdae72df2791064e8fd.nq.gz
    ├── 607485625888a42eb5e4adfc9c8d361d28fa7370.nq.gz
    ├── 609bc8df280123a446f0c0db4e5e1a9bc7e41dcd.nq.gz
    ├── 613a4360b3ca55fc10f1eb3caaa40aa06331edae.nq.gz
    ├── 6201b6028647bf1bd15170cb92c510c1356be106.nq.gz
    └── 6216b0594da34af2886b6c7329996675226befd0.nq.gz

13 directories, 200 files
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
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
