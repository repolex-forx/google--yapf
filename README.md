# Repolex Knowledge Graph of google/yapf

RDF knowledge graph data for [google/yapf](https://github.com/google/yapf), parsed by [repolex](https://repolex.ai).

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
rlex download google/yapf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 12005095296072751e3e4c1f33a047d41b0ce18d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 12005095296072751e3e4c1f33a047d41b0ce18d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0008df24a5f5613e87574514e56b45b8fa6d8e23.nq.gz
│   ├── 01b371051e2baa46c057b98e456f58d53ebc801b.nq.gz
│   ├── 01dd479b20daa66d0c057c8515c2de111bbefa53.nq.gz
│   ├── 03b36384a879702a415e9ebb9513c2c87d4521b0.nq.gz
│   ├── 06f3455d9b4288af4be850966530e4794917f4c5.nq.gz
│   ├── 07362287bac2ab8b5726b144131f18d1719cbd48.nq.gz
│   ├── 0b4bde36c76af4ecf5e74e3d52315f52787067e4.nq.gz
│   ├── 0d8a75e231881fe3d250634e873f074658625a73.nq.gz
│   ├── 0db5680ab9ef8733ea9c55f1d89e84d2fcc4d23b.nq.gz
│   ├── 141c2650e45d387f697712c3898354bdc073803f.nq.gz
│   ├── 1b6cc8061d42207c5cfb71e999e0f2b8b44c35de.nq.gz
│   ├── 1c03e800865ee0d275d7f0101129ee71d3c48d5f.nq.gz
│   ├── 1cf7820e2331559fc8d6c8166e7ae8d2902a7f29.nq.gz
│   ├── 1d908d4d3fca91b91e5a9305d8a5e3aa6909d7e6.nq.gz
│   ├── 1e79165d5035a3f9224b806ba9109d30882a28d1.nq.gz
│   ├── 2526b591c9745b88154d8f23a514505b3ab8186d.nq.gz
│   ├── 26bd40ec3926bb1644821b45324003f9603d865a.nq.gz
│   ├── 31591071225587aff9f4aeb529d84b7e37da695e.nq.gz
│   ├── 32faaa2f44d5594fc2de3c765d74d30924824161.nq.gz
│   ├── 3a0102368d130dd481e72e82435366e4fa9e1ff5.nq.gz
│   ├── 3a63da7ca6f8c0d714a0ef85153ff16ff43007ab.nq.gz
│   ├── 3c234fbfb500e7c09527f3b9c62c340a6fbfcd33.nq.gz
│   ├── 3e687394954dc3a9772c3fc52a1d8471782663d9.nq.gz
│   ├── 43ba4b9ed778b0a95517af9bae7e3f17bafb2dbd.nq.gz
│   ├── 4433276f76a32ff481ff97d2f367c14960ce6ffa.nq.gz
│   ├── 4c0273cd42d72b61ab52d49aba9922e4c7984f88.nq.gz
│   ├── 4dd7b8b532a2d45af87e95d1a0a9279d30548c22.nq.gz
│   ├── 502f59d958fa45a6772cfd0bcbb6f9e18cf81613.nq.gz
│   ├── 5bb982c518a09e598022ae00cdf95b5b2b8e9265.nq.gz
│   ├── 5e5b11e79000e894ff3834c921185b8ba2928851.nq.gz
│   ├── 61aa2c51b7a20b0461e3b213e9f6bc7f9c00b070.nq.gz
│   ├── 6458a0afdbbe5303083649fff56787a6dec03b61.nq.gz
│   ├── 64e64a5beaa601a7b41d3b7797d3a97cf410cd1c.nq.gz
│   ├── 6a6928eaedaa30037e70fc4751ba6fdea523fcfe.nq.gz
│   ├── 74b1ba405e40d4b98d8788c5566bc7e218eea505.nq.gz
│   ├── 754ff1555458d9f40f6733896be0e390e8c97cd9.nq.gz
│   ├── 75be820454e498586a86f681332c83317d0aab67.nq.gz
│   ├── 7642c01f4e109ada98ea3a276f3179c361b5ce64.nq.gz
│   ├── 79b68edcdeee9968c348c69ed50042cc34add6fb.nq.gz
│   ├── 7bb6b22775228811bda25641958bb5442a65a88d.nq.gz
│   ├── 7c9ab0fe9c7b0f2788eb085d400f8d12e40947b1.nq.gz
│   ├── 80e050fbdb4cbf86a7eeef23add55805f4beb153.nq.gz
│   ├── 87b6d863bcee9a36874283b0334510b389b26070.nq.gz
│   ├── 8aa1c83c48e49cb89f4bc3ccda0332ac084d2bd4.nq.gz
│   ├── 8cd25c9592b974b4483e04e2651416a64f76cd57.nq.gz
│   ├── 91b8e4614827df82946695d54a439635ef4b6cc3.nq.gz
│   ├── a7b4e33c3aa2e11aeeca3dbaf65f5fb5d45e7938.nq.gz
│   ├── a8aef660644f1f0882b3990d32362f14ebe8bbdd.nq.gz
│   ├── a9180f37c7a543944de18e8209b82bb6deb2479f.nq.gz
│   ├── a9ca011883611eacb3e24e7ca103cf41342bfc39.nq.gz
│   ├── aa010bb8f1a911eb16ba49af98a7e241e0ad5179.nq.gz
│   ├── ad3e7fc90a8acaeeb6be2706b0aaa96034264cdd.nq.gz
│   ├── b297560d86c8cab8b9c9f611d7af9fea5f82a021.nq.gz
│   ├── b5d9b926e0eb35f3b9672808c0885e36abf5416b.nq.gz
│   ├── b5e878e26cb65f57fd27827aae3a55638cfee098.nq.gz
│   ├── b6f7acb2e02b2ba0de45936e1ca116d6a0d3d536.nq.gz
│   ├── c01223a6dbd8d7ab9d8658d29bdb187452e54ab3.nq.gz
│   ├── c963e3c8bbffb2f5a55e7dfa779c284c1ca323df.nq.gz
│   ├── cb8c51b0599c13a3fcb1845c61a676b62cd3759b.nq.gz
│   ├── ccc8726c9c49882ea051652c4a0c9285f87aa429.nq.gz
│   ├── cf4be93792671cd9fdc526c1f14276eebdaf4601.nq.gz
│   ├── d2b1aaa1f4e96185ccbff781270811d999b161ef.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d9ce8b88c7cd3d95f73f6cfbd983182162359181.nq.gz
│   ├── dd5d0598e369711aafe33c2f1000753c374c126e.nq.gz
│   ├── de8cf5fb135bac36490f3d648ca7195a3f30e866.nq.gz
│   ├── dee2449d01291ac503e225ef3893a2f159de6bdc.nq.gz
│   ├── dfb87d378b6b2387a96fd09580471b60fdfaf392.nq.gz
│   ├── e2cc7fd2ceb91eed37aad5df0b74941de48c89a6.nq.gz
│   ├── e3b32777aee891bfc46722a842ddf3e390e2b963.nq.gz
│   ├── e54f1d3f829b3327d49f8e69737d27635b3d8da5.nq.gz
│   ├── e71742c6ac2be461ad152a337498dea70a4a23b8.nq.gz
│   ├── e7522b2ca4cd22f73b90b81c74f4d57884c2c5e6.nq.gz
│   ├── e7aa6f59ce7825aa205e2793fc013c158e9d599b.nq.gz
│   ├── e834fc4dba37472b19813e18357c32d1880a0b65.nq.gz
│   ├── e91752b8d4a95e7852c2b1c0133e8f0d6ba30fe3.nq.gz
│   ├── ec2cdb7e8fdaffba1273185f31691107b13a387f.nq.gz
│   ├── f0acd2f373baa913fbf97fc52f4033d2a6d99e61.nq.gz
│   ├── f1d0e322de42e429fec829ed0e62291011fa8b94.nq.gz
│   ├── f3f2fe8362cd5a377b04e6ba927e6d82f6f25d3a.nq.gz
│   ├── f4bd916f23e5a129bdfd1ce0844d0ac988d10377.nq.gz
│   ├── f5741b31346194d9510e15d4bf7d53c4e1164d5e.nq.gz
│   ├── fcfd78e02fa0585573c9623855b94481791871bc.nq.gz
│   ├── fdd07237cbe37372f7d5612afe4d3123ba2fedee.nq.gz
│   ├── fe31eb83c12f065f3e8d4cb52de4bdfee99cb9e6.nq.gz
│   ├── fe6f13d3b6d89c3dae0bb07a92ae4a3832b9fc7f.nq.gz
│   └── ff0952543b26adf1e96dbb1e60d01c6eba06802b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 12005095296072751e3e4c1f33a047d41b0ce18d.nq.gz
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

[google/yapf](https://github.com/google/yapf)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
