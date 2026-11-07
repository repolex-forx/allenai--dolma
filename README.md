# Repolex Knowledge Graph of allenai/dolma

RDF knowledge graph data for [allenai/dolma](https://github.com/allenai/dolma), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/dolma
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 669f534823b08d266a8fff01f8a1c916a5a56576
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 669f534823b08d266a8fff01f8a1c916a5a56576
│           └── chunk-001.nq.gz
└── blob
    ├── 004395f58cad5cc99d7d75719d90a15ba5a4600d.nq.gz
    ├── 004569fe7be0311806fcb40fa518ee2ae1339fd7.nq.gz
    ├── 00a6d2d684afbcc1a88058d04d2cd1bd201d3815.nq.gz
    ├── 012a8f76dbac8910490072d1c284c875662565e6.nq.gz
    ├── 014074604334b0c93026718b0af0d7c2424fb682.nq.gz
    ├── 03100d9df82d2a322f9d6d749b1c2be3d40ba8b8.nq.gz
    ├── 03ed8ec0e0eadc87b900d5e4f73f37110110246d.nq.gz
    ├── 04c7fc782208490d87b04fe089bdd7e237278789.nq.gz
    ├── 0599018d19a42f72ec28ce5259302dd8e430620c.nq.gz
    ├── 06681362835ccaf2de25535681cd6d0a3892166c.nq.gz
    ├── 0669e4b5ca354f7fb236dcd1367a1cda2074a92e.nq.gz
    ├── 069e06944d121d7e56a8d9507051b84b51da7a2f.nq.gz
    ├── 09ee99acc53f867563c4e0a91307892d33b3bdc5.nq.gz
    ├── 0ae2f3408c1a6935528e41b10833451911dfb9e9.nq.gz
    ├── 0b0c2016ae9ab198fc152e622dff3f40fa6a958b.nq.gz
    ├── 0b1c32c6ae6b34c80c3df892b93a8c12f9e27770.nq.gz
    ├── 0b278035a9e900eca848ed67483e9c75cf5138eb.nq.gz
    ├── 0b4212a7c63de7a15ba73712c7fa7de6ee8cbb95.nq.gz
    ├── 0b54b60495af4310e954ae13a50b4e24b783adee.nq.gz
    ├── 0b8a27201a5d2e64754c15eea1b26ebbf9ea9a6c.nq.gz
    ├── 0bbfc75fb420fb0af643bdbaf88561ab8b772c1e.nq.gz
    ├── 0cd8985972b22880857f97524fb95d309b2ef3b9.nq.gz
    ├── 0d3ceea2aca4afde7d2afcbea9d7dc4511ac8150.nq.gz
    ├── 0dae57f841ee01c82d291ba62dc95837c5850ce2.nq.gz
    ├── 0f4d1aff19bf183405182fdd496a61eeadf9ce12.nq.gz
    ├── 0f8dd2eefcec900ebbfcdcd679fecbff52d9e151.nq.gz
    ├── 106eedafe6e82d6076325ca779f27b54ae8adf22.nq.gz
    ├── 11b40b96410f3153531f57290cdb3a4fc7047f5b.nq.gz
    ├── 12e2e6c4cbb9967aaedf2e72caf85a7fe5f6ea35.nq.gz
    ├── 13117d6c53de4618a5136981c586de78a391fc87.nq.gz
    ├── 1579997afe1759f3ab20f4c3ffef67d556e48b6f.nq.gz
    ├── 15c39991ec3cb60590b2362f1067dc5a69ba860f.nq.gz
    ├── 15d06977d96997624d4992e2bffbf27ef282a8a3.nq.gz
    ├── 15d88a17789b1a4a88d7f876d22d2a47726407a2.nq.gz
    ├── 15f375d8aacf43c062b61e4de02ee7dacc760451.nq.gz
    ├── 162e8f68c17c36c3ee6447db207b5ca1ec9dcb83.nq.gz
    ├── 17f37bb350ff753cb09d74efd3a272515b9bb6d9.nq.gz
    ├── 187fbad7fb376830fc2df33e5374a577f36bb3db.nq.gz
    ├── 18f7ee4afdf4b68f16ad341afa707c65aad4ce4c.nq.gz
    ├── 1921a2ec5f445dc2405c420014e35dd017eceb2b.nq.gz
    ├── 1976206ee1adbefaa5ade869ad66dc37955376f0.nq.gz
    ├── 19d8363071445068734cfc587c388a136ec57438.nq.gz
    ├── 1a16df48a3e3450b66b5ac20519cc6f02c193771.nq.gz
    ├── 1a2068889cab21cda016a4d39d22af14eeb00577.nq.gz
    ├── 1a34fc399129e3e0317f2f1a9a152851f6a561f9.nq.gz
    ├── 1bfaf4256bd5604a671b4f8c425923adaeae84c6.nq.gz
    ├── 1c7b8f13a437902f16c1d7b18f6d9e046c05139a.nq.gz
    ├── 1cbdca797b2362a6c10b6bd9115d1f74d9864693.nq.gz
    ├── 1d51eedb6d52d709b4c7dc527a59973b9be76689.nq.gz
    ├── 1d7a1f4092e24d77f22a94627135c5e51d6d084b.nq.gz
    ├── 1de3f2b2c2f392e3618e9226e533b2609b10647e.nq.gz
    ├── 1e2f284807fa53ee975b74d06b82cc71922f5708.nq.gz
    ├── 1e503b74069dd1cb0e2b976e1ea8ff545a9217c5.nq.gz
    ├── 1f7fcf9774e3a46ce6ff597b63135d4f6151f0aa.nq.gz
    ├── 1fbd63a0dadf7e27de7cf2dcb6d6aec6a12d6cfb.nq.gz
    ├── 214c8732494bc0989e4f45207de890c42db58c35.nq.gz
    ├── 216a01be04db49593efee126ea9eda4526eb3e52.nq.gz
    ├── 21850a595084b0dfbce4fb150a5217e95e9f22d6.nq.gz
    ├── 21ff1f9393585713e0f91b22f3630c1ffb0fbfbe.nq.gz
    ├── 2208f5cb3f5c30f2a00c7c6663a7dcc39f60b65d.nq.gz
    ├── 221937f541d3aaec6e6b18598046f805102c23d0.nq.gz
    ├── 227b5a428b293eda57c3bdc6022b2d90eab00c46.nq.gz
    ├── 233323582605af86940f1ad3ddcd1e450ee934f3.nq.gz
    ├── 234b2006d27e82f281652bdf9a724145cf3a7ced.nq.gz
    ├── 23500fbce58fe645e19501aae8da5b81d2930104.nq.gz
    ├── 25ebedd701b72b82257d53adca70f2e5ec6a8d70.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26bf38ff5745aff79a97b11750da7b21b4261d78.nq.gz
    ├── 26da2a33c61232a510813eafac55f46a3973672f.nq.gz
    ├── 2763a5a032294077e5a092005b9bf82b75a3335c.nq.gz
    ├── 284aef128ce723553ecac5a33d11da8f47ddf6b2.nq.gz
    ├── 284bb7e046cac6db06d5a1b7510ae669e4040117.nq.gz
    ├── 2878f9ab655c51b4bc253aa2f8fac84e2b6bba94.nq.gz
    ├── 29156d75ca42a8a5ee520faa5ffa4b05336393fe.nq.gz
    ├── 295755dde2e77dd6e2805a47367684af3b8b441a.nq.gz
    ├── 298d902c3438c3c14bb1551baebead72b89f321d.nq.gz
    ├── 2a25c99e00b1271ebc46dda000eccab33ccd91f1.nq.gz
    ├── 2a8226da505b3e75af1898675f9830d85f6b93ef.nq.gz
    ├── 2aba7ab692ef892aa282e3f38a890797d9a90248.nq.gz
    ├── 2b18c76891aed542afa68b9f0cf7d4f878af093e.nq.gz
    ├── 2d368b269f65b1bf63c01e4501dded810eaed252.nq.gz
    ├── 2dcb5c1b2d941acf3709c12e4de9281c38636993.nq.gz
    ├── 2dd5ad5845e71c27a5c58cfb77081b889a07651e.nq.gz
    ├── 2de7c37be47d70c5a316ad5f3dc84bd3dca6fc3a.nq.gz
    ├── 2e63eb120a9b9d6a4332052023cbd3d407ca8c99.nq.gz
    ├── 2e9291cd466b228e46b917946fd655c5019ec9f0.nq.gz
    ├── 2eee26baf1d05c8f6ba0e4b812c1a0a1366d0d05.nq.gz
    ├── 2efdfb98f5c7bca2a9951f0233cd693c34306dbe.nq.gz
    ├── 2f3d4175bfc0d1f35fb7f9295a2d7bd88adda657.nq.gz
    ├── 2f4175512cbc593322a0987e9d2cfe56c8a8b62c.nq.gz
    ├── 2f66596ba0e7eadb6a8f2bb38a8f7e2e3ad1549a.nq.gz
    ├── 2f86a3bf19ec4b8ba67a78dc2b50b7708d491773.nq.gz
    ├── 2fce49e90e6bcf8b59c1401b7f4f71e2f5217d34.nq.gz
    ├── 3004716f88740b04fc95fb8744eb8fb9edbb717e.nq.gz
    ├── 30354b47e420004f6f3515db636fb4bec97ca5b4.nq.gz
    ├── 31b570876455737495d53f3468998fba7a8dc18a.nq.gz
    ├── 3272717cbd5076f51c47be69a8fb7b266b750d6d.nq.gz
    ├── 3355d8b060c350810473bcda920487cce28163c7.nq.gz
    ├── 35b2a0590615e9c5679fd1c0d57208599c4cd5cc.nq.gz
    ├── 372d05a3d051be16821baf1df874716db8d5da5b.nq.gz
    ├── 374a94dfa74739e339cb70a57322b600920d97ab.nq.gz
    ├── 3790e7a83bcd9afba2914701135f8d85d0d639a3.nq.gz
    ├── 37b7be6d6ea976e15c67126e624017a559ee1535.nq.gz
    ├── 38049f5c31b45435cf5ba824828b01735ce9945f.nq.gz
    ├── 3810817b51237a2221748d168d8f97ba6d5dfa43.nq.gz
    ├── 381d83fd055023caaa40bc1bba00d3abd6793565.nq.gz
    ├── 38bf268ddd38e044723f942885e5720807f8e04f.nq.gz
    ├── 39bdb264fe35463af82d253adc6d558acbad5df1.nq.gz
    ├── 3ad0a66c38ea92ce543da915d44e4455c755e8f4.nq.gz
    ├── 3afee92f51bad63f22024477fe4f1eaf7e18ccc6.nq.gz
    ├── 3b4ea842823212852ea99dc53d91649abc8f5e32.nq.gz
    ├── 3b76ebdacd0b6008df8e39a473ca2dccd1625544.nq.gz
    ├── 3b785143cbfc56625298af418ff210a9bdced8e3.nq.gz
    ├── 3b914919b7b35c6845f53f8fbd785661ba250bc4.nq.gz
    ├── 3ccb43c89ce9a6815776cc250193681b3731ab5a.nq.gz
    ├── 3e884a0936947de8af95b4b7a5e0bea243952a2e.nq.gz
    ├── 3eafae360450592420ca7c02308420a415ffc4ec.nq.gz
    ├── 3ef2ca1671f47cff06830885374d5a9f0d59ca4d.nq.gz
    ├── 3ef47dec06ae17e0c97f9ff2742febaa887841b3.nq.gz
    ├── 3f01c41975adb9aa6cc3c0b3ac1debb3057407ad.nq.gz
    ├── 3f47407734bd08b26b08e464afc8f1dbcd1f295f.nq.gz
    ├── 40a63d7e9da2531b52b519d5425f0763e7483382.nq.gz
    ├── 414615b5770eecbf1a52b48f4a65c6eccc944f20.nq.gz
    ├── 419696730b8a7e89d9e17cd2231e541199cd10e5.nq.gz
    ├── 41fc042cd7bad160fa08f0e098514c357575ebc5.nq.gz
    ├── 4242f9c1896ab8044ce5246394ef2d87750dd955.nq.gz
    ├── 4283e90578e9ee3a81128cf24b5235736ff7bd94.nq.gz
    ├── 42f67ba5cecebc8bbd602575f7e2f3ea5afc1a74.nq.gz
    ├── 43745b78bf9ef3f2301c4511251d84a065a150ad.nq.gz
    ├── 43932ddd7d70da821cb5f8e91bb472b2233b9baa.nq.gz
    ├── 43c607d7df3c0273bef90f009d7fb392933625df.nq.gz
    ├── 43f00e4528d1fcecda938ce105dcfe10bed308b3.nq.gz
    ├── 468506c83a1c780054cbc39f4f5e77c0df22ee39.nq.gz
    ├── 4749fe6eb02cc66d52f29351770599347b364664.nq.gz
    ├── 47a0284b53e315e61f8d2ab9b4fe8c35be705325.nq.gz
    ├── 47d18062b8d45ffa27218e5efa17bd89268ff373.nq.gz
    ├── 47edbd3eb7d0a951ec1f63f4033b4ef0e0bf1fe0.nq.gz
    ├── 4833ca48dc92739cfc2bf9a71624475b34eae272.nq.gz
    ├── 48d83bc95b876aed829dcd0d49d4b41d58387429.nq.gz
    ├── 495efe5f6dd545070ddd890529b675db89d27829.nq.gz
    ├── 49f74c21f818f6dc337f3a509247657c891151e5.nq.gz
    ├── 4a009e9eba7b47cc1dcf6ee57289e01c1641a936.nq.gz
    ├── 4b5b5a328291c81fa176ab7cb9cb9337a2ae5372.nq.gz
    ├── 4b6f7605a4cf7741c2094a7ab382b77d07283e9d.nq.gz
    ├── 4bb3f8d31dec369a6f50f8bf52c3c560e3acb920.nq.gz
    ├── 4bdfabd0a157494909c8af5cb695d77357890531.nq.gz
    ├── 4c8384bf04c9e2980b39abe8a2ea47ecb46b6fde.nq.gz
    ├── 4ce080e5b3fbaf29d1dbccb2b58d6ec8bb5688bc.nq.gz
    ├── 4d72cacb71d8bc72d684a34630991c9b324542fc.nq.gz
    ├── 4e95832fd08bb297cd0086c1fc4b479a76577480.nq.gz
    ├── 4f06a3088246b3e69e435fb5bcbec11c18e5af4e.nq.gz
    ├── 4f50471af3da10675ab66fad1ce957d3667d0db3.nq.gz
    ├── 4f71b9ed5acb2013ff6e9983c5c02877e3fa96e1.nq.gz
    ├── 4f912a2b3e99131c532284eb82003392ca469b53.nq.gz
    ├── 4f9355077657ff04112158ddd4e601851e9d2d08.nq.gz
    ├── 4fdc0615b77014fef0469a8e43f030d56e8e358d.nq.gz
    ├── 5022d512acd587c8090885839ff5baf6c62e2af6.nq.gz
    ├── 50fc977a0835f5d5ce20a64fe2b7305780c8c320.nq.gz
    ├── 5154ba732513acac247ae2568024b491c4df8e1c.nq.gz
    ├── 5199a769f889533ad8e0c432d93f185c3fac44a4.nq.gz
    ├── 51c65a5299d3bf90e7d870a5a1144451828a31f6.nq.gz
    ├── 5255fc9ccd13ab2f554f5ad7d15ee18af47e47e0.nq.gz
    ├── 52a9f9964655b204a4c882a6c352ab15ad4196e9.nq.gz
    ├── 52ab46e48f1134af43c11b0fe964eb3795797f3e.nq.gz
    ├── 52f73468916403b137fca762ddb5284b6f1c76f0.nq.gz
    ├── 542aa734707f9cbd8582d860c04f62547446b964.nq.gz
    ├── 544b930de321031d3813dd71ca6a8e0ed8c0ee94.nq.gz
    ├── 5481219348511a087eb884d8d70df4a1ee2e7df3.nq.gz
    ├── 54a1515d3211b03a8af1a65ce5e0657ffcb23ebf.nq.gz
    ├── 54dcc1a145965f87efc9ca9f1a9e8bd62935a2f5.nq.gz
    ├── 54df4ee7ea2eda8357d7792da7e51d9b9c9a9582.nq.gz
    ├── 5568f3b218e1c4344f793f599fae635a8d7eaf06.nq.gz
    ├── 56212fbc59fb7f4b892e4fb9ba2fc7d5e705f0e8.nq.gz
    ├── 568e338c7dfebf6204da6bee6da307dd5897491b.nq.gz
    ├── 573da56c7502b1d78c62b4c936060a4b9d8aecbb.nq.gz
    ├── 574af7ef699d8297f193418b77be2ea3562efb43.nq.gz
    ├── 58151cc14d4eb5226a3fbc64365517f7f7d21ac4.nq.gz
    ├── 58311c60d645cf01ec5830ecda3dfabce30672a4.nq.gz
    ├── 58aa0f53c7e4edfb419ae68d7e17fc6a40e3aa4f.nq.gz
    ├── 59750f2e3324742221f49a1446e2505258d4513d.nq.gz
    ├── 597bd2d1b873525a53a3f51aa30e2ef0d3252902.nq.gz
    ├── 59a414f77045bd60531026262ff9ed10b5b9d9ce.nq.gz
    ├── 5b40202ab6fb1607e25951be0d527427202f0a2d.nq.gz
    ├── 5c6c4ec79a9104857aa6ef52b8ca3d9859672c6b.nq.gz
    ├── 5c9eb7b400ed542c912fe8e3dd44c87b235d8e4f.nq.gz
    ├── 5d013d7038d384fd5fc4f607b572253009187a11.nq.gz
    ├── 5d3f043f40402bc8f28bb898859b9f586e6835b2.nq.gz
    ├── 5db81e10a4a5c31a7951d7e280ffff493fc6502c.nq.gz
    ├── 5f748471b1ee73fd6b7a982ff55f504f84844fb5.nq.gz
    ├── 5fe21eecaec1610612862da37c7ed52af90ff264.nq.gz
    ├── 6036535877657cfd6fa0782b17e8d1858d1c9288.nq.gz
    ├── 60b5a3d544ada0193449c47cd7f83a8e372b597a.nq.gz
    ├── 6145458f638f23d0b1565dfa14324925882dcaae.nq.gz
    ├── 6217ed760b10bb023bc7048a08c08b8ae3178c68.nq.gz
    ├── 63539f980ba0324a84f54ee7cb9b6004631058ba.nq.gz
    ├── 6381098ceb26c7494e76fbcdf1f5606dd29c21cf.nq.gz
    ├── 63f2266621115f46751138d63b7d91b0a32d7def.nq.gz
    └── 64e97c1bbf49d94700bf612e7f50824eda2f2d70.nq.gz

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

[allenai/dolma](https://github.com/allenai/dolma)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
