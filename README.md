# Repolex Knowledge Graph of langchain-ai/open-swe

RDF knowledge graph data for [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe), parsed by [repolex](https://repolex.ai).

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
rlex download langchain-ai/open-swe
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 54be3670c03617b5731d9821d0b944d3edbf24a5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 54be3670c03617b5731d9821d0b944d3edbf24a5
│           └── chunk-001.nq.gz
└── blob
    ├── 01087bee7b272b915a9a45366392efdf15e5dc75.nq.gz
    ├── 02b1e8723399b546f5e1f384ae71a031d5b93f70.nq.gz
    ├── 02b361b7f02ab65a25f82327950b489af7412ff8.nq.gz
    ├── 02fb66b4ed6daa11bed9e7d29ac47645f44cbcf0.nq.gz
    ├── 0331abc589db6d8ad6b5fa8f31a3c13d5dc2c29f.nq.gz
    ├── 041b566306c3838bb8b91b2056285f216ad6ca6f.nq.gz
    ├── 047b2fbf1f76292e70e28da650270aa5e9a3eb85.nq.gz
    ├── 0509256bd4e1c70d376b72690c06459f81f0d0b3.nq.gz
    ├── 0729a094dc09ed4777141e411755c0b277a4a24e.nq.gz
    ├── 072fa8752c6d9e35d893a0d9328de9d784fa2cfc.nq.gz
    ├── 075f078ef86e59f35578e908d886a1ab8f2dde9f.nq.gz
    ├── 086006b7a83b832f663d6650cdafea156aeef61a.nq.gz
    ├── 08a2e0f524394d86cc56e4b48a7586ac005a812e.nq.gz
    ├── 08bef82673b11cf0dbffcb7fd61002d52e135023.nq.gz
    ├── 08c4949196ba4b8542a39957056c6a3fc44d60a9.nq.gz
    ├── 094bc2874e84354e246f973223e9f8804063ad44.nq.gz
    ├── 098640eeb7189cf470457e8e9c07bb5c993c792e.nq.gz
    ├── 0aeaff4f60adc68bd7543e756269cb44e93aeaba.nq.gz
    ├── 0b8bb2e81a002143db236e0d495c00bc99b5dfd1.nq.gz
    ├── 0bc33f883180f89eac292ea40367a182d8ee2633.nq.gz
    ├── 0bce707d04f6df599d2563864b3ff0e4d63ff439.nq.gz
    ├── 0c19fab6af8ce29f0a45884ada9b13bc78b0f703.nq.gz
    ├── 0c813057e0659ceeda9fff0bbe3492d1312d1aa7.nq.gz
    ├── 0cf0b1ce61ece6f13a8491746d30398ee53f829c.nq.gz
    ├── 0ec78820b1ec79582d5d53948dfc098d14b797e5.nq.gz
    ├── 0eec0201a5b36a25384d3fdde547c5ca46bbe9cf.nq.gz
    ├── 0ef28ee4ef38846c4efbb636c4a602e65e8fb97c.nq.gz
    ├── 0f0412f2537f10b8fbbf1fd57010653d0c1b7732.nq.gz
    ├── 0f219ed2e7763407ce95631be1e66ba86b003dae.nq.gz
    ├── 0f8389c9ae66a285737635630de06d353abb9286.nq.gz
    ├── 1037bba259f351069cff8a5d11b3dd69ecca0568.nq.gz
    ├── 107f64dfbddf73229552a5e941f307a92aedbf1d.nq.gz
    ├── 10cae58cb8bbf6e010ad391c17da12d6bb2f329a.nq.gz
    ├── 115baec6483c7f312861cd013e2ebf924bd56a03.nq.gz
    ├── 1187e6a517517babf659bc431fd8f43309e6d095.nq.gz
    ├── 11e84ae76663bb5ceb9c099cb8922c864711f9d7.nq.gz
    ├── 126227bfa82fa478e9d3ab925a1c489944809056.nq.gz
    ├── 13cb2bd0b5cc4f59cd725fa5e034f56b1a2fde6e.nq.gz
    ├── 14638e273cc036805c1e257bdbcced46d1c72509.nq.gz
    ├── 14a947a04c1fab62c51c04938f4f0151f9a549e0.nq.gz
    ├── 14aa5477718f5c73f2eb5b0f7972eebe967de042.nq.gz
    ├── 15c20f2b55195c57821285bd4aa8204b6b764842.nq.gz
    ├── 161dc74e19a98df0e5a9eed37afda2887cc22401.nq.gz
    ├── 165850e6ecf7b046c44ffd972124e8f0a8793784.nq.gz
    ├── 18a83e9b974fe477a33b55a310c3520696459b92.nq.gz
    ├── 192ec9e55bbf91b9d84b7966a51a23d67dd92ebb.nq.gz
    ├── 19cbbe517cdd30daf66159de5bb28f9a86bcb910.nq.gz
    ├── 1a4d4bf2243c71352a97c28627bf4102bbc3a814.nq.gz
    ├── 1a669e6d842177c427fdda0aa2ca0302a960190f.nq.gz
    ├── 1a774fc3e3f4680e4e06d196767ea031c72b314f.nq.gz
    ├── 1aceff1ec1c27be83c9abd2a10a481d07d277dec.nq.gz
    ├── 1b1d01b05e3f03580eab6e357cffe6b6cf9e7f4e.nq.gz
    ├── 1c7d9274f70d72c6527c2ca50145dd52b55f7a38.nq.gz
    ├── 1c95136fedbd5562e1c6870321cf8e491202f6a7.nq.gz
    ├── 1cb5b3ce0c97329c6d1355484103b6fb91864d09.nq.gz
    ├── 1cf2ffcff3e0300fc82b2c56cf472439db301898.nq.gz
    ├── 1d42b63b1658dca12bc7a983498c7c7e52cf84a5.nq.gz
    ├── 1d53601f0241b8a41f1b03da34f1b35405e2daa3.nq.gz
    ├── 1e6e7cdf9bf222f61f33821bac9d1cb182e57a92.nq.gz
    ├── 1ef504cd08d53c2dba5364b7baa55d96839c0718.nq.gz
    ├── 206b94813085443fce34783580b443675a963e27.nq.gz
    ├── 206d679c8c7bdaa10e5997fbf403cd3ff8de2ae5.nq.gz
    ├── 223904db61b22b30f8b9567aa7f86cdd6d2425d5.nq.gz
    ├── 24302b13396c01f91462ba25e968d9d40c6b9c38.nq.gz
    ├── 24c9fae252118658608e52fdef256a604ce5cbb8.nq.gz
    ├── 2647fda96e3be769613ee4b017bb4b285deeec83.nq.gz
    ├── 2670a914c2e949c6d4d23a6347d0409f695d2785.nq.gz
    ├── 26a0737451e629e845f847f78bbfba399885be50.nq.gz
    ├── 26c816a470caf8f325bc362703f3fa4c4f036671.nq.gz
    ├── 27381f9292fe3c3e434dabec31c2281c409a0e8e.nq.gz
    ├── 2828065cf424b4657cb3500d85a3c72c8da3bc4f.nq.gz
    ├── 287d07cd9a6a4e8c18641db5a858f11731d1c00d.nq.gz
    ├── 29b5e214e2936aeaf1a25ee8ffa2cc32b37fd524.nq.gz
    ├── 29fc4989fe0506f9749a5c56a81067b484251686.nq.gz
    ├── 2a2f321552016bcd02610e81af0dce293de79e50.nq.gz
    ├── 2ae53c5109073abcada6689382d9019dc25faef7.nq.gz
    ├── 2ae902ae01a9255f0a35b26e3bf2cab40ae5e430.nq.gz
    ├── 2b441fc466bd765403987a10ce6cd4466c6295ae.nq.gz
    ├── 2b724c6b984a9b7a406eb8ac464379b88d653aed.nq.gz
    ├── 2bdd539c26f95dcbb9622937c4729f9a2d5da03d.nq.gz
    ├── 2c9e90ca04337842698d52c6dbe22f1be3be16bb.nq.gz
    ├── 2c9eb398eb1e0908975df72cf4fb3ef08e1cb21c.nq.gz
    ├── 2cc71c764c721888ddc0d154d7b5173e52283ea8.nq.gz
    ├── 2cee8dd1f377b3d650998659ab6b622dd9392b5d.nq.gz
    ├── 2d774fd6f3b5ef039ae8e40157342b00fdd549b9.nq.gz
    ├── 2d94fd4a99ded2a275acac6e5369301a6c3e9ca8.nq.gz
    ├── 2df8293cee8c28510af52e5bc7c07afcd42d5885.nq.gz
    ├── 2f1f10c8219f6927ba71ddd597e72e74e83891f0.nq.gz
    ├── 2f4bc6ad2a5f19f44b8e75a0bc85bd0b0e791902.nq.gz
    ├── 3045456a74300d86ff4c61ad86dcb70280d6031b.nq.gz
    ├── 33a3b495195ba96e42eb9f041ada471ebeafc4a9.nq.gz
    ├── 34b3378753536a42894ed116f764590f023dd54b.nq.gz
    ├── 34f94333a28450b4998e4ed62b00a3735495bcd4.nq.gz
    ├── 355aad77a8ca7b75fea3cea7a55e591bfaf636af.nq.gz
    ├── 3782ccf5823c87574b693f221e9b1980c84e6854.nq.gz
    ├── 38c63649477a55b93f7df0493b27ccb6ffedfced.nq.gz
    ├── 3ae6017a20a97900b08506100782fa5863d4f916.nq.gz
    ├── 3af4fcc5f6891725f6f44d721b60d930365f95b9.nq.gz
    ├── 3ce9a1225ef80c17ff1f548f2bd27f39623edda5.nq.gz
    ├── 3d101fd6bc1042df83578a052ccef61905ffe37a.nq.gz
    ├── 3ee8b3d521681461fa797ff339fd041b55c31a34.nq.gz
    ├── 3fd19137dbf77cf53dca1f6bde7fa085274c8840.nq.gz
    ├── 40a97a3b37d3ffbc66a8fdce0f3f7a7e9f1d0396.nq.gz
    ├── 40ef9ebc17358e9eba95b367a05ecbc797903890.nq.gz
    ├── 41023a5faab806e39ad2327d5f839799d994adcf.nq.gz
    ├── 41046a829f43e24c58848bd78e6133679adbe1ad.nq.gz
    ├── 4339110997ff89c7cac3b1b6d62e989bc9ec2f39.nq.gz
    ├── 442d2d2655e535a12a81566e22f0f24011001b3d.nq.gz
    ├── 447b21d7f02190e2e3ef44481da3407ab527744e.nq.gz
    ├── 44e667a5765f368ac2c0c6fdab72afc597d2fb42.nq.gz
    ├── 44fe48329ade3c8fc86f1515a4903769a41d8585.nq.gz
    ├── 45b46f9a179bbab426a3df0855e6dbb1d39a2583.nq.gz
    ├── 48c9014e70207750b68b3aacc76c99a8e0c0650e.nq.gz
    ├── 4b41c9411185aa60164a513cc4bd12be5bc20e00.nq.gz
    ├── 4ba5f52e38b03fc8abe112d1356e010f6ae7cbc3.nq.gz
    ├── 4bb1fb3fb01cebddcdb95d6ccb98d1fd5dfa7e6a.nq.gz
    ├── 4c0cc3e2cc098af87072fea3e4015ee6d8f7f7a0.nq.gz
    ├── 4c430c456f5540f2887a965c901a1876c9df4aad.nq.gz
    ├── 4d856f73a8546e4bbbcd2db144fcf2c1da7d346e.nq.gz
    ├── 4dd178c67b83022aa550edd6f19504811fce2af0.nq.gz
    ├── 4eb47b4554de9e3ccbe33a71efce55ef069d5b48.nq.gz
    ├── 4fc0231995f2722094b1772fa8ee5940cd42597f.nq.gz
    ├── 50b793435e9f4bc49f5c0589e2b07975f1c409f6.nq.gz
    ├── 50ea8a2a67249ada3969243c7b23966702891e9c.nq.gz
    ├── 511a991536e03c5da843b07adcf914a01e9690d4.nq.gz
    ├── 5160735a0d151e8daa6940d4498ea3dd274a456d.nq.gz
    ├── 5277f3bf612c6c1b3b07e2ac0743fe06700da603.nq.gz
    ├── 5316ae217e0936aa27667906244d7a9f2291d91f.nq.gz
    ├── 53af6fba6b1c7d766fed201d2199deca6f4836fe.nq.gz
    ├── 5411b644272f1f59c47c3cf563829557f23a5f5f.nq.gz
    ├── 542b3fdfc109010aee506fb50ef4da3778d0b757.nq.gz
    ├── 54754ced21744ea54cc042d1b22a793e52100130.nq.gz
    ├── 56238afe660b2ca86e961d736f388c36b5a76013.nq.gz
    ├── 569bf4fcfb5ccd5f3b2eea6a5947617c9db1d897.nq.gz
    ├── 5796d55892f8ed38f8572c5d8a706b85b9c85ba4.nq.gz
    ├── 585aa9dfdb410fa100d639b1f11a638b8803ef39.nq.gz
    ├── 58777f444d774e8e7e81c2c2126c111e0ac555b0.nq.gz
    ├── 58e3a20b5451bd43a9251e5ebaac9ab4594e27f5.nq.gz
    ├── 5989a05ac64c1b235d4226c12dde11020aea9de4.nq.gz
    ├── 5c5abcdba120e86f45f5c0c004ef6b307009c0ab.nq.gz
    ├── 5cd56862e364bd6fd0729b11efa181c6da25ca23.nq.gz
    ├── 5cdcd11a3a7aed8aa73f9c2104ba10df0391a503.nq.gz
    ├── 5d77538f83d9a65d821e2ffb9b979a73c3b385cd.nq.gz
    ├── 5dfacd2b52eba6d98be078a4e5528283551e8030.nq.gz
    ├── 5e3068655d486a104a3fd7a7416b0ff3ec0733a1.nq.gz
    ├── 5e88b6937fe0c8b1406aef0a9a397f7070ab3c60.nq.gz
    ├── 5f315f6b10b878b39970f555dfdd3e8ca2bca9dc.nq.gz
    ├── 5f4c7b61030a32a0a63758aab045b789a26a1afe.nq.gz
    ├── 5fc20248bfd7dd286b8927db3cdc8fa2f700efe1.nq.gz
    ├── 5fdd4c354f5bf2998b42db8431db2d430765f4d0.nq.gz
    ├── 6009b2639bdf1eb0ecca0a95e14227f899109246.nq.gz
    ├── 611da687a0f196b8ea5329ef1c4923ef9d4e4ec3.nq.gz
    ├── 6180f3c349ff898bc750f2aa48f653c046e38c46.nq.gz
    ├── 61b3f59085d33a0a89c7ff01967ac3049655c7fd.nq.gz
    ├── 6222d26a89e0d31e223c6cc80b77fc32341ed8f5.nq.gz
    ├── 62ab9e068902262a94d7b44fbd3e5a54867bae2b.nq.gz
    ├── 634aab042bb67eb6fed5dccc320b924877471aa8.nq.gz
    ├── 63e40d38ea07a178ae982fb14b55c3381220963b.nq.gz
    ├── 648006cc7e59142e9620497b3c378f874ccb2113.nq.gz
    ├── 64db5612cd7814870193f0c77a9c7f3fc178aa67.nq.gz
    ├── 64efa00134a2305c5725d58cbb880a7782b01703.nq.gz
    ├── 66a9949d17f0ee9ee5f517318fdb8180316dbf60.nq.gz
    ├── 678163834c5e533d8cbb78cd1c8ddf38251e5922.nq.gz
    ├── 691fcb8053dad58d22c63ac367138e61a9afef72.nq.gz
    ├── 69a59941eeaf06277989b7c9573e3983ffe0258f.nq.gz
    ├── 69e21d5b70be5809b2966b6bd336295c3edaddf2.nq.gz
    ├── 6a0c925ace9b5c7470bd0d5eae8f8e5f53aa5f72.nq.gz
    ├── 6a2ecb942c3715ab1ff1d87ff2ac4dded3b9529c.nq.gz
    ├── 6a4925fe44116a551f4c89bcc2e9582bb56f1c22.nq.gz
    ├── 6a7b836079fbbc30e4283bcdd17e455bf66e3e81.nq.gz
    ├── 6aaefed4b6d9b4e563f04bc141d88fc551f29f08.nq.gz
    ├── 6b513a701a5b9758feeff12728e188411ffd454c.nq.gz
    ├── 6c16d9446664e4c0905797126f0c0d61b55bb6ac.nq.gz
    ├── 6ca56d88fc82d390e37509f57a6b91d5619cca90.nq.gz
    ├── 6d4ce7d1f61d936529729a5867c74f9c4181a9aa.nq.gz
    ├── 6e0322941710b99be1e9f73a4b71160b89665773.nq.gz
    ├── 6e3de2bd6cdcc10d04dfe57a4dcb566b83a910fe.nq.gz
    ├── 6e88a28f051c6451ae257b2505ed896fec37fb98.nq.gz
    ├── 6f2541032ba4eadf34c6aff049852679d33b91e1.nq.gz
    ├── 6f408e2e127fd233fa4006273f98d1fabd33575d.nq.gz
    ├── 6f472d3c464a7d09f9f7109ed8c4d7ebc8484640.nq.gz
    ├── 6f9ca78ce000271becbc42e43a525aec8ca0bf23.nq.gz
    ├── 707b7090961009e1f3e2f986c3e65678ba12f370.nq.gz
    ├── 7080f792718f896ff121935ef4b057fa8d7247e1.nq.gz
    ├── 70ac56eb54dfd9ed83da488b3c997e0e77f1184a.nq.gz
    ├── 70c5df2806680ac6c8f1cdf8981b39ce9e090d1f.nq.gz
    ├── 70f4e058d907075fd1e60d246f855fd9326e8a88.nq.gz
    ├── 710b2997af4107f49da168394a84ee648c9060e5.nq.gz
    ├── 7162a1034aaa4fb06be628e1b176c1d4caf5e95d.nq.gz
    ├── 72218533d20cfa2a6abbeee8a6205781af34143a.nq.gz
    ├── 72720423bbaea91a3d142a36a808b1788f2d7380.nq.gz
    ├── 7361ecb84832166f9dc606789db56fe69498fab8.nq.gz
    ├── 73c80136c7abae4805d4df5b29ae5d2f6f183068.nq.gz
    ├── 740b0b084573a4b7a4178f4243fc7f637a287a61.nq.gz
    ├── 740fc7bea9fcaeef94a77118a1c6faaf06dd8540.nq.gz
    ├── 7429494817995a17204c23082b8859591ae12e15.nq.gz
    ├── 749be216d4dd821e51d4b529afef844d957b0d99.nq.gz
    └── 74fe0937b85ddbebe35a2be8ed59fe96ad98ed3b.nq.gz

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

[langchain-ai/open-swe](https://github.com/langchain-ai/open-swe)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
