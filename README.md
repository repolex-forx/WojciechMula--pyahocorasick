# Repolex Knowledge Graph of WojciechMula/pyahocorasick

RDF knowledge graph data for [WojciechMula/pyahocorasick](https://github.com/WojciechMula/pyahocorasick), parsed by [repolex](https://repolex.ai).

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
rlex download WojciechMula/pyahocorasick
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4e28d29898f1019d9706485b2a06026466814d9d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4e28d29898f1019d9706485b2a06026466814d9d
│           └── chunk-001.nq.gz
├── blob
│   ├── 027f1a918ae45a1b12204c77f3a68766f9043a16.nq.gz
│   ├── 0600752d2402e41433f6be133f390fac0b31af88.nq.gz
│   ├── 09f0cb988773cea624ae4b58a9e5f26388a6bd56.nq.gz
│   ├── 0a29613306aef11785ec0823e1cd4d45a72a3884.nq.gz
│   ├── 0acee3c6b32344053ffb53564c628726944f0574.nq.gz
│   ├── 0b63bdee9cffc565bc922ec20808f21a46b9d96f.nq.gz
│   ├── 0e6e0f5615e722512406f310f2c384b9995d6146.nq.gz
│   ├── 10b99eb7ecc6668993ccdd0617c48d23af143ca5.nq.gz
│   ├── 119cde9ba07162e9558827dfc08afab4c31ee2e7.nq.gz
│   ├── 135f67020f3ef5e73b921200f81a98f9a11196b2.nq.gz
│   ├── 14c10d42a2c11dc8fdfe608f3f43a11d0f642734.nq.gz
│   ├── 150a9f21836005c79b0ed2688ee8fec0dcc43427.nq.gz
│   ├── 1775ac57630830f68c0acc61747b38b044bb8b7a.nq.gz
│   ├── 19bbb5b988894b6604e70c3b8418bb19440132d7.nq.gz
│   ├── 1a9901a90c6b9d523a785000cb1618a7c86169a8.nq.gz
│   ├── 1d99a896f3fabb2ff7e9ba923865a8e2082f5d2f.nq.gz
│   ├── 20bcc38db9abba03da89850fd424ad96c5d90003.nq.gz
│   ├── 210a13cdf1789ef3feb4495a0aa1841c408a66e5.nq.gz
│   ├── 22d404c1c643bff81a08d3a21e9b4cb7bc283ecd.nq.gz
│   ├── 234970bb21dfc6189f85cf39f886696f82995d94.nq.gz
│   ├── 269a02155c5f970eb3d53faee8d8707391db00ba.nq.gz
│   ├── 27a9c90d68d3b1783e3bd4dd5f6dd8bcc2683193.nq.gz
│   ├── 29eaa434cfecb327ef175ab8d1b62dc7f16fb310.nq.gz
│   ├── 2d7bd0cafa544caffcf9c0cab3a025487aaf6647.nq.gz
│   ├── 2f9442120b82c5f0fd404142f3332481b0f3f174.nq.gz
│   ├── 32a74fdea765efb87e08aed68d064d76325f78d7.nq.gz
│   ├── 33adb77e1cf2edf7f8bb3379c37801479237ef44.nq.gz
│   ├── 3492e4444f586b2b2597ece02020868b95949911.nq.gz
│   ├── 39fc7c596d2710c945be42a538920225f1395e94.nq.gz
│   ├── 3b8c7a0241ea6e4f40315289bc72345a1d74a5cb.nq.gz
│   ├── 3ec4e0a172f5333f55baf4cb898304bcb961bcec.nq.gz
│   ├── 42398ed2756c5c8fcf237504741adf3bdbf89ebd.nq.gz
│   ├── 42aee395ec309de675647bce10b04d2860d42aab.nq.gz
│   ├── 438ced4ab0caaa397f31fb31c9a4bdd5ca232703.nq.gz
│   ├── 443a3d7d9a29d87c87dfd59a6ff43daf4cfee8ce.nq.gz
│   ├── 4443905418ec84a058e6f084abeee0ec482dc94f.nq.gz
│   ├── 45e2c1f1dc85bea3c9ac8aafcfc2d52261f11392.nq.gz
│   ├── 48bbad51af63a7ee9cca65a1db677b2e8ef1638a.nq.gz
│   ├── 495fd4c5c7e1994c0789347a216186cb97c44e54.nq.gz
│   ├── 4d53a14c22600c3dae058573778ba81a13577856.nq.gz
│   ├── 4fe0ef9a9b21859dea9fd834ce3d2fcf23bad2e0.nq.gz
│   ├── 552dfd4bd4d148d184d0516f552ec1efd3d8bd6c.nq.gz
│   ├── 595661223644840c5c4858db987500edbc335d61.nq.gz
│   ├── 5bcae1c052578d093443ff15007b0957541c0a03.nq.gz
│   ├── 601bffc92250c1e3c497a2eec4253ca89f54fae8.nq.gz
│   ├── 60b9b5fefc7d9043298624ad721e5dd0fb17dce4.nq.gz
│   ├── 67e954dca089a4f390bf0fa9ffe1d88c59218487.nq.gz
│   ├── 6f5db6060f8816f2efa40a4e8e7cc267d5692177.nq.gz
│   ├── 79356b05e2394308c252e08f75143a92e93ed0fd.nq.gz
│   ├── 797b485bf4dadb5010a8d9c918da851b8a9f7054.nq.gz
│   ├── 7bc72d3077bbee3af79e0881f73e649a8e6540a7.nq.gz
│   ├── 7ce3ffab45777bcd5fa51d4078f30a77b9a44d49.nq.gz
│   ├── 81ec28e58285ec2b64c65479dee3ae3e7da3506b.nq.gz
│   ├── 862c37a4876dedf910a983147b2dc62d811573b0.nq.gz
│   ├── 87c92133062cdcc790f5433a8f385af1a52e129e.nq.gz
│   ├── 8af5b08c18a17896c935cbbf92e0cb1461a2e795.nq.gz
│   ├── 8f4c5c860cc45910b89e95746a7f09c9e24dd7e4.nq.gz
│   ├── 8f55ca30774fc90cf1397afede3807259ffee7ad.nq.gz
│   ├── 90dd3e60d2f6343457614c531b2c968e067d1c72.nq.gz
│   ├── 92df83ec92b2ee4871734bde36d92951a93b53af.nq.gz
│   ├── 9374436160b4d380a501b197b5b1800bbe001981.nq.gz
│   ├── 93d0f816c63a151698b823cb72bcc7abd107413e.nq.gz
│   ├── 93d349461b7cca9bae790791a5f13a5589b177b8.nq.gz
│   ├── 941d23071b3525640e783a11e7f154b45be66a69.nq.gz
│   ├── 94d9e11117c2642efbb8429eccae279e5e81b8e8.nq.gz
│   ├── 95beb71f9230d844133ac7923c570a24d5983d47.nq.gz
│   ├── 964425c7d3d2a8747778696d0624b4b6e21fcd71.nq.gz
│   ├── 9c9d9e63bf5657ea5d66385464fc0af33fcaa0e9.nq.gz
│   ├── 9d5403a23e194f34d18a4d657778beab25367b0e.nq.gz
│   ├── 9e036140fb6b65f1e39f1549469d94a58e05ca77.nq.gz
│   ├── a1ee8b9794f190e0c83cab8434503baffdf19f18.nq.gz
│   ├── a2b94f4dcb99bfefbfc873d962af861b3812c631.nq.gz
│   ├── a2d76f339925654e0803bb35ccc077b84f054cfb.nq.gz
│   ├── a2f245373e4d95f006e98daf1a5de4dabc49fa1d.nq.gz
│   ├── a31b19668d32731fb0e73d66953c323831d758ca.nq.gz
│   ├── a47bdfb9cd32951afd3b6bf3a02c593486020e0a.nq.gz
│   ├── a5f180e3c7a2508fa89dda6296aedb84195dee7c.nq.gz
│   ├── a81744ea54247cd03fbddb8474a0b5498a792968.nq.gz
│   ├── a98b64744a037324d091ce08ccddccf9b9b25b2a.nq.gz
│   ├── ab867575d53886c9400750a9880991ba3193c62f.nq.gz
│   ├── ac7e32b6eef309f3849a2de66b0622bb09599fbc.nq.gz
│   ├── ae0459a61af884d6f228facfc618b4a2472cb4ef.nq.gz
│   ├── af2597d691a95e5ad4979c3fa6055dd26f8fec0b.nq.gz
│   ├── b1ca7c2b88c58f67122251083fb1a77dbe3b4176.nq.gz
│   ├── b3b83bc482b9f465619911499dbdaa93e85537ff.nq.gz
│   ├── b3cc0613f0eb720bfa759ebaf6a8ebadf16e95ad.nq.gz
│   ├── b51dc2e521ba85d173406e3262ce1f9ed40eaab7.nq.gz
│   ├── b64a7485abb28c4c50a9b75440a44c2180b90821.nq.gz
│   ├── b6b78712c7cc63876a0bff1ab15db8a14ea0fb53.nq.gz
│   ├── b7948663c2e4cca59b8cd194fa8538e450d69dcc.nq.gz
│   ├── ba65b13af5ea2386f0e5a279f93bd5064181b7ed.nq.gz
│   ├── bbd5da97a9750501556c55615e34341404416de8.nq.gz
│   ├── be61b6d0767b1de4a76ceee0619470a3c60cd24f.nq.gz
│   ├── c137afb23a9375b5fa5ef2f3639223e0fe3e3fca.nq.gz
│   ├── c93d968f66348309e85aa1c4d5fd445649bb1ca0.nq.gz
│   ├── c9e0f041bec9c773c63b426f795b38c8a7086686.nq.gz
│   ├── ca2598dcfcdce5afea0834f15062a66d93b995c5.nq.gz
│   ├── cbbce25fde83abc0746e4d9fdba82b9b90f9c131.nq.gz
│   ├── cc33520148ea658c5c0c5387e3f3038d84a125d6.nq.gz
│   ├── cde905128b0702f67cfdb38252736072ce1c1ec5.nq.gz
│   ├── ce46ad1ab1452b1221d109e69c5f5f8500144781.nq.gz
│   ├── cea598932cd33fc13cdcaf3da597c7e1e28f3d92.nq.gz
│   ├── cee2017d8abd3bbb79acc06239c6aec94cb5720f.nq.gz
│   ├── cf5acc99f4ead8449c46d3af14d668ada0918ad9.nq.gz
│   ├── d1561de79c1c5883c07e806ad25a7baa4771b679.nq.gz
│   ├── d79ac8b4936bb41562a02e7478c52a9fcf3de118.nq.gz
│   ├── d87f041ca7ffb87553eb46be474f0b9fc4eea478.nq.gz
│   ├── d938018e086af7b1ee2fe111da2df35401fd6044.nq.gz
│   ├── dd907db0d24873fc4b1bdef5536a23e36d674d9c.nq.gz
│   ├── e2083e8788aac1aae08cabd8647b19bbcc0fe9fd.nq.gz
│   ├── e4d7b94e59aaa54920a3a10c47be3d271c7132ae.nq.gz
│   ├── e76d3cbb3ee3b5af2fcc709a24de79f5e40367a0.nq.gz
│   ├── e79a098bf5a34472a99ede15074774e9608ee809.nq.gz
│   ├── ea56526039424217f8056a4018ff18032a1c64c5.nq.gz
│   ├── eaa6a4935454514697fb2706361d2fa44477f214.nq.gz
│   ├── f0e1308b223aa0a1a261aa561e4eb703fd3e219a.nq.gz
│   ├── f480d935580a06fc392484bbcd0ef1302e02addb.nq.gz
│   ├── f78971a2e85a38bdf66b3c24f516258eb7d9e455.nq.gz
│   ├── f7910c143ba1c7a8d833676618e9e1e5a47cfb54.nq.gz
│   ├── f83f68d9e60947f7981b36e212b1e5397d94d410.nq.gz
│   ├── f8cf3bf3b90249698da05640d5929486c945c7d4.nq.gz
│   ├── f906c79086abbcfa6d027a2bec8035d284d9262f.nq.gz
│   └── fe004e9416f79ff28df3c1679a6a37907f148675.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4e28d29898f1019d9706485b2a06026466814d9d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 131 files
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

[WojciechMula/pyahocorasick](https://github.com/WojciechMula/pyahocorasick)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
