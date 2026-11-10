# Repolex Knowledge Graph of ts1/BLEUnlock

RDF knowledge graph data for [ts1/BLEUnlock](https://github.com/ts1/BLEUnlock), parsed by [repolex](https://repolex.ai).

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
rlex download ts1/BLEUnlock
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2eeb35dcaa4e34ac994380e5dc9c0a692a6f7394
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2eeb35dcaa4e34ac994380e5dc9c0a692a6f7394
│           └── chunk-001.nq.gz
├── blob
│   ├── 022218ef8cdbd80986b73ec1a299ee7c5e5645f8.nq.gz
│   ├── 0227bea06bcf308698e2e574a012ecbd43b9f6ac.nq.gz
│   ├── 0297fed82b028b5a505429a28ca46c8eb01199b8.nq.gz
│   ├── 04d382355691797e5861acb4ef6f889c1d1859b8.nq.gz
│   ├── 08133a4579b986435e7f95ff293a6a1b8f89a6aa.nq.gz
│   ├── 08a046ac3f18c08b4cb4136876915d88a6ae0731.nq.gz
│   ├── 0999d757c19767877804c0d7f64f58ce22b4f568.nq.gz
│   ├── 0b7cdc43ab91018ea037ce6ebee0296f4b914480.nq.gz
│   ├── 0c67376ebacb410fd873cac1d8d8dd431b262c02.nq.gz
│   ├── 1376de24508528b8b1bf6206cb61d150a63b8e69.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1d30b3a2f3cde0f6402dd0a606db7c32336dc7cb.nq.gz
│   ├── 2be8c8197348b688a40db9dfabab6582b98400d8.nq.gz
│   ├── 314da5dfaadc95ca300e187109dd9f2103e7c620.nq.gz
│   ├── 32eb06fcaaa191930a174df37ec5449f97f02fa1.nq.gz
│   ├── 3434e16bac0bd6ab897b925298a5b365c4b9a0ab.nq.gz
│   ├── 37bc754a496d2d28029372ab2a29745c73ea734f.nq.gz
│   ├── 37ce87a6dec48a00bf93749a413e2753516bca78.nq.gz
│   ├── 384d80dcc7aa30b160059c47b0b6c6d3dec9e7f7.nq.gz
│   ├── 39910a7e1cff697ab77e5f250da088af810ff89d.nq.gz
│   ├── 49ad0bb0904a0646357ee8bc31e1a07d378f2f4d.nq.gz
│   ├── 4ca0820ac773036144a635e00d88759c31f0d556.nq.gz
│   ├── 4e75488cdb38a12b7df19cf43d9ecd9d58627571.nq.gz
│   ├── 4ee9c918b08d100d413a816364f5ff727bb6099e.nq.gz
│   ├── 515dfefc6a4f2fc843d9a2ed00207bcb7a44f5cf.nq.gz
│   ├── 56415519b062463a820ec458faf15e1ea4714684.nq.gz
│   ├── 5bc2c9f7ee5b2c1bf67a9b555ebdf9d5a197d457.nq.gz
│   ├── 641b2f7ae25bd3726fa94cf4d50bf9418534e2f8.nq.gz
│   ├── 66335542d9f9123800621bd6c39aba51bda7b764.nq.gz
│   ├── 6a5c2958c1dd7aeaef860dd49c8e9cfa45768e2a.nq.gz
│   ├── 6bc71d2aafd9f66ba27d01603d7aacc67baa1855.nq.gz
│   ├── 86fe9d4f7d094b22c801a8defec73c8c3f09cf45.nq.gz
│   ├── 8a6799b414684c50c04aa83bdfc147a3d453614b.nq.gz
│   ├── 96d18c132f0490ffe2685c8d5a3b716485f8f98f.nq.gz
│   ├── 9eaee0f74e20b5bf8163e349e5e887931029016b.nq.gz
│   ├── a1b38996ac26c8bb41bad1b702aa839be97ab954.nq.gz
│   ├── a40b0b74004f3c4498db69c924d700b3418f982d.nq.gz
│   ├── a59935ba9cf28f4db6001b81e1e95c0905e1a616.nq.gz
│   ├── a62ff6564085d9e7553bd88690aa7b246d02cde4.nq.gz
│   ├── a8713454721d764d76e5680af0e4193278fc3c42.nq.gz
│   ├── ab8a7ab47677a1c9793c962b16c798a347b62d97.nq.gz
│   ├── adb38d6c53b4523dba9be16be237d6887854e8c6.nq.gz
│   ├── adc1e697246d83dc0ac30c942178d190fc19cb10.nq.gz
│   ├── add5e5b0fa73d38bc6256c584b1745347eed8f16.nq.gz
│   ├── af1127e710298b5ea183649cd0dba195fd471507.nq.gz
│   ├── b2559a50a47252e6aa332887656a39cbe192d5f0.nq.gz
│   ├── b37fc88b276794054f4d79b06cc36f2f2fd92d86.nq.gz
│   ├── c2d1db9a565c830b2bd41cdcb6d572e25760e865.nq.gz
│   ├── c4b6a0eac17bf8ba57921e0fea8c0e937128ce56.nq.gz
│   ├── c7befb8b57b239296ed86aee8940e373ac9d44d4.nq.gz
│   ├── c8a0303ff8ce42209cd5652ba66f8595ae867478.nq.gz
│   ├── c9d978ef0a65fd8afcc2c9bd8f73de7b5a2b72e6.nq.gz
│   ├── c9e46088403232366c6354ac8d7e07a2ab0935a0.nq.gz
│   ├── ccc259e5c90d78b7f2818b55056442baa04af68e.nq.gz
│   ├── cedbed628a96e03edaef898e7bec07da4a3564e0.nq.gz
│   ├── d2d50b01acbfa282de88fc1b5c72986358483899.nq.gz
│   ├── d4e1d9546ad11a3b25200048a205b26b8b8d1072.nq.gz
│   ├── d607635c146ac1e3521295dec4f4129aa312e8fd.nq.gz
│   ├── def5847a148b869c81a8409de0d89114722e810d.nq.gz
│   ├── e3db5e2fbfead0abeac703c96833c86a2529d363.nq.gz
│   ├── e66d934cd563683f2b7c1dde1c6cee9d78d938f2.nq.gz
│   ├── ed1738ac6edf899e95b826125133a9ec5323f7a4.nq.gz
│   └── f06d168d460236975159e4ef97274a523c8708b4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2eeb35dcaa4e34ac994380e5dc9c0a692a6f7394.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[ts1/BLEUnlock](https://github.com/ts1/BLEUnlock)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
