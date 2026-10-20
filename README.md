# Repolex Knowledge Graph of PyCQA/pylint-django

RDF knowledge graph data for [PyCQA/pylint-django](https://github.com/PyCQA/pylint-django), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/pylint-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b1a68472719f4050f7af3c5abacca9c3edf8051
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b1a68472719f4050f7af3c5abacca9c3edf8051
│           └── chunk-001.nq.gz
├── blob
│   ├── 04a3458293abeb3daff57a6898603adbf3d39119.nq.gz
│   ├── 05d5b48fc14f14c0098c7784cda2c684f99d3675.nq.gz
│   ├── 0d38dfc9161cdbce5292c3539adf27ef1c6dab72.nq.gz
│   ├── 0fe8ab803b5c89e2296a80e7168edc3c66e63699.nq.gz
│   ├── 1274aa94420abf81361c78b11b998aff2125c5ef.nq.gz
│   ├── 1a302dc2f35ea27488ea18e9de94e7c831b948fd.nq.gz
│   ├── 1d92a6d5c7b0e86e41c3a08c7dc9fd163eda7c47.nq.gz
│   ├── 1fa664af506a7e466b3b714d11afa48a3f2cad77.nq.gz
│   ├── 212eb2c2d0d2dbcaf6c1dc82a315c63324767955.nq.gz
│   ├── 25771811b9bb0f13ed9bf5df1e5d0273c56866a4.nq.gz
│   ├── 27575371c7e418e8484e5aee1567dc66242f1e40.nq.gz
│   ├── 29380f881cebe80fc98fcc2935a8ee374841c3b7.nq.gz
│   ├── 29467b98f3c2d8a18fe32fc36032a92cd7aff863.nq.gz
│   ├── 29f4162965371c801b91e721035fd2b457fd9098.nq.gz
│   ├── 2c18f2760ca984f4a843f73ff2a73c9da24d2c97.nq.gz
│   ├── 2d6ea6fd723304244fa3e478cf598c3f24e489d5.nq.gz
│   ├── 37e6909033fbe2a5e57898df079132a89533eba7.nq.gz
│   ├── 394c910ba06b62e4b2035b711a4534f41d6fff0e.nq.gz
│   ├── 40a5d3ed4e7c64fd9a0fb915ab1d80d4e84e3796.nq.gz
│   ├── 450d4fe9e6e3e96a3098a2a6adf05857d8592478.nq.gz
│   ├── 463fc695c68eda396b2b87ff21f0dbe86738b6b1.nq.gz
│   ├── 4b8bab3acf80de182bae72c0e0a5174700a29f97.nq.gz
│   ├── 50a84f1d5dce62fbd567457cb50ba263aeecee93.nq.gz
│   ├── 52f40ed5788e9d450e513f4ff7d5d8d623e2e32a.nq.gz
│   ├── 57d7061fcf300ba2633bfa4b61f2e88b240a4eca.nq.gz
│   ├── 5813de294368cda68ddcdddf55179f97ad97709e.nq.gz
│   ├── 5e0d89e4a3b5fd3253df71a5cc32844e83213af8.nq.gz
│   ├── 5ec670e36cf578f8d59f8675e3451dfecd8b78a5.nq.gz
│   ├── 6061b9dcbbd342995451216f0fedf50e43ba234b.nq.gz
│   ├── 63942adfa75c1d3bc8317dc934105e257a62f47f.nq.gz
│   ├── 668a35cad7723b4a0812b342c5cd6ae2e2355b82.nq.gz
│   ├── 66aa3d0133664e05215c3d546ced6855b0d01002.nq.gz
│   ├── 684c3867bf64f211b131509b421f66666f178641.nq.gz
│   ├── 6cad8fcf5766da39eee2aada767ec47b1b0b329e.nq.gz
│   ├── 6e982c86491b30afff37b8b80151421a6f4099b6.nq.gz
│   ├── 79453a71866d3bd9684aec2a13fcb160d55db044.nq.gz
│   ├── 79f3fcac6dd0b28a7e839b74b77067105dab19a7.nq.gz
│   ├── 7c6e6e02125a94ace207dababea408c09a999a02.nq.gz
│   ├── 7fd3111e651908e994e419348f392dd0d186260a.nq.gz
│   ├── 809bf938f95816330080840e9c649777a2ab0a8e.nq.gz
│   ├── 8153f3b1dfa895ae91cf4a0bdbea597f0a75243f.nq.gz
│   ├── 81f00bd3af294de9d6567c057827ff2ce653f1bc.nq.gz
│   ├── 831f161d31369f501cac4a5cde1836519c55eb15.nq.gz
│   ├── 869a6391e8977ad81354382d9c35e8547b885d1d.nq.gz
│   ├── 8c20b4fc8631a12ff0fb1cbbb421efbb797e4fa5.nq.gz
│   ├── 9460ac55d4444173decdfda33e8f2f41a97513ff.nq.gz
│   ├── 965664258705ba80fa74f3b17aab8fdf0e72195b.nq.gz
│   ├── 975a5a0f909d617a27b46ada7802850bf8a3ebea.nq.gz
│   ├── 99e3041b47b2f9748e1f38213577282e4c67c46d.nq.gz
│   ├── 9c19d076267ce3f5c1170e881daf8748936485f9.nq.gz
│   ├── 9c5938ed3aec491370e84970709f75bc43cc1827.nq.gz
│   ├── 9cd1b0a8e7eb9992135a96234fca6bfc5d854764.nq.gz
│   ├── 9db69920b8eae199f870fee1a8d2de0f345c9b08.nq.gz
│   ├── a0b4e9c2b99e5fb5dcc116858ef4804157825862.nq.gz
│   ├── a1db11b4473e8b18a759680bb9f92fcf0f9699a6.nq.gz
│   ├── a3fa4a35c12121639105b3b1b2572bb856ce9108.nq.gz
│   ├── a5c761d39fdaeb9786dc49b90ed6951789a06ae6.nq.gz
│   ├── a84f5b7e839f238343d70863b9bf2102bde8bf9d.nq.gz
│   ├── a963ee0e603b0fc5ee0b507d81d5c25e96580441.nq.gz
│   ├── aa7842a69decfe5deaea8445ca67bb77a91781a3.nq.gz
│   ├── ac51e2410c622b57aa31923bf8301379c7ccb585.nq.gz
│   ├── ac94ce9c996593c33ee837993ef941b2c760efb0.nq.gz
│   ├── ae18839148e9a0b740d871b2737a0105de8c162a.nq.gz
│   ├── af5222bc854ba7815832c55566974bd52ea55455.nq.gz
│   ├── af9763129e9ec5b5488352ab44f5628383008cbc.nq.gz
│   ├── b0f5eddd8d5e9eb03e60c3a0f8a10716d5ae515e.nq.gz
│   ├── b2fdd994d602fc5b9f512ed72c4eb400c75f4946.nq.gz
│   ├── b404ce297dadcfd525f27fb1a0fd0a5d2644b8b9.nq.gz
│   ├── b6fa7e1a595fba34471351b4abd695dbaf00c7ba.nq.gz
│   ├── bb0c72aa45a5c376ba71bd602eaaa3b470965644.nq.gz
│   ├── bc91b48db57f520643dee3618105b912b8d7af6c.nq.gz
│   ├── c2a303fef44febecce92b532a9c0a644fde79544.nq.gz
│   ├── c34d3cf83de216cc68972e150decbd1c40186fac.nq.gz
│   ├── c372e709c0ef5cde5ac2844cdb6c0fec600d1789.nq.gz
│   ├── c88aeda2f6b96b636a3308d5fef3c7c5dccd5fca.nq.gz
│   ├── cc5a1839744fb497cc5c1f546bcc4393111d661f.nq.gz
│   ├── ccc30cb72734844cd55888be1b35240788703dd2.nq.gz
│   ├── d01e6ce55c89881e8348bc3de75ac9f5acadcd68.nq.gz
│   ├── d111218d2fb159793ce9c95f4f7dbe90ae3e10ca.nq.gz
│   ├── d174376dbbf9ee1dd69a68fe8288aa4d6d7cba5c.nq.gz
│   ├── da690479d2912117f8e92e68b533e26c7081f907.nq.gz
│   ├── dd190a4df7490d32fa85d3c83b2b4340ebf85bf9.nq.gz
│   ├── dd4b68e2f1eee6cfc04e70b1d6f7a95dd4274db1.nq.gz
│   ├── df1f8d40b1c5481dd7e20a6f1ee1976a54949533.nq.gz
│   ├── e13d0ef9c264b8fbbefa9a395b1906dd200305bb.nq.gz
│   ├── e55ba49df1e2b7bdcf4201ba70167ad5151c97f7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e711ec5efca8e32a9031b537b7a3f037c7f79d8f.nq.gz
│   ├── e9a8ea251de61f2bcee3987f196792eacd17e648.nq.gz
│   ├── ebcf236cb8c3c5055414589b8f5821ea61143168.nq.gz
│   ├── efed62688624ed13fc6a717108614186cacc09b5.nq.gz
│   ├── f0e894334911d14767421212f3727c5880fb3e6f.nq.gz
│   ├── f168fd5ff5a97b2dba82ce7a38444d557ba7bce6.nq.gz
│   ├── f1b36330b3c6a3cf49987a52f5847ed9494fdeae.nq.gz
│   ├── f22701f53b3c062dbed1230bbbc8e906d44246d5.nq.gz
│   ├── f2c18d5c91f93352451fb29637894d8865ffbf16.nq.gz
│   ├── f61c7f9623a4125d4e435a390f5d829966b27cdb.nq.gz
│   ├── f7e40b9e9cf962df2a253a696690717737f799b6.nq.gz
│   ├── fab465f6e87ae23aad0cbd7412916932d9f5d881.nq.gz
│   ├── fc2e8bfbf68b09a8bc022ae82c7f948ff2db2d66.nq.gz
│   ├── fd7575860a6293fb75c988fd1a0b6cbe85a33331.nq.gz
│   ├── febcde0e9e6a0d59f2fe0e8a8b1d6572388b8010.nq.gz
│   └── ff6f91cb35368eef17184f71851736df4dcb819b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9b1a68472719f4050f7af3c5abacca9c3edf8051.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[PyCQA/pylint-django](https://github.com/PyCQA/pylint-django)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
