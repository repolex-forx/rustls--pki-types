# Repolex Knowledge Graph of rustls/pki-types

RDF knowledge graph data for [rustls/pki-types](https://github.com/rustls/pki-types), parsed by [repolex](https://repolex.ai).

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
rlex download rustls/pki-types
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e29ad15465126acc089b39611bcec85e27ce0817
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e29ad15465126acc089b39611bcec85e27ce0817.nq.gz
│   └── repolex
│       └── e29ad15465126acc089b39611bcec85e27ce0817
│           └── chunk-001.nq.gz
├── blob
│   ├── 0074a0e2bd641af7156d97b3c75ff82bb5618705.nq.gz
│   ├── 1623c3746b8e5bab75e55e353907291f2dae5b53.nq.gz
│   ├── 16a17c7bb87a4fababc91d3954b6a2e9f5279686.nq.gz
│   ├── 184d13a0188afaf73d5fe51ae32d8e853a26a041.nq.gz
│   ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
│   ├── 227fa8ab5e0ee8ba6b26e52c67b4896279d2545f.nq.gz
│   ├── 239a349e1694e184d5fd5504102d28401d4d68ed.nq.gz
│   ├── 242ea48f1d3919a92c94e8d9d65fcd5c511dd133.nq.gz
│   ├── 2730088cf516430ec3e159560079bc4faf451ed0.nq.gz
│   ├── 314a0f270b19430238c06a078b1cf6c88990c9f5.nq.gz
│   ├── 3501136812cb639f6f93412fc9ef5bb7ce177a64.nq.gz
│   ├── 45cf697fcededd45194d328b3b545f03efb505de.nq.gz
│   ├── 473392f7b9edfa4fa8f4765d5ca72c1052d3fade.nq.gz
│   ├── 4b2c66b9662780bb3a028fc2531e6cb98e7a0c43.nq.gz
│   ├── 4bfa301efa71ee6e8e11556d1a37a9cf2c14e6cc.nq.gz
│   ├── 4e1cb207ad234c4816153570d88229730e2de0a9.nq.gz
│   ├── 53245c673d4bf4a4b493b71cadddd475f4512a99.nq.gz
│   ├── 544972973857c01b20594704b4233e2523dc3696.nq.gz
│   ├── 54eafa3b15f01bb9fdfec4025215d4aa5b534d9c.nq.gz
│   ├── 57551822e40e63d3e9dff134e85a8ffd84d95851.nq.gz
│   ├── 57faec8b6e9606fc28e75757dd398c06c30e0010.nq.gz
│   ├── 60330126a73b508f0d4505d8cec416faab80cb51.nq.gz
│   ├── 644365f1b8387624fb613f0a0a85da590b3bf1ae.nq.gz
│   ├── 6839131a70137be182900377e3c8af12a61ed8fd.nq.gz
│   ├── 6a82253e0185caea4b4575624e9325902a5c26eb.nq.gz
│   ├── 71aded5b9ec3aee05f8ca669e90cb425224d8ef6.nq.gz
│   ├── 74d4a01659d0be15ff23e96e38d41e09a1818370.nq.gz
│   ├── 76e748e571b209bb622b9dc4b8a0560459efa4b4.nq.gz
│   ├── 77d159a1c6fcc68fac95281029ab0c6ce52bb58f.nq.gz
│   ├── 7c61d3aabdbefa420cb27ddd3e5e47d9a33c4c7c.nq.gz
│   ├── 7ca46fd9522802e2cdf67ee7b4f6b939b8e39f6b.nq.gz
│   ├── 80cc4c95d0a11022c9b564873918fecb76a638e1.nq.gz
│   ├── 80f0769af0d0d7501fb3c778cfcd79f76c14f91b.nq.gz
│   ├── 81655bb3083398623c395c9af1c7ce39a6eb1dd9.nq.gz
│   ├── 846fb546d5ed2a4d5b2fa7a8829ac2f38eef5d78.nq.gz
│   ├── 87328f7c64bc252ea54283bb542fbe36ac98e9a8.nq.gz
│   ├── 8b24916caf9bfaeaecb98407738772aa659fc65e.nq.gz
│   ├── 8bda0c70831e37ccba2baf5aabb2e69d8c45b5d2.nq.gz
│   ├── 8e5c2e817ddfe06b75a1be432f600f96c25834cf.nq.gz
│   ├── 8e64b2c81f3c56d779dfb7a6ee4c3ee9d0cec000.nq.gz
│   ├── 8e910d86271856b40d3f7a6f31832a95192c0c0b.nq.gz
│   ├── 8eff00da9f2302d364110b78cb9bbbbdb750950f.nq.gz
│   ├── 91bc1c12fa00b7939a62bf097428d158e640830a.nq.gz
│   ├── 9257be28f7445a70bdb11fb536a7d5b7c62c3595.nq.gz
│   ├── 93cd4eb5e267ee423324c692ec9a4b131c00782e.nq.gz
│   ├── 94104b1d3bbfbd1414ddd669540256342a1d7515.nq.gz
│   ├── 943a7694ab2986e02f63e72b3ce4cd24f7cc1e81.nq.gz
│   ├── 98700ee10c64ee916c20ed9da0e310c0f1af3ac9.nq.gz
│   ├── 9ad544c2c77f2fd26eac3b783622069507ecb806.nq.gz
│   ├── 9c3b170f2bef5721f65f49f0e3beb46f89c7ed90.nq.gz
│   ├── 9f35cdff1575d24b96fad2c3794f03044e9021c2.nq.gz
│   ├── a76e47d9590ba89ad54a8641a2211564b7db3707.nq.gz
│   ├── aae49672bc3c0ad4096ef98fee2200bc3b355835.nq.gz
│   ├── ab52bcd80b62813edb30a9ab628a5530b2ada8eb.nq.gz
│   ├── adda089e6adf0c5fbc19db4d42996487d9432ba6.nq.gz
│   ├── b11e97b2bd7b04f3fd35c9c96adbd700031d0df9.nq.gz
│   ├── b1ea6d411243783f68712960ea88310561ebe7d4.nq.gz
│   ├── b2ee12891442fc9a46b3bfe2fe95aa42cdd32a61.nq.gz
│   ├── b7db4269cabe84a622a73d6edc6f108dbf0d72b7.nq.gz
│   ├── c0ad57d612a2bd66d003342a1d32ca975baed06d.nq.gz
│   ├── c0d43b17fd5b83bbb5f2a1879013225f5d0fc09a.nq.gz
│   ├── cb8de090a4376d07f0221322d1b27a59f8a1fec9.nq.gz
│   ├── ce0bc8623a2f7d00686c1f922c0ee8114a223c50.nq.gz
│   ├── d49c30da3dfcf8cb86f45064aa81a57364aaf927.nq.gz
│   ├── d55fb4f3fbfda728a4880ba04bc6b6798ac58131.nq.gz
│   ├── d81f12ed1b1cf9affa3ca75d42332368150a2ec5.nq.gz
│   ├── d87b89921f57c73ee6097780ee6d2eb6f43046c6.nq.gz
│   ├── d93402d2c9c4339d38407543b92be1cf32beb9a6.nq.gz
│   ├── e2496664b32161b55e6b67be21ab1b2e68cc42ce.nq.gz
│   ├── e6b8623c5ebabd1ec97ad44da98610999b20bfc9.nq.gz
│   ├── f80dbdd7e756e50c72f5af249aebc9c8db6dffe2.nq.gz
│   ├── f85de4319c6542670ee6b443280a0c6b30662bd8.nq.gz
│   ├── f8cdbfd08222c6994755a2bd01b1fe78a0c55acc.nq.gz
│   ├── f9ba7a65146862de909a52abb7811f1422fca214.nq.gz
│   └── fa11b6cf8c41fd33557d6dd54b98f72520ebce8a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e29ad15465126acc089b39611bcec85e27ce0817.nq.gz
├── filetree
│   └── e29ad15465126acc089b39611bcec85e27ce0817.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 85 files
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

[rustls/pki-types](https://github.com/rustls/pki-types)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
