# Repolex Knowledge Graph of exa-labs/exa-py

RDF knowledge graph data for [exa-labs/exa-py](https://github.com/exa-labs/exa-py), parsed by [repolex](https://repolex.ai).

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
rlex download exa-labs/exa-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ca7b446a18f3c6db52327c5544e868ca628d599
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ca7b446a18f3c6db52327c5544e868ca628d599
│           └── chunk-001.nq.gz
├── blob
│   ├── 001b41554760d1e9871c052ac7c11584817fc08f.nq.gz
│   ├── 0187f4183880191649bfe0381d19a8e1bf502a80.nq.gz
│   ├── 07454c6b2b47c25c567fb9362eec8a5d6b1d9082.nq.gz
│   ├── 07efc8b30a502ce103c5f0c528310a66d2bba4f3.nq.gz
│   ├── 08255181fbf2f6773d0cb68b47e01dedf2c8010a.nq.gz
│   ├── 0a1c1a5e702d8d1239eaf7d8a43a51d20c1b517a.nq.gz
│   ├── 0c457a8eced90d1d5844f8eadd37e5a371a44159.nq.gz
│   ├── 0d2866e8991e24f72a47b01a4f39dcf662393d0f.nq.gz
│   ├── 0dc8c8176954951fcce664f51c42bff14f41e5dc.nq.gz
│   ├── 157ca96038c31051647f967dd6ac68c4e86c4bed.nq.gz
│   ├── 182d10744a22f42c34df2c9acd82b8771e732969.nq.gz
│   ├── 19b81872952290180fb0fde65d24762071c37a89.nq.gz
│   ├── 1b82e907cc84b5190ff3f46e0c0d69ca90184380.nq.gz
│   ├── 1c7b7769fd1b170273008f20c1f1afbcbb729456.nq.gz
│   ├── 1dd650fc5d454d603a9ec1aabf8b972af8877901.nq.gz
│   ├── 1ecb0bfcfb307efc28bdfe336e9ebe7a9afef944.nq.gz
│   ├── 205f8e6d4818b6261acb00339bfca1def7881fc9.nq.gz
│   ├── 20f04365f8ab5e2fa3ac5d8d3e4d29db35b568d4.nq.gz
│   ├── 22e88aad47cb9f339bf2a20d20c7d1c31805bd31.nq.gz
│   ├── 250f5665fa64b70c822190199b3b804b10f8b9d8.nq.gz
│   ├── 257d8f5794238dd083119febda4d3a9dce1d0346.nq.gz
│   ├── 25ad1bf4f37f4537c7fd3021685d345539f4d78b.nq.gz
│   ├── 26778a29a87f645805ac801529d53bc612dc76e1.nq.gz
│   ├── 275bb0691649e95d6cd427f5f3f44669047c4e92.nq.gz
│   ├── 29871415af2b64fe62e3eaf052a33a10456be3f6.nq.gz
│   ├── 2a924f1d6a8bc930c5296bdb2d5c2d3e39b04a1c.nq.gz
│   ├── 32257db538b2c48df1f60bec251edc355c55c7d0.nq.gz
│   ├── 323eebbbc7b502ea44dc6fbf821cdc1beb6cc9f9.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 3489c59b61d98771bc0163185b22e181c8d5fe40.nq.gz
│   ├── 4157edf27f6e21684e2560124a97aef51588f8a9.nq.gz
│   ├── 41b0cf2ad7bdf43f129de101b631d5c4a41cdfa9.nq.gz
│   ├── 41e774a4b30128d947f5b2eafeb1f260a123c714.nq.gz
│   ├── 423e694c7656efde3090a9ea0b8e12df3415e8a2.nq.gz
│   ├── 45d25fe13537f643b3dd2be158b72302ca109bb8.nq.gz
│   ├── 47dbc97a764fbf165a8c2c528272492b18d976ff.nq.gz
│   ├── 48caaf2c1265108ff82ac0be781cc037a304db5e.nq.gz
│   ├── 493c312bb6c0a543dbd2ccacca6d455486eeff7c.nq.gz
│   ├── 4ba6024e0a7826f657d35d3498267377a9ab0ea6.nq.gz
│   ├── 4cc2c0d95a8c5f49712789c9bc5cf37373f9c0da.nq.gz
│   ├── 4ce62f236b8a4d9a0ad487fa40d0b1d0b8cfba86.nq.gz
│   ├── 51a58d1292508b01b2e2e6e6df6c387b7338e3b6.nq.gz
│   ├── 53db74c9662f6c91a776d01f474c08f28a7046c9.nq.gz
│   ├── 55b0a91b7aae621b1b264f192f2206ff1fe96cd3.nq.gz
│   ├── 5740bc9aa4c76f99c92d3e12be0d3f60956f1f1e.nq.gz
│   ├── 575d2290ee1170e4d6cbcacea814dd8c729df385.nq.gz
│   ├── 5769d2275b71422c0e2e5b5a13ef37a9742af592.nq.gz
│   ├── 5983d0fe2bc91aac4f7264ec694f2012f4b8f5c8.nq.gz
│   ├── 5d26fbe8936d9b10b679e9ded501af5939917048.nq.gz
│   ├── 5e7f3805218f1e944cb1dbf82e5f9a73cc0d8968.nq.gz
│   ├── 63b89c0be97cc0fcb0302b3e2b22fe90ad2a35e8.nq.gz
│   ├── 6799023338ff97fb442ef6ba363b068e105e73da.nq.gz
│   ├── 6918ed24105d97690d0605300d47d020eead62aa.nq.gz
│   ├── 6e77d416fdede9f58d3bbccc67818928fe3530db.nq.gz
│   ├── 7107cec93a979b9a5f64843235a16651d563ce2d.nq.gz
│   ├── 7127e81c638733e42ca1f94fe4b8788c3bf91645.nq.gz
│   ├── 71b0fa098c2691246652627d3d0e8a236c9497e8.nq.gz
│   ├── 71fe378b098f05ecb7b43875f11101d838862086.nq.gz
│   ├── 72a4c6ebd4b97084977eb9602f7edba184f8f231.nq.gz
│   ├── 74e7f0b615e0f270c68050caeb342839898818a5.nq.gz
│   ├── 74f5311742f1d424f6a782f6446e82c8a716d58d.nq.gz
│   ├── 757927cad6ab25a42754ba42e5454c6b41762cf1.nq.gz
│   ├── 78265c8ca58b706b51af1c453b3ace638bf81194.nq.gz
│   ├── 7918c3fab3116026a6626a50bdc8966abc24b0b3.nq.gz
│   ├── 792d5208ef479cefcb65eaa9b2c170d4f4d8a47b.nq.gz
│   ├── 7bba5012c876f14bb351db46f2a3170ed65e6e96.nq.gz
│   ├── 7d16791405bc36b8eb6d642aaa56aa8ede54b963.nq.gz
│   ├── 7e4c114f212585b10b77123e4cb1b1cc703a2d35.nq.gz
│   ├── 84176cc031c01a39df15e55e0d844f027f935836.nq.gz
│   ├── 8419517f5e4215f8fd376bbebdc3cbd899075414.nq.gz
│   ├── 84fd93badd69ef2be8719125e0f90d4b2936ff39.nq.gz
│   ├── 8712676e8c2e53cab48a867d2023e186372c33b5.nq.gz
│   ├── 872b9080a2efbec4340b2e5d22fee1485db8c2c0.nq.gz
│   ├── 872d962c23eb3474af5464c66a2514f6c190c510.nq.gz
│   ├── 8757951a48ee19ccb5bc9f399607337d62d91c77.nq.gz
│   ├── 8787ce4ddbcf7aa104e7a8a69e8e1ca22801a554.nq.gz
│   ├── 87df15cb96c4ed5454a079003fe1d93a60308e30.nq.gz
│   ├── 8a96c69a1942318413af68fd459122b56edd8d69.nq.gz
│   ├── 90a649cd1860a2e16ffe0f39f546468a5a35d4b8.nq.gz
│   ├── 95f021af0939da046cdca00b8b5884c7d7b04e30.nq.gz
│   ├── 96625e7cc3d6c9858fd5e827954be09065b3ab3d.nq.gz
│   ├── 97e0c5ae3a61120f3b801c98c8e18c4cdf787dcb.nq.gz
│   ├── 99cb6cc36291aaa3fecff3c4395f1ead14862e39.nq.gz
│   ├── 9b2ba1766ed02b27c880d340f54dfaf8c3750430.nq.gz
│   ├── 9f50ea82778dcc3a32fd91419be38cfb56aa23a5.nq.gz
│   ├── a28136601fd441efb3a42523c0e683b1b3c45469.nq.gz
│   ├── a858a410e4faa62ce324d814e4b816fff83a6fb3.nq.gz
│   ├── a9e0b34e0f9fa4092ac6ee2ca4bfb6eb611453fb.nq.gz
│   ├── ace6b4523b5892474545ad312ac70e8412808c78.nq.gz
│   ├── ae649dfe902480879d652e18a99f4dcc9f311993.nq.gz
│   ├── afece852829d71b643f40f019215c143c246a1a9.nq.gz
│   ├── b18fe997c4f675b5faf4b483986ec66b025cd8d9.nq.gz
│   ├── b73e6e3a6b90c708046be3239d7f54f37c370364.nq.gz
│   ├── b8d1389d82ddbfdd06f57b2c3705bc8b19959e38.nq.gz
│   ├── bb3bda5171ae797ac2f681cf2bafe1fc70d548e3.nq.gz
│   ├── bbcbb426e94e59ce1de8705495d811507d09a9f5.nq.gz
│   ├── bbe4b59c11ff6f3350dc0210b1e31444a8124dd1.nq.gz
│   ├── bcc751c830a91cfc934eaca33249b8c4b8c99ba1.nq.gz
│   ├── bdbc91796123eb6823edb94a1aefe34497ffb8b9.nq.gz
│   ├── bf072cfbb548e55d4e1a69e4e4d511c3d64451ba.nq.gz
│   ├── bfa6b2620464ee94f210861f23ef7cb443b8e60f.nq.gz
│   ├── c087ff4f67996bca112317eef4f6582b5a9e08c0.nq.gz
│   ├── c1f65a00a915de71310766ab6c63f9305c5bfd8f.nq.gz
│   ├── c4f753e07a38c1a48c10f1c568f75cc123bec5e4.nq.gz
│   ├── c668cdb19026814e195e2298ca8709a1dd3547c8.nq.gz
│   ├── ca17de8f2efd46ec33b19c9ab63b68c59ac8434f.nq.gz
│   ├── ccc1488d6c45aad4e2ed0a6fe17b37203f0188f9.nq.gz
│   ├── cd45af0711f26caac34486e631162bf354abd175.nq.gz
│   ├── ce21999607ed4e8ef087f2b6b14408b0a2b29618.nq.gz
│   ├── cee5a8f7d69f0448f6e6be1c36afd72af50a3b8e.nq.gz
│   ├── d007a05b80c894dc4f244fc4836193ede451c372.nq.gz
│   ├── d06a71d7518041301a303697d2a3c372648eb7bf.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d96755fdaf8bb2214971e0db9c1fd3077d7c419d.nq.gz
│   ├── d96c466d0efbfb48637a68032dfcff5088923cfd.nq.gz
│   ├── dac3cf0b86ec8016bb3b11cc9ab39dae9f681d4b.nq.gz
│   ├── db6242bad9a155b0992b5a479d67200d85551015.nq.gz
│   ├── dbe6ae3af208f8dac13b12167a1c728a3d827f25.nq.gz
│   ├── ddc68e33f14265a10758ef4c1ca63fb6f0f1230c.nq.gz
│   ├── de290f7bfe1dfa6ba8a5a258198d92eb12024766.nq.gz
│   ├── e0eb3d3036e6946e937754e06fa5cf6aad0e9dd7.nq.gz
│   ├── e3174bf93330c46c312dd303435df091aed0b230.nq.gz
│   ├── e4de0c3f0b852bf1cf6731816a9d762dcbb126b7.nq.gz
│   ├── e5412ef88781071070d14bbe33b4909b05bb60e8.nq.gz
│   ├── e5cb2bc76dc26f2ae7565bab152351adfc4b4940.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e79b11115f86b50abce4b59d535a6de5be51d312.nq.gz
│   ├── e7b3d707adbe406b8abfc6baada9b51b566fc053.nq.gz
│   ├── e9fa031275ce53dbfd4031e639393a0ba7726b65.nq.gz
│   ├── ead5e7acc47a84bc24f9332e625487da6f7f20a5.nq.gz
│   ├── ecf9f6b5e611fdcb47bb9bf390a7eb526109e6b2.nq.gz
│   ├── f004f39333ea482611359d20380baa290412c632.nq.gz
│   ├── f1016d3721de7a30a26fe325e988a9e9151c8fdb.nq.gz
│   ├── f233ef29e8fe860ca6b9ab7a54f0071842d468c7.nq.gz
│   ├── f3b582f41966539706ff3026b00d60f2a5be9039.nq.gz
│   ├── f3d89bf3557da7d1913e7043e0e38792945aa43c.nq.gz
│   ├── f71ebd864fc28fd6a3dbe1f46dd3120ef7e525d4.nq.gz
│   ├── f7660b123a0debd47d46c78354f343794e4c57f6.nq.gz
│   ├── f88cc9c143b6908290d32686840abe81d6bad332.nq.gz
│   └── fe746405d689e4fbf9fb39a1feffa21ad33c52c0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8ca7b446a18f3c6db52327c5544e868ca628d599.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 148 files
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

[exa-labs/exa-py](https://github.com/exa-labs/exa-py)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
