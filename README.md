# Repolex Knowledge Graph of repolex-ai/ravel

RDF knowledge graph data for [repolex-ai/ravel](https://github.com/repolex-ai/ravel), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download repolex-ai/ravel
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e897e6be7f7e37124f256dd950d61ca2f2e72213
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e897e6be7f7e37124f256dd950d61ca2f2e72213.nq.gz
│   └── repolex
│       └── e897e6be7f7e37124f256dd950d61ca2f2e72213
│           └── chunk-001.nq.gz
├── blob
│   ├── 034c610993a340de4eb3c29abf105976f81727cc.nq.gz
│   ├── 0394b5aee175663c394f24283c567012339873ee.nq.gz
│   ├── 048f73ebbe49e8894e643a9c6c88a1e765c2605a.nq.gz
│   ├── 0f17b700ea47aacd7ee15e1c01d332d9d1840357.nq.gz
│   ├── 15bf220689ed6869f2fcae59777ccb20f7c46bf3.nq.gz
│   ├── 1690588e060d3fae63f429d1f0efa4a746528dc9.nq.gz
│   ├── 1dfcffe3d90bb96e16085784c86a9746b75c5378.nq.gz
│   ├── 21c0fc1ae6686e2a184ee5a4166cdf019602cf1e.nq.gz
│   ├── 24889ed6a251d524a93ca47c9cbc69cd7632c408.nq.gz
│   ├── 24d624ee78a7433c1e45d63555bedb3b9d849e32.nq.gz
│   ├── 2623915bf44508edf60ca3ab89dd9022ecf2bad8.nq.gz
│   ├── 2bcb8dbd5c2c4c8bcc11e7b74df23b3960ba7951.nq.gz
│   ├── 2c0c289405695f8bc3af5c378f95c1ee453cfa1d.nq.gz
│   ├── 2dc3c7ec1327f941004a542b245a6ff415f64ce1.nq.gz
│   ├── 2ead27f62d13aac88d706bad7e1bae1fd920cd82.nq.gz
│   ├── 303222868033af4f7aec0afdf04aea692973c214.nq.gz
│   ├── 32acacafb3af0605d678da827dc6d81986c7b5ee.nq.gz
│   ├── 3bbac967b48507749c3b58316166326bb2269929.nq.gz
│   ├── 3ca4e0ea36cf9b1b388741e7c42785a4ed9af214.nq.gz
│   ├── 41e80417be169cd71cd726fdc28db4ec6d3dc201.nq.gz
│   ├── 44ec5e9011dc98aca691318662f9b11621fcdaf9.nq.gz
│   ├── 51fec3da0d74a6d6d65485713614c0421263f319.nq.gz
│   ├── 545a2678950c4982148466995a45622efe43794a.nq.gz
│   ├── 54fc25d76d4f2aff2958589ce3502ca518e2aa2c.nq.gz
│   ├── 563759c8a64acdedbd7cac66e32f4d7cd3f84ed3.nq.gz
│   ├── 5a7a9b18a92da8f8af2a5462a7ca18e9bfa0789f.nq.gz
│   ├── 6008e69d4abedcb4387437fd53e0304e28589550.nq.gz
│   ├── 63dc9c020f6f521807a5a2c9107a6999d6d4d8c6.nq.gz
│   ├── 63de7feafdd432dd8353872b2f156390f456f718.nq.gz
│   ├── 65c7b940fc051dbf5480e94ee7fcca7d1a6c60e0.nq.gz
│   ├── 66c605ce1991a593c345903525d43dc7ae387143.nq.gz
│   ├── 688fc21cd6b220de03e6ae16c5d92bca3f2f2480.nq.gz
│   ├── 6a3db3972038cc40fc4207731763a0d3df49f017.nq.gz
│   ├── 6e659532f51afbc176ee207fb1c0d7da231726f6.nq.gz
│   ├── 725355fc0d34824ed32450405c11ad84b599996d.nq.gz
│   ├── 72a8e4d2d56ca5d32a1d9f23f1454f6d32bc7278.nq.gz
│   ├── 73cb480f84981e7d4751af4de287fc2e395109ac.nq.gz
│   ├── 7b7ecf8b5bcf8db14633bc89d472286f16fd18a6.nq.gz
│   ├── 7ec0364e0aa5e1e09454036c6ad5eb093b0e6de3.nq.gz
│   ├── 7f36e76a580f4f217db57c8be39b1050496a7625.nq.gz
│   ├── 8f9843f952310575bef5cdaaeb4ee159e80616ec.nq.gz
│   ├── 921ee595ec6543039c0739a6df6bad23d3d45b7f.nq.gz
│   ├── 9519b4b264639bb6c35053e5493d4450cf1fff61.nq.gz
│   ├── 96702f12f71bb64a3e65c4e915fb98f5e091a4eb.nq.gz
│   ├── 96d8ae0a247329d0e52ce6867d4bdae8adf3c9bc.nq.gz
│   ├── 9d41ca8e45ebcf651679c74e5d27e0b96280d2ca.nq.gz
│   ├── a20439f54e41923a9452651d876d02b3e5c78320.nq.gz
│   ├── a4f0896e6cc03d6236fce354b62fe52e3c01c133.nq.gz
│   ├── a882b947b6bc764d4b31145e3f447a9705ac7a88.nq.gz
│   ├── a8b5b3f492dd2d7d946737710348e880c76644d4.nq.gz
│   ├── a939bf4ead633f7da87675981a481647c9ebcb42.nq.gz
│   ├── b279351d24d1a791900ee8344b7c5d947184f421.nq.gz
│   ├── b4488ee469d03c46331d0226b437df13ce8e6e22.nq.gz
│   ├── b5036211108c8863d5a1e71bbf7ea12ad88cb7ce.nq.gz
│   ├── b604758207881bd3e1da5a024745c35e25207236.nq.gz
│   ├── b7753af4311b2b026b9e9650507c4d518b6a5683.nq.gz
│   ├── bdf96bca773f9d5f483b08abf09fbcc7ddda9260.nq.gz
│   ├── be1cc16d7c47e563e04a28a381a5bc17cced20e8.nq.gz
│   ├── c171a52cff81786812ba239a3201dad8f1e2f243.nq.gz
│   ├── cc34b887cf728e537b8937d9940498d4cc733dc9.nq.gz
│   ├── cddd9a26d07275dab832bfff559a29a89ab20fd7.nq.gz
│   ├── cf8fe119cfd203dfd39d2c011041959caac297c6.nq.gz
│   ├── d02c397009322e18688dccf5e5c7891a403004d2.nq.gz
│   ├── d1cc0c3bd382b1d9ef16a50eddaa7fb448871914.nq.gz
│   ├── d894b39182ee97bc20bc0e14c77f49c4467e0eca.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e620efb55ce8af24610b0a23651b1cec03f2d994.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f59a13503da90b23dc11211849eeef7e3deccc72.nq.gz
│   ├── f8388db74802590bfb68a4afc8e341e50b752079.nq.gz
│   ├── f8770df9c9ea282494b0539d448cc000af38b789.nq.gz
│   ├── faf7547f7fc1880c43990dabd784565faea6e154.nq.gz
│   ├── fd69044b894d09cbc14d00b45939d6ded9bffac4.nq.gz
│   ├── fdbd1ea1e68a2e874eb4aada571c55a811b1e3c5.nq.gz
│   └── ff1eaa66e5dc985cf19331adcf377a0254d3a096.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e897e6be7f7e37124f256dd950d61ca2f2e72213.nq.gz
├── filetree
│   ├── 04c5bf0051b5e5d41e489be6bd9c0af262ac3acc.nq.gz
│   ├── 440571b158f984edb365a7fe885b6bae0a1d6386.nq.gz
│   ├── e897e6be7f7e37124f256dd950d61ca2f2e72213.nq.gz
│   └── eeae5be8f1afcd88f0029d670ac1120f967ae87d.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

## Source repository

[repolex-ai/ravel](https://github.com/repolex-ai/ravel)

---
*Parsed on 2026-09-21 by [repolex](https://repolex.ai)*
