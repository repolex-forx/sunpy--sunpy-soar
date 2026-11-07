# Repolex Knowledge Graph of sunpy/sunpy-soar

RDF knowledge graph data for [sunpy/sunpy-soar](https://github.com/sunpy/sunpy-soar), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunpy-soar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6932a91e9e547fdf5f365e8787c88ff0360f1d6f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6932a91e9e547fdf5f365e8787c88ff0360f1d6f
│           └── chunk-001.nq.gz
├── blob
│   ├── 01137eaca076a239dc27a65d334ac6fc8307f44e.nq.gz
│   ├── 06cd7af5940d819ad8f273ec9a5b05e1da5d917c.nq.gz
│   ├── 07a838854819346e02cdd7fb84ae0770f7c54714.nq.gz
│   ├── 147bbeb71be9594f2ed94d05eb511e754b33949b.nq.gz
│   ├── 177b067fba090c996d6f9b6b3e25c831086d59cd.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 221f8feb3910fbaddc9d4fbe3d67bec77dd98f46.nq.gz
│   ├── 2d48c82441b1d37931132e4db08d909848750e03.nq.gz
│   ├── 2e647afafa62f54de30b8a60d23eca67c015f913.nq.gz
│   ├── 2edc040cace223aa61857a1663494a8e1124ebe7.nq.gz
│   ├── 31b9c1bfa1a3eecfe5dbb7ead1764297b3c9778f.nq.gz
│   ├── 350c895923f4521808b4958b2e6d0fa325dd2b9e.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 391ca9dc13f8fb82fead7824a6d87f09b24dacae.nq.gz
│   ├── 3a1862f6948f003bc1e7ecc41c8ab27da4a98fd9.nq.gz
│   ├── 3d9312dad2812647930c612e16cf87bc7615379f.nq.gz
│   ├── 3dbf373a566075f9a7bdd4a16df1ae239053d461.nq.gz
│   ├── 446a50ab3441849ba3c6e5cf33f477d69071c129.nq.gz
│   ├── 4fc8bd54ecdd1f7e4b05be0f1a0798f62a70e483.nq.gz
│   ├── 521babd6cf8abf6a0e6306e91c42efcb010407f0.nq.gz
│   ├── 53ae140401b01f960441530c7a800e3e2f56397b.nq.gz
│   ├── 595cb0a05000da0f1574c5a68018d4773ecd14db.nq.gz
│   ├── 6167971d67146f685c43c22ea524c986e62e4746.nq.gz
│   ├── 630d1e115435d865df139e35268b48667b29a094.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6bab13d2a33a0279ec46dfa095581ef816d86213.nq.gz
│   ├── 73872a169114f1a8920e4c24d371a0a1878db3fe.nq.gz
│   ├── 74b5a396c7ee9b74b2384f9812e81b0ef3db88bd.nq.gz
│   ├── 74d158a18913b1ea7e07c1d42b549809bbeebb6d.nq.gz
│   ├── 7d388e3ef17b14d560a2a08fa3004807ad0bcbd5.nq.gz
│   ├── 7f2177583dc65fd964140ed8b3a7cb1a87ae2d85.nq.gz
│   ├── 7fd7041da77d6a6c7f4d6b304c35db5c4016d764.nq.gz
│   ├── 809e85c0fc00db863907118a34400258a9300990.nq.gz
│   ├── 874af8b1fbf123025be8b0eb16aa36d63ee220ed.nq.gz
│   ├── 8fcd3990bbb17a8aa989df41f20490f53dfb3e0c.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 988debf51060eb223212788187f60b37891ac768.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── a3c8846c4c8754602c4096546f4cfb741c841df8.nq.gz
│   ├── a517f31f3da81db3843b75e5d7a96cf6e26b6386.nq.gz
│   ├── af747558f2567574346a326acd27ddd35c978e1c.nq.gz
│   ├── b6023fd8718e8edb932db7fcc8b5abb208b04737.nq.gz
│   ├── b6127463b84ebd01508d7e7d9074a9494922a296.nq.gz
│   ├── b8df50db8a5f0d386193618ea69e61c950fbcd9e.nq.gz
│   ├── bb68d7b3269f7b122c6919bbe91617bbff2483e6.nq.gz
│   ├── bd90735010badbd2e1835c9b650c3808018e4568.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── c99ddb5ec5b6cde00840544d2124ddce177c2085.nq.gz
│   ├── cfa7e077c76dafb8f838d6307636f8e24ad07f4d.nq.gz
│   ├── d3e5202b42dcf7ee8cb73075485307ac55de31b9.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── db2a7b189b1bcd07cec27c4d44df4991152b2e06.nq.gz
│   ├── e1c43fc0c889b9743ef1a2bf7636d854e400f4aa.nq.gz
│   ├── e5ef6f86902792b501956f1ebaf1faea48cc974a.nq.gz
│   ├── ea82948464f16bc2aba59e383c3d2129f9335a7a.nq.gz
│   ├── f0124edc70c46dc47eef58b13f0bb337f4cbd333.nq.gz
│   ├── f13f9aa4d22ba5a4f63aba39649ca3dfe361b6d0.nq.gz
│   ├── f835b677d68831559648f6d234d04d13592ed87e.nq.gz
│   └── f9332c7444d17413eb2a4df4375ebd9c08b56f0a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6932a91e9e547fdf5f365e8787c88ff0360f1d6f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[sunpy/sunpy-soar](https://github.com/sunpy/sunpy-soar)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
