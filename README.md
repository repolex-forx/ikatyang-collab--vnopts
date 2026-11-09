# Repolex Knowledge Graph of ikatyang-collab/vnopts

RDF knowledge graph data for [ikatyang-collab/vnopts](https://github.com/ikatyang-collab/vnopts), parsed by [repolex](https://repolex.ai).

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
rlex download ikatyang-collab/vnopts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eca8ed1740ef6130c68c242ba66f92093ee833d5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eca8ed1740ef6130c68c242ba66f92093ee833d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0865778f43d24b8a4de3e692f76c68d7039472a1.nq.gz
│   ├── 152cfad08f2c177abbe597215cb89cce0a565489.nq.gz
│   ├── 1587ec5f1365b3600321a674f5537d23075806ee.nq.gz
│   ├── 15a98b8ea6e434639878a86fa1cbe848035c8ab5.nq.gz
│   ├── 1d41242c221229e58170efbaa13885162244ae85.nq.gz
│   ├── 1dbfb9a01b6d110334bd5b867ba2035eca405701.nq.gz
│   ├── 3432ae5850d3840a331750832f28ed349ae9f5e6.nq.gz
│   ├── 3700368db70606936f7c8b5e94e1637d601ef70b.nq.gz
│   ├── 3ac8615fb238691dfbe275e378392dc951a01426.nq.gz
│   ├── 3b6492f772c3cf6b0e53646f69c5a6b3d2ff930d.nq.gz
│   ├── 3bfa065768572ff41c0f945257f8d27674da33e5.nq.gz
│   ├── 3e36ecd25d015d69079392b839fa13f227bc217a.nq.gz
│   ├── 40a749eb93949ee5c30665d5ba55ee5a65abb185.nq.gz
│   ├── 41af33454afd783e7f5c602f638e4b3eebbb2960.nq.gz
│   ├── 42d1f5f80dc11e803cd31934c325e270af6d01e5.nq.gz
│   ├── 48a30d1e4781842e6ae070b7207332f05ab50f78.nq.gz
│   ├── 4b86fb5106e9b572f7e2712efd27ee896d5b543f.nq.gz
│   ├── 4c7edb050974c985139d1e665830ccbc1c6a08db.nq.gz
│   ├── 4cb8df7d094ed49de829252daf99b29eb46964d2.nq.gz
│   ├── 4d434395945a7d2e5fcc94bb5405bf1dd5bf6cd3.nq.gz
│   ├── 4e393d1951af87e66f7c601ff008d2131ddecfb3.nq.gz
│   ├── 4e7df5f76106d62977cfa12808a5da1f333e677e.nq.gz
│   ├── 54e8e7dc16ef5e77942f4c3c828e41793478d2fa.nq.gz
│   ├── 5d27878556d512d20ed77a4883b708b30c0b80b2.nq.gz
│   ├── 5ed0b5af0d45919f64c66edfb16a5f4512461fa1.nq.gz
│   ├── 6063e4ad81073e3fb277b3f699b37b806b826ec7.nq.gz
│   ├── 63127fe992fe1a24df96e426960a39984b74a0c1.nq.gz
│   ├── 652013a16c887c8150888954fe6b6604d86d9d42.nq.gz
│   ├── 663abebc1fb5095fabb5d47b85fe18a5e90ed2e3.nq.gz
│   ├── 729a5ae76f13b4f5601366190c1aa27b361675a9.nq.gz
│   ├── 76a40c893423632a6eb5ee19fdda003959f824cc.nq.gz
│   ├── 80f5c9b59ede3c117d68907a725fedbff74507d5.nq.gz
│   ├── 82ec15cc73e188e47a470fea71cb5469af0cff16.nq.gz
│   ├── 8d55ef1d05f29018daab0daf6bbe9bfb61f26e15.nq.gz
│   ├── 8edda1c8c204522f7598f48f4101b469b29c327b.nq.gz
│   ├── 90221e5a62549ee9e95b5378b64121f50bc31442.nq.gz
│   ├── 913b09c8bbc088d7bcf76fb9744df5f5adef3b24.nq.gz
│   ├── 9c0eb7b6192d4720b830e17f1c3a9c2c70edbea2.nq.gz
│   ├── 9fa656eea4838df66989e0f10e063875689913d7.nq.gz
│   ├── a14b3bb1448c4f154826468005768ef48d169748.nq.gz
│   ├── a3ae447e0435481248408131949ddb0605971de2.nq.gz
│   ├── a3c2a736791fd7fbd3985dad7096c6cd19156082.nq.gz
│   ├── a5577dc1896f24e3adee6940a04e0dfe35a3c1f7.nq.gz
│   ├── a5fbe7726b9639c3b54cfdb0971c676fb9d93c89.nq.gz
│   ├── a7023463463f76ef9fc0729678d202f52f4fb162.nq.gz
│   ├── aff317fee633ef0aa525ecda68081f5716cf94ef.nq.gz
│   ├── b211e6651af32b8627dba6115378299e7c6f60fc.nq.gz
│   ├── b36a6cf123740214406396606e2905965d214d68.nq.gz
│   ├── bab5f62dfd29cc706490300d1fe346c314bc2c4a.nq.gz
│   ├── c33a02a0a52244d367f5c8bf5521538b5dc766be.nq.gz
│   ├── c34181d7e0a037e116fdd1398755fc9632778811.nq.gz
│   ├── c35d56bb8bdf9eb8389a3d4933ddf39f7743b47f.nq.gz
│   ├── c84fa512dd3361293595a3e14a253a6f793492f8.nq.gz
│   ├── ca9e6dcad5b0ad3aa658aa21bb83b972cdce421a.nq.gz
│   ├── cbc4fc8166c2f64801291013601164321bf069e9.nq.gz
│   ├── ceb6f8f3513d8fffe1fd55e3887348e44cb5e12b.nq.gz
│   ├── d96bc0d9b4c5aebaf95173b17eff60ab565a1593.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dc0e1e5d0efd090f3f66da3294fb662ddd044b4a.nq.gz
│   ├── dd7255e8a44b71c26d3de7e172f1878795a2f236.nq.gz
│   ├── ea6f0c23846dd41d5e636e4f90969b472a12a25c.nq.gz
│   ├── f1185777e619d1d1bf3ba476c3df83ec5e4a5ebe.nq.gz
│   ├── f47157188300773550efa595160e0ded6b556e6e.nq.gz
│   └── fa8f1161c92e14a1eaaeb46e4506bf6575e8c568.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eca8ed1740ef6130c68c242ba66f92093ee833d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[ikatyang-collab/vnopts](https://github.com/ikatyang-collab/vnopts)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
