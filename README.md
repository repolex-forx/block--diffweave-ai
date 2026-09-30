# Repolex Knowledge Graph of block/diffweave-ai

RDF knowledge graph data for [block/diffweave-ai](https://github.com/block/diffweave-ai), parsed by [repolex](https://repolex.ai).

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
rlex download block/diffweave-ai
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1140ed05faac7e6234d90447b780d219fa176e94
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1140ed05faac7e6234d90447b780d219fa176e94.nq.gz
│   └── repolex
│       └── 1140ed05faac7e6234d90447b780d219fa176e94
│           └── chunk-001.nq.gz
├── blob
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 0db8ee05f7f028ff8def9d6c92de66bd130a5a91.nq.gz
│   ├── 10277da07ea9e78a55e1288cdcc1d8ca9ea2f9fc.nq.gz
│   ├── 1983d404258a71f020ec5b024e23f8aade3aa188.nq.gz
│   ├── 1afbe2e9ae630830e665753bbe9790d118345ee5.nq.gz
│   ├── 1cca697313e36999cd6e0d055c63049b386ec894.nq.gz
│   ├── 2c9dda78f471e74537ae24a3dd823ce42b5bbb42.nq.gz
│   ├── 32259c0d840ae4e471c915986dfc518c33556fa3.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3b62e6e4e3e303e9d24c102a264d8e2d9446c860.nq.gz
│   ├── 41087ea7f2a54de374d47a58245769459dc49d0c.nq.gz
│   ├── 4267e366b5e589fe6644f516b5498ccf0714347e.nq.gz
│   ├── 45b7b57858df87cfc5729f43c077b5467192ecbf.nq.gz
│   ├── 50c7a8fdfb9a1c492ed1b8eaae1e7d576e3ffdd7.nq.gz
│   ├── 58ab5f2098919cc344cc5c6d89b09620d227a9ed.nq.gz
│   ├── 5bb0d4c635a2a365c6950c3472b8d1731ae1bc55.nq.gz
│   ├── 5be3a677a927854fc816d94455800a69291a97f5.nq.gz
│   ├── 6253a999519da4aad29f4aa44b1991b2b769a6d0.nq.gz
│   ├── 6a7e68f5bdf9e14bc91f704441efd03ab2114c71.nq.gz
│   ├── 79bf6def700e361b1f69d335bbff13df50502097.nq.gz
│   ├── 7b3dcc4f2ba14f68a27daaf3d9caa0b9c940ccd4.nq.gz
│   ├── 863b4e10b59d1228c8b417485513c1882e19a66d.nq.gz
│   ├── 87acaadba3d3a97cd17d084637a6cdd94caf2167.nq.gz
│   ├── 89babe16779db04077099c43ba053f5e3d952fd4.nq.gz
│   ├── 8ded93b7b1e6f2b8bd4f486722fd1da8fa4d634c.nq.gz
│   ├── 94b130aba9fd7d7885c6d988d0d0b37baee9efd1.nq.gz
│   ├── a453b7925fb066ebf0c0c65c771bd79a7c28146b.nq.gz
│   ├── a6ab1f3e6d487fd689d156dd4c37dd5db29e20ed.nq.gz
│   ├── bbbfd35f40a21c4be104b3aa410d95bea6531294.nq.gz
│   ├── c460fe37e283098bb8d33f66ff5852336d6c6d85.nq.gz
│   ├── c887f71d6cb9617e130b1e3ededb67cee5b9b7e4.nq.gz
│   ├── ca904c96fac49f562a79c936ef2cf52d3ea73ec3.nq.gz
│   ├── cc17d794d8718ff258b63659cd8931a1cb004e08.nq.gz
│   ├── d8636a9657e3a6206412c7ccd9d5d567fa308458.nq.gz
│   ├── de758b9e605b1cc09bf69de8371ed6baba03332c.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e66b832673ec750b7ad5686b8c9c1f1e490d3166.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e860639324c8c5ca82abc798aaf00b78393db8c7.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── efb9139bc3a7c0bbcf3125a86ede09725770b5b1.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   ├── fd8f4fb631b289408e5bd0796106cee2bab59e8b.nq.gz
│   ├── fd91877899e0a9b5e45c74d403e18640261a6687.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1140ed05faac7e6234d90447b780d219fa176e94.nq.gz
├── filetree
│   └── 1140ed05faac7e6234d90447b780d219fa176e94.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 54 files
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

[block/diffweave-ai](https://github.com/block/diffweave-ai)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*
