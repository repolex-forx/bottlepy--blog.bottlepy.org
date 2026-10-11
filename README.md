# Repolex Knowledge Graph of bottlepy/blog.bottlepy.org

RDF knowledge graph data for [bottlepy/blog.bottlepy.org](https://github.com/bottlepy/blog.bottlepy.org), parsed by [repolex](https://repolex.ai).

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
rlex download bottlepy/blog.bottlepy.org
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 409834c3809458762dabdf3b6bfba2d06f465191
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 409834c3809458762dabdf3b6bfba2d06f465191
│           └── chunk-001.nq.gz
├── blob
│   ├── 087417abb53337b097ffe620913c098742c0b8c1.nq.gz
│   ├── 1105305850621343d54022dd422415ddf1f659e1.nq.gz
│   ├── 1e19c21262bccf6ae951636758b99708de331f27.nq.gz
│   ├── 1e217566acc77f4b4aa491e92b69806b5d71f950.nq.gz
│   ├── 24314f603a3bc44cf66ddf3e0246a0927b9d1179.nq.gz
│   ├── 3376f4c70cbef43dfd65b5e0622e02a6bc601aa7.nq.gz
│   ├── 3a31202b4dcfd05b5b942d565035abc304d8d3ee.nq.gz
│   ├── 3bacf37aad4a26ab259c8b83db95b63e6cedaf2a.nq.gz
│   ├── 3f82357b3741dcff8535e20798fc8df069ca6174.nq.gz
│   ├── 483c6c85e527d15a84bfe82977fd7f3b0b39f8a9.nq.gz
│   ├── 543a0ed6df878d787138931fe818a0b0f58ba19e.nq.gz
│   ├── 572c66cbb23127e2587e29ca5f09f6ee8a9bc40d.nq.gz
│   ├── 5e936851c5e1b097b6ef9b7701951d18f0a8be71.nq.gz
│   ├── 6d838ba150a0c5b7de46555f424f437b8ee1cdfa.nq.gz
│   ├── 7086584dc60f090ca7775d96becc456059f1d43d.nq.gz
│   ├── 7b760ee29b7c5c9081e4b9f9685a882421989cb0.nq.gz
│   ├── 7d2d2e5d570fce223547489a4e0d8540df1b51e3.nq.gz
│   ├── 7d4e85d981cbecb04b76dab5a234dc4690bd15ab.nq.gz
│   ├── 7f6d57345d8c60fcbd53057b9c1915f0e6ea55f1.nq.gz
│   ├── 826415ad73257b6bd59d672c63ca787d928fc36d.nq.gz
│   ├── 888c812eb8113a03cd3dc76db4d574cac6c5e7dd.nq.gz
│   ├── 896a9bd302a643638f077e00d67849bc8603fd5b.nq.gz
│   ├── 909cca319afe5a15833c51efa9252ac63e0503ce.nq.gz
│   ├── 92ff3904c1cde30c537ed455da454822a6a56f09.nq.gz
│   ├── 952cb85a706831a87c39ab3ea42cf9674cbbc023.nq.gz
│   ├── 9a9d3451a9ec57f3660ebe3befe42e5d13bfd63c.nq.gz
│   ├── 9acca9f2c013efeb2a9144d29dae8e5a240ef4de.nq.gz
│   ├── 9e9460a020c0e458093aa14272da5d75ff3a79a9.nq.gz
│   ├── a1e08e0ea07841765e5bde598d1f35bf15b30e8f.nq.gz
│   ├── b09c7876537ad9faa7a7a68ad6c8035d2e32ec3a.nq.gz
│   ├── b21704e5979ab26151017e52fee01ec0f2de4cb6.nq.gz
│   ├── b6b83f12da8eda7f5202f228db6d4fcec59effcd.nq.gz
│   ├── c2a49f4fb82f19ffa9089fcf8630e5a2870d3feb.nq.gz
│   ├── c4bac06bf9d65728845ce3d5f2319fe9f87bd3f0.nq.gz
│   ├── c5af51ed8b4ac3640a052e464d281571e197e341.nq.gz
│   ├── c6ce246a4602f8f74e75ea8cfe9f5a00daceeb33.nq.gz
│   ├── c70e1395ae245cd54b388adfad903b3db26ed0ce.nq.gz
│   ├── d0bb0ed7b24d8a32f2387273276d112531812577.nq.gz
│   ├── d0d53ac6cfda73931ae54d4ee35bd9f3fa5c84a9.nq.gz
│   ├── d5484350c62821e96630a992b111b276c71624c3.nq.gz
│   ├── d6119280123364c3b37171b9ff0b37c1d67ed2b5.nq.gz
│   ├── d6f0960e0ed47490f41193407c7cc2620b840d41.nq.gz
│   ├── fa95caf7410473f81cee3fa1929025d796b5d3f0.nq.gz
│   ├── fae014dc52100f81ab72a67059b213786060e092.nq.gz
│   └── feb04962bfe2fd712cb5003c8c20b43af4c18201.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 409834c3809458762dabdf3b6bfba2d06f465191.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[bottlepy/blog.bottlepy.org](https://github.com/bottlepy/blog.bottlepy.org)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
