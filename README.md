# Repolex Knowledge Graph of jazzband/website

RDF knowledge graph data for [jazzband/website](https://github.com/jazzband/website), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/website
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 340e43e1e068f2408448e4b69035e1af6a077d22
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 340e43e1e068f2408448e4b69035e1af6a077d22
│           └── chunk-001.nq.gz
└── blob
    ├── 002dc54b73157550d1851b506982705b61f96725.nq.gz
    ├── 00869b2ac7362ef474fbeb34611edf6902ab8adc.nq.gz
    ├── 010f1c8e198bafd2d30aa9efc5e58f244e9022a9.nq.gz
    ├── 015ba4c7ee6eb237f5b45e1b55173875a4ef7fd7.nq.gz
    ├── 0229a24def98bec666872b1cefede404fb9f6678.nq.gz
    ├── 02dca30d50665eb44c8bfeb24864c0218ca02e7a.nq.gz
    ├── 03104b2c3cba83e39bc210273dfc4c96de921eb7.nq.gz
    ├── 04c83c221b7535ff4315f4bef214cdfb46adb65a.nq.gz
    ├── 05150f95176fc1ce729825ff0a3c5d578f0239fa.nq.gz
    ├── 062e5151156b0892a9fa8d69ade3b5f47f6bae91.nq.gz
    ├── 0849220573d3dfc68edc6805407f4fbeac3bbd25.nq.gz
    ├── 08a59bbd3ea729cb6a3a9c92381eef941cdc8da9.nq.gz
    ├── 09fe3dd6820a49e314ee452634843be20380fff1.nq.gz
    ├── 0abeaf2ce6b42680a5e87d61732920dcb3b62cef.nq.gz
    ├── 0c422a00a2a144ddfd656f3aa363cecc59861014.nq.gz
    ├── 0e7649a9be31c328b841dd37982f0bfd5b0b046b.nq.gz
    ├── 0e7db795158057d05aa9cc1d9f071979f214f56b.nq.gz
    ├── 0f6287d45f88e16948227c215c7723f599ac2d57.nq.gz
    ├── 0fc74d97c3a903c7a4f5b91e65754a58dd3d0708.nq.gz
    ├── 10f96894105f0a6b9d7c3aba49870d1dd892a28a.nq.gz
    ├── 11c92df351758dc4b19b76dd791c4d128e5f83c8.nq.gz
    ├── 12b18f88807f7b9b0d7354692887c307fd3b9fbd.nq.gz
    ├── 12f3bc14069c3d419f4b5425b04a006aa921cbee.nq.gz
    ├── 13bd129e3f542fdd9ce16115b2432f5a4dd22686.nq.gz
    ├── 1456a1f653477bbc134bb13824cf828122e65a0e.nq.gz
    ├── 15d615e1aa79c311bcaf691d96a9c8785d18e348.nq.gz
    ├── 1611b7e39f75f92e8e8d954e5b124606834e75e8.nq.gz
    ├── 1aa126be045b2e41155d87fbf7f135b6334663d4.nq.gz
    ├── 1af9702ef8b03f9514fea4f214b493e2b8529d33.nq.gz
    ├── 1bf010acbe8c053e06519c73a7a59f8e28c726f0.nq.gz
    ├── 1cbff014f33b6bb91a4d1d1af4afa1f8cae37449.nq.gz
    ├── 1cc35c139e6c68b135b41eb4395fb4eba25e4de6.nq.gz
    ├── 1ced0906e39bdfcd8e15e9d1ecd18a9a177d34cd.nq.gz
    ├── 1d56327323b9c2fc99176c0d8fb32017a8ea8fb7.nq.gz
    ├── 1d7ccf5feadc4c23e9857b6d34da63cd9965aa35.nq.gz
    ├── 1d8c176f08625b10495927302dde0faf4de9002d.nq.gz
    ├── 2122284f0ab2d8430d260ac89bdeb246f917d89b.nq.gz
    ├── 21d2b037d6e3ac9de501561f1d5e2dd709c96b0d.nq.gz
    ├── 231d4cca2b6cb444aba95e3898055f93759a840a.nq.gz
    ├── 235ba030c288682c1f61e4b1fc6dde13b892f6b5.nq.gz
    ├── 238b644327d2c9cea64ae06825479003e0abdb71.nq.gz
    ├── 24b2fb97e4dff07d9777611cdfa2acffefb7fc58.nq.gz
    ├── 25e91d60b27deeea469b5c40d4a569c2aeff9132.nq.gz
    ├── 27277eaa2ce6f02371ccc174c17b80395345d671.nq.gz
    ├── 27a4fd2cf5a08bf5affcefdfa1dd0c062254ed53.nq.gz
    ├── 2845c559e898c2e0973606af8d62d576b0d7278c.nq.gz
    ├── 28b012d0560315eb22872a36422d953ce9e8cdbe.nq.gz
    ├── 2b1891556204a19b2d1bb44d959879865b277a8a.nq.gz
    ├── 2b94bac1f70e297e526fe202a58e281e8a7bff3f.nq.gz
    ├── 2d93493f8646fd3279956b3b3cc3685b57760793.nq.gz
    ├── 3064c9c5b849452a63abbfde9c0ef416af4d94be.nq.gz
    ├── 31f83d6aa703830d804321de842a3c752461ee6c.nq.gz
    ├── 3244fdadeaabba25138bc605f0e31fb04cad275d.nq.gz
    ├── 348f332114050bdee1b8bb1a33e0e7fb67f7240d.nq.gz
    ├── 34b66873992d1dfeb1202bb2f2da4634462a2356.nq.gz
    ├── 34d4dbeaa3aa19981fa112d95b19d6e57c65c34d.nq.gz
    ├── 3502749d4f5c6f8145150775afcdf62352a5782c.nq.gz
    ├── 3552354fdaf18aca28ea9a70f8f37735d3b17dda.nq.gz
    ├── 359bfb1bcc1f943ba07be3567251412ae3209852.nq.gz
    ├── 39a411a0d95d847e6caf9ece4493ef40441c03ea.nq.gz
    ├── 3a36aec5d40081fd02383138f1ab0440684319f4.nq.gz
    ├── 3c4ecd1d44225d1744fa91fc5b4332d3c6bb4c1d.nq.gz
    ├── 3dd7b5783ae4acbe0ca4fd0f6b805f847310ad0f.nq.gz
    ├── 3dde968d98c8c4cdf1f03674805f694e7a0d8c15.nq.gz
    ├── 43d68dc2c641e58e20bf7e944d474c1d9dd04da7.nq.gz
    ├── 4494e85c5b6b18d7601ec39261ebc0a5e6728e5e.nq.gz
    ├── 44b675e1d2c661b7a9ffb5327b608c84981d01ba.nq.gz
    ├── 4793ab003203b55479f9d32d568dbec880a97cdc.nq.gz
    ├── 4862d0756baa7fa59e5f896f1c0f6b3930d737d3.nq.gz
    ├── 48988e4e5a29e5a0d3ffe84701baa1f2dca94a76.nq.gz
    ├── 4914ae8916e31bf78e3237f0d9c3715cf864595b.nq.gz
    ├── 497197e8160f66050f5ff35191627ed365fd3d86.nq.gz
    ├── 4a3e166656346b4c941069573d2790ce4141a99a.nq.gz
    ├── 4a53f803f38b01b9491036445b836827836df725.nq.gz
    ├── 4a9767dd9b390cce83a1543bca2099594c7f45c8.nq.gz
    ├── 4d8cafd107950897356796fbc400ee4e6946f820.nq.gz
    ├── 4f946aa819c899022efa0f20594b183ad35ec7e5.nq.gz
    ├── 517805e669aee86961d1a3cb98d8b8a1a531a6a6.nq.gz
    ├── 524fdae102429ce90bc1a8b4843a3adb2d8b3415.nq.gz
    ├── 527e22b38f1b24cc300b856f5fa4f86b07d76290.nq.gz
    ├── 52d7dcae1dbed5d00883aedf4b702aaa7d87b9e8.nq.gz
    ├── 5325a6a5a1ec1c0b08cb09a89ac7e43cb71a8876.nq.gz
    ├── 53e899c8a7c24c83c24fbda5cfcdc7c6db99bc40.nq.gz
    ├── 549e04772899f695e693c54f1556bb0a9c75873a.nq.gz
    ├── 5556cca78cd1138ab3b21cf7528422c9696d5fcf.nq.gz
    ├── 5601d3a95d9aeed7176da9eb3b8618f735cb129a.nq.gz
    ├── 564399bead0344091838eb97011a4ceebde0f0e2.nq.gz
    ├── 56fa6f2e4d2c666abe7d27b3845426b0f58c741f.nq.gz
    ├── 5741a64062edcc9cb2ea243a83fb9f518d2e297b.nq.gz
    ├── 57e5e1e8b8cc2510c05ee371871bfa61e395aaed.nq.gz
    ├── 58bea39dc5ed0bca3a09963bd42e111cd14a012a.nq.gz
    ├── 5996ee3d08e25fd42d477c4ff3de4ec1bc0b1abd.nq.gz
    ├── 5afc814d4143c2947671b2c38ada134e6d4671e5.nq.gz
    ├── 5f884652cb4def8121358e94181e290b7064e59f.nq.gz
    ├── 614f331a33050f4630cd62d6c94c298c207dbede.nq.gz
    ├── 626426046dee0b62a52fc6982048253672e7d869.nq.gz
    ├── 62fc51bbfd0f9ea229bbfc843c464fa71045c55f.nq.gz
    ├── 63fff44f0d56a90b5c941d8a2fa1f0c6b76bf4f4.nq.gz
    ├── 64a6cc8b7db339a85b47ebbd0001cec935366b31.nq.gz
    ├── 654e81c15b1d8827b9ef4deef37628b127b7f4e3.nq.gz
    ├── 66e003be18c42e57ff2a647a930f5bd9128de24a.nq.gz
    ├── 6880f98453dfe4b9cf116214cf9dda2378f28c45.nq.gz
    ├── 6a9fc6a6e42058f283138076f556f8efa8848d3d.nq.gz
    ├── 6b3e7cf76ab2f41dfc168a0881086035871322b9.nq.gz
    ├── 6cdf5751ed547e8d530fda87ac87435133cba4d1.nq.gz
    ├── 6e27c03c66bcc56b909b53db2c13ffcbcdf57b5c.nq.gz
    ├── 71b57df4f19cf03616c61171138c4ca4ae84f10d.nq.gz
    ├── 7290ff6cc5301e64a3af06fb8e1be2124374a172.nq.gz
    ├── 738c54f6b0b8371a819ed9539979d5b5f029c850.nq.gz
    ├── 75500cd82f9a8be41f35c7e52c7954f2b23526d9.nq.gz
    ├── 7615b472f1ef16ad3a3426c597997bb3ffad3036.nq.gz
    ├── 7646b603edad288207677a80dadcb5d8c583813f.nq.gz
    ├── 774c589fe8a81d0c4e01d660b572dabc2170de9d.nq.gz
    ├── 7938fdbd601befd4a77f6dceeb5efa605051326c.nq.gz
    ├── 7c9a92521707e8f8d07093a37a5f3edfd2c0e7bd.nq.gz
    ├── 7ca29149578532c3c2bd3d12b5242ff7e13750b5.nq.gz
    ├── 7d319e9ebfbcc0f827d0b11153781c25b969a6fa.nq.gz
    ├── 81503af557d5acbd54e53039cc2d0a0c9fd4fc9e.nq.gz
    ├── 81a0e7e93362613bf11f4014ca44aaea24f1d353.nq.gz
    ├── 82de5edf4e54043432542a7af8be8e6d86365dfb.nq.gz
    ├── 85d3a245cdbece956d8b6b999a38361b8aad8e6c.nq.gz
    ├── 85db41064ba304eba1cae828e802e6943b6272f2.nq.gz
    ├── 8686f6aa15b04ba462ebf03be812ac0574fd38d6.nq.gz
    ├── 87afdc5090854dfbf2fd47f444fce66812d5c0d7.nq.gz
    ├── 880daab1ebeb32cfe825278f61f65cce29149525.nq.gz
    ├── 894010a4a19f47ca10e2db2c4593f1b34c5b3f73.nq.gz
    ├── 89b1ab63156aa3d4d5dd9c57994495f1a4725ae6.nq.gz
    ├── 89d85e9906fb8c0faeb92dff1fed3d8b13c921b3.nq.gz
    ├── 8aa609492c6e768be5256fc29b222f30a8ca5915.nq.gz
    ├── 8de4797107f662d541ab1f82f74ddafdc12adfa7.nq.gz
    ├── 8f233772e530bb53e902120bd5488b5659c41589.nq.gz
    ├── 8f35cfa9eb1508101f278696f77c7776455061e8.nq.gz
    ├── 90a41096a8498db4f232129cc9d2b96af8dd35b2.nq.gz
    ├── 912e9451ff23b62337d767c1ae195d9679b78d16.nq.gz
    ├── 929366e53284d7931ea2a68f385e0d47518f17ae.nq.gz
    ├── 946d74634a9ecc7d2ec2993ece1264b0e490897a.nq.gz
    ├── 98e4f9c44effe479ed38c66ba922e7bcc672916f.nq.gz
    ├── 9c60e37a5089d164acfe0eaa694c637c1941fedc.nq.gz
    ├── 9cc983a9d6d4a161234115fd3466ad570140182c.nq.gz
    ├── 9ce3821b5d6de87bcb2203d399d926086b2fe214.nq.gz
    ├── 9ec43d1f35ee630e57055fcd5e0fb433cbdabaa3.nq.gz
    ├── 9eda4797cacccb8c1493f1bfe621b48a9b7b37e5.nq.gz
    ├── 9fddda7f69c411d49951b9eeed335586aa7afa85.nq.gz
    ├── a08c595889951ee100cb526846d6504fa808c843.nq.gz
    ├── a090380ca4b5aed621c0d42c843807005c0f3273.nq.gz
    ├── a19cf4e8da6d2ec33ecbe86fbe4af4f5d09af75f.nq.gz
    ├── a5af2ff32d6fc62869331de0ee51d3bdcb85843d.nq.gz
    ├── a6941eb78a4863ee5521e8b279e538b186c7de39.nq.gz
    ├── a7130a8506fc6d81f9ab10e1c03662006a1e6806.nq.gz
    ├── a779bf5aec53ed12e5b5c90d0b4a9911eabfd6eb.nq.gz
    ├── a99a7ae05d5b55e9427ce29978f67593aee84e4b.nq.gz
    ├── ab3444c20c712002428fa623dbe8b9c3daaf202a.nq.gz
    ├── ab4f19128567ccce75d1792980c0dc0590e1336e.nq.gz
    ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
    ├── ad8b4deb3874c2da1b2f9a219718a69ffa24bb19.nq.gz
    ├── ae6dac93c30dd6f6a83370405e580807301856b2.nq.gz
    ├── af3b40c8c3bc74f637c46ab2c39497e682ad5110.nq.gz
    ├── aff4a4cde8f14154b8070ea9302455e6db263e60.nq.gz
    ├── b172984ecfdca725c777c85ab8b2e1d31dfd721d.nq.gz
    ├── b2e1980bd600e6f7d1cd76b3ff8a1d4faefef9ee.nq.gz
    ├── b3c3853634cf9a38244becd08124dd329532db55.nq.gz
    ├── b59768a6f28caeea4e3a936b4c91fae9093d5df4.nq.gz
    ├── b881314857475d972c089b754801916dba3f259e.nq.gz
    ├── ba4a9802740f618d3d67a1ad5b1e0d8565d1a157.nq.gz
    ├── bc9e8adaa499d4e1874bc34f7c206fb341e98bfa.nq.gz
    ├── bd98470996ae7192ed8d6198b0e704e36fec109d.nq.gz
    ├── bedea9aee7b79e3fa375c3282281ccdf886bd2c7.nq.gz
    ├── bf016937c510f2e178f75558ebe8c4b7a3faf3b7.nq.gz
    ├── c16919b840e0f3c7752ec8babb668641644c0cab.nq.gz
    ├── c27a76690559d47df6a1efbd1639a00175cdeca6.nq.gz
    ├── c7bab33e6f42936e436427b4f6ee3ac2256464a8.nq.gz
    ├── c94dc64a62f1e3fe682795375e273bb749313f15.nq.gz
    ├── c9b3ce3933acd744a52615b7fe2d5288c204c911.nq.gz
    ├── caafb8fba26a592c459183cfdf1cd87d879e8e54.nq.gz
    ├── caca77237bce2cd28a3049a1770bc589e09a20d0.nq.gz
    ├── cc2180e6963140826756bd069772f50fa9c033bd.nq.gz
    ├── cc986b7ae0ce2353d3c53b9309556aa09ae73ea0.nq.gz
    ├── cdd3530994b62319886d5e77427158707b3d88d7.nq.gz
    ├── ce053f5f6cddbea344855ff35d4dee53c3c98e24.nq.gz
    ├── ce7b91d995e33a29a3d5107f61776407c7149854.nq.gz
    ├── d291733498ff20489e2b0941d2439d88484c7f3e.nq.gz
    ├── d4bcbce09daf8996de180378f1dc56016267c529.nq.gz
    ├── d813c87d5739dbbfb191feff887bfd7a186f560a.nq.gz
    ├── d83bf8788ed29d0e5877b471911f0bd573d9236c.nq.gz
    ├── d8d2158a22be8e6ab7ae1161491dc976f3907b87.nq.gz
    ├── d97cb3cbbb756132f4edecd72f4822ff45f04118.nq.gz
    ├── d9eddaa46856dac25b7abe0bad16cc95393c6a11.nq.gz
    ├── dab243ded85536769b58e1728aa7747c9909dcbe.nq.gz
    ├── dbf0427fdacd2876a426e6bbcbf49cfcc264f9fa.nq.gz
    ├── dd14e29f1535fc165b277ef66b852c9c972a552b.nq.gz
    ├── de13179050d29b0e342c96f4dd649b0d0364f920.nq.gz
    ├── de36dd675dd82d5d7f7420d90f63788535cdc043.nq.gz
    ├── def90320398a977ced9f28aa722090fba3d63068.nq.gz
    ├── e0433f4e6056c91f9223647478c1cac990c28560.nq.gz
    ├── e04f932b26cc9ea51b28646a0c2b9fbee4791c3f.nq.gz
    ├── e0a825e0d24ef70529c1aa6bc1dc272b559be661.nq.gz
    ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
    └── e2157ad85706ea16d865fe2fc0ad672544a33595.nq.gz

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

[jazzband/website](https://github.com/jazzband/website)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
