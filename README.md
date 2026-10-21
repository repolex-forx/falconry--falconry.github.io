# Repolex Knowledge Graph of falconry/falconry.github.io

RDF knowledge graph data for [falconry/falconry.github.io](https://github.com/falconry/falconry.github.io), parsed by [repolex](https://repolex.ai).

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
rlex download falconry/falconry.github.io
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cef774f9b3a966d2053ee59a3ac8370d96d5fa91
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cef774f9b3a966d2053ee59a3ac8370d96d5fa91
│           └── chunk-001.nq.gz
├── blob
│   ├── 030147ffc5fb27c883456a1fa4e16a7e58aa4f78.nq.gz
│   ├── 0988a52f8a3ff5d05ae4a9470dfa91a7ce8a7047.nq.gz
│   ├── 09f874624ce0f614e4d52c6dc55ad4db0da67d96.nq.gz
│   ├── 10ca2ff2a38153d932e5fda6169d93b013649869.nq.gz
│   ├── 16bf1734e2c9d73ecdbab1f885c6f3f5af136fbc.nq.gz
│   ├── 237be2c6a052286c61de8e501ae0afbec3fa3b8d.nq.gz
│   ├── 237fb85adf9d3563b4701e63bbb3f88946f754b8.nq.gz
│   ├── 2b68067abe563b3961a639631ec2c7d6673f70a7.nq.gz
│   ├── 2ce2b891a8019536fb298c920dc29d5918aec5ef.nq.gz
│   ├── 2ff2032d191f3da25ce36d5ea14e795879119472.nq.gz
│   ├── 39da2e7dff93ec1fa3dd9dc93d4de46da3c3cbff.nq.gz
│   ├── 4364954a766ff115e32a7d07df13faf77ad3c8b2.nq.gz
│   ├── 465f49b85ba0d49663be02d9c1080ca7cf04b948.nq.gz
│   ├── 4db4f88a530908e8289738220fc44bf3f3724f91.nq.gz
│   ├── 53ace0b4f2ad21d8733ee0c898592ab630639b53.nq.gz
│   ├── 55bf3f737c24abf7c8dc1e287a400ba6fdf51892.nq.gz
│   ├── 589e98d4b64189a0630de2e31c0d854f9774fad3.nq.gz
│   ├── 59028091e6fa337e2e5b77e83fc790cfdb4ff46c.nq.gz
│   ├── 59144c53181b390cf4f7f092ca318f3dabc0263f.nq.gz
│   ├── 5e4e075bd68565682e9260607929dc467bcbbc53.nq.gz
│   ├── 657bc83c518a5f412847e3406980d3d1f716a798.nq.gz
│   ├── 6604ebc08aae51e8f67312fbd6e43bdc533ae47f.nq.gz
│   ├── 66cb5b671c8cbb79374edc6783c72f4e51498f03.nq.gz
│   ├── 677f5142dab202676df2457ccd6a5bacb52af6ff.nq.gz
│   ├── 6b8b675f35aea49ae35f5e4651dfab94a6bdb529.nq.gz
│   ├── 6df3751fea2dd313ae4546ef6f20d81d37a874b4.nq.gz
│   ├── 6eb127bda3b37acde9c0c5d676700034b1fd12d9.nq.gz
│   ├── 70ac384f1c30cef7deb05ccdf6a37f45597761ea.nq.gz
│   ├── 735fd062dbfb310a5546d65a50b5d1781bd52162.nq.gz
│   ├── 777e9f0a226ec82a61c1abd21f991ad4db9840e8.nq.gz
│   ├── 798e3a2211687fb19d3b29f2269f8f560f234c35.nq.gz
│   ├── 7a0de7f1422849d28c9217ef8a726e04f375bde5.nq.gz
│   ├── 7faa49a72880d815ffaee71482cc874317692032.nq.gz
│   ├── 85b54fa79925df8f2d97c3530bae5a58d03ffaae.nq.gz
│   ├── 8a3ddb63cf26faaad3ca770e09b98fc3280fa8d8.nq.gz
│   ├── 922ed14488e1268537b2218c9d002e1dae53b6ec.nq.gz
│   ├── 93108bd98b171386208efd8fa8a0af2ccc74a4d5.nq.gz
│   ├── 99c42c65411f53e22b63d2464cd3bb90f79501b8.nq.gz
│   ├── 9e05b1cde7a41f812946b83d3650a342a4bd3d0a.nq.gz
│   ├── a53dcbc7d28eb8493a1f1f3f585a67e4109d6d73.nq.gz
│   ├── a9a4d2b04239c82c3dc05ed1186d41373897d7cf.nq.gz
│   ├── ace82112901c5b0e2f37b5598bb82c96882e7d26.nq.gz
│   ├── b38d3c07fe07104dfa15cf14df0596cf3e1cce01.nq.gz
│   ├── b46fad676853fdf3da743ff04d533fcb4b3a11a4.nq.gz
│   ├── b53d722016a908ffd3261635fa57860aedfa1039.nq.gz
│   ├── bcd2ae0540252d9a4abdfb658aeb0d8ac461bc0a.nq.gz
│   ├── be7414dde78d8afd5e14d2c25547cb6e0c2b2bc5.nq.gz
│   ├── c0fc1fc595baff9ddea3b384993c78b6fe767dbf.nq.gz
│   ├── c141e878b168f96a695224a93aeaaac87f76899e.nq.gz
│   ├── d0e5f1be6bb0124953f05108e71171eb531e46f5.nq.gz
│   ├── d4e69ec2170937a2cef1dd04bad27b20ad2b0f85.nq.gz
│   ├── d6b189c5ad184440bd25677b92c87b21c25fa81b.nq.gz
│   ├── df1bca596f2bd0def9140b31b78ba08a7260dbdd.nq.gz
│   ├── e58cea9c863eda7a49acfecaaa9e81aa3bd74d07.nq.gz
│   ├── e925efd5eb49b7faf5c6a9ff12d79d744fdccb57.nq.gz
│   ├── eff0a9771ca8f0586c0e67f455bec04b50324328.nq.gz
│   ├── f4bc72ec51351125ccae4a708a832db8bd467ef4.nq.gz
│   ├── f6d4b7369eb46d9cc68eb6e40cee24a3210f4692.nq.gz
│   ├── f8896003d4f0bb1a7b4fb943c6e45d6608215c81.nq.gz
│   └── ff3f825d09226980063bb10499838a5bbdba4abd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cef774f9b3a966d2053ee59a3ac8370d96d5fa91.nq.gz
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

[falconry/falconry.github.io](https://github.com/falconry/falconry.github.io)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
