# Repolex Knowledge Graph of argilla-io/selectra

RDF knowledge graph data for [argilla-io/selectra](https://github.com/argilla-io/selectra), parsed by [repolex](https://repolex.ai).

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
rlex download argilla-io/selectra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e903cce13cecb06fcb6914a398cd2fd72595a705
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e903cce13cecb06fcb6914a398cd2fd72595a705
│           └── chunk-001.nq.gz
├── blob
│   ├── 0e8a5c59177938199543e77f21ab593cf2c5033b.nq.gz
│   ├── 101852e980ac0a380e766a31b97ee862083deba1.nq.gz
│   ├── 131d48f1c55bd9739a54f5e9368de041ec4b6522.nq.gz
│   ├── 2684369c9684a0735e9b72f189eb3b3877ddbf13.nq.gz
│   ├── 268b88f3d8ca5da7520680c47384838945b5d46e.nq.gz
│   ├── 29e362195f6ae65e340d164a3222dc144e7777d6.nq.gz
│   ├── 2e8df0573ea66e81554ccb7596731c0fa07ed5ea.nq.gz
│   ├── 39068819cad600db03b787e7d7b652136db2cb62.nq.gz
│   ├── 3991666124c5d022e63202e6fe7b0224a1a45b56.nq.gz
│   ├── 3f5ec7ff91056782d3336d1b2b9375406b76b3f9.nq.gz
│   ├── 4241467eddcc96d95c06850ff13fbaa2e3739acb.nq.gz
│   ├── 49a544196f20fe5c49c5f568941984c7839f895e.nq.gz
│   ├── 4d8d8e979325f114339d481ed9d3632f94e0ffa7.nq.gz
│   ├── 5156c6fec2db4f2c5533f78c6fae800340b766cd.nq.gz
│   ├── 56561906b22cb7951f57d169f8cd90ee4954cbc0.nq.gz
│   ├── 57358e23ae8d4ca4bbf2fb97eb65fec3305aa861.nq.gz
│   ├── 614196e9da6eaceba2d90277aa4d5040673f6448.nq.gz
│   ├── 6545fb2ee439020bcc8f4cc9c396890ed5528884.nq.gz
│   ├── 6924e2cbc70296894d5518c640883c7688b6a464.nq.gz
│   ├── 6c34f48d38a49f59cb3df52fc4c9b0e41cfef1bf.nq.gz
│   ├── 74c6de333cfd7262cb1702647545182347a12008.nq.gz
│   ├── 7b3dd23a141e0fe1c4707b18cc48db115695b7b8.nq.gz
│   ├── 83039d546be8867fa3d2e5f2d0396c48378ea45d.nq.gz
│   ├── 8593698586873cc966a918613a17db2918496ddf.nq.gz
│   ├── 885945854a00f265b8971182fac70ad67e63b7af.nq.gz
│   ├── 885fc1ed6256d966b2071d9e3ec94afb9c9ab6f1.nq.gz
│   ├── 8dea6e1fc3f39616e941504804cf5fa71f2091e6.nq.gz
│   ├── 90f80f33cc5048f626f9222d3599b94e1a871dd6.nq.gz
│   ├── 910f383a299ca717516da71d73d466d59ac35532.nq.gz
│   ├── 920dbb92470c2a45ff5b5ece8130d877373b55ae.nq.gz
│   ├── 93fc292da16fcb19492970671965f5a73d38b1e1.nq.gz
│   ├── 9b26ce00f103130bb641998d3b0a8bbde26cc41d.nq.gz
│   ├── 9b6dc3cba0cff229df2fcd9751ccadd2ea9f3995.nq.gz
│   ├── 9eaaee29cdeec6df6dfac7998e16c1e542aa8b68.nq.gz
│   ├── 9fd489a6ada05b2e1bba8ad095d2a0ead7a587a8.nq.gz
│   ├── a7c580a361099b2ad902c6523cc5a97c35bbef35.nq.gz
│   ├── b5f670463d24f37187c1954a212ddbc7ec344feb.nq.gz
│   ├── c42f950111c2242cad857aee59db409d08773c86.nq.gz
│   ├── d1fb190d10f8f7586c602e8be710b7619d02c03c.nq.gz
│   ├── d41c1444cb75a68dd6b0dd13cf97f2377ec85aa2.nq.gz
│   ├── d67f5b1d5a4a1dba2d5cba0d7702116281a481f4.nq.gz
│   ├── da12c9bdc062babb3fc55af04ed736eea34d5ce6.nq.gz
│   ├── da38249a3c469670db776e7d7a6472c59b87597f.nq.gz
│   ├── f5adcc3b83d7132499b1acfe3d6bcaa8f8698c07.nq.gz
│   ├── f60832e27f24bfa3ee26b2cb19e2011d7fc4a9a5.nq.gz
│   ├── fdb764a28df4b13351c83a811586d006d3a23133.nq.gz
│   └── fdd486f1b8ff21cc9eeec744b116b77d11cd9394.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e903cce13cecb06fcb6914a398cd2fd72595a705.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 54 files
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

[argilla-io/selectra](https://github.com/argilla-io/selectra)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
