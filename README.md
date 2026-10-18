# Repolex Knowledge Graph of mpdavis/python-jose

RDF knowledge graph data for [mpdavis/python-jose](https://github.com/mpdavis/python-jose), parsed by [repolex](https://repolex.ai).

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
rlex download mpdavis/python-jose
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 018b310ddb8b50dcfd09a0c152117835a21dd656
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 018b310ddb8b50dcfd09a0c152117835a21dd656
│           └── chunk-001.nq.gz
├── blob
│   ├── 02eb3f675f312da45826588e4e6a5c7b5dbd838d.nq.gz
│   ├── 03589cf83776a53c19c9e87bc11985b7b8a21fdf.nq.gz
│   ├── 04d0e350d034ec2f55c40dae1b346ad9024d22db.nq.gz
│   ├── 09e5c329817ad6657c2ea671c06727819c9e09e4.nq.gz
│   ├── 0b6ad275d2e28fff93cec3f68abbb0ee1389616e.nq.gz
│   ├── 1096591c2d87c68b7d1a5175cfcfe267553db402.nq.gz
│   ├── 1520217881603fbe41d99628b44b6fc4cd2c399b.nq.gz
│   ├── 1609b6b599ec1d7d36119a1011ec295d4b569b8d.nq.gz
│   ├── 1bb7373a7be5ff6fe0ea014e87f655e1e0f17e47.nq.gz
│   ├── 1fa4f6572f2dab9c1f5364b73572abbc8b7f33eb.nq.gz
│   ├── 245e66d0da2919fea26f436a039a3a318abf681d.nq.gz
│   ├── 27f6b79a2a26620b6125750bebee3a2110e6edce.nq.gz
│   ├── 2a31847547073c729e09d4b4e4e19bedd70927e6.nq.gz
│   ├── 2b0859ec469ad0a2c84aadcbac440296451d0fc9.nq.gz
│   ├── 2fbb08dcb3457b662b5c28c6fc548226692dc3ad.nq.gz
│   ├── 312cf88817a5aa2b634d1315865c33473955c994.nq.gz
│   ├── 3ce1a7831ceb96e7670a320b398e93e5ec4882cf.nq.gz
│   ├── 4086fd8ed406af528639ca20ad472cc78d89a889.nq.gz
│   ├── 429d33252617e668f666a9d290ac3ec3f0967dd2.nq.gz
│   ├── 4ce71a7d12bdda84d8233900bf7dd10af3d91c6d.nq.gz
│   ├── 4f05bed5e0c9a74ec6bc1397cb2aac53e08d8dd3.nq.gz
│   ├── 544b38883332bf78075f1cdb9c631e6d346c05da.nq.gz
│   ├── 54ac132be24749c9dd2901cb35489c207f3f53f8.nq.gz
│   ├── 58787d4640a4e01a95e67688afa9bbbabf06b008.nq.gz
│   ├── 60bf7b3d5236dba2c2fa98698b99705e99195b28.nq.gz
│   ├── 6ab9971996e5734d639deb9583414a1c44b93264.nq.gz
│   ├── 6e1b10390f6fb9edbd47350c5bbc13132c46dab2.nq.gz
│   ├── 756c7ea8ca58815f90340d68fa2d1a0ebdc95c63.nq.gz
│   ├── 779a15a6133503159014a047015236f4a6facbf7.nq.gz
│   ├── 7bc375f5d30ea6ee6a8b335b2750c8de91e44368.nq.gz
│   ├── 7dc90d099e30a190e1f5e44b0923b02f8fc7c74e.nq.gz
│   ├── 7e53b60c1d88cf3b96afc1b81ef1d048270054b4.nq.gz
│   ├── 8139d69854428274bd827b7ffb43884a226c6ce0.nq.gz
│   ├── 85c8a80848628fd810620c0268074768d7e61446.nq.gz
│   ├── 87e3df1b89eabcfd0c69e2dd099b79471933d2ab.nq.gz
│   ├── 892b5c23adf5b38e589ca00f6e7b2b5c17859c79.nq.gz
│   ├── 8cc77dab75d54065affad1cbf75b6d24fc722da6.nq.gz
│   ├── 8e99ab94ecf432c3654fed4fe65ef09b3ca72be9.nq.gz
│   ├── 8f68f76e50626b70ef8a00d352b4176b8febaa06.nq.gz
│   ├── 9052f65c3cb97eefd643d8e311b7f163b63754b7.nq.gz
│   ├── 991896913748a68335bf5d7eb38fb543e9e12d6d.nq.gz
│   ├── 9a1aa676b9ad6a289474d94c08363f84eb3a10cb.nq.gz
│   ├── 9b9d03dc7ab3778246349035bfc76fec5269ed2c.nq.gz
│   ├── 9d06017ceef9b355e8e8943bc053e79eb9cdba7b.nq.gz
│   ├── a6bc99ae8e9b6cc737940008bff7492a8e90dc21.nq.gz
│   ├── a841996eb3c78ad5bf61e4c250dc65fa71609f0a.nq.gz
│   ├── a9c1a1be35681f5a9e7777a5939e1a325ed162f9.nq.gz
│   ├── b000a5253afae35681aa2013a073e625b71c1628.nq.gz
│   ├── b181993c8f1b0598db8b34d5f50e35e6c95412d3.nq.gz
│   ├── b468076c68e00d4ad2a179d61fc0c97fe6275b54.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── d62cafb0ec55202af5667667f69d05ff82bc9917.nq.gz
│   ├── d8602a2b1c20816b1089c78ee3433cea1d8b4732.nq.gz
│   ├── e4e3d1922d5e1d2f638ed85f3ad1ab380f0b4d30.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8009d64e678289f6e7940f1b270a04c927a5d07.nq.gz
│   ├── e8edc3b6a5a8da1d09a2ba504690b4f480a4f416.nq.gz
│   ├── eaadccc881e6b30cadacdd6b261fae2b65f5d564.nq.gz
│   ├── ec7a7d9ff8fa173abbfc74537d17e3b32b907eb0.nq.gz
│   ├── ec836b4ce126beec946bf8d7a92f1896c0f23711.nq.gz
│   ├── f2fb899c82157c829f5d0a3859dbdb4884476599.nq.gz
│   ├── f47e4ddfbe55c545dbb05e5fa546f151a0f85a69.nq.gz
│   └── f9d54cd1df03bf24be20a54af2bc0d1de43ddf20.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 018b310ddb8b50dcfd09a0c152117835a21dd656.nq.gz
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

[mpdavis/python-jose](https://github.com/mpdavis/python-jose)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
