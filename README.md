# Repolex Knowledge Graph of mlfoundations/open_clip

RDF knowledge graph data for [mlfoundations/open_clip](https://github.com/mlfoundations/open_clip), parsed by [repolex](https://repolex.ai).

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
rlex download mlfoundations/open_clip
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7067b350050dc409bfdfdbb3f0cc6c9a1651c000
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7067b350050dc409bfdfdbb3f0cc6c9a1651c000
│           └── chunk-001.nq.gz
└── blob
    ├── 0199d9212e6f0b9ba9cab3b82c705cdc4f9155c4.nq.gz
    ├── 01fabb29db2bcbd9513e903064d61e3e1974d580.nq.gz
    ├── 029c0cc0d459e8cc2d43cad0a9ed1c19228766cd.nq.gz
    ├── 036fbfabb3805a83dbfe276e233936425666a3c7.nq.gz
    ├── 0404ee15f35ed31f1fcdeac150b6d1f187ddfc3c.nq.gz
    ├── 04a3a3fd575f8fc6139f693d23bec7195651e592.nq.gz
    ├── 04b2e62d60d031b1a5762e365e070e52b6fea7b1.nq.gz
    ├── 04dc47d980cceabfb5cb21efff4ba9a29e160564.nq.gz
    ├── 04fe908aa051dba3b52d62d975ac26b73674c360.nq.gz
    ├── 057a26187e5aa0923b14d44e15aba607eb6c948b.nq.gz
    ├── 061f8bfe35b595cea6a4ed551444d3b1cad6284b.nq.gz
    ├── 06376949258e49aa8d09bd684efc178896f2bbba.nq.gz
    ├── 0641c1088828542b71dc1b58783484b7ac2cb4f4.nq.gz
    ├── 071c71561ef223bbd40600edeb17c24e35c56b9c.nq.gz
    ├── 0761b6ced773168863d58b99ffe00ce230aad4e8.nq.gz
    ├── 07c8e28eb06fa1813ba932fe4eec668262d1c47f.nq.gz
    ├── 0840a63439046126dff9a7b717da8496c51da060.nq.gz
    ├── 08de98a4b7fb9e4d3017a00aff4e1ddf25c0fc69.nq.gz
    ├── 09766e6aeac208bc62c592413351146af6ece9ba.nq.gz
    ├── 09d001527c62b5e836d9f7c5d08734d25a0ba33e.nq.gz
    ├── 0a07c4e16abaa4015ecc5f82ec845de16e1f9d88.nq.gz
    ├── 0ab8007709c0177675f88687a45dc6933ae9916b.nq.gz
    ├── 0ac3485762b5117597839b3274ed85340a2c76c2.nq.gz
    ├── 0b699dd23309a80606c24321d63184769a28ef99.nq.gz
    ├── 0b76fd5f8d157717791fc207006e35a4d58a3a77.nq.gz
    ├── 0c14fa3aab0cae0fe7a9c808c17e59bccabf1cec.nq.gz
    ├── 0dc4424894ab0394b3b2ea6469765eda3667cea8.nq.gz
    ├── 0dfed19dd526bdeb5cc3ec98304161c402e60897.nq.gz
    ├── 0e76ffb93eea182e3df4cdc22ef032c1f3ba06f0.nq.gz
    ├── 0f42941775f41866a035673f01ba5858120ea63b.nq.gz
    ├── 1072ddd3a6065bbf88346c2c1d6ce7681363fab8.nq.gz
    ├── 116c30e7301a5b7c3869c7adf3ecf6fc82436c17.nq.gz
    ├── 1177eeca43f62e9a9e973ccb6ea909ec90a0b147.nq.gz
    ├── 1278d8393686b9818c7635c2ec3e97a4ae5e57e9.nq.gz
    ├── 13b57e4a90e78df79a7a235cf5b09514bc2cca1e.nq.gz
    ├── 1473c6c2bc2f30eb97ee6b90d540a29a3cd20458.nq.gz
    ├── 155be1ac75e307ad6578124b1280692b25f5c651.nq.gz
    ├── 17cb8bac1354431e1f871425c2d1899322b7aeea.nq.gz
    ├── 187de9e3847ae7550b614dd1db916ca95eae8712.nq.gz
    ├── 190cb37174df03364d88dd710277f67ae5595eaf.nq.gz
    ├── 19510ec811eb9cdf059ea90f98e70697a6140627.nq.gz
    ├── 1a317aad8e02d9c26d2decc7cc49a18dfdf9e0d8.nq.gz
    ├── 1b80f82b8dc91910c81bb70869b22075bcddf319.nq.gz
    ├── 1c8cdfab7cc31d29fda3237eab1b887d5c87d0c3.nq.gz
    ├── 1ca890bf73f923a3640a7a133ccedbf202cf5016.nq.gz
    ├── 1d8504e59658803f3093e5b05de45f30a09b8185.nq.gz
    ├── 1d8ecb8f56f8d38fc0713297547289f46a302969.nq.gz
    ├── 1dae7fa5a897768f1eae0e3c034d55e6bba839f8.nq.gz
    ├── 1fb6cd24a681500d94284b29f645595ca2727e2a.nq.gz
    ├── 2262deaefa82792d35d73c0d7c8e620525092581.nq.gz
    ├── 22a1a24618ed339cb429dcce0d6969299fb49cac.nq.gz
    ├── 23a55a681c346d1a315d8a163c1cb6ad495e6a91.nq.gz
    ├── 23c8032e2ff7c439c54fd5751f42e426adfd3d66.nq.gz
    ├── 23e3a36ea688843ef54c9c887b3911c4110663c5.nq.gz
    ├── 2497712413300dc269247ef100e321a5b63f5de6.nq.gz
    ├── 2642427dbe2118932c8170e5b75c78e5539618cc.nq.gz
    ├── 27c8627c1d2ce5f834591596db32dde739cfde76.nq.gz
    ├── 2911dd7eca75f1cea70f4907140b9fff649a19a8.nq.gz
    ├── 29befb370c6768568cfb2391c86f98f751e4ae89.nq.gz
    ├── 2a8eda62138ad54ebbcd18e826b49337f840109a.nq.gz
    ├── 2a909965932eef994177c829fefc2bdc1c219b3f.nq.gz
    ├── 2ac021571aad2ed1527cdb51f610f393d71b7ce0.nq.gz
    ├── 2b2cf11149915a1f648ccd8fbd97136852b27ce1.nq.gz
    ├── 2bb07f3c082fd88c4e86131b272163aaacfaef9e.nq.gz
    ├── 2cf0a8e2268a2e824352a56cd188f797a9ee1f55.nq.gz
    ├── 2cfba479a2e8f3737e71ce240732bf3bc743d8b7.nq.gz
    ├── 2f09c857de9a4c01ae51297a7e2451984879f9de.nq.gz
    ├── 30115426d8b811c4cc91e9779b36b91ba9f66948.nq.gz
    ├── 3070f70e7ec62308fc1aa373f123bc57c2c21451.nq.gz
    ├── 3161e1a2c9a839161e652a4d729c2cdc971161db.nq.gz
    ├── 329452ddd172ba70aa713818b4e4001653840ba8.nq.gz
    ├── 32f248ba7370117fb06107229b72e819a7302c24.nq.gz
    ├── 33aa884d54fee0076c33676831e49d5e1ffcb8f2.nq.gz
    ├── 3592c2a5cd21aae8d2544931773cf7603f67ea28.nq.gz
    ├── 36682e6caf51b715392c2c2fed48f17c86aff53b.nq.gz
    ├── 36715e4d398fb5d43b6fe4cc70b48c136c547a36.nq.gz
    ├── 375fa9e12f1629ef049a715d43ba2a8b1822ff1c.nq.gz
    ├── 377085afaa1bb8a84083463b805b515468e6ca1d.nq.gz
    ├── 395eea77ec3907c0611531aba63459b193e67b9c.nq.gz
    ├── 398644e633a76ea7f15ed4fdaaa9fdf284425865.nq.gz
    ├── 39b2a6746dc9fc16a710b535a97a46a917b211dd.nq.gz
    ├── 3ad81a3cdfa030980a80feea7441d6293e7d2a6a.nq.gz
    ├── 3b1a24fccc7019d3e3bdff6d96ea92af947c78a9.nq.gz
    ├── 3b53034a72944fefb87d504433a1ad14c238518b.nq.gz
    ├── 3b5fc808391ccc0e22d45fa461df20b2d1455abb.nq.gz
    ├── 3ba669f1e6ac113fb7d31d16f1fc5245fec2f10b.nq.gz
    ├── 3d14b710906775c89143b9f227bc38414ee9ad11.nq.gz
    ├── 3d5ca4ca2338540f06852df5ff35ea6277e64555.nq.gz
    ├── 3e3a7e934e7f02e41f4829996c4950e05f015a74.nq.gz
    ├── 3f8a2329ac62c053c13f7042144b740ffa0f9c8c.nq.gz
    ├── 3f92357287e1f6600da1e7f391cb6370d7f66de4.nq.gz
    ├── 41040726cdffef31dc26043a1cbeafe664c5b334.nq.gz
    ├── 41f22f65bb002c320111790e0cd0f2425a575df7.nq.gz
    ├── 422bd042c8ad53f2a53d5b0921978e8a008f20bb.nq.gz
    ├── 42d53b651e2bb86f8cb1725ca617b42eaa505a21.nq.gz
    ├── 434398b1fa78ccfe940130787bb7ebf6e442e884.nq.gz
    ├── 437636a18d415965bd7a459a7d96860f0375be46.nq.gz
    ├── 4562c8adbfaa3b309ed91a760ab80802881aea6c.nq.gz
    ├── 4593ba939ca8b7eb1625d0385cfdb63e4ec7d497.nq.gz
    ├── 4605a8468b81fecddfc27a5e9c3fd65b09728a87.nq.gz
    ├── 490a5fbf2cf9e65943535b2e5c5a710918fe1b29.nq.gz
    ├── 49760e69fff83b023758cab3d23add58d4b9b734.nq.gz
    ├── 4a88cff091d5d6311f2c0ab35e3294f630d61d29.nq.gz
    ├── 4b48a526322de8c23912e258019c1737fb9336c8.nq.gz
    ├── 4b6648e25092b151a9095e0a66956c7ebf835b16.nq.gz
    ├── 4c14f76fd59b1dba6ec46ee05f6e90f092b109d7.nq.gz
    ├── 4c527f581230938d7b39baf36b6bd749b0e7f169.nq.gz
    ├── 4e39b1b46fa2d2b8616c013bf8f972e2047a31c7.nq.gz
    ├── 4e663092f58794d144a8a0d402f4e782faab910a.nq.gz
    ├── 4f718642821035d9776d1e006817d65ede074366.nq.gz
    ├── 50f82425da4c0780faf7962a1b1b3507c2e0d643.nq.gz
    ├── 5204dab4212e57e4b33076b9225c87466581ed44.nq.gz
    ├── 5210c144618a5d9e29f78e4e0e50af0cf9546651.nq.gz
    ├── 536d1d05b975a68bf7f3393b12dce1a00029054c.nq.gz
    ├── 54c3df36a6f56ace0b12ada24c13058de96feed8.nq.gz
    ├── 5529612c26cb2c70ccfb98ccf99cd51aaf61a0a7.nq.gz
    ├── 564eb78a49c8ff31cac047277b9344bbe85fef40.nq.gz
    ├── 572002a29877d1e7528baecb65dde3bbea995177.nq.gz
    ├── 57265b33f7cfd21b07741744d50cbf30208017d1.nq.gz
    ├── 588485455fdf8193ec16474450b94e31c91ea93c.nq.gz
    ├── 58e2e54f15cf94c5b198680bcf487031bdc783f4.nq.gz
    ├── 5a1c445b71d25084eb8b76d82d7ec2c87769f128.nq.gz
    ├── 5ba8f7abb68e5a798d38f976a828c63f74b94ae8.nq.gz
    ├── 5bbd12bcd01f64d6d0a0aa8316b129327a0d169a.nq.gz
    ├── 5bdfc2451286e448b98c45392de6b2cc03292ca0.nq.gz
    ├── 5bfbf6c09daad743dbf9a98d303c0402e4099a27.nq.gz
    ├── 5c8082b34df2318dd25a4ec8346b3f9a888f38de.nq.gz
    ├── 5d76452215f8421e2cfe2b4e9b8ef73174d02bd1.nq.gz
    ├── 5d82e18dc692adb0b4dcbf1ee077688505ae65dc.nq.gz
    ├── 5dc1e09baccef2b15055c1bffeb9903e760101c6.nq.gz
    ├── 5e0bc2267662fb80b01c60d66df722d4b23c07cd.nq.gz
    ├── 5e10a3f5a63d376f39c1de3f93827e950363f4d1.nq.gz
    ├── 5f655ee211dd614a9eaaf57990a247ef22b87013.nq.gz
    ├── 601b0d2ab131f9fdfb22741098c241dae2799338.nq.gz
    ├── 605cefc3934e0b86d12630733da40f6846c06d08.nq.gz
    ├── 60a4df589b9e9ed269807204ec9788e613026382.nq.gz
    ├── 61df92ee3c62880a863b34307eb61517de286940.nq.gz
    ├── 628e8af01057a320b567a83418532afa7a5f366f.nq.gz
    ├── 62d30246a0fff96ab81eec2cb23b980583ef030e.nq.gz
    ├── 6340918ed5b7c56fdbbfb84e2bcb26ccf662c8b5.nq.gz
    ├── 63aa8cebef0f19d5276e99b104380b01f0a8c58e.nq.gz
    ├── 63c582d75766962be3e6fb23ba4b16c716bb93cd.nq.gz
    ├── 65bd8ed48d6672e660ae2869e4ed3456e32b5b8d.nq.gz
    ├── 65d21268e9478abf002a2c63b83b295efa9d7c9e.nq.gz
    ├── 660afee224f949cc0cc01a928dd3b8c0c498166e.nq.gz
    ├── 66990842e98241bcc269f06e21ed78c9f94c235d.nq.gz
    ├── 66b92b2ab2bf047cb47c14e354798eeb1255b4c2.nq.gz
    ├── 66ebc16aaab350091f29c8330c15ead59c228609.nq.gz
    ├── 672fea6e2f253665ed6b2548cc2cef792409360f.nq.gz
    ├── 67c7674a91127861168c6ec15d8750bd19d85a6e.nq.gz
    ├── 68465befbe72ab02dd31248fd322fd8d1950d2d0.nq.gz
    ├── 6849433cb3cb37305526a49be4d2e18cde452d54.nq.gz
    ├── 68f672f0cc3c3564f4c7ec6e25255034e5af45cb.nq.gz
    ├── 699cdb1b16855582606551e4196b24aba2ffd871.nq.gz
    ├── 69d8369c173a0f2daaafa04b7b75f7eaa34e1967.nq.gz
    ├── 6bc14fabc30a9e11cbc9ca53d353f2d1216f9d2c.nq.gz
    ├── 6bc8caa39b01dea7ee2f9e771ef893e4523d5bb5.nq.gz
    ├── 6cc4e13591c8cededfa12d311b3a77292ba38f8e.nq.gz
    ├── 6cef625a89daf4431f1c9f72e10bc9640eef2ba8.nq.gz
    ├── 6da9d7e219b8e3ed233909055308f994187ebae7.nq.gz
    ├── 6e43cbebf2c1fbaec2e1c11637b01253c03b3021.nq.gz
    ├── 6e4e0434a5bf7e3303ef8008e1a27f6468a7ab57.nq.gz
    ├── 6e9cf21feac73fcbc9c82da9fd42b81bbf944bf4.nq.gz
    ├── 6eab86277664bd64643aefef18218a7ef027aea8.nq.gz
    ├── 6efec36c9b8462e360725337e5f560bf9cd4e29f.nq.gz
    ├── 7123850c9038d12b981ea8acbf1f9e2d54a314bd.nq.gz
    ├── 71d6ac95b98f655a9696962cbb74edf5abdf2cd3.nq.gz
    ├── 726d609dcaf5a3ac4be68cae84f0d88a63a43cb0.nq.gz
    ├── 72b68e3387049c1b95f032172ebbd54eeedeb08d.nq.gz
    ├── 72cb19ee17f94e9172b6743d9e16993f02ab452a.nq.gz
    ├── 72d04a73316e513135581f563c74f8cb69dac1c9.nq.gz
    ├── 72ffbe2bcd28488cc847edc7f901bd1f2b117033.nq.gz
    ├── 73c08b7dc028c024770f2feacf5a05b8ce24ca40.nq.gz
    ├── 73f46a71e664fce987218b8eb48903e7bd895f41.nq.gz
    ├── 75ba7675c643cd482f06886e58ded6fb934233fc.nq.gz
    ├── 772efaf1e5a1eefa75a555aae5958c9bba680466.nq.gz
    ├── 775621409becce43a1b1aa5bd61cdaf93c578733.nq.gz
    ├── 784bd4eafc0f67045a6b49d5c83763e7ebe35930.nq.gz
    ├── 786ac05f241d3cceb9b6dfdd62203a923a61e78a.nq.gz
    ├── 7a28797a7e1487af986540872447a68da0dd69b2.nq.gz
    ├── 7a6d6e8009159ebb69c8eb1de1d93372ceb7e587.nq.gz
    ├── 7ab6cb301ab95c6b5627a5ab63db854bbe941f41.nq.gz
    ├── 7b5088a527f720063f044eb928eee315f63b2fc0.nq.gz
    ├── 7b80ab1db63a4a635d7d34a7e684158a91c2b462.nq.gz
    ├── 7d17f2f65484f04500ff9f91c1a837597effa1c6.nq.gz
    ├── 7dbd84867445bb519a03bcbca1437623cdb6e2e2.nq.gz
    ├── 7ddf3152235c6b716ac08eb65d1213cf55b4d890.nq.gz
    ├── 7df0338844bfff4d30f3ca08711311f645dda866.nq.gz
    ├── 7e69bc413dd77729061b2e964640d5c98733e867.nq.gz
    ├── 7e79088b8004ca60c25653898601003ee3099c4a.nq.gz
    ├── 7e7eb520a6a0096e5602d509ecd6186e278f4725.nq.gz
    ├── 7eaa952be04bfc19afc3866eb7d2497923ed84ca.nq.gz
    ├── 7ebd8ace519ad281361ddd529c025c208735946a.nq.gz
    ├── 802e5f69fbcab2721f41c2fb88055e2799b362e4.nq.gz
    ├── 80780c5eac6f3f9e7b09bc891abb63599e4464f3.nq.gz
    ├── 80a2597d8f7d5d500df2aacbded9507196dad6da.nq.gz
    ├── 811787d4668d0f681f0edcf72ce4a901a4b12754.nq.gz
    └── 82565f4a2fb5a0e0ea887446cbfd475598fae5e9.nq.gz

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

[mlfoundations/open_clip](https://github.com/mlfoundations/open_clip)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
