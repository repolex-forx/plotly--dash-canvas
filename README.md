# Repolex Knowledge Graph of plotly/dash-canvas

RDF knowledge graph data for [plotly/dash-canvas](https://github.com/plotly/dash-canvas), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-canvas
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f4df65b43acb20bae7eb34572ca240dabfbfb72
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f4df65b43acb20bae7eb34572ca240dabfbfb72
│           └── chunk-001.nq.gz
├── blob
│   ├── 033cfcc1a111f12240a1c72b7d7eda6854fddd4b.nq.gz
│   ├── 04ad9247c199ba2e56fa47654c8f707df2cbad2c.nq.gz
│   ├── 051e84224523e6b363195b34c7a5bd39b30e090c.nq.gz
│   ├── 05cd81159f1d1eefa6d41bce81310798fe15b5b6.nq.gz
│   ├── 0b6a3a62ad23d814597cc8bf8166040b1ce29f40.nq.gz
│   ├── 12789e504be884d8f529740338de255d3817929d.nq.gz
│   ├── 13b646086523888f9137db19aeff3bf27fdc33b1.nq.gz
│   ├── 14597d808b916a54088c8a3a8eae0e4cdb142d3e.nq.gz
│   ├── 1ad8aaf0c7d474daf194afaf16740d26c9cb5067.nq.gz
│   ├── 1cb3958c8d0f012bb2334eb4ee761a7959d3dfc1.nq.gz
│   ├── 1f6660731cdf8c1435ad45c8e0c037d266508822.nq.gz
│   ├── 1f7b1e3db27ea460fe6e20885b82fd32f03fda70.nq.gz
│   ├── 22cdcd5f1c565958cac857163c9ac2269d560c68.nq.gz
│   ├── 232904bcb88c9af88999505b1cb128a957e5afb6.nq.gz
│   ├── 234fe2c75a5ddc1a30c51c94194f3f8e813fe29d.nq.gz
│   ├── 23e8052195526ab3a845394a868549a1800edac1.nq.gz
│   ├── 26701eedc9ec905219dec1f89a3af4f6cc0715b3.nq.gz
│   ├── 27e21ed03c397050d69499329c4c489c0b3d2dc3.nq.gz
│   ├── 2bae4311604b6cdd732bb4624598c144f1557861.nq.gz
│   ├── 2ff2c3db521ddc6b370ab0282ff3ae34fce12e49.nq.gz
│   ├── 30dc161dabd43edd0707a52a9648be9382d4f812.nq.gz
│   ├── 337d135104035e26ae2f8f389b9e0cd4afa3f4ed.nq.gz
│   ├── 372d44271d5a32dc3671a7c4af0d1890206585ed.nq.gz
│   ├── 3a7ef6b83b9c3187f66f1d8de7016e57477abdd3.nq.gz
│   ├── 3b1de0329c8b820aee2657255ca6c6ab358a4d16.nq.gz
│   ├── 41ecf647cb0187625f43cc651d8c0ba89257f712.nq.gz
│   ├── 474313f58ba1a2aef26e8d940589c98063cdbb43.nq.gz
│   ├── 49263c7d66402ef22546a85b1d3bcdd8399aaf64.nq.gz
│   ├── 4a8b0edf106be3083227916b26cf0a4ae24adbed.nq.gz
│   ├── 4be2196252b1100409c90fff9b503250464c4714.nq.gz
│   ├── 53fb37df533d4b46915628664f58278764761308.nq.gz
│   ├── 54374cc3ece646cf6cccd178259bb2a0f8dfc6a7.nq.gz
│   ├── 57bcef1b03d75d220afc410032b29aef54d3476a.nq.gz
│   ├── 5a9ac4bae655a227d4d51052f329cd200b093329.nq.gz
│   ├── 5e8fdbbc1c6ad9690cc21c40ae158dbb47d40076.nq.gz
│   ├── 61231eac92be2aec51fde71efa6663bf8f6c3e2c.nq.gz
│   ├── 6215814006f2ef0c3f1a14cf0a92e855e8b0ae46.nq.gz
│   ├── 626d012fa0e6c2750a67de9ebf94d3022d17a015.nq.gz
│   ├── 64239bb24e3505b0a663f1ea3f33d9283227197c.nq.gz
│   ├── 69227a1441391203ed75813a57d3ba2158eaf647.nq.gz
│   ├── 718a40405b5808d7b8af037169fc2a32bdd8863b.nq.gz
│   ├── 7540ce0b51729ea327aa649e09b7ea32496e5e61.nq.gz
│   ├── 765b2b1768cf2c771482dee6250ba9be512562dc.nq.gz
│   ├── 77e01ec7c8049a1040507cc46d33434dcd060c89.nq.gz
│   ├── 7992cd57935a64f810ef5cba2af0bd5f1bc4b546.nq.gz
│   ├── 7a6933821bc89692f3e1cc766fb0dc4414044c52.nq.gz
│   ├── 7b0a3cca86b8b8611e70035391d87b5c2cb4eeb7.nq.gz
│   ├── 7d1f058f66580489804a8021572d9d98265dd07f.nq.gz
│   ├── 7e3735aad9529d3f068a780041bedec5e8b62c29.nq.gz
│   ├── 817dd00b301c7cb6e0739f76b473db98b46a00e1.nq.gz
│   ├── 8394bcfeedc45962e96c0eb6f99d977d1ed82db3.nq.gz
│   ├── 882082356b27732419659ad9c1b5e4d44779dea8.nq.gz
│   ├── 8bbe21d8a4eeaeb724888ab551dd6aba1c164618.nq.gz
│   ├── 901e06e4e6d6218c518647c288e0769874a08395.nq.gz
│   ├── 9728bb37253c9b975f0f6407325473a2f603318e.nq.gz
│   ├── 98aa7c79da1754b97c57856c4bb5bf7ca63cfc36.nq.gz
│   ├── 9bacdf1e584d9f77e191ac746d1e0a1f56148325.nq.gz
│   ├── a43b352ef7a4fe26caf20fae9263c81c5d8510a3.nq.gz
│   ├── aa2a41947ef4055caf8ec143149c5f7440b09c04.nq.gz
│   ├── ad999f98cbe284ababa076651c4866eb21ea46c3.nq.gz
│   ├── b06b2ce7b6764586a561d11db23aefbe99256bda.nq.gz
│   ├── b0cfd28bc06bc73d61b8407b2b01f6c235d7b848.nq.gz
│   ├── b597a44232c2a3b77943c95857fa5c6075cf69d8.nq.gz
│   ├── bc8371522911dae5c57fa15028a9c84eeb316709.nq.gz
│   ├── beb1cb74a2e666548c765a46656e003f78666c91.nq.gz
│   ├── c4ce1bde2836f6461994b01a0c2d2b32b147bd4a.nq.gz
│   ├── c6c85eb3e7ef23326ccdc5b7409aadc24d741335.nq.gz
│   ├── c834fa224cc2ae47d8239b1cd73d51b83570ea34.nq.gz
│   ├── cb18819df18f418671a7264f642fc4ad9fe6e76e.nq.gz
│   ├── cbd4b98b4dcecb526048bff487b18dafb385801e.nq.gz
│   ├── cbfd88be48adab655c57233dcfa5737f17a0fc9e.nq.gz
│   ├── ce72b69dd50e80aa2b8dae3eb2a997c9cf9c9cf0.nq.gz
│   ├── d076c247e0095f5af635c708c12ac4f113e1b4f7.nq.gz
│   ├── d212e40a851da9e88973b3c8b44db9baaec6e90d.nq.gz
│   ├── df33a3b49eec730827a736b49194566e9516944d.nq.gz
│   ├── df867d0f8984719afb6c3024af18b9276774643f.nq.gz
│   ├── e396cd63954ea9050b656fc9baa5e0bd9a342322.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75380ed39f237fb68728d2fce7b62bca1cf4f4b.nq.gz
│   ├── eb81a49a94228fc85213e5bd9c8d45722b89887d.nq.gz
│   ├── f0a9be6c891c21630a418f83370c9fbef4b955eb.nq.gz
│   ├── f3ef06880d813b4ffccf9128c602fd4028e6039b.nq.gz
│   ├── f603ba72e4dd86f543a8af579a4af32c74242eb8.nq.gz
│   ├── f8256a76eba8d16e9724f15f9bd58fba3d795240.nq.gz
│   ├── f9622ca1f6f77b58c88cb4e39d1b6586bea97567.nq.gz
│   ├── f9d9f5a40344dac38d80b431dc883196bba18f62.nq.gz
│   └── fcf1f6065e15e81afeaa2cc03252bcf830a61382.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4f4df65b43acb20bae7eb34572ca240dabfbfb72.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[plotly/dash-canvas](https://github.com/plotly/dash-canvas)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
