# Repolex Knowledge Graph of gruntjs/grunt

RDF knowledge graph data for [gruntjs/grunt](https://github.com/gruntjs/grunt), parsed by [repolex](https://repolex.ai).

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
lexq download gruntjs/grunt
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8372e118eb8c4c6d40e9c6c5684948a786dee8a9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8372e118eb8c4c6d40e9c6c5684948a786dee8a9.nq.gz
│   └── repolex
│       └── 8372e118eb8c4c6d40e9c6c5684948a786dee8a9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0253333077399f612930ea6c8d859b46ea119b44.nq.gz
│   ├── 098e7b84a14bcc74d1edef7e20f2ba56c49c01d2.nq.gz
│   ├── 0a17765d73ec8b5d223d66adc16b1568bde9a202.nq.gz
│   ├── 0b68cf0db542d3d778d8d1a31154f51ed5521075.nq.gz
│   ├── 1252f54a96fb1a3c53826a92775a4f62b695a91f.nq.gz
│   ├── 14c7029ad2c94743d9a67bb35259240386822d74.nq.gz
│   ├── 15e1fe10b94d91d6b82b668b4177137945332695.nq.gz
│   ├── 19102815663d23f8b75a47e7a01965dcdc96468c.nq.gz
│   ├── 222ba621bcddd9308173a887901e71f0be157010.nq.gz
│   ├── 2e4e0c168202f55cede2ec57e4c8b0689d633926.nq.gz
│   ├── 31e1dc34837bf98ac844f219c73ce441e6d02b35.nq.gz
│   ├── 379162011c2fc088958090f82a5f6cc8d7be371e.nq.gz
│   ├── 382fba125b0287611afa11af08a8929b99c45110.nq.gz
│   ├── 3870b3f4750aacbeb1d296b46592a52e441090dc.nq.gz
│   ├── 38725bf86c0dee6dd5aab2ca24320454b9affd60.nq.gz
│   ├── 3a519f6491f6880787b25dff69c615120b7e8497.nq.gz
│   ├── 3f9538666251333f5fa519e01eb267d371ca9c78.nq.gz
│   ├── 44a2ea0dce95f857a9b61a1fde4e82c529b3fa36.nq.gz
│   ├── 5d08cc3879a0bcb62e516656f4b929150e4ec64c.nq.gz
│   ├── 6024b19ede9ba89cd1965ee0262b10488940b020.nq.gz
│   ├── 61cf35dd0eead8e38d473a63cbf13c3125de3033.nq.gz
│   ├── 62b11566754d5be57c9515a45274711fa4c66879.nq.gz
│   ├── 631e249ac9b15fe1af949ae1ead1624eb2adeb48.nq.gz
│   ├── 78df5b06bd324da777762461e147ff3e4c72fb1d.nq.gz
│   ├── 78f9d6bb9d5f498c3cefbec37d9fbb097814df98.nq.gz
│   ├── 7eb7321c688d18c802422cffedf5e86978295161.nq.gz
│   ├── 7ec1027d4609b406927f7fe10d7bb6062ff4f294.nq.gz
│   ├── 855f17f872e37f7ad1edca751cae13886216aff8.nq.gz
│   ├── 8c18257f8e6794c3b88ba10e1947938ad1925c3b.nq.gz
│   ├── 8cfc6470e2ddcc64c9e490b3d10749db690f62d8.nq.gz
│   ├── 8de3ba72d5de52acb3834c8a67dfa6ce260e53ac.nq.gz
│   ├── 8eb853f3c8be34bf8f5fcd8dd37b1f689f173910.nq.gz
│   ├── 919d3d703db8e5eab1caab91bb4c8693e407830f.nq.gz
│   ├── 9619e80838e7420284ecc5ed18c6107d2eeb7bcf.nq.gz
│   ├── 99342d672223f440c0f5d3319890d34677eb3578.nq.gz
│   ├── 9ffa44405bf16f1f36dd28ce98e42a92d7f73b8f.nq.gz
│   ├── a2f31225c2eb20d00018731fa995227c873b549f.nq.gz
│   ├── b592341c6eaeaa4b34f91e7b1b2b967aa4fb5477.nq.gz
│   ├── b869cc121242e07856833b771dbfaa8a3f1a2dfb.nq.gz
│   ├── ba0e162e1c47469e3fe4b393a8bf8c569f302116.nq.gz
│   ├── beb5036d7cd5c0e873d3fa65a90c975e3e0d9365.nq.gz
│   ├── bfb4074f16f8975c631f51601d320b20422def51.nq.gz
│   ├── c4a1684464c7ee0e128dd05b1b3a830b5b4c8957.nq.gz
│   ├── c8359dc85ff70297f270004b3b798a3a653fb1dd.nq.gz
│   ├── c8e3c04d4368ba1812b84c3255c07f8dbb3d15ed.nq.gz
│   ├── d087677af564184ccafe5d5c8302b3442a539be5.nq.gz
│   ├── d10e97537838512c6c0c2f2cda2e5d43be863b6a.nq.gz
│   ├── d1f857b3cc128d202d3547d90541d78e7761853e.nq.gz
│   ├── d2ad44c7ab463bcb5e1d2fc0e13f3553493c6cfb.nq.gz
│   ├── d39ce1b0285a3f117fa06aaf5ffc0521f264ef51.nq.gz
│   ├── d761ef56506e648c83e400562ff6c292c8047751.nq.gz
│   ├── d9d1a3b26b397f49130c742ffa3033163c644632.nq.gz
│   ├── dba8d833e9fbab368cd6a1763f2dcd08bc285830.nq.gz
│   ├── dcf8a0c01b35b948c1a3d80cd2279d1879914444.nq.gz
│   ├── de5fb74e5ee45b3d9059015345faebbdd90ad7f6.nq.gz
│   ├── e03b5f137c7988e9ab70603995e78fe1abc17c30.nq.gz
│   ├── e188b47388264c3cd6c681835bc971d7411c04f8.nq.gz
│   ├── e1fde7839a6e674eaa894701dab586bc6098c2cd.nq.gz
│   ├── e2db6cf12571c86c1601e5c956d134a234b8ffbd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e99ca6d3740f26b56e4c0b06ffeb0d909aa702f2.nq.gz
│   ├── eadbdb40bcbb22ec0b97b5932134542254a492c7.nq.gz
│   ├── eafc577456bb832e70d2a20bc63776f8e99efd13.nq.gz
│   ├── ef2bf80945ac7dc45d48c6d15915f401d731a2ef.nq.gz
│   ├── ef55520eda9cc6249a02fa572e4dfc898743f65a.nq.gz
│   ├── f688910ec09319ddff49cf9be29b4230bb146812.nq.gz
│   ├── f8ff08c9bc994de1aa0dea3eee0c928e10f73adc.nq.gz
│   └── fe6ab8b06f389b41e5f3f5d580dbc0c80fdb4aa3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8372e118eb8c4c6d40e9c6c5684948a786dee8a9.nq.gz
├── filetree
│   └── 8372e118eb8c4c6d40e9c6c5684948a786dee8a9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 78 files
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

[gruntjs/grunt](https://github.com/gruntjs/grunt)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
