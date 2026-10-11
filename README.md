# Repolex Knowledge Graph of sphinx-doc/sphinxcontrib-devhelp

RDF knowledge graph data for [sphinx-doc/sphinxcontrib-devhelp](https://github.com/sphinx-doc/sphinxcontrib-devhelp), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxcontrib-devhelp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0177fb44f165305f27b34e69e6e7e5ed6f24d752
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0177fb44f165305f27b34e69e6e7e5ed6f24d752
│           └── chunk-001.nq.gz
├── blob
│   ├── 03dfe8634bafb6233ac59cff33662b2a9e49783b.nq.gz
│   ├── 0597c19fa8ec0476d1357d1eba1dad0cc4dda748.nq.gz
│   ├── 08a33064467e6bc79d2faff7fd11d03de081c461.nq.gz
│   ├── 0c33552a02231063c6f740c355e81034b2e6bac8.nq.gz
│   ├── 0ce6166645c3b9672c8a766729dbc4ae2b3b3775.nq.gz
│   ├── 10cef947b5c9825090a209f2e6a9f0409e20de24.nq.gz
│   ├── 144c52470e4527a240b4de7b524b0bdce134e20d.nq.gz
│   ├── 1bc3c01ad429615afa741e49823f2140ff00e353.nq.gz
│   ├── 1c17c86034755a7eae357d2d2225b89104b290e8.nq.gz
│   ├── 1fec81e5f4bf40bfaa65a1ea3892e355fea55bec.nq.gz
│   ├── 200b4047776eca07ca590f50d9a9b70e70d48069.nq.gz
│   ├── 20152a45bc87171f2436e4193249e4268c0d6c6a.nq.gz
│   ├── 2254d70607a152e3e1341b46bfa3140fbb9f2143.nq.gz
│   ├── 24dfb1a93caa991d29d2200ac9a1137171ef1981.nq.gz
│   ├── 24e6fb818554adb85196ec2dd67924e0ce8822f7.nq.gz
│   ├── 26aa24acb859fc8c401624e273460c9f302b3227.nq.gz
│   ├── 27fb43d2f49c4c0df7a7263635eef679f3e3025a.nq.gz
│   ├── 29efe4179d6508d7dc49c36a9e3adbaafda62cc8.nq.gz
│   ├── 2abce6fa4eee9d29bb17df90dcfb244a299a7f4b.nq.gz
│   ├── 2cabbfed50d121a0513511a54b8a5cb438830f7f.nq.gz
│   ├── 2daf3a948218b9fdb537c2c2ba2bfe72eab17fd8.nq.gz
│   ├── 2e1b173e4ee1bb04fb39e141099f138e31fbc9ec.nq.gz
│   ├── 2ef286a5669e58407560bff4e0bf65a98c1c0a2f.nq.gz
│   ├── 332cb86ac60bd8838ac9c89b34aa05e06c02ca5a.nq.gz
│   ├── 3934d3fc39cf1fbfb6ff26d92dddffb9b818bb43.nq.gz
│   ├── 3b6accbbdcc15bb01ebf842f7c3969fe9cd3d8d3.nq.gz
│   ├── 3c1554cd1dd581bcf5fd8ba57f91fe038ccbca3a.nq.gz
│   ├── 3f004dfe52b08b39905a4a5a0f093735af510991.nq.gz
│   ├── 410df2a1d5babb92fd2fa03d7ed2576818a73ce5.nq.gz
│   ├── 4128f8e3aba509b4828a6d2116c558f5d7c9dcc6.nq.gz
│   ├── 438ee542159fe05dc8a18a22cbacea27001281b8.nq.gz
│   ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
│   ├── 49d581e40c68a50f347497779bd8d87c1b8b9054.nq.gz
│   ├── 4b7dd2a5ac321d8dca7fcecd8e6507f3da934aa8.nq.gz
│   ├── 4d1e7133c19edc3e0247e8231ee519c92c12bfd5.nq.gz
│   ├── 4df06c1b362531aedde280a7ba29ad6537e323a7.nq.gz
│   ├── 503cde8e2c5759aa128b7c1f90499242a82fc08d.nq.gz
│   ├── 5166a367bfac5198757f19ec701d46a6a946c2bc.nq.gz
│   ├── 52452fd8445f362e3b6c7932ccc3a8fc63312c70.nq.gz
│   ├── 53d59b80fe1cbbd443cbb18cc38a2a0f5aa2e712.nq.gz
│   ├── 5478e1eeb5e79ef01a0ab6708092f8688673677c.nq.gz
│   ├── 56f6aaaec2226dcca79e0bb9c0a7212031ff4c3f.nq.gz
│   ├── 570300ff541ff1a744a724bf231eaa1e8f4798a4.nq.gz
│   ├── 571fd4ca18e24f0c3075cfff42715b27dcb3de09.nq.gz
│   ├── 5789ecb32ac890b90a73f80ad0a6ed16d0476b5e.nq.gz
│   ├── 57f2152c92da20cec8e8bdef80a41cfdebd1003b.nq.gz
│   ├── 5978407a669dcfbdab97c3e7e5e632dd22dc6749.nq.gz
│   ├── 5b4d68e65c98b95e310edfc8f73b1604ea5522fa.nq.gz
│   ├── 5eb7f8b2b776c71ba177cd5543e4ddadee17e530.nq.gz
│   ├── 6357ea480c6d39f701989b42796dded372bd11cd.nq.gz
│   ├── 63b08174fca6ea4d23d82d67b95273896844ed09.nq.gz
│   ├── 64a48a09479ac0c76f34d9daf7902ae0e2391620.nq.gz
│   ├── 6957117e9a1d307e8ecbd4568acf4aef82ff277c.nq.gz
│   ├── 6a40836d3fd20f1b6a6cd982443ed1054d5670cf.nq.gz
│   ├── 6ae8723bda0c745bf5f839c02fd50c16d8c510d4.nq.gz
│   ├── 6bd13cc014827280ece6e8d1bda2eee9153470a9.nq.gz
│   ├── 6c64985485ab576dfa226f5b0afef4d794809faa.nq.gz
│   ├── 705428ce85f847b60b522f0130ad4939e7a0342b.nq.gz
│   ├── 784e7efa9662812d910aae26bc36ba599ab7481c.nq.gz
│   ├── 7cc0ef32dcc169624030c7c74bdbea19bac3a608.nq.gz
│   ├── 85ad1d8ee8b5e7762c7e8e50eb01719afd889315.nq.gz
│   ├── 86467c8ca29f23638283434f19bf8311a7ad428f.nq.gz
│   ├── 8757ffe04cd7a6c135060b25b6194849940e74e2.nq.gz
│   ├── 87ca6db4c4dba27a4c3bfd2e9bd58bb4c643ace3.nq.gz
│   ├── 89667530a744798f5d0649be4f381b5e4989f978.nq.gz
│   ├── 8a945e3e5f70ae08684a466705554d1c3d9264da.nq.gz
│   ├── 8f22dbc8d5619cccfd5fa7b6bfb623f7bdc9748d.nq.gz
│   ├── 91ed7955d4d456d3f7801d4ae73cdea920909899.nq.gz
│   ├── 94b2f5188b2b2a08a5b344bda936608992d44536.nq.gz
│   ├── 97630404aa4ee9cc3be013a169c2d048d69ea38d.nq.gz
│   ├── 9a767c38e9f5eb194c3780852446f3c53dfc7066.nq.gz
│   ├── 9a9de1152edc83f88476687f8dfefca9fd1a08b0.nq.gz
│   ├── 9d8a3afdd287268607acece6568a7c16717f34f5.nq.gz
│   ├── a0914790d18ef285bbaf5f25a9c742c75b6458aa.nq.gz
│   ├── a196dab98a89df47dbdde09f3ae460674063ffd3.nq.gz
│   ├── a204ed78685f4e3ee3b282cdf240e0ba95f9ea9b.nq.gz
│   ├── a5ff67b770dee3433580e5db14d3f7732dafbcb0.nq.gz
│   ├── a636afb1c75f75f6b947d48748637869013d0d50.nq.gz
│   ├── a894091971159a83e75ddc528dd6146c29264c97.nq.gz
│   ├── aaefaec097f7981b2a052fd67ede610a4a271766.nq.gz
│   ├── af93c511c8a9c67ca912cdd45d4af7757f281cb8.nq.gz
│   ├── b6dbcd866dbf39efb3dc4cc279f156a64bebb120.nq.gz
│   ├── b8c1002e2198869ab34d03676e3c7fe6ce00e66d.nq.gz
│   ├── b8de4ea78622e3b794edf8cdb0a5c07609f48d32.nq.gz
│   ├── ba2cb762c5de7c6a4366a80b447acff4187e8098.nq.gz
│   ├── bb41fde756d85a40de35bc0ec5d3c67e692f07d8.nq.gz
│   ├── bb429c495c2d79a8e1d67eec80573989bf6fe8a1.nq.gz
│   ├── bbd9642e943e8ba0c0e61d685fd60f54e6354b88.nq.gz
│   ├── bbd9ed77b748ae723a106e9b90ef88f3a66ada2c.nq.gz
│   ├── bc25ea36ffb7722e3fd702e888b3a1a9fde9599b.nq.gz
│   ├── bc5038e967e49ca81b2d21fe0ca3fd417dfbce5d.nq.gz
│   ├── be5b79f7ea5f5e9762e5eab278f8e0a0aa050972.nq.gz
│   ├── bea11962e0970b1b9153d4945939ae6107deb57e.nq.gz
│   ├── bee2a8de21aa59e99333566f05d6033ff94701e9.nq.gz
│   ├── c9ee4968278eb3632c1b8ca529d46cd4cec1efdb.nq.gz
│   ├── cf920384ba8875fe50bacd29e4ef875de40d214a.nq.gz
│   ├── d1413652452777f8df6c8989f5dfdaff0b75aaab.nq.gz
│   ├── d297d4b1deadd405b58975b4cce389f628f05980.nq.gz
│   ├── d7e98e4e7922c1ca9814a3c1a2eefcaa69a7e800.nq.gz
│   ├── db12615eb788c6dd2e8e1add74011e64d60c1e43.nq.gz
│   ├── dd5466c9551e12b9d995ba8cb12eb2c8b865c74d.nq.gz
│   ├── e04fcc12f1768f9eb579db0b32ba5a1cea61e12a.nq.gz
│   ├── e337f0f6b13a21f1bb165fd67cec569e65c94ad5.nq.gz
│   ├── e3eae3b0275242abea7db852badf0d8d18748aeb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e755949fa5c01b68bbd560cf86813ce3597b7b7d.nq.gz
│   ├── e77d4453f633cb98a4de9840fcf7e79ac2943dc3.nq.gz
│   ├── ec2e14360a2f4a427140229f3e287e001c880d6f.nq.gz
│   ├── edb7d27d5903d9ca8988f37715e691ead81d379a.nq.gz
│   ├── efd895c40db47c4a4f9ce49ae5aafd0c78571422.nq.gz
│   ├── f255c01cd76a015d6a64080e8aa45824395c603f.nq.gz
│   ├── f2b8ea1b192babc55a67de260d657f4fe0e8f430.nq.gz
│   ├── f5913cda7c5b0a5605410ad84621c3309d0202a9.nq.gz
│   ├── f67b9453d57a4839712b280157d7f486dfe8814c.nq.gz
│   ├── f686dc9f1c8049de6702e7529a20791dcdbb2832.nq.gz
│   ├── fbc0491061abf2ffcec1511ca685cad0db478d2f.nq.gz
│   └── ff3b77545454812edfffde6602da317a371b3b3b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0177fb44f165305f27b34e69e6e7e5ed6f24d752.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 124 files
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

[sphinx-doc/sphinxcontrib-devhelp](https://github.com/sphinx-doc/sphinxcontrib-devhelp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
