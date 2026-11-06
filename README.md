# Repolex Knowledge Graph of pyenchant/pyenchant

RDF knowledge graph data for [pyenchant/pyenchant](https://github.com/pyenchant/pyenchant), parsed by [repolex](https://repolex.ai).

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
rlex download pyenchant/pyenchant
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c145b62454369e5bbc1145850951f06290d4f8c1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c145b62454369e5bbc1145850951f06290d4f8c1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0053649bfde5729b93d772d5be199deb2d2568e4.nq.gz
│   ├── 0409554b767a5767409c3f5353176602e4838c60.nq.gz
│   ├── 04d47b66f23e2c2b987519bf10590452926424d9.nq.gz
│   ├── 05063287aa4ee10c32b671509daccd0e7206a640.nq.gz
│   ├── 09b743964296bd586988cee50d4c10f6a2f9cca9.nq.gz
│   ├── 0aba87898cd5cece8557b8e57b3ab1c0becf10ad.nq.gz
│   ├── 0dad622aec2c9a1ea45738229e29b8ccd417ddf8.nq.gz
│   ├── 138025b141d65eb5240d3d0283c4e5ba27e0b172.nq.gz
│   ├── 1631a8f0c0de9fbfaef652566f6f4d4193718723.nq.gz
│   ├── 176cd19e7f85fcb10ce22a116d82f976161ecff2.nq.gz
│   ├── 1943a29db84f6d2baca55d8056b3645003bba78b.nq.gz
│   ├── 1d0afc4a24b32727c55d14a21edc64371eeab561.nq.gz
│   ├── 238da3c63f269d8b0e31599b7c5617495e8a468f.nq.gz
│   ├── 255a4732bc66eba89e891fbac8b88e09454b3990.nq.gz
│   ├── 28d658f0a9a015020a1e8c5d8479608d27ed8210.nq.gz
│   ├── 3002da48bea8d42c698ce635a4065fe5c34973cd.nq.gz
│   ├── 31bb32a0714e7c68fc226ff97599b4fba54c2fb2.nq.gz
│   ├── 33bd5c071a5b20fb73f7cf9aa430abd4275643f1.nq.gz
│   ├── 371c38ea3c38182af1764b577547281a3e20eaea.nq.gz
│   ├── 3a2a00a9bd0bacb22f42c1351618b0d054b7ee77.nq.gz
│   ├── 3b448bc7317461ffc57d8226c87e29b260777654.nq.gz
│   ├── 42c7d7fc394f2eb74c85801093efc70292da5a68.nq.gz
│   ├── 4b99c3b42b283fc2ddc8fe29463100715fdd870b.nq.gz
│   ├── 5ab7695ab8cabe0c5c8a814bb0ab1e8066578fbb.nq.gz
│   ├── 5d7bf33d948c45d40befd4769d0c15f74615472b.nq.gz
│   ├── 5eed7e2582d3359e52331178a86acea398d4ed05.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 606fa0269a196382fc29199ba907918b19b1a9f3.nq.gz
│   ├── 616d2f3a0f5ece8bf2773588500bcef469bdcf31.nq.gz
│   ├── 639c042005efd6f82b49c109dffbaa3867ccef50.nq.gz
│   ├── 70837cb3531750d751b2c8d7e93c9d6374c68d57.nq.gz
│   ├── 72a23939150a9a10f2b908a0e83d18357f254263.nq.gz
│   ├── 775ccde2cd35b7f8243443eec1b903eba712a395.nq.gz
│   ├── 78c65961f06fee38bd100e1960403399b308954a.nq.gz
│   ├── 7d53cd09980a75031d44d2788d81a53985ebfaa8.nq.gz
│   ├── 84c0c33be53c99de59a5d9b90b6c930dd5d74173.nq.gz
│   ├── 8c50219e6ac18f4aa6b0b508d0bbde86c72b9c51.nq.gz
│   ├── 904fb32c1544c8351841d6428531363eacb2de1d.nq.gz
│   ├── 9cdcd79d7d252abf83ad3a84fbf0781bca5501f2.nq.gz
│   ├── 9dcc008949d7fe25a14e121df71228e4a848cbc1.nq.gz
│   ├── 9df1cabe5a671a1ba11b7887b98c4ba8364d12d1.nq.gz
│   ├── acbb3c4dbe1a4dacf488e596636ce5d546d8246b.nq.gz
│   ├── b0008afdd524610b0c94aa2fa44c7c61778815ad.nq.gz
│   ├── b2347e1dda795d3cef4a5adb03d2b5c7894d2722.nq.gz
│   ├── b4dc9505eff74c9cf668a37e9764234b171e1e95.nq.gz
│   ├── c10a6dbcd7d51e3b09c525371e9080a2aa103d57.nq.gz
│   ├── c396a7f8fbb4cf888b9f8003dc43b2f58848b4dd.nq.gz
│   ├── c3abecf4a6d5950feb0c8b00c09fdafd0aa10d61.nq.gz
│   ├── c40e433d2b19c4b820a7493f5e2fb4f4c4b1d387.nq.gz
│   ├── c41df4902b6e47708a738b40497efa7bbb7e12ed.nq.gz
│   ├── cb46abbbea5d4898554545f51436062540922674.nq.gz
│   ├── cc65584b6a90c7fe5d91d6a82f43f3489b019bd2.nq.gz
│   ├── cd8ef01cdf38a1acf205ab7b94ce53dedbfd5268.nq.gz
│   ├── cff40e72a87c62965b32fe9530865b2f0cc4ccfd.nq.gz
│   ├── d516ff163624be545a22e72f8b6d4bffa1341dd0.nq.gz
│   ├── d89a979e2c9ccc9a7b19159011dbb177288649e7.nq.gz
│   ├── e5d7d382af0d41d936c81ad6c2a82d43614cc4b6.nq.gz
│   ├── e649ec2e8dfd5e8ea9eccd1c1a9306e1f5a7dacf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e784502a9631dbbc88067ee9c3237bec49df4887.nq.gz
│   ├── ecc15522432270d7584f15f921f80161c12af5e7.nq.gz
│   └── fa5ecf690b386ce04d6b5edf0bf3f0bdedc72a19.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c145b62454369e5bbc1145850951f06290d4f8c1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[pyenchant/pyenchant](https://github.com/pyenchant/pyenchant)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
