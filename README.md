# Repolex Knowledge Graph of cherrypy/cherrypy

RDF knowledge graph data for [cherrypy/cherrypy](https://github.com/cherrypy/cherrypy), parsed by [repolex](https://repolex.ai).

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
rlex download cherrypy/cherrypy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f75bc9eed8e0e385f64f368bd69f58d96fb8c2b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f75bc9eed8e0e385f64f368bd69f58d96fb8c2b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c228b6867587269f395f3590c92a3b2756e026.nq.gz
│   ├── 00e31356b0dfd82e6ba5fb897a1a600048b06e57.nq.gz
│   ├── 03a2b0600f8a1daf62e04d6dba0e74fa9acd62b7.nq.gz
│   ├── 03b96b857102200db20d0f2e5d87fff0b8aba8b7.nq.gz
│   ├── 05b3eee706e7192a73fe109f07adc06940952d3c.nq.gz
│   ├── 05bb17ad71cd26f102b362fa1a4783749d336493.nq.gz
│   ├── 06fa74507e95978947cb85de5c6ae66c6ce694fe.nq.gz
│   ├── 0828006a308c74095d3f9895a621da04f1db351d.nq.gz
│   ├── 0878b740f5d39e1ba9d0c378ec24a2cad127b9d8.nq.gz
│   ├── 0a8b65a014eb9da96fce1716338cc003e2379030.nq.gz
│   ├── 0ab0fb4f1e18cc30cd06d8baaecd48d7462031de.nq.gz
│   ├── 0c839dcba3487660120c4d0b60212d5efeb395b2.nq.gz
│   ├── 0ca8a4e93728bbd74844bad9f37f27e3be16408c.nq.gz
│   ├── 0cc7f07d21816a8f6b5f5622d7241e0ed9bb512d.nq.gz
│   ├── 0cce9b4ea53c044bcd9b5ff83cb467ad3196ddf0.nq.gz
│   ├── 1508242231c9c516fb8d8e14736a962a0576766f.nq.gz
│   ├── 15834b7e35f2bf7a06ba9aafb82a37f74ab5d5a6.nq.gz
│   ├── 17e7c7372b8bc79fe78db5a06e692b9b56eb917e.nq.gz
│   ├── 1817ba07a9b7f31cf338089cf496338dbacc418c.nq.gz
│   ├── 189e9a0fa682cff68f2c60af8388c0eecae33f19.nq.gz
│   ├── 18bd840b4dfe3a800ad85a21203df126dd669106.nq.gz
│   ├── 19fa995d4c95e68d957a3593ee5e394c2eb8724d.nq.gz
│   ├── 1aad300965128f66b410582d286dd67d1e1a0a6f.nq.gz
│   ├── 1c4503e8b9795aecb58989f35caeb79ed3e244b0.nq.gz
│   ├── 1c6d5d27b8a9f83e1471d43660c0683e55a1f259.nq.gz
│   ├── 1e65b7486f64390eda40889011644b2eb7f65116.nq.gz
│   ├── 1ea2dccaa7591760e975bdad2c828c1430314703.nq.gz
│   ├── 20b4d1178acf8eb2ab5f7b1a26d43c4eeb50c13f.nq.gz
│   ├── 226dfe18f73406a8f56c1a4b3508ca5e3601853f.nq.gz
│   ├── 247576ff0a3facd2808db199002e5cd0f95817b7.nq.gz
│   ├── 25db5cdf32c835529b9d7cf285eb6dbadbfd8d07.nq.gz
│   ├── 27f5471dbfb31c29333a5d2fd6646b6e58fc805e.nq.gz
│   ├── 2be2a5f9cefcd59179a577a5b8ad0e3295a8aec7.nq.gz
│   ├── 2daca0087d2f5dce33fb609ab41e7b5978a70972.nq.gz
│   ├── 304d87a5d5601cb2f423dd38bddd3f25cc9b084e.nq.gz
│   ├── 3062eb35b2c0eea697f87beecc5c4fdd3a68089c.nq.gz
│   ├── 3110004b70e4109fe1bad1883b4f44ea26607e5a.nq.gz
│   ├── 3110b5e840d8c109beb7951ecb3b8b294da243ea.nq.gz
│   ├── 315026706566dccfe520d50c80585c8493b7e446.nq.gz
│   ├── 32e88ac95b5746802028eed3e0e3de3fb4e91149.nq.gz
│   ├── 33074979ee9b5e48f706b1ca80939c6157163ca0.nq.gz
│   ├── 3632a5ac0dafa91f090141ac69c93360fba8710c.nq.gz
│   ├── 3ac4de2ba9d5fc542325379e7334f1345fa65511.nq.gz
│   ├── 41f2eeea2a22891ddd4ef556f8c9022786cfcc98.nq.gz
│   ├── 43437728db83069a3000aa1dfb3bdcd72c8aa81a.nq.gz
│   ├── 45797b3ef4ca66b96252c4b9aa7bce7d41ce5443.nq.gz
│   ├── 46bbd4f1eb9de0ef2e06092dabdda3beac53a3a8.nq.gz
│   ├── 47a47042b603d660e6640ab4adf689967f09ddb4.nq.gz
│   ├── 480ed39ada1e27f501416d6a49bae2ec6ece7727.nq.gz
│   ├── 48f7703d72707719afceb1e8e4ca67f9acfaad87.nq.gz
│   ├── 4e55009163ed20d1ce67c8bbdb8d6b3789d48614.nq.gz
│   ├── 4e838bbeaa2021823edc4a52ad3589ce994af80e.nq.gz
│   ├── 4e974979bd90da661ce8231a3ec36a9ad9a0e70d.nq.gz
│   ├── 4ef85580f1b1408a6a5fb13971b7a8b453b911ef.nq.gz
│   ├── 500bb256c38133e291e6727c29ba9740aa7d8bfb.nq.gz
│   ├── 50b7362f06cff0aab0afc581529b3d6e987e756d.nq.gz
│   ├── 52823dfb53cd5c5db5a6afec418114067da7b6a7.nq.gz
│   ├── 52b6cd56c5c1b2d17b8718e4e2ac1cdf5dc46d45.nq.gz
│   ├── 52e29d4909106f25dd5c1f5c5df114b293ac9fa3.nq.gz
│   ├── 5cc335481b7d0af5217703f08f01912589e30e0e.nq.gz
│   ├── 5cdde927c33e87ff84646c8cf0c1b7aaebee0591.nq.gz
│   ├── 5ce8b9bd4f36075666904ae5f3ef5d9f48f873f5.nq.gz
│   ├── 5e224435e40e560a880f7f6e27bd12c5876e14df.nq.gz
│   ├── 5f602e281dfd41b51f047699bd78a8dc4c2ddca8.nq.gz
│   ├── 61176fee9ff9429019d04721cac518796f70364b.nq.gz
│   ├── 618792f57f2137befd98d51dfe1a2705c5aedda0.nq.gz
│   ├── 62c406c27798f02209bd1f7c4cf7cb23d0f1e799.nq.gz
│   ├── 63250fe3a36a01d553d7b57902f77d0df8f7da1e.nq.gz
│   ├── 6364dfb69ea3196b6655ea8b41001a04fa0ba3a2.nq.gz
│   ├── 6537fd30c0ef53719ac6b96fb23837c12870ab0e.nq.gz
│   ├── 659df56cbfb52c8372d7415db035ae47359e3fa0.nq.gz
│   ├── 6aac68d0473b56d49ef27b02122ef2463d8e6147.nq.gz
│   ├── 6acb3b415aa0ee5568c3c30ff1e447d21c53b6a5.nq.gz
│   ├── 6c9e17d52691671d16165cf7f32d6c693b1a3b1d.nq.gz
│   ├── 6e054ba7852aa0a361542f32207476ff80e35a87.nq.gz
│   ├── 6e4f144cf45ae1e1e982e28c31c605e373ec407a.nq.gz
│   ├── 6ed3898373838a85d3dc1bf5725def8662646cbe.nq.gz
│   ├── 6ee0a59c19dfae833e1bb2970d66eb225822cd2f.nq.gz
│   ├── 6ef52ad7c232196d5ae4ecbc3f94e9f7373ff9e2.nq.gz
│   ├── 6f863a50642e209d0f3d223ee136b685a8541c3f.nq.gz
│   ├── 715f85a6e9cfae87aa3f0f744b1de81336a3983c.nq.gz
│   ├── 71a69ced7f3242d5ff9d5eb0b13ba11a1e0066e5.nq.gz
│   ├── 71b6010e4132e633c1059c14f3f84ad6dff23f96.nq.gz
│   ├── 724f9d72d9ca5aede0b788fc1216286aa967e212.nq.gz
│   ├── 72dc49a5c9300755b48359ff41f46fb638f01bb3.nq.gz
│   ├── 75e4e96cd3c47842e268970dbe0975521901000d.nq.gz
│   ├── 76366789d9fa07a50143c86cc2419a76962cd41b.nq.gz
│   ├── 790bf96c9458e015095d078779015a01a289918c.nq.gz
│   ├── 796b96d1c402326528b4ba3c12ee9d92d0e212e9.nq.gz
│   ├── 7a913a980b204217b8963ee7c9c97a2a2cb2c1b9.nq.gz
│   ├── 7abb75a01009ac1a5130f3ade5f6e27b1ec243d9.nq.gz
│   ├── 7b4729209029b3474bfe63034cc3e47b226e74b8.nq.gz
│   ├── 7bd7f194e69423f07629c1444152b41fa42bdd82.nq.gz
│   ├── 7c6de4c81907ee73c220a65556f5da2c9abf6ce6.nq.gz
│   ├── 80403dc227c19b9192158420f5288121e7f2669a.nq.gz
│   ├── 8434beab789f2f5b8eae451283ad0b8b42db9e1c.nq.gz
│   ├── 84cc7a593886c8ee4d37cf7182577d28bedee98c.nq.gz
│   ├── 85c449b3e2e3b92bb82705a8f3799e5387c39eec.nq.gz
│   ├── 8882dcb6b32d5cf196501db16830844389013bdd.nq.gz
│   ├── 8a926aaa40a3657d26c571c3d077ebdfb137ef77.nq.gz
│   ├── 8c279a6d0da6ebe58f9f2af123702adadd8215cc.nq.gz
│   ├── 903118b2dc84f0b9429a323514d18b89222424bf.nq.gz
│   ├── 908ae13deb515b1c806194e1f27c0405c0e3c87e.nq.gz
│   ├── 92e92d902f19b4f8d03bc998ce690edf34921d50.nq.gz
│   ├── 941575b9243f1bdf7bb116e5ce60ccdfde420237.nq.gz
│   ├── 960e502130fa91d3e65932f24ada9c861cfb7991.nq.gz
│   ├── 96fcc68c447fd39fee6e047106beefc6f0adc07e.nq.gz
│   ├── 98792ec214edb0b3792d67bbf09473add332bc1f.nq.gz
│   ├── 98a203a82dc7f2009425c7b4b18f7cfb0ca1bab5.nq.gz
│   ├── 999f1af688f67fe720a9d75773073792ed53bb73.nq.gz
│   ├── 9adae2b56a2b0e6cff3049f4ba6d007c7d667f1f.nq.gz
│   ├── 9afa0fddced30195e363e6cfe9879b4c2b0feef7.nq.gz
│   ├── 9d864feeb541a4a15cc14ca7411db528c89686b2.nq.gz
│   ├── 9dc7af4a9386f6be1fd10041f5454c32b37efd5d.nq.gz
│   ├── 9dc8d3e5c14d429516e2d9160d37e7dedb75ff16.nq.gz
│   ├── 9e261d3839f67e1e1a44d69e548f142d020ec51e.nq.gz
│   ├── a00b24b4ab197e1e4ce2b6d835177597cfa31a3c.nq.gz
│   ├── a43f36f91d1b76abce0c650a346a86542e102ea3.nq.gz
│   ├── a4ff5054d7c75a6f56df30c90955e83c5d7965e5.nq.gz
│   ├── a5c6fc909c74ab54b9c63633b5eb6ca9ea2114e9.nq.gz
│   ├── a6008adfaa373b434818d0a2da4ca53e938d0d88.nq.gz
│   ├── a818a9f1b699e2c282e29b140898d0fe7d18f0ce.nq.gz
│   ├── a8cf5c37314976843fa04d630d3b5541d5b34472.nq.gz
│   ├── a8fb896ed8363cca063d94fb1bda31255b47998e.nq.gz
│   ├── ab109be802c48e563228cfc8d69b3affcd33b1b0.nq.gz
│   ├── ab84be5a45b695e3520115be7a11393fa5915677.nq.gz
│   ├── aba0020e147615f7d8480c288c67e0d6997ea86a.nq.gz
│   ├── aefc42e31ccb25f9fe8609637e83e8e44c37768c.nq.gz
│   ├── af02e2a8f437fbabbacef6050d0729119923b49e.nq.gz
│   ├── af8168dca2cdbdbc41abbbbdc051ff713d2ebd96.nq.gz
│   ├── af86b79f91e2d11f47fa0e3658dff99c11a8a1c8.nq.gz
│   ├── b1257ff6a92e83f4c3dcb4c4b14fd2591a7c0b8f.nq.gz
│   ├── b1bf919ac0975890202c63da27a553038016ff00.nq.gz
│   ├── b2126c789cc6baea588657bde9b436fb5f2f7afa.nq.gz
│   ├── b24b142faa4b7d4542e246eb3320573126b1868e.nq.gz
│   ├── b266e93de719869049d3991eb6fe1c13691089f4.nq.gz
│   ├── b4fd6ee53a7710b4dd1c0c9d3f035e56315256db.nq.gz
│   ├── b650caa025cff6da1e11bb11295c5d86c71cd70b.nq.gz
│   ├── b7418b95fc2a1ebd4d61f54c2f3dea589f3c8f91.nq.gz
│   ├── b8898443fdbb2d83f0f463ca71774df640c864f6.nq.gz
│   ├── b9e080b7cf0285a75dd2c418a8bbd31ff01c5eff.nq.gz
│   ├── ba166913df734e93e226842cdde17a1e7c21dbba.nq.gz
│   ├── bc88815ed495607e65ac10c84df4655263869a37.nq.gz
│   ├── bcefff75d6fe85ec0287361a5dcac19d9d142315.nq.gz
│   ├── bd30508f9a3b7cade4ebf5d54611958a871b9558.nq.gz
│   ├── c020f5357a1f9c4af0bd48de20b4319d2c21efce.nq.gz
│   ├── c47e7d3259905dbc4cb7e572f61d662f97a331cc.nq.gz
│   ├── c7d519d436b00b190d0304c8865bac6e1434183b.nq.gz
│   ├── c935bd73cef774efe992d073f646407936a84f3d.nq.gz
│   ├── ca52e160b5a0bcf780bb003361f28aa0321b49d8.nq.gz
│   ├── cb2364b3796e310f6ede620a3a8f2514fb9ac296.nq.gz
│   ├── ce28cf8f2b2b9b40989d20d8e3f252d98d03e26e.nq.gz
│   ├── cfedaf2d51efce049a1216a990bc435425b93d16.nq.gz
│   ├── d4417bc2674568058c4572680ff7d35a598379d9.nq.gz
│   ├── d52d76e9388d8d320a7cd5bb4a928401d0f1ff44.nq.gz
│   ├── d6247b14a9ab76121620e1cfe0422c08302783f5.nq.gz
│   ├── d6b7ef32c8478a48c3994dcadc86837f4371184d.nq.gz
│   ├── daa1ef79ae95fae3b5b14a17381cbbd8f5c2c926.nq.gz
│   ├── db607c6cbb56b412f66469c83de880ff2144257d.nq.gz
│   ├── dd88e0741d86ae7defcfe8d61c39b89a522c35d0.nq.gz
│   ├── dd8f073c378ce03761ab140dc55dd67801bf319f.nq.gz
│   ├── df132ba6f5346edd3dbc404571c364b42008d82e.nq.gz
│   ├── dfdac3fddb3d29ba7112ca2ba91ca42db2df4720.nq.gz
│   ├── e2c6ab119f78524272538d8d65153395855d1637.nq.gz
│   ├── e2f2b106bcff672c10263f665102cade7bb85709.nq.gz
│   ├── e38c7f56d92149ee34015e7ff6d710dc41968bde.nq.gz
│   ├── e58344a8227cad1e7cb9f01b7929ad4928731893.nq.gz
│   ├── e5c5163caf5f75a8b5eab05fd26aa846f7714e17.nq.gz
│   ├── e8d9d6df02d57296bba7b4f99f449362dd4b3674.nq.gz
│   ├── ea24461e349bfba4162a42ae1dafb176c540f297.nq.gz
│   ├── eb28946b3e3c149a361ac263f044c65aa7db5f04.nq.gz
│   ├── ecae3b76dc4b246ecba627048fe02afec0157a91.nq.gz
│   ├── f073a8db31f9f9ee2c34559b164a364cb6de3704.nq.gz
│   ├── f0d7e61badad3f332cf1e663efb97c0b5be80f5e.nq.gz
│   ├── f242d226a170cccd4f4e5d1add793332014b460d.nq.gz
│   ├── f29efef10cc2ae773855938f3d84b61c72c7d6ca.nq.gz
│   ├── f4ba3374db2cdb339ebba24a2f9bffa8fb934d09.nq.gz
│   ├── f5ff2a5265494c6af3adcb658a01a2cd02a56828.nq.gz
│   ├── f78edc83d62c6e6a60972522d8c5453ab429da7c.nq.gz
│   ├── fb0059018b1408bc7abbf65ace3f19ecdf6baf50.nq.gz
│   ├── fc81ac9191fbd143e2fad9fec2702caa80bb65d0.nq.gz
│   └── ffcca536dbd8e15a8c752ba73e4e0aa84f14742c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1f75bc9eed8e0e385f64f368bd69f58d96fb8c2b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 190 files
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

[cherrypy/cherrypy](https://github.com/cherrypy/cherrypy)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
