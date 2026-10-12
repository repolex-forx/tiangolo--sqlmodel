# Repolex Knowledge Graph of tiangolo/sqlmodel

RDF knowledge graph data for [tiangolo/sqlmodel](https://github.com/tiangolo/sqlmodel), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/sqlmodel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5ce1a472488734363b2ab36f8ce2bcc773e4593e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5ce1a472488734363b2ab36f8ce2bcc773e4593e
│           └── chunk-001.nq.gz
└── blob
    ├── 01fcb14ac245915be30cbd414951f8817c902e4d.nq.gz
    ├── 0215129130c217628cc62cfe9aff43ae897ba36f.nq.gz
    ├── 0221d8834c5a46449adf7659252cd899236fad33.nq.gz
    ├── 02855262053244400cf03217815e7d65803abfc9.nq.gz
    ├── 029c371ad8cf3a6d7065af0223af337952e0d26e.nq.gz
    ├── 056c1fd98acee2b66c2c025612bc4f8330663d26.nq.gz
    ├── 0574e5a200523955c556c0d31e3611509ebe466a.nq.gz
    ├── 0681d1c0a5940cddfdeb68fb5b769fbf6e776839.nq.gz
    ├── 06b2a80e4ed86140246f88a031dd0b9e2ffb2abf.nq.gz
    ├── 07127c69011c387f2947629f8ba7e5806143429e.nq.gz
    ├── 07417aa79c8cc7abf05147f4b9724c8572ba0f0c.nq.gz
    ├── 07967936062d398ddbdbc79ac54131964a334956.nq.gz
    ├── 085f71a86633b0e03aa39b0e18713699e0a84140.nq.gz
    ├── 08adc69d32e49f7942c9827a92101142f83e086e.nq.gz
    ├── 0904eedfc3148113c1cd4b123d52fc2ba688c66d.nq.gz
    ├── 09e54e1ccea2579c152e7601c4b59fc7fdbe44a5.nq.gz
    ├── 0bb4cb934ae3a8f9aa3d1ce04546eda5b51be4fb.nq.gz
    ├── 0e113b0f160e77175f436774880a03d48bfe2c49.nq.gz
    ├── 0e2c898f40cdbf1b64b198eadd0ad0ba12047c78.nq.gz
    ├── 0f3ad44cf17c96cd43ce429cc888adcdf3abe6db.nq.gz
    ├── 0f3e7fef32989240e2d089201be30694619a9d1d.nq.gz
    ├── 0f8555a8dddb99515f43d381ebbe9d5b59b7e38c.nq.gz
    ├── 0fb9f54bafeeb3ec657c539463a8affacddd6237.nq.gz
    ├── 0feac29ddee7d041a3701f1f0f32a69dbd424c7b.nq.gz
    ├── 107141ff24560370c71f6fb913559ecfef12a917.nq.gz
    ├── 109e7c9d66bca975d606e9618cb003ef8dc33775.nq.gz
    ├── 10af5b9c2feae3bee61829870fb6bd8b674ca869.nq.gz
    ├── 10e5df55bb53524bf3f20294008b9547ce01ac32.nq.gz
    ├── 11029f2d8e4dbf29209b1e6fc6ee5eba21ef9bec.nq.gz
    ├── 115c447bcf3250d62b05b303436a45697450d2f1.nq.gz
    ├── 11bbf09b5e073869363186a468b38af280ebce91.nq.gz
    ├── 11c6a4c3a4960a6e1e30d6133dc29962bfc40d85.nq.gz
    ├── 12a343b452bf96d6045ed993a937f49886e089ae.nq.gz
    ├── 131c74dc15fc389387dba8008d625177d16cfb34.nq.gz
    ├── 134508fd11b6bfc37ac1ffe292e235e0d33b94ae.nq.gz
    ├── 1360dc7d566494b391b6cf16ee26a9d65cc2b43b.nq.gz
    ├── 13ae331bf17bb1cb01e9b9fc423ef1d817e0fc5d.nq.gz
    ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
    ├── 1595deffb047d52e4bba6d002b819bce6255f1ac.nq.gz
    ├── 16c2c7fe0961d9902c66fc3c585182348743349a.nq.gz
    ├── 18646e5d9a0a9d963c0f89a2472787d98d78bb7b.nq.gz
    ├── 1a4628137c551ebb3681eb1c2d7b65712579a71a.nq.gz
    ├── 1b7f8c91622c45f995b6712a01097dd3711b1fbc.nq.gz
    ├── 1bfca79503b915174e9d34732205cda1966707b9.nq.gz
    ├── 1d8153ab9fda45abbb27acfd651940cfd156fca8.nq.gz
    ├── 1e91f318f4f2a07516f7337f2a397c954c5a90cb.nq.gz
    ├── 1f23e8682b82aafdd7554545954b2b1b4f2073f5.nq.gz
    ├── 1f367ed95f172f36dd3bbd36781186a739c73696.nq.gz
    ├── 1f485ef0b121ae833f3ca52545bbde21dad26cb7.nq.gz
    ├── 208c2238102335999eb31ae45d0bf34da63e2a69.nq.gz
    ├── 20b5dc210716335fbde3f196a5809ccd500b20ec.nq.gz
    ├── 20bb952525c4db026ee594c8fba5b5cc9ef56058.nq.gz
    ├── 20dce60f69086178958eb0bdaf3bf266209f2022.nq.gz
    ├── 20f439287830d9773a120fdee8005a8a7954ed2c.nq.gz
    ├── 21a4e28c0f89e224d87e149297d68c2a71eb120e.nq.gz
    ├── 22d28b46c8bc6beeb056adf4f7ec7f3f34cfaccb.nq.gz
    ├── 24d09f8e6e2e0028b3eac0f3b7911b10dd3f65e4.nq.gz
    ├── 24d847899a4c7bdd52b819a518a326b03753a487.nq.gz
    ├── 25825b41ecab2ad9179eedcac2735a83d11815c9.nq.gz
    ├── 2668161e929d6794c104301e506d3c1be31c7306.nq.gz
    ├── 266fbb8d32607de9d9f30611e9e006c2ce15aab0.nq.gz
    ├── 267338912e073179d88787a831d681b022fb461a.nq.gz
    ├── 277382588b50f0444a6b4baaefd44b219066d41b.nq.gz
    ├── 27e8f219abe63e2de74a5ae6ecdd3a27d0579fbb.nq.gz
    ├── 281f99081cb3c747d6df1387f49151663045d712.nq.gz
    ├── 28a38cb99317c5c20e653586b3d3694b65c9c430.nq.gz
    ├── 2900ad73676b87fd0b28a706b96f84533c436715.nq.gz
    ├── 2947ee7db9ded5b1a4af8fd05fc484f523c08526.nq.gz
    ├── 296751c0186f8f640aa18a8d94e0c92643280fa3.nq.gz
    ├── 29bce28251746d9d3373bd9473dc1f79b16288a7.nq.gz
    ├── 29f2bf8524aa0de30a830940738892bc21b9aff1.nq.gz
    ├── 2a036508f69c948a47f3f7100700971c33b51d67.nq.gz
    ├── 2a411671a6a8767d8366357a0d008402e1b36f12.nq.gz
    ├── 2b48ebdacf3932b005ed68177fa85399c53ce0cd.nq.gz
    ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
    ├── 2dcea1cd6cae32d350b422011d884fd70fba1070.nq.gz
    ├── 2e0061f5e5dfaeeda49d050646d0a8c35a129f0d.nq.gz
    ├── 2ecaec0c3ca951cd7e636ed9623ebfd2b53bdd8f.nq.gz
    ├── 2fea0482bb48c61b0dd76be5c6cdbc2f1decc1ce.nq.gz
    ├── 30b1c9f85a7181363d35bf87de2deafa2dfa6389.nq.gz
    ├── 3114f5bc2f6d0238fb3ed63efb1d6c0dac51a0ea.nq.gz
    ├── 31c9a8ab5ffc7c1cc000d0b51f0365b5789fbcc9.nq.gz
    ├── 335d27a6c64979b6f09a03fae6ac749daa9e1746.nq.gz
    ├── 336ddc8f757dd0da3fc3827f9868daaafb02a7ad.nq.gz
    ├── 3402d4045ee800fa8c4a114c81127bdbf86314a4.nq.gz
    ├── 3415ecf3781e975b6a7cc197e2c4b104001e5764.nq.gz
    ├── 34fbd3b2f90a29b3dfea52b8fec5f9bad617671b.nq.gz
    ├── 35567360e1f8d4cf7bf277b4ff0a4a0e897862c8.nq.gz
    ├── 35d089860c07306cb8c912c67f60c5679b5d3094.nq.gz
    ├── 35faa201fddc7bdadf629aae19da368e1fb678ac.nq.gz
    ├── 36e5a28aa1e6092e4817dcd6b4eb6903a1bb7c4b.nq.gz
    ├── 3764a9721d81a122868f8be00ab3e788cfe94cf8.nq.gz
    ├── 3780bbd22450d2ce89602c54722abe9db2e14748.nq.gz
    ├── 38d4f04b415d85592261a20eb8ddd19b4ea4d2bc.nq.gz
    ├── 39c2364f31e070d6c32d9c7c360816cde42bedef.nq.gz
    ├── 3ae40773f975f9ef908177c8f5437d0df603f784.nq.gz
    ├── 3bd479507e481cbd8434de1dfe9e3437ab3dbc68.nq.gz
    ├── 3be0f1f7c159c9d2913c1cf8caef167a5834a2dd.nq.gz
    ├── 3d1bfc69a0d6b567721f37a3069851cdc366b430.nq.gz
    ├── 3daabe5e37a31c77f93a294aacbaaa2415221fbe.nq.gz
    ├── 3e1e262ca5f3d4be7ed5dc3a52defd677d166ce2.nq.gz
    ├── 3ec8c80fa0a423e1cffa01de6db6274143d75447.nq.gz
    ├── 3f1358d0e157e699fcd64ac1945fd536336497b9.nq.gz
    ├── 3f943a40dd99d0922fd0e01fa40ca1d73db26684.nq.gz
    ├── 418c219acb40872ee6767cce04ec24136a269e9c.nq.gz
    ├── 41ec69a3cd3e34de6a835fa16f443b85d30f0878.nq.gz
    ├── 426304f456e6fa173419baa726619a2840d55b64.nq.gz
    ├── 43114fa3a9379af9b6ca0f4f2910b47d03df874f.nq.gz
    ├── 434eab1c32acec1b2f276c1e4a84ac4309e87ff2.nq.gz
    ├── 435787c79bc7a2f0a6578de926834e2510caf599.nq.gz
    ├── 445572a147eb99813750faa1100dc7b552c52ff9.nq.gz
    ├── 44806ff197e823496864c8444e36f291f97d0d6f.nq.gz
    ├── 460b9768d77e9719d9b7ebc9dff5d1a221faffcf.nq.gz
    ├── 465c525108dce580804877194790b695ab4be815.nq.gz
    ├── 47c2e5f0bc8f089012b0fd177d2bcc63e0625182.nq.gz
    ├── 47ca776249102a70547bc829f9bd543814280ba9.nq.gz
    ├── 47fbca87c29a160f5d134a4b6f8a340f818b9daa.nq.gz
    ├── 48e33c9ba2e3ba3ff5c802e3feb41dbd4fcba077.nq.gz
    ├── 48e6a801773fb44beb33645af0d48a7605b2461f.nq.gz
    ├── 4960fbce3696c8af455ef2737c653157537d1fdc.nq.gz
    ├── 4a4e51247458144c0a1c949e973b80f6e10d8253.nq.gz
    ├── 4aa4cc1f0819bcf15c5442f091fa907f0102e816.nq.gz
    ├── 4c1ad1225960175b7db002b16d2c47a7f9722a00.nq.gz
    ├── 4de2afc1ac721625db9746c800967f7d4ecede7c.nq.gz
    ├── 4ec9e1f6d4dd5e02dd227e7ccb8e99d8ec869a92.nq.gz
    ├── 4eef6dfa8859c5e8b3db2e146d37f18c94a8cf9a.nq.gz
    ├── 4f04037155a1f6a7abe52b6d6a32a35f96174aca.nq.gz
    ├── 4f71d7873cce2058061c1293a6c7efb14b364b5e.nq.gz
    ├── 4fac2364eb0ca0d1157d84e4b617f560dd18d04c.nq.gz
    ├── 50c7241ef46689623bf4c9ad1279b9250d171567.nq.gz
    ├── 50d203f5e265b27cb992f5f0898307ced71eb192.nq.gz
    ├── 517c37612d00722b1908e931f775fe66a68e0568.nq.gz
    ├── 5251506970e0c8ac24e79e4da2a66d37d1d0ad60.nq.gz
    ├── 5264ae79bbada60e11ba881bda73743b581fb682.nq.gz
    ├── 52888e81ab20acc0344bcb3366746846120a54cd.nq.gz
    ├── 52a7c7e7734ee3de474926fbae4a0b34943efd19.nq.gz
    ├── 52c4b54712ed1f8f276b57cee84df4a9086ed44b.nq.gz
    ├── 52fe68be169ee96d85c0683410d3d0328df45d9b.nq.gz
    ├── 5368a822979e352c3bb9ab66fd9bf14fd49c3589.nq.gz
    ├── 53cae9270d6d6dcb4d934ba4f1af330904a02c38.nq.gz
    ├── 545d30a18cec93495328868463868efc1fccb7d8.nq.gz
    ├── 551f5be9263d47dac7d3dec1a5e6ff192f456bfa.nq.gz
    ├── 554d4fad14c756a6fa034d92bdafe70e696c287d.nq.gz
    ├── 5569e8ab0f4939c28c7a681204e8c5aba81bd8bb.nq.gz
    ├── 55b0334df9cb23944f57397b79bff3bb2bc365e4.nq.gz
    ├── 565cd1f44ce71f6be87124d4c566b03414a33cc7.nq.gz
    ├── 56650ab4ceeb475331a59b20dfd833e59e4365ae.nq.gz
    ├── 5733b717959f865d6906e19f38f125d2223edd42.nq.gz
    ├── 57db99ea420cfb3bace5a71a96589805de952e59.nq.gz
    ├── 582f82f91a239994c86322dd873bb4432ce79ac6.nq.gz
    ├── 589bc98671371a91bf4bc3eb37a28625d09d49ce.nq.gz
    ├── 58bb20b090879360085ae7da8764d458648c54cb.nq.gz
    ├── 5918e1d2002e348e682551e22425db3a879ab8d5.nq.gz
    ├── 59d2b5b2c36a30a34e9c6b055453325a0b16829c.nq.gz
    ├── 5a40f9c1728dcad5e6350acf61ea89ea424867de.nq.gz
    ├── 5a5c5a379cb1ba7b6b36994f135adadd9a032feb.nq.gz
    ├── 5a6bf030cfcdb7ac1a9db8dc65118bfabe208f2e.nq.gz
    ├── 5ac24937d620b7c78f01e9e4c4aadb9284c856e9.nq.gz
    ├── 5b41c2e02c3c87cc4ecbe788afae259942aa6d1d.nq.gz
    ├── 5db10c5808bf706e8d6a622491647c153965663f.nq.gz
    ├── 5df80e9f86f1e91c6ab1898b90d9bb10f6be74ba.nq.gz
    ├── 5e31c012ace252752f68fb0a76130337ae9f495f.nq.gz
    ├── 5ea2d61946c92292f7f21d44b6d70ce97f270872.nq.gz
    ├── 60093ea0bfea660007b0e4d8dc050c0f9f0bb3cd.nq.gz
    ├── 601454acd17a7fcdcc501f5923974800150f530f.nq.gz
    ├── 610ec6b0d44cb9d81567bf915133b06ef46cb331.nq.gz
    ├── 611c33177b7fb331f1045cb3711ec960c7a6b86d.nq.gz
    ├── 63082c6132f8f73c83afd7e62de0e025c5a31276.nq.gz
    ├── 635711bdbf06bb189965e73bd5e34bac7ac5f261.nq.gz
    ├── 6366d40865368e4cd1ef771bf11cfc58b772e7f9.nq.gz
    ├── 63ce4d4e239c579b93c1f1b4be84f9115a9d4d44.nq.gz
    ├── 64bcaa0d793dcf918bc7ebccc345ed3a7790d5e8.nq.gz
    ├── 64cb6916d8a6184f2cab9c3959b9809271e8768c.nq.gz
    ├── 64fb4beaedf92cfb11b95e5676f100bf328e2a1a.nq.gz
    ├── 651ad3287ccb4481cd56394329f11399a5934d48.nq.gz
    ├── 66193e1706442ab48c94902917f3fca9acc4de9e.nq.gz
    ├── 66729c69dc994cfacaa9543b2a1d34a76733b4d4.nq.gz
    ├── 689cc754b215fbbd1447436d8615d3d611f75e9f.nq.gz
    ├── 697011de108f2168d0b0be0820c91a4332d12cd5.nq.gz
    ├── 6a9295eedcd9f2d79348cf446d884b3b578ef0d3.nq.gz
    ├── 6b76da58ff88ba9708a8e4a2f65cd9a67c82e622.nq.gz
    ├── 6bcdee96be7a167cb9711be6afec2b405f8f6dee.nq.gz
    ├── 6c51d8fab2444fa72e77acac396e1e4ae3b2bafb.nq.gz
    ├── 6cc4f4893428d66359c97b4c61885b1821b63806.nq.gz
    ├── 6db6217dd8d41af694d29c35e623f2e883168abf.nq.gz
    ├── 6e364d407baaf80d747c18def9dd3385eeb2890e.nq.gz
    ├── 6e53aba174a42b0031a1ca799bc72685664c984e.nq.gz
    ├── 6f9b7371ab342c8f78bdec4db31845406829f03c.nq.gz
    ├── 702ce61d7f3066c752f4f5ed57a19935476949ea.nq.gz
    ├── 70de2170f664d646fb8d96528719527ea5f18f91.nq.gz
    ├── 727580b68f66cfe91fac029f0849f257591edb89.nq.gz
    ├── 72d5fe9b142692717fec2ebf0fa28eacb09ce2a6.nq.gz
    ├── 72f95ee279047f331bbfb64e2150d2b415ab17b6.nq.gz
    ├── 7380e1b2c8d83c28a42f5c7de2ccd7c40f7a19e1.nq.gz
    ├── 73aa4aa8c07840f0a6422ef898017f91e9681dea.nq.gz
    ├── 73ea40f2ff49cd7462f743566bfa59d8709f1c5a.nq.gz
    ├── 75ebe51f437778c87a0987ecd141313b766e82bb.nq.gz
    └── 76159ca325ce53b4023d06ce1d584da16bf66fa8.nq.gz

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

[tiangolo/sqlmodel](https://github.com/tiangolo/sqlmodel)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
