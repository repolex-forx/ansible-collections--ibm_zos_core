# Repolex Knowledge Graph of ansible-collections/ibm_zos_core

RDF knowledge graph data for [ansible-collections/ibm_zos_core](https://github.com/ansible-collections/ibm_zos_core), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ibm_zos_core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 46ec35e41b3bb89d4097dc7ad097ec85ad314ae2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 46ec35e41b3bb89d4097dc7ad097ec85ad314ae2
│           └── chunk-001.nq.gz
└── blob
    ├── 016db26b96696bb7195623608049f2f8ce971e25.nq.gz
    ├── 036e07b9e3afedfd1fbb05637bc1c5eb7b8e312f.nq.gz
    ├── 05029b821eac8c618001113e540ec3a16c8b06ea.nq.gz
    ├── 07dd38bb152594cafded28c7291a3bb2a4e4ce1e.nq.gz
    ├── 09c49eab4b0900ff7e89c3feedbe8b579a1e6d85.nq.gz
    ├── 0a0f9f3cedc938215d16471ed83b333416d02a88.nq.gz
    ├── 0a4be1665dbc1b857462b5d7a45b4999d555ed70.nq.gz
    ├── 0afbbd88d0f5c9c2863de762bfcd9bf273c31438.nq.gz
    ├── 0d28b8f25342e0e408ce20db47e42a52fc99356c.nq.gz
    ├── 0da55c83c9ceedf2ddaada0caeb07a0199bc587f.nq.gz
    ├── 0f28a010eba415b609f0a1f53d159e8b7ebf810d.nq.gz
    ├── 11a6358b0e098926adb40cbd95bdcb77487b2486.nq.gz
    ├── 11beb2bd08a4a327dbb1056677a00bfd156272c2.nq.gz
    ├── 132eeff1ee0d6d2cb6c2d32e1ccb9e5e45e7a5eb.nq.gz
    ├── 146af86b95f5921a1c43070a078180bc64d7ce74.nq.gz
    ├── 15552c36e629d0ffdfa41ecd70251248e40713a5.nq.gz
    ├── 15bcce58b7e546a54d25d7d902b35d67a6302d79.nq.gz
    ├── 15d883b340ffb8c502f1c8b5df0e379fd12c7325.nq.gz
    ├── 16ff8e9577327193232f06cc595af357bd5d6d32.nq.gz
    ├── 17e6334c8826ae9a91eb3bfad0aa960f1a5c02cd.nq.gz
    ├── 182fe91dde4b49391df48a3b1df6d8d08e900ad6.nq.gz
    ├── 18a40dd970048a860d968996b35fe15e1de4e7e4.nq.gz
    ├── 19ccb3db65065ce514fbbf94b427b8524c92a9ec.nq.gz
    ├── 19d42c51c9c71b5a314d9f292ed7ad7f48c71c53.nq.gz
    ├── 1a3e031aab573b8fbf2769d1a9d9cc7f4488d9d1.nq.gz
    ├── 1c09ed02b7fecff90303e34b86ba78072011ba2b.nq.gz
    ├── 1d5878766688f4bfa103b0e702a60e23cd2095b1.nq.gz
    ├── 1d7783e38f540df447e229ba7f31979eaec9e4ae.nq.gz
    ├── 1ebd7ee649bfa3148862acb4a75ebb725cc692bf.nq.gz
    ├── 1f563c2bdc3cf06e2e8db2ca59c4f851baebcc68.nq.gz
    ├── 209996fa9a87faf68cda05820d3ad1c55e20a3bd.nq.gz
    ├── 211618f101237f2f77b639b568cf44c6298eee70.nq.gz
    ├── 2120f6a3a7137d16998d39a9f86e0038ed6b626e.nq.gz
    ├── 2195ccdf5ecfa214cc962f1e600b3022db47b7d5.nq.gz
    ├── 21fb26cbd4d93df2e999d36e8c5e1dfe8d45d27e.nq.gz
    ├── 220bde728444450e77d60292c985905b9190486a.nq.gz
    ├── 22c72076acfb50e920771046deca012bf895dc78.nq.gz
    ├── 239b9bafdcf5396d141eb0ccaf9395cbab1bbf96.nq.gz
    ├── 24272b97f0e6edb3c61616e3a822ffffee5f5e8b.nq.gz
    ├── 290ce6c296e0d70cb4d7cb7d082b5423c5d85eef.nq.gz
    ├── 294f6c5d74763945f7e9755ac43b7f425a55a432.nq.gz
    ├── 2a527b492603874f9935e14422e08db76b631c68.nq.gz
    ├── 2af83563bc03fa784fd6b4db975de92c7116bb75.nq.gz
    ├── 2b45d4893b88b4327128f5ee03ed9e156a758b3a.nq.gz
    ├── 2d4c1f924dd8a72bfd18c57b7f3909bd6744d7f6.nq.gz
    ├── 2ead019637c2cc0c93ec8cb63726001b92773c8f.nq.gz
    ├── 3073ce08e51071b8c49239b2190875cee77ab9a7.nq.gz
    ├── 321c4c474deeabd167d376a10d51581368c73d72.nq.gz
    ├── 3252481df6c48c25c445ded7719ca23ced254e08.nq.gz
    ├── 34bd0d7cfedd8b8fc89c1b5ad4d91ad3f0de0fba.nq.gz
    ├── 34e5be0c0b5d540884eeee2b575a8af3eecf5811.nq.gz
    ├── 35398ef8d69e445ee98ea580ed9aa06d903e965d.nq.gz
    ├── 36070e3150ea66c902a32fc56465c61c993571b3.nq.gz
    ├── 3943b5304540e8e258f67a41255a4482c783e0bd.nq.gz
    ├── 39c8741e1df69bbf2d6eeb7440b18aa75cce1ec4.nq.gz
    ├── 3a735902090b63ee246cf9b744a72e194e37cdfa.nq.gz
    ├── 3b35b35526ba8ad5745e6ae3519f9711cd566dcd.nq.gz
    ├── 3bcc077c58a5cd4c1f7043a73449dbcfbf8065ab.nq.gz
    ├── 3c8858f4745c03a272d317448d9f0aa00e22ac73.nq.gz
    ├── 3d9701679d4dac7fcefd9e7418bd0b92b270db9c.nq.gz
    ├── 3dc8914b98167bdaf57158cdcfc05e429b8f26d3.nq.gz
    ├── 3e23bf202aea71a9a24853080e1280e8e97bf0bc.nq.gz
    ├── 3e709a99ff03bc6f45abe5b995d55cd53957afd0.nq.gz
    ├── 3e7617d43459984b03a357871359a30f4f3c758a.nq.gz
    ├── 3fcb8ec30beaf5b839fa566d612edee6b2986dfb.nq.gz
    ├── 3ffdd07c91bcdad976413cec8b082d8715b14113.nq.gz
    ├── 4047f29bcd6c479ac896b5a1b6ab5f87028f87ba.nq.gz
    ├── 40b01871b200823ddadcd9d6820f9be8235294d8.nq.gz
    ├── 41f410a65a74fccb24852e0daddc431c278c2266.nq.gz
    ├── 4237eaee185f09306f20b338501869652e5e56bb.nq.gz
    ├── 42bafdbf0decbf30856f58373f5c64cacacb39ba.nq.gz
    ├── 44364c0592db78491f4b8759f55186d267ef3280.nq.gz
    ├── 44c00d9d2bf26fdfeb47e23ec74ae5fa8ef91479.nq.gz
    ├── 48358966af3c0c151f5b35b3eccdb575f19207dc.nq.gz
    ├── 483fbdb731ab00c8fbca0fcf476b89a8f1c4ce20.nq.gz
    ├── 48ac0cc82dd563d2154962ba37090360bd6f33d4.nq.gz
    ├── 4ab7fbb61eff4bb13798e2280bb2359d90d276ff.nq.gz
    ├── 4c3af3c155802b382d315d0c1e9450569a34fa65.nq.gz
    ├── 4d4d17154c518c7da1ce822c866bc75d9c2ca9f6.nq.gz
    ├── 4e01bbf8b8aac089733b23bdb24ae279868b0220.nq.gz
    ├── 50691209d41164a483223fa958b117f9cf1ac5ca.nq.gz
    ├── 50f44dcba61ee631242e667ae92884c1de037718.nq.gz
    ├── 5172fb284299c7fc81d945a4791fce7788de0cfc.nq.gz
    ├── 51845ff5bcbfb3e907819e274d9c15c7c4990e75.nq.gz
    ├── 521b81281bc485d06ff29dd1500a7956f0e08b8f.nq.gz
    ├── 527b9d681c2bb75f653645e5b2e54af9fb111ca1.nq.gz
    ├── 5349fcbb6b60a9ee92447a59a5517cc4fd521433.nq.gz
    ├── 5411350b905fcb7076978dbdc168cacd2e1c0221.nq.gz
    ├── 5570a3486bf480ec1b5faea25314a412598cf870.nq.gz
    ├── 5630c6dadd9762b1eccc0007e37c8e4709e43c96.nq.gz
    ├── 5744f4cef1e95c95f2bb5e3e6bbca2f0e119a096.nq.gz
    ├── 579fe077d8293e444e1addb7acdb0f0c0f362594.nq.gz
    ├── 590477678e17fdf288ff68403d5d3af23e0e2c9d.nq.gz
    ├── 5a29f7d70964f76b839133c3b3f1f5b42a4a994a.nq.gz
    ├── 5b06f84aee5d8f8d9f41fb9c38da0ed1e3cc985f.nq.gz
    ├── 5be09c0fd246d65f517c2842826a8378cc796015.nq.gz
    ├── 5ca061b9814c7c35ae1072ecf0e62b2b779f9f99.nq.gz
    ├── 5e3f66bf57f7ad97399349053d4b54da1ffeec93.nq.gz
    ├── 6015758475ea2ee0194f12c51098a4c6c98ec7bd.nq.gz
    ├── 6168233d2703f57b9cc7f35ebf7fa0956bcb35cc.nq.gz
    ├── 62f56d21feb90dfa2f1e803741ce135772750c68.nq.gz
    ├── 63cfc077ca7638e0c95927cbfba74ca2a2591d93.nq.gz
    ├── 6536dbf23c7e8160406bef8edd5148fa3b083d7a.nq.gz
    ├── 65bf0f6b1ce0ca6e606bb03d85f999cb036168ec.nq.gz
    ├── 66786e3e8d5ff57b28911e5eb1a32f62d4522405.nq.gz
    ├── 69f0de7ea9ab44b7b4f2f84ebb640b7c404840e8.nq.gz
    ├── 6ac74829c342e9f72132d7f346138d217ef0f7b8.nq.gz
    ├── 6bd30bdd6812832daea6ea800c83a0471dedf807.nq.gz
    ├── 6e105e11be8b9d81049d509b80cfc4b598877b77.nq.gz
    ├── 6e79acd17ea4601c2337d0ef4393307e25acca94.nq.gz
    ├── 6e819aaeb84b6f6044e532665f8a531f39c27d04.nq.gz
    ├── 70654e123b8e61f7de0ffdc00635e26496e9ca19.nq.gz
    ├── 7081e2163b191011e7c4dabcd4f7e2df9ed709f8.nq.gz
    ├── 73175ec355e4a37f13e8f9fa8fd1da36dd0cbf98.nq.gz
    ├── 7365184ef55c7c302257d1e6560d67dd7dbefa9b.nq.gz
    ├── 73c389af0a10d480cb4bfddfc6688b7feeabaac4.nq.gz
    ├── 73f7d6f08bb6e91d502297269c0656a0ff494749.nq.gz
    ├── 742c885d54b288823147941ed4d89e5633cd930e.nq.gz
    ├── 74d4adc0bf8bdee09358164a19d6e16ddb510ee7.nq.gz
    ├── 76cd9a257689c98c77b1b2b128298f75c10f2c87.nq.gz
    ├── 773ebbc904b5afcfeaa1fcc39e442ca0b42ca0fe.nq.gz
    ├── 7789c5abfb08380c172dbf8b987372aa0c000234.nq.gz
    ├── 78e09f6b5ef0bceae16df35824f9d063c5c29d04.nq.gz
    ├── 7965a8264ba580a6d9ab7aa3da6d0ea852105ac3.nq.gz
    ├── 7a35499b9b326e42a19dc5f5b121037f9b8231ff.nq.gz
    ├── 7bbbd7c2c3cecffd221688628fe3ba546c4e12c5.nq.gz
    ├── 7cf1c36de3deb4765c41572a092a8107cba6067f.nq.gz
    ├── 7ec112f18d4c97bdb56ba68c29c1334164168eb2.nq.gz
    ├── 7f172416f2c7d18d37472b0458ded63689e16393.nq.gz
    ├── 7fe9f94dd92bc8fef3d1d0f21c008d4fa0b8bce9.nq.gz
    ├── 836f48e6c635c5c639c4671ec121fed683061c0a.nq.gz
    ├── 84431bcb0e48c2c2928be7a5269fa9c8d622394f.nq.gz
    ├── 84647b974bf9d92e72826d29e7370318a23be73d.nq.gz
    ├── 86aba7f48fb3a67c9384235c6d506d90cc802f34.nq.gz
    ├── 86d21f0d5615e826955d4b6947c2a45ef9bd4b33.nq.gz
    ├── 88609aa950016468632209ac0004ee8f257caf39.nq.gz
    ├── 88d8bdc88953321467a864ac64a1a064d56eae99.nq.gz
    ├── 890c2a69faec37405bd5fb7d84c244103e1967c5.nq.gz
    ├── 8cb31d0ce78891ff0cd45eec384ad44321ef4dd9.nq.gz
    ├── 8d194cd81093118c0827af512822d61a0914fc21.nq.gz
    ├── 8f2d8269b4e0a47fd112dd80288e5e7e721894b3.nq.gz
    ├── 91a87fd131005ae1dfd64c5909cfd5ceaa7b4e1b.nq.gz
    ├── 91af0639e3aeec590f48c4ce51909399b4b459d7.nq.gz
    ├── 9313dfb977faeab7808ccdbd2b7e76e51d49dbae.nq.gz
    ├── 94f077e1e9a1b3038df88393fe9baf94036d69b2.nq.gz
    ├── 959acb79281d7ad3b99c3038d118369a18cd179b.nq.gz
    ├── 959bcab4298a5d84767189690a63cb048dc08936.nq.gz
    ├── 95ef54230900f6a15a4b60c40a8091095923821d.nq.gz
    ├── 97a58a2b6d9b812a4138cb87774006e86a493e33.nq.gz
    ├── 982908dc9ccf7cd3a66d6bdddc38d9c6a1444386.nq.gz
    ├── 985169ac7cb129f983e28fb215c83c926e5f2331.nq.gz
    ├── 98d5faa08a6cef883e508cbea030e7843b1178cb.nq.gz
    ├── 99334a6e6d8e81e76de3a871944dcf0131ad03f6.nq.gz
    ├── 99919b44090de9e7d7503afe8e513120e5bcc163.nq.gz
    ├── 9a04d90fbc26839e28496e074b97f7fd963dfe0d.nq.gz
    ├── 9b5ce50146760c619c5d09e1dffa31136e8fdc4e.nq.gz
    ├── 9d350537e9f844a5c63c11b2ad8c051d85a14d92.nq.gz
    ├── 9dc9a9e41e6eeb312a311fd6aefd6c47c1b709ec.nq.gz
    ├── 9dfc00c3da7df91655abd85b16de3ea2014dda39.nq.gz
    ├── a1be804d8fd9f25e970e37e87a31e2906b99c73f.nq.gz
    ├── a41f70a72ee1b9727ba6214ce0d9f740330a081b.nq.gz
    ├── a564513501c3e1e70eea826760ec0626970de42b.nq.gz
    ├── a645d3362e3c06bb6a3e6aa3cc7012a960991fa4.nq.gz
    ├── a684e856eba4695e6088aeaf5eaeb8b5fd56aa01.nq.gz
    ├── a743bf540ee2e136bd78875fbc156dd38edbb6c7.nq.gz
    ├── a782962ea3c81679a5ff698c33d85a7b1722188b.nq.gz
    ├── a7ab4a8032742d5bc8ab2e5f80befe017315aa3b.nq.gz
    ├── a9aa57148918e3b33d1e2550aa4b25ab2b8bf834.nq.gz
    ├── a9d0510b8c3fbc67f501714bf0d140eee9a1e2aa.nq.gz
    ├── a9de1c9074344bdbdc6156d48025978d36873f49.nq.gz
    ├── ac04848fe29cbe534f180ad9252292cc88e3e3fa.nq.gz
    ├── ad2c79f43f1325b6683861367d53433bf56da050.nq.gz
    ├── add1684572246ce799ce7da2adeaeeb779fad6ec.nq.gz
    ├── ae88f53cdb517c6814f0d1a8f58f77ce0dd95043.nq.gz
    ├── af05cde2ec61344907bb02ea8feb43aae695078c.nq.gz
    ├── b2c00bc49911483b60111ad99a6324f50b82cf64.nq.gz
    ├── b30fb0b5549f7b0c73f694b9fc0b5bab84735609.nq.gz
    ├── b3a1d908d45db2c806bb3178b079586f781c18e8.nq.gz
    ├── b5409ff533c31c91dad2c4ac0c6ae7b914b6798a.nq.gz
    ├── b5f025772e899136a74d9a4687b1c6bfc6cade3d.nq.gz
    ├── b5fcd4405debdc1d756e1118ffc5ff3d1baa5eca.nq.gz
    ├── b638b8574d90abc25cca94b3f62a6b51e65cea9a.nq.gz
    ├── b6cfa7d04ab8d39c68ce3b9132040d2a65985131.nq.gz
    ├── b721ba7c889a8c7868c90ae55675b81736e01e8b.nq.gz
    ├── b8349e60d28aa36d27b42cfb290034df1239e414.nq.gz
    ├── b8b51363bb111eaefcb6772a9d6eb28b611cb7cf.nq.gz
    ├── b8ce6bcba3a2ad0a5b369e6dfad06719d500b225.nq.gz
    ├── b9a8bce780d0927b62915ac3c788ba6566a58bbf.nq.gz
    ├── b9f6217a8c2f86c9dfb2a32389b027119d7c52e2.nq.gz
    ├── bac392e80bd2ee41fa40d58033712d8a18a6acec.nq.gz
    ├── bb1f8a82bc187585709e6f7d651b18f23e1545f9.nq.gz
    ├── bb5dd702183a90dd1747f4fbaab07e36dee048ae.nq.gz
    ├── bbb6e0380cb2f2370fae5d766b0bae3a4b7586e4.nq.gz
    ├── bddf624b8def091f26fbf724c4ad1fc5958f3e98.nq.gz
    ├── bdfa4653605094d5ae085010d53640265d260b03.nq.gz
    ├── be630bbc79dddf193935f4947f35600769e254f7.nq.gz
    ├── bebe9860fb3eb57ba80f1ffe8ebe5302987fdad4.nq.gz
    └── bf4fe17a706693de823ac71fb0618f78d7cfb5a4.nq.gz

7 directories, 200 files
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

[ansible-collections/ibm_zos_core](https://github.com/ansible-collections/ibm_zos_core)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
