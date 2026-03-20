# Repolex Knowledge Graph of markkcc/crxaminer

RDF knowledge graph data for [markkcc/crxaminer](https://github.com/markkcc/crxaminer), parsed by [repolex](https://repolex.ai).

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
lexq download markkcc/crxaminer
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 0049354ebc8237bbbe0c5ddb265d8d7d9db77122.nq.gz
    ├── 01aa77324971032e2d4515705d361bba5506fa5f.nq.gz
    ├── 035f64755cef93f8c8c9479e1b0fc8fccaa83766.nq.gz
    ├── 04b34bf83f34441a1f7ae93a6f7f6ac0d27bef16.nq.gz
    ├── 04eba59fb7dcfb31b2c023205fe410db956d4e01.nq.gz
    ├── 05376348935c6b48e5fad3e6f76a77cdc4d4b8e9.nq.gz
    ├── 056be1b9aa4e5bf32d19431bd5963612d944ca91.nq.gz
    ├── 0818e0bb316402272f7f521cbfd364c76d6d751a.nq.gz
    ├── 097fa19e639ce61b96e5443b8287e973b1d716ff.nq.gz
    ├── 0aafa3d16bb8c2015315f85de3f9991067993864.nq.gz
    ├── 0becaac10b2f182a7da006e98d8744d81a8a648a.nq.gz
    ├── 0c22470ec14ec523287bf465a3a3b9c1939a9908.nq.gz
    ├── 0c45eef2955b609825f7238cc8cf05bb7f6fb0e0.nq.gz
    ├── 0cd308c055689d7f5bb045bd0f93be8b237fc9bc.nq.gz
    ├── 0e01502fa743eda351ae31c308ad7d71bd293889.nq.gz
    ├── 0e8a13b29189f8b42aafe1376d2fffdb94402366.nq.gz
    ├── 0ee620794579c6ae43bf50c9d7c36b6499206e2a.nq.gz
    ├── 11f836e1d02f3a5fd887fc0919a742f55257c216.nq.gz
    ├── 127e5a0615355334e47ffb59a93101c0ad7ddfaf.nq.gz
    ├── 12fd7a9453f54655c59ec630e4dfb48c757b7d4b.nq.gz
    ├── 1303e39019c9f545b550ae166b5d379b6e0ca47e.nq.gz
    ├── 131f12b7eb1c091916de5ea5c151e38887583ef2.nq.gz
    ├── 14ec4f576dfc8513226a404bb483fcb3ff08e650.nq.gz
    ├── 1723f3acb4888cf8ef08453b88eb5ed6fcd111b3.nq.gz
    ├── 181763e4adaaa66ba57ad215044e3e6ed2050d12.nq.gz
    ├── 18320091e55e2b66bf9b6fb51a030cf54b80be48.nq.gz
    ├── 1857c64fc2585f606873dd95ae88cc7704f018dd.nq.gz
    ├── 1a3fe6bb3ef722fa528d4f802b3d8f55d5583101.nq.gz
    ├── 1ab0a0ae816fe149df3b34c0fdd31c882941a79b.nq.gz
    ├── 1b29fd07a7199c28c103b61bdeab5d43354e05ed.nq.gz
    ├── 1bf27ee95c8584f668f0c693052c3239ab41146f.nq.gz
    ├── 1c6aa5d508bffe3fc7dbdde53e5d22d2b5128a09.nq.gz
    ├── 1e69b32e81d6538a11382d3502d55db7c840517b.nq.gz
    ├── 1ea809d1a3f2f435c6e78d5a7ffd7ca214649174.nq.gz
    ├── 272ba7bec22210109df031521768b7291d228fd3.nq.gz
    ├── 28cfb9f279c9f27359235a1cd1abee477f20e0d2.nq.gz
    ├── 293ef119aaeea7ea17603158a2794042ea9dacc4.nq.gz
    ├── 2a230afb4f2612fb9616f22695cede545af46f69.nq.gz
    ├── 2cf20f900494c1eecb56f00415625e3d2177e193.nq.gz
    ├── 2dae2a973a095e8fe68e3866686fec5b462dc9d2.nq.gz
    ├── 304e546570f9c60c937a451bf983a14b2b3d223c.nq.gz
    ├── 31675dbeb1f061a35be0fee37f706640ab70e217.nq.gz
    ├── 32ce74d84e807a104f3352aaca46b8813db4088f.nq.gz
    ├── 33c4c04390290cd98d6bf1d80d1cbc6dc4af8fd0.nq.gz
    ├── 3464d7a7b96752945b98446fea60a19c01addeb0.nq.gz
    ├── 354e2a6728e2e88bb61d4f118477da6e4d6a3504.nq.gz
    ├── 36bde2d832f6c5c1545ec6eacb82cbb79f4473b6.nq.gz
    ├── 37f0bddbd746bc24923ce9a8eb0dae1ca3076284.nq.gz
    ├── 3860f659ead02224f524351d612cd92aefcd5d8b.nq.gz
    ├── 39361ba7523217fce8af841b7418a94958199cd2.nq.gz
    ├── 39dc10efdc7e63466d87648c9e94fe200019fdd1.nq.gz
    ├── 39e4a17ccc9e42d99b256d6b571b3ee228212293.nq.gz
    ├── 3a8d6e5b6cbda399e75848d34138c0b69adb690f.nq.gz
    ├── 3aac9002edca73300507bcd9f9589ffb36ba1faf.nq.gz
    ├── 3addbb65e2c7d495903be68411b74ced8b1de64c.nq.gz
    ├── 3b9b24ce52bfc9161d8af2165261447c8b889dc8.nq.gz
    ├── 3c34c8148f105d699e8ec9b769531192f8637d9a.nq.gz
    ├── 3e19cdf3063e246dfb9293b66804c30bfd03f97c.nq.gz
    ├── 3e650bc120bc061a86238635ad19a2af026b0495.nq.gz
    ├── 3eaff566dbf879dcaca8a08fc4e95e1e43562cae.nq.gz
    ├── 3fd6d0e520112a862b183984053f9f0a665643d2.nq.gz
    ├── 40330c0ff1cdcb147d15fbbe1cc8f633ea948eb0.nq.gz
    ├── 418c55bdc3b9659b93d625f277c9587c6b28e9cf.nq.gz
    ├── 43d3e167e2cc8ebd59bc9df0f20a47547de397ac.nq.gz
    ├── 4746de28112d7b39f4669c6728e0dead3ad010a1.nq.gz
    ├── 4814c63210f677c0163190b7b5b751e43556039f.nq.gz
    ├── 4817a1d8ffd73bc60eaa4a0503a4645f74bf653c.nq.gz
    ├── 48f18eed9cef10abcb0035f5ed98357bdaed7344.nq.gz
    ├── 4942ab66948b7fbb64de6600664e2159c243f9a9.nq.gz
    ├── 4a3c09a6889a97a54af8cbcc1a47e03e58cce376.nq.gz
    ├── 4ab27b4605d8a778196e73e65dacd4f24284f0ea.nq.gz
    ├── 4c0c48fc71394a4966b9f0e572c08655a1dd8d97.nq.gz
    ├── 4c35cc5b6c5bbe2a9deb6f778b9adac60a79e905.nq.gz
    ├── 4cd2e9f3c883ee9291f6d1729eed12f31a1d8e42.nq.gz
    ├── 4db96b08bd963b39f4071e69e34c21a18b7fcead.nq.gz
    ├── 4eb04115e561fdf6afd951aaf0e2720eaad480b4.nq.gz
    ├── 4fbd6ed970cb439af968458dc6aec586ee0dbc76.nq.gz
    ├── 4fbf10b960ef780b748861e6a616a4d88b00b50a.nq.gz
    ├── 50050d1d2661541089ccc4f6b332034348ce7f96.nq.gz
    ├── 5073f362e25d5dd49582cd6cb489bd226697d64b.nq.gz
    ├── 5384f4e4f45b186e263f365811f766cc392df88b.nq.gz
    ├── 539e05b3f2c2deb650ef6ccb2627cb2247e7caf5.nq.gz
    ├── 554b8936fcacbcabe77a816697fe48af08bdb044.nq.gz
    ├── 56fd588970e25a425c9c972f062a302e4ef06fc6.nq.gz
    ├── 57567d69b4b6aeae7a5d0386fbe0fe9b71c212b3.nq.gz
    ├── 57578bdb625c984891f6997a304fad67ead7fc1c.nq.gz
    ├── 58887a2b71e319e7f1baecedf63002daadf2662d.nq.gz
    ├── 59718f62621e554ac81282e4e36d36f79d6cab81.nq.gz
    ├── 598a0eda631e23fef7e87517ca1e99a351e30d92.nq.gz
    ├── 5cab5b90fd79a3fe4fef29a4113fde1238e63e2e.nq.gz
    ├── 5d0f52a64a2f7181459648bd428bbd439d778a5a.nq.gz
    ├── 5f9841dd021cdaafdca35623522f3997ad571a49.nq.gz
    ├── 5fc994339fb36af948f8bf9dc3090f6ddf70fbc9.nq.gz
    ├── 5fe310ca06164bbe7ea2ac920a33dba86dff8ea3.nq.gz
    ├── 619eedc636a14747c170a66052e125b2faeb9b4b.nq.gz
    ├── 6362a76434202f8ceb8cdf733e87faf547a8a41e.nq.gz
    ├── 63c4190b7fa0c2486d319263e14a4b021b06c7b4.nq.gz
    ├── 63fb152aabbc82e1657ce3f2a83359b47987db7d.nq.gz
    ├── 65c548fc401de17c1c3d5bf09e415dab947a1073.nq.gz
    ├── 674fc6981809545d1b5335a30cd3565b72ba306d.nq.gz
    ├── 675fb7b48e4c92df9d3d7eaf16e3d2ce0840d4b9.nq.gz
    ├── 6a5baffa6398820e91dc9ee38faffd1e06b9fdfc.nq.gz
    ├── 6afe9fc25a95a504f45c7387ee83a9756f684276.nq.gz
    ├── 6c1ecdcda2435797c632ce2cf5350b26bc3e00fc.nq.gz
    ├── 6c349ae5e37433af7fd8c4ced3b219e710a368c3.nq.gz
    ├── 6c9cd11d7c266c11054e48f5b7687ba0cac034a2.nq.gz
    ├── 6d7b1892c1a0296be61ccb6bbc4636b7e44300d7.nq.gz
    ├── 70c2757e7044848a614ae08d4dc2fface7560a9d.nq.gz
    ├── 71a3ee82e2501acea5f51f9690dc64ad8be5d14e.nq.gz
    ├── 7517c95df135884e829c59c8b2a01e8aab421040.nq.gz
    ├── 75405937b6b413b4a4f107856cffaa475fa4d6b1.nq.gz
    ├── 75747d30168866711123ab0d066980aaabd85703.nq.gz
    ├── 7751347d6787319a444bc979e6fecb1bdfab405d.nq.gz
    ├── 7938ef6bbaf769631aca335e464c1a78300e88ef.nq.gz
    ├── 79dcd513ec1e565f8018f3a3d0d0195a8fe60a86.nq.gz
    ├── 7d054697c90d5582f7adcb1b1401af136053665d.nq.gz
    ├── 7d5ad763a47c8a2483074694485296c8730e62ff.nq.gz
    ├── 7d6ad98fa390461db4afb6f4e1ebed0b47aa60bf.nq.gz
    ├── 7de08f93b3de59f72908a92ebc16acb926303a1b.nq.gz
    ├── 7e58a3337800562128215ffc600952a71c7c2631.nq.gz
    ├── 7efeb7add6220981815dc9b692083013c7e25043.nq.gz
    ├── 7f7d71dcf78d30bf563fb413fd31c6cf3dc4fe49.nq.gz
    ├── 8197604352372fa26ad46782fcfb037e568760b8.nq.gz
    ├── 81d963512928b5d560e609ab4292fc81683bc283.nq.gz
    ├── 824f599e1e9a0d02f5c260d939d24a378a9008e5.nq.gz
    ├── 82bd08945bad7fcebee94ffbe2b7d2ab7e5ddcb7.nq.gz
    ├── 8698d5c7b07deb231bb3fcdb26e60c042cc556de.nq.gz
    ├── 86b47a276c1842a3cf0a8962baf6b745fecd6d2e.nq.gz
    ├── 89dc9f4c5b235eba72a23f16939ebcd0f6e96d96.nq.gz
    ├── 8cc3f23d0af43a6c096246934325de4ec9be7449.nq.gz
    ├── 8dc43234357fca35624a6991774e6b078a391a70.nq.gz
    ├── 8df61e8b8a2327d6f0e4d5cb767fd44561a47651.nq.gz
    ├── 8e8dd54dca9e2140c7e31cf54426a15a0acb91d3.nq.gz
    ├── 8ff9371552c8797be402e65a0977ce149e84b75f.nq.gz
    ├── 915d3cf2b99926a6dcd61eee3774e06d0782ad2a.nq.gz
    ├── 916cd13bece0dbdd6aedca777be5df28a107b1a5.nq.gz
    ├── 91f43b23203e633146ce0579b3b0f636187c498a.nq.gz
    ├── 92c81d49acb185a78bf6e8dbe4be6a0ca0f9ca85.nq.gz
    ├── 92d526f47e4c6a610b933e7add160ce52e3117b7.nq.gz
    ├── 93f13d99baf2a4686493444b618dc2b8c5507e6a.nq.gz
    ├── 968702e323b0c390a6a3a21a8bc467b5ed00c454.nq.gz
    ├── 970e6346b0e3cdeac7a2ba7d1c15915b596b7cab.nq.gz
    ├── 9759372006ad347958e1f3024b8d5469d5adac65.nq.gz
    ├── 986d1408e0ba21f015e21c68775f19055c8f4285.nq.gz
    ├── 988a5ddc460f03c2cafb3b91d98f0cc930ebc8ed.nq.gz
    ├── 989ec80c76a1b118b97526afbcd72169fbad8763.nq.gz
    ├── 992d04cf5191e7d243ff4986687f51e5e8caa873.nq.gz
    ├── 9a5ea7383aa83eec12490380a7391d1bb93eeb96.nq.gz
    ├── 9a771a398563109137a72c2dfc10a10b99d0a745.nq.gz
    ├── 9c25013dbb862ffbc9b2b7ed79ee28017196db35.nq.gz
    ├── 9c2ce22d4ce6090ffa540ca9a196c614121b1eef.nq.gz
    ├── 9d8de8c0e301ef73432a11740c1b01e35eafaded.nq.gz
    ├── 9dc351764500e5a2ed5a0daf59bfe7a7a4e9cbbf.nq.gz
    ├── 9eace59c41e6a3a63d294e53480eaf5a8945e014.nq.gz
    ├── a007d6f471f7a5378d63e90ae107a866ee8549ff.nq.gz
    ├── a248513b2427144aac5cf9b81fc61f2aa1ca4170.nq.gz
    ├── a7237f298a5a4f87c6665ef592e2149dd0691402.nq.gz
    ├── a7762c991967e65ae54b842ab6c3c791e5a6901d.nq.gz
    ├── a8028c3ad20feb3b7617e019f3ca4d3c6102f11f.nq.gz
    ├── a8a2a22bd9defa84bbc179fbfcfc95e07d5024dd.nq.gz
    ├── a8a38884bd098c5fa725c7c9af340db3b43d6bda.nq.gz
    ├── a93dc5cfc45b4a4791f04de19ec2a6907b5d2b46.nq.gz
    ├── aa5135501ee2ec53270b20bbf85176ca7067974f.nq.gz
    ├── aa8d04e22bdd98501d673e3bab1ca0ef6bd03d53.nq.gz
    ├── ab4a88e8dae319f8b20bcec193843ce24d1f7959.nq.gz
    ├── ac39df46605bbb0d0245b4a9f48e712d188647aa.nq.gz
    ├── ace1c9ba08ad76f113b8cb284494a1d65cc3749e.nq.gz
    ├── ad72c7d53c221932e73560955b2b1ebc07c6a07f.nq.gz
    ├── aef28e3cdef1aa03d803eb680ab45b0c40995a8a.nq.gz
    ├── af86160052eab8f016a81309db4dbca890bce60f.nq.gz
    ├── b066e587356e546d432b1a33c1b5980aa9ea062b.nq.gz
    ├── b0f4e4ffb6f0c1839791bde4d53c46adde8b3cd1.nq.gz
    ├── b16be87d6b1f10364e57d1e01901a30070f18258.nq.gz
    ├── b3076b38fe14399a56099ba187b1cb21cac15f09.nq.gz
    ├── b3a13fb7bbbf2b8a4666ea12446a7903243713a2.nq.gz
    ├── b57fa0fccc74ed0201e4bbad6343f6e4218aa321.nq.gz
    ├── b63caeb8a5c4a21feec3ea870c4e4a52b89a8fa5.nq.gz
    ├── b846c6ac20907c29e7564789735408df9439833e.nq.gz
    ├── ba9aa2374ea70f51448b09bd255c7be2f7d15a9a.nq.gz
    ├── bcbd2fe88f60c8d97fcd6328a5e87ef06607e100.nq.gz
    ├── be3db3c0d62cbe282139b11deda7c646f7e72ad3.nq.gz
    ├── beeae82e993d1cff9bc48f92037e86e973be9c07.nq.gz
    ├── bf6ad185e5a080124d0354bd484a2295b470c3d1.nq.gz
    ├── bfb423c6f31ee3fcfee6bc445b25403f2cd915b4.nq.gz
    ├── c0b717f7ecbb904e158e17ff5236b05211e03f81.nq.gz
    ├── c0b840e7062613191a4cbf9923ec0736c09e140b.nq.gz
    ├── c19f78ab6836efd56c42aa56457d58871d9e2782.nq.gz
    ├── c1fc712b449419c3745f4545a29e7e1b7db38d74.nq.gz
    ├── c2095b11743b1dfd2b8bab2a8b9f69eef7d0b263.nq.gz
    ├── c310539e5181573356bc09e38e0ca9321e6cf6c5.nq.gz
    ├── c40fedfef0aaebbd40d24531fae86b0eeeed6df3.nq.gz
    ├── c4c9dbfbbd2f7c1421ffd5727188146213abbcef.nq.gz
    ├── c4d8dcafcc6b6c0d62151e763f8ba34f57b514d9.nq.gz
    ├── c60a9e4e0af8d77791a59cc2148d3219c74020ea.nq.gz
    ├── c6cf6dd7198f8c41aab8869d93eb36effa6ea03d.nq.gz
    ├── c73f5bd542fc5970b9cc1b372739b2fc50f4098f.nq.gz
    ├── c8f0c44a8645da4c2d09a402e7b3ee4474b770b1.nq.gz
    ├── ca9541a30f42880f2b8b63b9728af2dda8839a81.nq.gz
    ├── cac5315775258a68f5e18885605d3fb1b758319e.nq.gz
    └── cb0ff5c3b541f646105198ee23ac0fc3d805023e.nq.gz

2 directories, 200 files
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

[markkcc/crxaminer](https://github.com/markkcc/crxaminer)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
