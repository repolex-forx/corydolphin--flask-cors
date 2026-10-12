# Repolex Knowledge Graph of corydolphin/flask-cors

RDF knowledge graph data for [corydolphin/flask-cors](https://github.com/corydolphin/flask-cors), parsed by [repolex](https://repolex.ai).

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
rlex download corydolphin/flask-cors
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ad4f355791dc251227a48a35419f5f144e44a22f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ad4f355791dc251227a48a35419f5f144e44a22f
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 032d78249031cffa8ef39dbc15c23073f95dd807.nq.gz
│   ├── 058cfb76552d027f9be6211a32fac87dc01a2ab4.nq.gz
│   ├── 0a656b77af89cb1470228aa6aa7bbc2563c3a19c.nq.gz
│   ├── 11ead12c734ebaaf3491711288a69df3e56bfd7d.nq.gz
│   ├── 16926da57ab8655660926f0cf10438f060795097.nq.gz
│   ├── 173bdeac50c1d9c0d87ff05cf48b2265bdcfce04.nq.gz
│   ├── 17c21f85ab0ce452948bb1b17ddc0fd1e4b8873a.nq.gz
│   ├── 1b4ced389c5a7e69a72786b92705a6cb35152382.nq.gz
│   ├── 1e172142c438ca1afbb4ee627cbd7f1424c5a621.nq.gz
│   ├── 1eeb20a83a6798edf0b5554fa5723a99620e02f7.nq.gz
│   ├── 2041023b318b0d5bfb2df8ec5ac98bc523475080.nq.gz
│   ├── 255cd5c2d39b71e57ddc516da93d599d1234b93a.nq.gz
│   ├── 2a8fd11ad027db5ccbd57821340abdd8e0f21c14.nq.gz
│   ├── 2b1f9086fef71bf3d188e38333e63720010880e1.nq.gz
│   ├── 2c8b745bdabef0ca0e7f380abd6c2412543e0ca8.nq.gz
│   ├── 302d046b9c2bb40fe8a442a67d6859e2fc0501e0.nq.gz
│   ├── 3cd5881112b13571798544f9b84559c5c31703f2.nq.gz
│   ├── 4276148145827483a1c09d7d5b86ca193663f983.nq.gz
│   ├── 4f266ac642ff60314ee251000c9193d48b6e36a8.nq.gz
│   ├── 5e7e20ae8e1542876f74aa927e60ab80ce805a9d.nq.gz
│   ├── 628b3f887d33bd9a96b736d175b361db2e112288.nq.gz
│   ├── 6446a41697b86f5af6c39007429ea314295f36f1.nq.gz
│   ├── 6a6911127c8fa33b18f75b8ca0f2159ca6a4a911.nq.gz
│   ├── 6ad3a0074eacd16fc13a4e786a0b8d3b82549123.nq.gz
│   ├── 70c1a718bd9d0aefddcf755100f2aa59e04a450c.nq.gz
│   ├── 7140e474e68d2789c945ea4e2dfdb21c7d954914.nq.gz
│   ├── 7b6980d888c5b98fba536a8c991ed19699d10ad0.nq.gz
│   ├── 7c7e0c7b5fa7d6e47b6b5a53926b6a84c49f6fe9.nq.gz
│   ├── 849117ec8eb676438c14efec84740c11c2af8fd8.nq.gz
│   ├── 889b4accc31a47cdc016969f651b229e0b395534.nq.gz
│   ├── 89f4904299d6bebda661155e28c7acf95794cfd3.nq.gz
│   ├── 8c3a1532a849b4c4e4ce58dbc20019d81d7e1624.nq.gz
│   ├── 8ce5cb3493448e61b9e6fddcab1dff99779666c9.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 958965c14b10ab64b1de8bfeb89632f79de389dd.nq.gz
│   ├── 9cae42beeacf375ddd240d63dcf46dd05ddb393c.nq.gz
│   ├── a3c2be4fa95244eb1a2942abe13e278e8d7ffffb.nq.gz
│   ├── a75c913ad95cd8608bf7d7f60e7846895d9cba50.nq.gz
│   ├── ac811be27efa02ee35a08692c5aa9c7a9d1ae4ff.nq.gz
│   ├── ad9c6056d174f7d80d1d4d55ee4ded9adae79d92.nq.gz
│   ├── b49a2c9711a21f0f0dc6fc6a82bfb18b12b23b30.nq.gz
│   ├── b55b01d18956a6b23a9f870a8a37ee7da4ef3519.nq.gz
│   ├── b6cfa59948ee9052ca2484c60a38220ed74b5a69.nq.gz
│   ├── ba0472df100e75bae21fc0915f2f48f48182cb29.nq.gz
│   ├── bd07887c80569dfb9994a9c2b93f4aeddd6de6ca.nq.gz
│   ├── c5b9b4b70f749d37eb3c37bd266c943b5d6c8cc6.nq.gz
│   ├── d3c883d4bae12cbc5f12e09050f9268b25cb587f.nq.gz
│   ├── d8c5e72d2cb104b37f1e197d6883d142909db77f.nq.gz
│   ├── e498fe444e5db2d248b8d1527d855b97e2899f75.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f1bafd4569ce3d40fa876bcb3d6297eaae36d070.nq.gz
│   ├── f5b8d18f43ace36caa8a0fe1722b6778a4f9164f.nq.gz
│   ├── f76a1cd9b23d43baececa2b2888f34fa9d1e37df.nq.gz
│   └── fc4929500539718df6f86865de53166ac41072fe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ad4f355791dc251227a48a35419f5f144e44a22f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[corydolphin/flask-cors](https://github.com/corydolphin/flask-cors)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
