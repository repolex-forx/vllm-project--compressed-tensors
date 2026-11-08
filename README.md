# Repolex Knowledge Graph of vllm-project/compressed-tensors

RDF knowledge graph data for [vllm-project/compressed-tensors](https://github.com/vllm-project/compressed-tensors), parsed by [repolex](https://repolex.ai).

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
rlex download vllm-project/compressed-tensors
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11489fea6e835606bbeeff8b72d43364404c4f41
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 11489fea6e835606bbeeff8b72d43364404c4f41
│           └── chunk-001.nq.gz
└── blob
    ├── 00d8f827bbe8295eff1ebbabd1e6833fdb20fd82.nq.gz
    ├── 026dca77f234c7d5aa9c03fb14076620b6d0ef03.nq.gz
    ├── 03b4865c5a080d720f4957ea0fc72c91768d67a5.nq.gz
    ├── 03b9c95f2d6bc3b10215b34aedf10f1aa000dded.nq.gz
    ├── 0548a49b1d1c3a874c7bedf3558b5a5d07389eed.nq.gz
    ├── 05d2269ef3ce07bf6b29cfacab052b177f1a4a75.nq.gz
    ├── 05d3bffb6c1dcc48f092c12fc9e1ddd2d946f2dd.nq.gz
    ├── 05ed609dd9c2c9379560f0076f72320969437a90.nq.gz
    ├── 0a45a3a59927b8a0b72928792b2ad7a6405400c0.nq.gz
    ├── 0ab5d5f4b4f80d46a9b8bd95609d584c02966cf8.nq.gz
    ├── 0cb507c9331c361896ea9a8f30eb6a7877ee1311.nq.gz
    ├── 107656de29566f6d39926aac80217565b7cde86c.nq.gz
    ├── 129c15e5f6113bd8a7c9085a430332febb710649.nq.gz
    ├── 1459f84405d0b02a8e141c47509dcfaf547289bb.nq.gz
    ├── 15f25870f0be9e0b104342fc58744f96932006a9.nq.gz
    ├── 16fd30712bde4a45cd5f418530209de70aa3089b.nq.gz
    ├── 177d20e8271f188117ca7c477f23d8cbb32486aa.nq.gz
    ├── 1850c48d08abbda377da7f5adeba9ab273d3b61b.nq.gz
    ├── 197bd9ab9bb238e5b499096943d3c00e6ba8939c.nq.gz
    ├── 19ace801006ce742a1371f5dcaf90bcc82d171f8.nq.gz
    ├── 1d53aadd616aa0b0c9a93ffe1305258ab49ff6a2.nq.gz
    ├── 1dd5d55f89528bc0668aee6bbb719c00d6fb584b.nq.gz
    ├── 1e7f59ef465edc946fa2c1389945fd5f77856e07.nq.gz
    ├── 1e9a056bcf04d6cb82eb51f341cd83b60ced9cf5.nq.gz
    ├── 1f5430662ceba3e9275e8aae4811bb07ef474f79.nq.gz
    ├── 2063be592a423bd15c6dedf2ed6eb89b29e9e328.nq.gz
    ├── 208f01a7cb5ee04c88d276fec2082cd4e830884b.nq.gz
    ├── 20a1b492a6ccaf423408af791b878ba4cffef7eb.nq.gz
    ├── 224c8230ab0b44e8e79596654dc0acda11c47b2b.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 28f2a760d00503b3966a7e27eeffb5998dba8e46.nq.gz
    ├── 293bc3896eaff35821f5a0640854c76ea68af6df.nq.gz
    ├── 2978aaca79fca3fd541e7f85c2ba0b7b0afc8b80.nq.gz
    ├── 2a00df00621d3cd7ea9a4338e8df0388bcc1bb18.nq.gz
    ├── 2a8d739145dc716295eeeee1058637f1c9a2724e.nq.gz
    ├── 2b34934c8cc50c07d15b7b0462cf5290db0006cd.nq.gz
    ├── 2c470879b223a2cd7c626ba43b71bde71f27f869.nq.gz
    ├── 2d45e4d5e8014819c1c8c4c63b1dea455e57ac58.nq.gz
    ├── 2f519ed03292ed04d16e8953a2cfcf1a4711817e.nq.gz
    ├── 3040182e1118bb5f231b29b339185b77bf6255d7.nq.gz
    ├── 309401516a783412d88ad1555527b9b4465ceb15.nq.gz
    ├── 3323a87efe1cea61a70e9fd440b4a5600dac37ae.nq.gz
    ├── 337be09f9d0b9abaed1c4ec7d7d35e7f6c878c33.nq.gz
    ├── 33d2255059323e54f85670d0a9572644ad3cb062.nq.gz
    ├── 33d432749757e4c5a439c3ff3d875bb974eac90a.nq.gz
    ├── 3450af57468c1e77906e1511c6cdadbe7a88b98b.nq.gz
    ├── 349e4b3424185a9bf7a07ed5c232e4f7aaf0fe63.nq.gz
    ├── 36aada41965a2ea010f4674a93faae1144905bd6.nq.gz
    ├── 36e6b82dcdde65ddd6523595b937331c9bf3e18c.nq.gz
    ├── 37165973a037485df099388bc8dcbff83c13e21c.nq.gz
    ├── 37e728b02954f1cbf2853c595ec664e7a2ded2e8.nq.gz
    ├── 381f1441fb22866d23e277162b9a8127cb746a52.nq.gz
    ├── 38737b10a79747694b2f6a89fbc5671fd4ab3bfa.nq.gz
    ├── 39e8f4ab4d8cb3a588c9416d5525618f635aa65e.nq.gz
    ├── 3c2a23cb1c53a5ea2de3f55705acf2e50c141320.nq.gz
    ├── 41a539b32d385f34071a05b8419d4c12454094ff.nq.gz
    ├── 432262d721337529df1cff84e8faf2db641aefa3.nq.gz
    ├── 445cdb38a5d659070cf61a64bb36abb855085b2b.nq.gz
    ├── 452f5d515871fb1909f1a00efeb87bd410016333.nq.gz
    ├── 455a340eac9f73b09e3301a8e789a4a88a2a64dd.nq.gz
    ├── 45d0562e398ca771a735cc92032e36ed27bc5e8f.nq.gz
    ├── 4739dcaa2223a571967c867c1c8b04875e0c831f.nq.gz
    ├── 47d78d844521ca69a570db9ccfb9b606af6684b0.nq.gz
    ├── 48c8ae560b21bea69315b7cce086a53fa0bc7712.nq.gz
    ├── 49c47e659de80608b01fbe25d9dac9f405c625a2.nq.gz
    ├── 4a6f6bcf47d840ca4ae8537eece9559cb8cb5ab1.nq.gz
    ├── 4b3d0cfecd5e9d82bc24fc47b54e0e8005d82839.nq.gz
    ├── 4c257d4b5266a9fdb5a25d519447b64f7304d2b8.nq.gz
    ├── 4ce684241cfbb1ae739c47c865d6cf792345c3ee.nq.gz
    ├── 4d521fb32d42e6876bab24cdbf14431ac6fbeaae.nq.gz
    ├── 4e681997f988396b41fccb0438f47764087cf67e.nq.gz
    ├── 4f8387ddea6a08588a9adb2825f481fc17c1d76a.nq.gz
    ├── 4fb8ce210d3ce463c078df407627046053f8cc88.nq.gz
    ├── 5002f9b0305167ef152524a69d5d5e4b76fedd71.nq.gz
    ├── 501d2c3d6d1d914860955a10c199747d573fba09.nq.gz
    ├── 50f3b7ba55e954bca209236d93ffcedd9a6e7ceb.nq.gz
    ├── 5134cf32110254ece466f5dbfbd6cd3116ec9481.nq.gz
    ├── 51412883e2e98f952ad008dc9c5ed90b3f32ba4b.nq.gz
    ├── 51680600acc4812840db3b4fd82554c8a091a7db.nq.gz
    ├── 5273d32aa158d312bde9728013b0f5e1dc36a7ba.nq.gz
    ├── 52dcf4e90f3771f9899bd9a47e28007cb1a3ea02.nq.gz
    ├── 53c2ba65d1239db4cdbee89de534baa9ca7d6a1c.nq.gz
    ├── 54582f8b774664bcee45b1c04c88532b7c718b1a.nq.gz
    ├── 56668bdb188d7952b626ce456060b3fce2767313.nq.gz
    ├── 59358cfde367f5df5e47c62c4d1fb09de99dcdbd.nq.gz
    ├── 597253a9fc523131faeaa27fc2b9b696f80494b0.nq.gz
    ├── 598c548dd4ae2d30fb13bddf6dfcdf59e3032a6f.nq.gz
    ├── 59bb9da32466162183fb1ee0956b915bafec7169.nq.gz
    ├── 59d51396c38690b6ff683acb9b2612ec3546b52e.nq.gz
    ├── 5a4684918bea15d1f72e29ca9ec7c11787a0b2cf.nq.gz
    ├── 5af62f1320271ca8c9bd8986fb3c2df393916f00.nq.gz
    ├── 5c5990e7eac7de244df890ad4067c8733a236a5c.nq.gz
    ├── 5c7b34bbe5616c3facd196f37e71379d4b2d4162.nq.gz
    ├── 5e3eeb888c2cac583737c92e26cc7a235d80b40b.nq.gz
    ├── 5e5f8d2a1fb4a43839db7e91b45dc6e9990eb15b.nq.gz
    ├── 6031b73f4688f2e2baa61d99e6dbeba71718acfa.nq.gz
    ├── 60cb3c784f1b13d7aee9837410d24c6f5f02b893.nq.gz
    ├── 60e937818c2d7768a1b2d93c7b6c6f4ede3a1981.nq.gz
    ├── 61950ee65ee2b71486cd9fd4c34e3835b8fac3d5.nq.gz
    ├── 61f1dc50d8d9d969329690ceaef2b9d85591d2bb.nq.gz
    ├── 62248cf1418210e2b0e5744f0a41937c38c00903.nq.gz
    ├── 62b81428acea070d20baf5ae10eaac0e92ef54d8.nq.gz
    ├── 62ecd169a722ce13bebf6e1bd58609585da45e99.nq.gz
    ├── 63069d8f1ba6fd504d2fe24140e8879ecb990fbf.nq.gz
    ├── 63cd989132e64dd59c576c9178872d4d5abef449.nq.gz
    ├── 63efd0e541f7a3cdbe0e80f39a9cf23ed80c33ff.nq.gz
    ├── 6456ecd8348b5a57cbe384e5d295d4678defc6d5.nq.gz
    ├── 6460a977a0a575e7c97d7c530667372f78d90b8d.nq.gz
    ├── 64871364d0c2cb250a6cd34045d2058d9b27e614.nq.gz
    ├── 65093d858895be11f7990c2bb7670b0969fc876d.nq.gz
    ├── 67e8b6f8b904cdd6e7a615590d9204008f34a36f.nq.gz
    ├── 6946e445eb3ce11202ea595aed93e4cc92388bfd.nq.gz
    ├── 6b2ed9e9dfcf79de95c7fa2750b7b36bcd85c81e.nq.gz
    ├── 6b37d312c47ffb8bca77d2e74c644d6bc5f88a62.nq.gz
    ├── 6be2f5502484864aafa6f6bc03e52c5968263ce1.nq.gz
    ├── 6c581d09f60f05c8c9f06dac28798f5a428ebb7c.nq.gz
    ├── 6d9d15cf8b7726a803207941734f3367d1d3ebe2.nq.gz
    ├── 6ec8f9f821d65f60dbab963de3fd60c1daa0f91e.nq.gz
    ├── 6ee624c59dc98821d4ed94fd24d953f23157b69d.nq.gz
    ├── 6f2a4b764f828c8d041164d630839f635a611cdd.nq.gz
    ├── 6f2ad78666df91956d195a640b712ae4318d6d8c.nq.gz
    ├── 6f9a3bfc4c031b934580becb5aa675585ded9edc.nq.gz
    ├── 7040c9621f0e0adfae55e75448d9cef42f783fe2.nq.gz
    ├── 7155a73a927fbafb91c5b7599706a4fcf709845a.nq.gz
    ├── 739649cb4d3bab1154ae95c8f5639121340abda1.nq.gz
    ├── 743e599adbedccc7f4d4ad77efd4d66308554d44.nq.gz
    ├── 771705ce806e4801ba04c64450c98f45116369b1.nq.gz
    ├── 776fdacd6490f8e016339c0448e20a3f635696e0.nq.gz
    ├── 7863add140884492006f9753c4886abb5fe4b116.nq.gz
    ├── 789b8b562dd0770e15abf680f1ce2e792c8dd5b0.nq.gz
    ├── 7908bcd0841b381bba0d73072e2d36e173d89b92.nq.gz
    ├── 7921c0fd75326453d73b43d0b8d71538d346d0c7.nq.gz
    ├── 79d72fcbb86ebe98f41a6336d407a6ed11a19db6.nq.gz
    ├── 7a500416e8401d188b437127344d1197f6a77552.nq.gz
    ├── 7b902b0f049174f05f08263bc9760dda2bc0e101.nq.gz
    ├── 7d56e54b1ef66c3256e7c534de372cd5b05b98fa.nq.gz
    ├── 7dfa60e6ae6d7ed314bee0dd678d176b9c4887e5.nq.gz
    ├── 7f9f1b872422fb16c88eab1c324478cdf841ef23.nq.gz
    ├── 821792647a015b92417afe0fb8343194e6922bdf.nq.gz
    ├── 82fda17555243e120eca62d1d6d73cfcf28c16f9.nq.gz
    ├── 839c5de0f51fb168e05b6c032585b710e2a72a5f.nq.gz
    ├── 855c60eeb95f7ae9c819c0292a4f5ffdc604e5ea.nq.gz
    ├── 85b68741a4530c1074934c63fca509fcad77e5e4.nq.gz
    ├── 85d06694f6a335297062021432cbce5fcd1ed60b.nq.gz
    ├── 863ac4fc20f9b7438754da399cad6cc79166470c.nq.gz
    ├── 8644795e2589a55cb997c74bc49de998d3da0b33.nq.gz
    ├── 8786b7d644df9ff37756cf328c7781b842e42ac0.nq.gz
    ├── 87c6dd0f95f000c47ae88c2db682f5e61d52d302.nq.gz
    ├── 890dfd6901e2b088ab3fe5f33786f3f2dfb9223a.nq.gz
    ├── 892794718b783bbe977ed0277312882cbd1b758b.nq.gz
    ├── 8a440d11a7352fbe9fea0f6386b38a9f58e64ff0.nq.gz
    ├── 8b88563ff5f5bc755d5998d6014edf236a4f4cdd.nq.gz
    ├── 8beedffe475bc8bbab513ed25c33c4f6b5b81c21.nq.gz
    ├── 8de2f14f4ad8f73dbff8c067615d3d8c32b040c9.nq.gz
    ├── 8eb4e1d9c49a2aa8c71ea85dfab835dffec2e5d4.nq.gz
    ├── 90c7aa96e1473da5b76922e6d4317fad1a7679b0.nq.gz
    ├── 90f1a4406dcf829f0b0ae33c064a4aab48b53e9b.nq.gz
    ├── 920230cd906b12f8d27ee0048490961af7d2c3ab.nq.gz
    ├── 94ab40a3f57368a773698df51010a050ee312423.nq.gz
    ├── 94f9fad80e9654b3fbaa13c02db0f501494bad81.nq.gz
    ├── 9617b91a382a6b87e6c3f4a2501e2b2b5fbeec41.nq.gz
    ├── 9624e008623e86678a2da7f27000106e03055257.nq.gz
    ├── 966d2ef23cc2b3edf65fc71d304414eb73f315e1.nq.gz
    ├── 9a6ee08ee4d9842fe69e021d85dda6f4611c4879.nq.gz
    ├── 9af581d6bb4282f31458036cccf5ee0eba835dfb.nq.gz
    ├── 9b96896af7057c46d34270fe39aa728ae56cce07.nq.gz
    ├── 9c720b0760b49fbe84c981b1b49a0aed9f136619.nq.gz
    ├── 9d02bf95ebcd8c46dca7192a9e9a69a10f933849.nq.gz
    ├── 9dff932572cb429a0d1b14c943ad0136041477bc.nq.gz
    ├── 9e3bb1227e2b05d5b68b260a4842554efceed2e6.nq.gz
    ├── 9fc60d03f88bb8e15d4048f7c99c86ef8b375cd6.nq.gz
    ├── a1b69b9fda9153cb8c04dde58dd1d4cd7bd44a87.nq.gz
    ├── a2025c491a0db9c7fdccb77040a844e8032d7a58.nq.gz
    ├── a6048efe0e91d311a296051ede34115a3a50eb68.nq.gz
    ├── a623c2b4c9683db5ef2f5a6e59e626eec6dcb5e9.nq.gz
    ├── a8c08a086b8bb0be0351a47b7fae86136a09c829.nq.gz
    ├── a951af5f7a56e0ecb75bf36136a9cb7ee90aa037.nq.gz
    ├── a9b7f5166940c4397cea8839be9d481c2a834e0c.nq.gz
    ├── aa10e5b6628f4d330fa52e7c3169d0f5c6a8fa34.nq.gz
    ├── aab583362fba65051ec2d18fa74109b952226b26.nq.gz
    ├── aac661a164eb2a0655cb41636e4aa45a84f748d1.nq.gz
    ├── aae98784754e76bd1feeeabe2d12cfcc9dca876b.nq.gz
    ├── ab63037dae43da787123157ea07005085bd256f3.nq.gz
    ├── abbb427bcac23c6e915284a6c7ca427584ad35a3.nq.gz
    ├── abe14f988bc149153f350ac70d111344312c4f0f.nq.gz
    ├── ad00969c00e4bee011ddfc42ce465242bd5c40e9.nq.gz
    ├── ad57127656a441d046b1cf0e2aeba37af5e84cf3.nq.gz
    ├── ae0e5c8fe1d66797b9faff00fb2f23b071ee23fa.nq.gz
    ├── b0615a1817c53e22ebacf2a903af23d739f8ca51.nq.gz
    ├── b0e6b3e11b8a3542f49bd589d57180e9658f7cd1.nq.gz
    ├── b102c78d40a06496e51b443d6cf7984e8599b9ed.nq.gz
    ├── b2f3b1c09020f0f84e9ab0520ea7937b5ced6461.nq.gz
    ├── b5b4a499d66f9e1ed1abc7c6a8094b6972d271e8.nq.gz
    ├── b5fb9edf8dc7c7393a6ae4d6e7bf6464ea3fe51f.nq.gz
    ├── b715e7c2a10f2c40524532e883cf42ffe89b3363.nq.gz
    ├── b7b6cf80ab7e7ae2a1b1ff9a9292e59056fac27e.nq.gz
    ├── b826e645bc2e4ebc57533ddeb20b4cb6ce822747.nq.gz
    └── b83dd234b8bcc2f158d56d3dbbb82abe1ce6a5fe.nq.gz

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

[vllm-project/compressed-tensors](https://github.com/vllm-project/compressed-tensors)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
