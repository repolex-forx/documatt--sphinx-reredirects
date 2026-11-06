# Repolex Knowledge Graph of documatt/sphinx-reredirects

RDF knowledge graph data for [documatt/sphinx-reredirects](https://github.com/documatt/sphinx-reredirects), parsed by [repolex](https://repolex.ai).

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
rlex download documatt/sphinx-reredirects
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 114983d43f8d346e30c05399ef5c6f9c11151c26
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 114983d43f8d346e30c05399ef5c6f9c11151c26
│           └── chunk-001.nq.gz
├── blob
│   ├── 0100eae146edeb514ca618bf0a92b1a6ae367080.nq.gz
│   ├── 01e951254a90290b8f63a4a17571e2a3b0bc02c6.nq.gz
│   ├── 069d9c3b77237c93ed1ee9443bfd3fcce0ad3ddc.nq.gz
│   ├── 128548315e41e05827394a26b774c4edb3276867.nq.gz
│   ├── 19e52efd02ed8f326243c1f5bd9c854a9f18193b.nq.gz
│   ├── 1ae57acb25c99c9d316e0eae00f1cb7d35065224.nq.gz
│   ├── 1eaf8b6f85783911a453b37a9cd87b7d8d8639b2.nq.gz
│   ├── 1eeffb385b3d3643fbe5806147dc9f57d18f7c5e.nq.gz
│   ├── 2044403a31613fb0b27bc5a4956f87bad11bf292.nq.gz
│   ├── 230819302c9cbaa1a9508d051154aa6451305ca5.nq.gz
│   ├── 2847b8c41e8b8e4da489a41c8fff404e2673fe8c.nq.gz
│   ├── 2857d698b7e1fdb61c6364a119e5ebec1244f80e.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 2c41a4dccc1ddf8ca0cb7b90042dbe1a94ab2656.nq.gz
│   ├── 3ae12249f1dcd42c3feb2a0e0851e46c7156a080.nq.gz
│   ├── 3ec52c26ad160c58877d889dabaa85fa32d9df99.nq.gz
│   ├── 402ec09e0b42c706874cae6528d127d5746723eb.nq.gz
│   ├── 5540d0bf8be9a93808ac3b8e4f92e13190638f53.nq.gz
│   ├── 57d923506268570ec8e2230887d5c71728271940.nq.gz
│   ├── 6761fa7a4f0893f5bcf2442375965c123af195b5.nq.gz
│   ├── 68971d67fd3ee76e81214aec23a5371f5f5459df.nq.gz
│   ├── 6d761e3e3809094b922d1835e787ea5252b72516.nq.gz
│   ├── 75b2a8d926b7e60dad3c9d0efd010fa3d47f2498.nq.gz
│   ├── 78f4d1db334b946897b324d018efcd5d1c4c69e2.nq.gz
│   ├── 80f56be7cd044fd65ac2a8bca784cc2f7bf3f54f.nq.gz
│   ├── 83165612fd42a21a582455ad8bc28ce35e878f1f.nq.gz
│   ├── 880376540877283a4fd8089ea96ba80939c73bc5.nq.gz
│   ├── a2b67b521ae7396842df30a8ee0308e0dba18a2c.nq.gz
│   ├── a3bcee6c43791b2d0dfbe0a4a028e1162f6e1a59.nq.gz
│   ├── a8ce83a448be33a48817385fdb982162ddb8eb15.nq.gz
│   ├── ab6d61d8f829d3361446d69538f33a271c538358.nq.gz
│   ├── adc79dcb3b04db4deed58005d257a6a0e0e09340.nq.gz
│   ├── b10a69d6fe6e51a07003d9c5b9a6b27781689e7d.nq.gz
│   ├── b4834669a945724ec58a25bca68f8fcbe83e9379.nq.gz
│   ├── b6b528736214624139a15fde9dbce2f2a4f2d253.nq.gz
│   ├── c0351664b863a0cd93f26c78f62d85b30cde9cf6.nq.gz
│   ├── c2718aebde80ed8a4f4c721cc17474d9efd20117.nq.gz
│   ├── cc08e34e5b3edc841f539e1d3c188873e6e5b9be.nq.gz
│   ├── d43bcf551ce4a69373f432ee38a410a7584f8a58.nq.gz
│   ├── d631f40db6e89b486cacc875078cb86fe6f122ab.nq.gz
│   ├── dc1f97006acf4d56c85c62680044ee23b81cbf66.nq.gz
│   ├── de314aca308a9c68d095327f0b4e8ae7cc40efb3.nq.gz
│   ├── e08d08095ced0c66eb5d9ea7169869b2c9a1b30f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f4d5025a634ac74d45b756d03a8746f19f95b851.nq.gz
│   ├── f91feb43907825b3ec3e7e2c528d2217a07d7493.nq.gz
│   ├── fd4725e0a974b5765a983e1f55ecaa9f45edfe67.nq.gz
│   └── ffdad603f7f2a975b56336a2aa883ace47ee3e6a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 114983d43f8d346e30c05399ef5c6f9c11151c26.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[documatt/sphinx-reredirects](https://github.com/documatt/sphinx-reredirects)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
