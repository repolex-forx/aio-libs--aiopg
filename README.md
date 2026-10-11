# Repolex Knowledge Graph of aio-libs/aiopg

RDF knowledge graph data for [aio-libs/aiopg](https://github.com/aio-libs/aiopg), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiopg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eabd5216c0adf7a131f79d028af9810c99e9b8ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eabd5216c0adf7a131f79d028af9810c99e9b8ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 034b93302206a72b6986b943252b8da2851204a4.nq.gz
│   ├── 036731a59cf34f883c397f6c6a3fc1900c9ec78b.nq.gz
│   ├── 07917344d0d0e022e52cc0901a3b19532efbbb17.nq.gz
│   ├── 0ab63f716662c3a50085f06b273eadcb4f92a0fc.nq.gz
│   ├── 0aff1dc4787406d6ae42d14f32067d3b75496b9b.nq.gz
│   ├── 0c4539fee6d1e46860fa41f1018ef8846d723bed.nq.gz
│   ├── 0c7ddce5fd7a28c626c7dfd047f08efbfa81d21a.nq.gz
│   ├── 14c574261eccdd85bcfd152abfede515f88971d5.nq.gz
│   ├── 15addeabcdcd9807ebc983cb96c75893bb2a8d63.nq.gz
│   ├── 1e1c456619c504f52e00fafa3adfd4d85bdc6b60.nq.gz
│   ├── 20bb09cc6ca220a0a2876880d777a0894a910738.nq.gz
│   ├── 2100dd89c00003142fb21d30d81a5118cc0c2918.nq.gz
│   ├── 24e62ea836486df0dedf272ef7427b2ef96ced89.nq.gz
│   ├── 278be6526f4c313b35ef05ab2e954e543b95a370.nq.gz
│   ├── 2da23669ebbe41a5a218942b789c8239d7a98ae8.nq.gz
│   ├── 335172845116f2d5a016d23e00e0f703bb0039b2.nq.gz
│   ├── 33a4c6f1267fa432c48731b1587ad30c9ae05f26.nq.gz
│   ├── 3ba87bcca2919a1f3692b7e885ad7c524e4ee4bf.nq.gz
│   ├── 3ffde3b30287cb8030055f7c6b017e00dd3d93cb.nq.gz
│   ├── 4079932ddbaa0404338cbd391eb2e0fc3a23d3da.nq.gz
│   ├── 43cc9bd6f80abeee141121493cdb3b83e58346f6.nq.gz
│   ├── 43eb20b6e6cd4e92f24e662b219115acc9627fb7.nq.gz
│   ├── 452c9af9b2da423dc8242d0e8f3c8e1ac27bb4ca.nq.gz
│   ├── 4c00139d378d2a329e51ce4c181b151aca5942f2.nq.gz
│   ├── 4f8c6e48204b88edbcc22fcfd1bfc6cdd8c4858c.nq.gz
│   ├── 553c6a50411ad725fc2eb7df354cc5310a863251.nq.gz
│   ├── 62e11c4c22c496a9d7e43fa5fe3cd84696174fb4.nq.gz
│   ├── 667a949ef9874be40c9f30e283c2f81fddd0c1fc.nq.gz
│   ├── 682395c3e6a318ed9d732c338bcb548f6aa03427.nq.gz
│   ├── 69e550ab5b5d5fe560975f5d4893e043253b54e4.nq.gz
│   ├── 6a43c191d349820a399c6087db9cbb8f41ed9d73.nq.gz
│   ├── 6e5ff50268172c5ad17bacb169b78c3429d47adf.nq.gz
│   ├── 7141815690c2278373e7ed861f122e67a941f6e5.nq.gz
│   ├── 75f971166aa4063943ec9c92aed81e04aac28046.nq.gz
│   ├── 778edabcf51e371ed53e0e5fb5c1f26feeb72678.nq.gz
│   ├── 77e2e204c67a2a6d0f2778721107c20cdaeee6e1.nq.gz
│   ├── 7a1acb481d62ac737f206f713d03bcab9a095042.nq.gz
│   ├── 7bccef6f9051b345ea647a6a7db1feebbfa40b11.nq.gz
│   ├── 7d0a389fed886baf09a14a37e950606dcbb4a00a.nq.gz
│   ├── 7e4a9f3f5581466d6b4b8174ece3b7df2bcfab56.nq.gz
│   ├── 8369426a3488c53cc3e74e91d1f806e807b33b13.nq.gz
│   ├── 8a9c4983aeb177dd01707dac13512c56315d5e4c.nq.gz
│   ├── 8d45834f70959f2cfb3ce6764bed904a27441557.nq.gz
│   ├── 8e147de555cfb4fe2f255b3ad9f67070b8f07440.nq.gz
│   ├── 9277453f6b6458e4cb4cb100ddc16c3236ca2b4b.nq.gz
│   ├── 93568bb54c56969489e08a5dc19908b03770a1e0.nq.gz
│   ├── 96191c097755e171e4a9e9bf1616accd8960c79a.nq.gz
│   ├── 985ba45bfd5b24433c89584f519df6e114b26f2c.nq.gz
│   ├── 9a6382491a8b76e26c2bcba10cd76dc4f1439ebc.nq.gz
│   ├── 9c82138157b30e8de0065612889d3a9ce2d89ead.nq.gz
│   ├── 9c89c62198124eb7c66aebc5668747863e7d96a2.nq.gz
│   ├── a8a2d519f823fb7d7634310d7b856b9b9dd3113a.nq.gz
│   ├── adcaddc77a345fca92de8f92bc46441c06a008d9.nq.gz
│   ├── b1e4edca7e67f7db4d7c97690f48e15fc38e4aae.nq.gz
│   ├── b60c05af520aff5e58d363f987fb6831d2b23364.nq.gz
│   ├── bdd303797a9766dc812a70646ead585f0dbbe215.nq.gz
│   ├── bdedbf9c9d081c8d242ce649b36bd2f04fc8e83b.nq.gz
│   ├── c157817e2d390d0bc1c6d6c9ad17aba118cc03fb.nq.gz
│   ├── c3c25e76be3bbcf7a986755674b6204ada270215.nq.gz
│   ├── c61db4d6e39d2292ecf7544c5e16991c3e7bceec.nq.gz
│   ├── ca32bda0e8473b1b0757239f57fdc6efaa9ba516.nq.gz
│   ├── ccfe1334bed6023fde3a606de5a3154dbc27d448.nq.gz
│   ├── cd161ecff4603855cbd3637bcc85017c77abdbee.nq.gz
│   ├── cd6ab3b8be28655a3fc0f844696aa447f48dd1db.nq.gz
│   ├── cde0c6b8176bacef37bde063bacf22c463c0d832.nq.gz
│   ├── d1f720c2eedef9e45b8854ac24f8c10deefee8ca.nq.gz
│   ├── d662d286996c9a1e2cf5f5bbc01b4dfffa8ea470.nq.gz
│   ├── da44b9c8a7cb8f0a0883099731fbbe49261aebba.nq.gz
│   ├── dd2a8a4c927d35db2f302ac86f06c207c3cde0d1.nq.gz
│   ├── dde974da14b887340b62f10ed3a4ffc1277a0334.nq.gz
│   ├── e1d4ce4caf9052c65f079b3f9f58f8abd5d3477f.nq.gz
│   ├── e23f77747d3d9dd958673cc4fb96ab7ef837e57e.nq.gz
│   ├── e313bf073eb1ddc75b3e4a45414912d5d71a0cb5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee0910801c3c2e5390211ae12d87b6ae6a328c8a.nq.gz
│   ├── f1041efcef8419dfd8434ed269b79ceba70135f6.nq.gz
│   ├── f361a61976e5ce9072d79857b193e767c18eb1a7.nq.gz
│   ├── f38233d65288bd3003342a9d8af62a3b080a7407.nq.gz
│   ├── f71709bc508f6f69471e2d95fbaf1e7c77a5c746.nq.gz
│   └── fcb43358ba56d4f23a34db1adafedc6ddb96df27.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eabd5216c0adf7a131f79d028af9810c99e9b8ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[aio-libs/aiopg](https://github.com/aio-libs/aiopg)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
