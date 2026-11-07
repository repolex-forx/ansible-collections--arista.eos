# Repolex Knowledge Graph of ansible-collections/arista.eos

RDF knowledge graph data for [ansible-collections/arista.eos](https://github.com/ansible-collections/arista.eos), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/arista.eos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── adc333e92ec56754001115a1b6ee613e2c3bd925
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── adc333e92ec56754001115a1b6ee613e2c3bd925
│           └── chunk-001.nq.gz
└── blob
    ├── 004b1bae5a61256d3cf482b88014befbc7c7f631.nq.gz
    ├── 009d377e62e1f53e120a9f3fdf36e2cb8e0ee91c.nq.gz
    ├── 00c0e8c33bb03bf1fc992b8a0c6a51ab36236fe3.nq.gz
    ├── 01a7e807bd33bc2d2e84b8b8deb785cdd622b15e.nq.gz
    ├── 0269a4cc22e7af69aabefda927880fb45efeb4e1.nq.gz
    ├── 02d4ebd3a596cac94b3a94f81a3634e5b440026f.nq.gz
    ├── 03018cc9e2856983f4e42bb4ec541a5f580c98b4.nq.gz
    ├── 0321e1d76d6b63e0c15baa1b7c4bd6f9d183cf0b.nq.gz
    ├── 033bd4532fe993ff5ed8c923284933b018080dcc.nq.gz
    ├── 04ab196a9ba52b458e8a0f7c40ca3b2cd8911c67.nq.gz
    ├── 04f9c1811985f0b2000f1028a3154df99c587cce.nq.gz
    ├── 0543e9a2eadf094230ec0dbc9350d0ad8138e937.nq.gz
    ├── 055b89a49ff4c24e59efa2929373f4c2f2591c8d.nq.gz
    ├── 06137bb6473a7070e12fe629797f31f1ec6eee27.nq.gz
    ├── 064d2ae2e196d47c49fb4a9de10e6ae0233dc47c.nq.gz
    ├── 06ad086a885327167b927eba709721e15be2a4f1.nq.gz
    ├── 08059b6ef886ab32ad9af57298907b33233b1493.nq.gz
    ├── 090f39f0a3dc3167834c66f81bfed6808afb7eda.nq.gz
    ├── 092fe0774a72ecb0246af52e4383ae966acaf7b1.nq.gz
    ├── 0c540f7741c54b575abd3a39ba3cd254c73953cc.nq.gz
    ├── 0cbdd432e5c2a847156523facc57af1f2394aa25.nq.gz
    ├── 0cc2026be26ecd8d1359be5f2c920bf00f24b611.nq.gz
    ├── 0d2ec11c0c2628b4e99cb2d7ae982a26d2973d2d.nq.gz
    ├── 0d61147283d5184f3cd508dd9155feb2e6edec68.nq.gz
    ├── 0d6863157d6137c8065d98f0fe027d6d83c756b9.nq.gz
    ├── 0d8545975b4841e8a3eb7de4d59435170f5ae7fd.nq.gz
    ├── 0e554420d203bb431879ef8d44e5a14a66cae438.nq.gz
    ├── 0e7128e79b09a8e93ab9f2c6c0e75ca9b6504310.nq.gz
    ├── 0f2aa73dd9b952ec9694e097b24fafd7573656f8.nq.gz
    ├── 103519b1bc378484b10776cda5a89b7238b14c4e.nq.gz
    ├── 10e2c784c363e44e206b441691ca14e052a423a7.nq.gz
    ├── 10f624c968796fb51f90f33e31d8059f2241a8e9.nq.gz
    ├── 12032ca1c11531ca4c1803ce8990c65fdfcd698f.nq.gz
    ├── 1315186947830688b01255a66b036ea35752591c.nq.gz
    ├── 1325a0d0681d81e77dfc7e804c5f03eb80637d47.nq.gz
    ├── 149f40debdfcd4e631b60c85982742dcdc67033e.nq.gz
    ├── 14f259f1006049ab749cad3f86a618fbe41c13eb.nq.gz
    ├── 1560924b5744b9c05a0acd25d1a1037d3e3f904a.nq.gz
    ├── 164afead284de6add13c8f514561691b2f1c8dba.nq.gz
    ├── 16efdb80fd202dc466887635ec0cabcd5a859797.nq.gz
    ├── 172d15be89f50e7a91452db15204e3911dd2d348.nq.gz
    ├── 180fbb0c58f7b9c2efa48895d9e74d719de81626.nq.gz
    ├── 18142cedfa2c3b95a7a7357ac2076caccfeedda4.nq.gz
    ├── 18ea1c5bc8cc0222d2b304e844ce86dc61b0ee47.nq.gz
    ├── 18f380b968a07a56be1391c1d7c3e6edabc82215.nq.gz
    ├── 192835906c551e1e016ac381c6baed3992bcf730.nq.gz
    ├── 1a72174b2bd7389e5c36ed51aa33ad232fe4f4ae.nq.gz
    ├── 1b4080f14b13327cc4cc6c4b2001fed27cfddc20.nq.gz
    ├── 1be361fe095e228be0d3bc15dcac9746c1798c00.nq.gz
    ├── 1c3127592782760190a244782c872415652214c9.nq.gz
    ├── 1c3d029610648082ce49439c24d3f94dbd5adb93.nq.gz
    ├── 1e02dbd1b190029cb85f9dffcf3df08e711dc68e.nq.gz
    ├── 1e0cc102c80e57b70d68098e3823e6f77fab02dc.nq.gz
    ├── 1e27303fe1e59358ccd2e5d56e454e9bf06dde63.nq.gz
    ├── 1f2fdebfc44bf63fad1e2371885528f3e4a9fca2.nq.gz
    ├── 2185cc4f92be49d1094525428837c607d22f8f40.nq.gz
    ├── 21e27358dcbfbc047af1ad3bbfe03d652a1c67f2.nq.gz
    ├── 221a4ed5f7f801e328c26ca1f65e0ddb207ce967.nq.gz
    ├── 222c45c4b5376952ec7f1af05a96ed93a6e25be1.nq.gz
    ├── 222fd1b4d3559e312ff7755a73c5427919a63f02.nq.gz
    ├── 23ae4e72972c7024d653ef1075c9476663407bd6.nq.gz
    ├── 23e4df181fdeefb926cd76012f2aa7b847f9afdf.nq.gz
    ├── 24d238d068cb7686eea3c1bf4ac618ce334d83b9.nq.gz
    ├── 260aa199682d9aac8ac1dcffae13faae6677ca6a.nq.gz
    ├── 28810c9500b672bf7e706d1cb4e080257330f1da.nq.gz
    ├── 289af59c54ce9993d112bad4f4bf99cd7cab0633.nq.gz
    ├── 28bcab93c5781b9082f3231fcddd50130097e2cb.nq.gz
    ├── 2918b6064ac45d23c6b3ee3e7d02a6cd0d45fdc1.nq.gz
    ├── 29f6d99aa942cab6f0d43044be27e542bf6dfa86.nq.gz
    ├── 2ad3386d117b63f96e68cca063fe1acfe9a90b37.nq.gz
    ├── 2bc00601891cba080e97765ced9d35d2a8ad2cda.nq.gz
    ├── 2cac9289be5db703fdd0f57f8c4b69aa016e5669.nq.gz
    ├── 2cd4b3bbc78a3f24c3daa66297b5d68a9d5ef1fa.nq.gz
    ├── 2cf1ea5aa099e52d3c303896c0ff4c30c04c59a4.nq.gz
    ├── 2d738e03e4be407e15a96c94ac83b4a7b6c58238.nq.gz
    ├── 2e952efce73b8f336cd3f85aee2f4bb138ecd905.nq.gz
    ├── 2ead37e444ed4422357eb85734bdc44eb5be1524.nq.gz
    ├── 3014acf8ab99a50a6d0c42793f3049cc8c035a65.nq.gz
    ├── 301ff5400fe7c110af4e972829eee5f90719c757.nq.gz
    ├── 307b63f01e67d5a02959ea596f2177b258416bc1.nq.gz
    ├── 30e64370d8ebb9c68d79fd0f26fb68a22dde3e1b.nq.gz
    ├── 3112bd183c55c5bfca1e861978404153ea272991.nq.gz
    ├── 325e97a22139abd2339f80bc3b724f318bc446ca.nq.gz
    ├── 32c715cf9ed916df2d0ece3ec116feacac2ab137.nq.gz
    ├── 32d8f580ab278205096c55ed45f8122d222dc739.nq.gz
    ├── 339a2b77e3e9b7f3685e496e869a21a5c939e334.nq.gz
    ├── 342eb6d0585ea75784a680842843291417570fb8.nq.gz
    ├── 34414ba5b34dda98e0bbf3374a5a3ec69a0ced56.nq.gz
    ├── 34c596016e1252d4ece5e5b6f8d3e4a8acf7e8ff.nq.gz
    ├── 3585857f66d4316ab37a0fc5c6739473828b47ab.nq.gz
    ├── 36862ab6b51b6e74a621e2fa481ae9e24e8e62a8.nq.gz
    ├── 36cb606c614077ba6a5036ebf8129b1c54255303.nq.gz
    ├── 38664361688e5440eef2d01cf8e735202300a762.nq.gz
    ├── 391bef55677db3b34d4845807c54fdb059cd4305.nq.gz
    ├── 39b9527fa27ac38a3f24861d704698aabc99a032.nq.gz
    ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
    ├── 3b338c2cbc08a5cd45d127eabba2aa9d5f15180c.nq.gz
    ├── 3e22fe780911f635ae5b59d73a4e12ec62290dd8.nq.gz
    ├── 3e6099eabd8465e26c54f498a7cd01fa445c959d.nq.gz
    ├── 3eba5e69c0cee251ac62c4ebd3bfd1acc1951767.nq.gz
    ├── 3f9f3aa7586de46a7dfce03285a7a416d0b8326a.nq.gz
    ├── 3fd8ed21e1c8845843ec6a3977e42c499ff4e0b6.nq.gz
    ├── 416cd59974f95cd16991f23cb662c7f3245d6d7d.nq.gz
    ├── 418a70b0ac3ac40c35d77c5ca5f9806e45151767.nq.gz
    ├── 436da9ff60cda122a685ce1d4391abc812fe45a5.nq.gz
    ├── 43bfa3cb22dca3ef97a6e54bad8a2f45b0d5054d.nq.gz
    ├── 4409e7ab25dac04aeba7fdd87a982d559f1f6ee0.nq.gz
    ├── 4473d108f486a0e5b93849110f89a9af3311e37e.nq.gz
    ├── 4477d0ee4bfcc00dea94f6bc5876aa2b7e068d22.nq.gz
    ├── 44b4d82f88e01868657fd994e35cc48469f47cbf.nq.gz
    ├── 44f22e6f144807c73074e98ac1b48b4815215acd.nq.gz
    ├── 44f5b7ffd56cfb4ddd519062a25a8b07f7c1b725.nq.gz
    ├── 452019e17bafa05ed2a43224126bdc6843eeb695.nq.gz
    ├── 452aa89938e5b8a5e20a07f5a0dad53f644c3aa4.nq.gz
    ├── 469b95f08b0efe1ec18262521cb3dc561f4cf528.nq.gz
    ├── 46b7cfea15b1a7584a8c845a58497987cfc46109.nq.gz
    ├── 478d2eea152a00e555b91572ca0bb8d862cad095.nq.gz
    ├── 47a760452d12a1692bbb52a48a82e1ec4e986134.nq.gz
    ├── 47cda48aea065f652c54c47fd141196c45478acf.nq.gz
    ├── 47edf4366cd6a6aff292bd0d749019395679da7b.nq.gz
    ├── 48c0f4584305cab244696a699273c78e6a504f00.nq.gz
    ├── 491d61c3087a4fdb20e098cc08ed41e0d7b6ab3a.nq.gz
    ├── 492f29662af8a8dacadb33f84c5b1835f36e11be.nq.gz
    ├── 4936b9778988081355b32e5d864f9c831493364c.nq.gz
    ├── 4951329dd179636db5d467e94ae0f90b53673a7c.nq.gz
    ├── 495e31507ecd2841d923b9be52b57a6b9777fedf.nq.gz
    ├── 4acb4eaa2be9e453edc40b328081744d73c6a442.nq.gz
    ├── 4ae53495354c46189f6b89866cc6762787993c1c.nq.gz
    ├── 4b15c6eb0dbdc0fa3da83e14ccbf170e4ca6b146.nq.gz
    ├── 4b46461ddd93645b9184359d57dfb6eec2b2e50c.nq.gz
    ├── 4bb752fffe3e68f15b582987e6b93819398c1952.nq.gz
    ├── 4c40256f1abbdf6927ca95f1e340a180332ab292.nq.gz
    ├── 4c960185d6d66f8b23a40df1dfad297d9c53e591.nq.gz
    ├── 4cd89815409773c0a1c902d9ecfbea7c9d182f90.nq.gz
    ├── 4ce161dc9df90860ebcb46a730cadac2d72203ea.nq.gz
    ├── 4dd91404a0bd0ec0c80f4f26635abafba77bac34.nq.gz
    ├── 4e16a33334af727720b9d8685cf18233d48bd5e8.nq.gz
    ├── 4e88f9d9418d8ca1fbe46a9715cc59780edfa4fb.nq.gz
    ├── 4f31cfbb2f4a82f2070b67ae0f56d6e541dee493.nq.gz
    ├── 4fcace450ca62d9420ce506b8c1b7b30298d78ee.nq.gz
    ├── 4ff62759ec33908ef13bfeb0fff08ec6058928f7.nq.gz
    ├── 50a37b9e5580f0fc9cab547c5899fd5e5bf95e87.nq.gz
    ├── 524fdefc649cbdc3682caa1120321bcf736c87fd.nq.gz
    ├── 52a3f4d394318d9597af99e164740e4374952b36.nq.gz
    ├── 52a5296bfb9a79a4ba5d72ca31bf566f6d13d0dd.nq.gz
    ├── 53b75afabf3175f1bdaee702ee1d451a253b679c.nq.gz
    ├── 53c00da4e52d36c83feafb672142407f0a24d034.nq.gz
    ├── 546efdad73b9520f51482a38e071c61978a562e5.nq.gz
    ├── 549dc8a8ca8aa96fb82ac698074b5bade2bbcad3.nq.gz
    ├── 55ce0d00455710e3730d4a4b8a989012f092faf4.nq.gz
    ├── 562bcb915915f10a53ec20217d378a8f4c76286f.nq.gz
    ├── 5636124840f90e1843a57125388d689a285fc791.nq.gz
    ├── 56420dd4df92faa3eaa8efdbff087bcc0996e382.nq.gz
    ├── 56596359216b37b16998a1ec803421e3842da12c.nq.gz
    ├── 578b022863430ad54d7526a742fc002ad493780c.nq.gz
    ├── 57bedc47470b4caed04d2a2e69f08e60d4e134d1.nq.gz
    ├── 57cea5b65fb897565ff062c8208ad54851233a31.nq.gz
    ├── 585a6a2c17efb38fcb0ca9c5a0ae2ef5c093476b.nq.gz
    ├── 58757860d6efebb16f41c687f4afda744ea4bea9.nq.gz
    ├── 58fd833fc12bfae8793b5f052655649b955712a1.nq.gz
    ├── 595725b6237d42c4a8011c01a0acc552773c8ff7.nq.gz
    ├── 59e767e96922b184f118388c208ac2f64f9bbd22.nq.gz
    ├── 5a2a70f495cdbc221dccc25c5cb673537c9a5e61.nq.gz
    ├── 5a5fd77a331db364b0950f224c0188ac20e085ac.nq.gz
    ├── 5b793084ed5a6284c8e846332a41803eff7b9c97.nq.gz
    ├── 5bf6573ee50efbad94444772c47de4862eafc69e.nq.gz
    ├── 5dbfbc310107ff2628cecf79b7799f0ac37798fa.nq.gz
    ├── 5e87c055deeb52a554396c4ecebc3aeb2381640f.nq.gz
    ├── 5efb66ff5fe51179dcff112b30e48b11ee3ce506.nq.gz
    ├── 5f6297e1c111f615e27d0891cd642201961ca76c.nq.gz
    ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
    ├── 6017edbbc6f00647aaa68c6a052040a56723ed02.nq.gz
    ├── 60f45f05951e15a2eac8be1936f49f38f92a7226.nq.gz
    ├── 6174cf12265dac9e75bf2338d862f834a7bfc5bf.nq.gz
    ├── 61d3ffe4f9416869d4fff5118f784dd567977025.nq.gz
    ├── 621581670552fc59a69743e1de2058b638cb42a4.nq.gz
    ├── 638606303e91a80a725331167ded665a4813b38d.nq.gz
    ├── 6496bc37b914489ff63e8cef0caa758e887856d6.nq.gz
    ├── 6532608a606ee779889239f0c62db8678925fbe3.nq.gz
    ├── 6611f3ba604eb5430608fb6e788bd415f941ab85.nq.gz
    ├── 66439c8a08fc8f1f1a706e47ae759a0f1a53b876.nq.gz
    ├── 6686667862d7d5e5fa28434fe297fadeac6eff1a.nq.gz
    ├── 66961fb0607f3b7da21e25a6e26ea7ed8c0ba47c.nq.gz
    ├── 67909ba8aa38cc8cad9fd909f0e400dcba6b155d.nq.gz
    ├── 67e5188f4286464b3bc5272a3424746c5337ef3f.nq.gz
    ├── 68175e6f8cab60167d3d57245cdbd29802520b66.nq.gz
    ├── 68698469437cb5dd2977ca2ccabe3ae89bd4825b.nq.gz
    ├── 6891cabbf58e20281d2b4e4b21186194dc4a1b25.nq.gz
    ├── 68b5291b885395ab39dddd9747e5584bc2b96818.nq.gz
    ├── 68be4cd2530727eaf57dcba179cff0b788f17a3e.nq.gz
    ├── 690eff732ae39804613fa27c87aab0fdf9eeaa48.nq.gz
    ├── 692ce5cc7d3ab6798b71a45e78c4925b46d8b6da.nq.gz
    ├── 69fa6f8b74b5c6afff3547f75d5478dc084daa41.nq.gz
    ├── 6a471371a53d463023bab6040d3f1bf71e22949d.nq.gz
    ├── 6aeb5537576057c4d269bce756d7fa227a05540b.nq.gz
    ├── 6ba42a47e343234939f9e8327276a1604731b9ea.nq.gz
    ├── 6ba445594c64dbff89577cf3ba920f4f874ef6d0.nq.gz
    └── 6bba246e7ea17bc11b53b343361a371c2c2eae39.nq.gz

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

[ansible-collections/arista.eos](https://github.com/ansible-collections/arista.eos)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
