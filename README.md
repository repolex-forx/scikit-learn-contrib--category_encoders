# Repolex Knowledge Graph of scikit-learn-contrib/category_encoders

RDF knowledge graph data for [scikit-learn-contrib/category_encoders](https://github.com/scikit-learn-contrib/category_encoders), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/category_encoders
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fafdccced2c5154478a5f10cd761e138daa56d21
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fafdccced2c5154478a5f10cd761e138daa56d21
│           └── chunk-001.nq.gz
└── blob
    ├── 00be3cc2b40bdee3cec0865028842505df694da3.nq.gz
    ├── 0123adb6f2737f3b5569cf14d6cb5dc9cd21b3b3.nq.gz
    ├── 01a641ec0472d4ea3dd1a9e30a03bf53a960d57c.nq.gz
    ├── 023e8660bb141d9186a9bdf7bf8a890a4f3d7803.nq.gz
    ├── 025e480fd651ea84b5d9d1dfb9ee50f449a24af8.nq.gz
    ├── 029c1e8f4f9724a75528eb36d58e89e157dc3e31.nq.gz
    ├── 02c060e6548cc4a0e594652a1c711ae781c384a4.nq.gz
    ├── 02e7c90626d5fa2073f2ddab3bbe89fdf7540897.nq.gz
    ├── 02ed588102413147868876fbdf752b52d662cf07.nq.gz
    ├── 030cee5bc19d262d6dd2e6c0f68145b97fbd1c4e.nq.gz
    ├── 0337f4702a13c8fc99790d624e09d4c2c1e08bbb.nq.gz
    ├── 03bddc4651d4d211911ba9d4ba7ba25aff2d3c0c.nq.gz
    ├── 042877e54de019ab6c832b906b5772a96f54a5b2.nq.gz
    ├── 048c1ddb2e0e9c6f11fe3fd4dea0e1522b500bfa.nq.gz
    ├── 05c77eb137fbdbb08965d2b8704a3ccfdec9d4bf.nq.gz
    ├── 064045dd00e4efb7f210269754d7fc77984b9666.nq.gz
    ├── 068402e1e041b2eff318116965c5aeb897ee4a7b.nq.gz
    ├── 06da73dcb03d6ec5c7b344d0771c9c7b2fc58d8c.nq.gz
    ├── 0722cc333970cb28f234112fecb23d5ccd864b4b.nq.gz
    ├── 074e355caaa41833d23126afbe24238f0b12b04c.nq.gz
    ├── 077817bcb65d3a40725e6c2f779336907774a4f5.nq.gz
    ├── 077b78203b1331cb75e6ffa88ceabc47b285720d.nq.gz
    ├── 0789a607835ca3c974cbfb2c01d4dae52724adcf.nq.gz
    ├── 07dceb574287f43ac624dd3b3209d778ad933735.nq.gz
    ├── 083408ce1ee0a8fe2a1eaf0897f15a066c5151d0.nq.gz
    ├── 084666944f705a48367778a7a3f079bf6ca6fe86.nq.gz
    ├── 0860b6b18341c801c7c45940959edef472f8cd27.nq.gz
    ├── 0882e40ff96ff9b28157fd29331642f79c0216ce.nq.gz
    ├── 08f21f5c965616a4551b40f073049f3183cca517.nq.gz
    ├── 09b585e00e7e1c2180e170a6578c6e3b77853637.nq.gz
    ├── 0acaacddc7ba5a11d68a2441dbbd4cc145f57a5a.nq.gz
    ├── 0b2447fbd67c28db63bda6cf3b00f70231e79644.nq.gz
    ├── 0bf6c6615d8fb3a7d6f57ccaf4065d135d9fa13c.nq.gz
    ├── 0cbb5e339f76b0c7c7700f9f89ba3fd802d891fc.nq.gz
    ├── 0d1aa7177d857d8b7cd0cfef56b9c7c9acefaaec.nq.gz
    ├── 0d98858611c8f0b7bc895d0dda5d0dc5a661c2bc.nq.gz
    ├── 0e9e3d0c8b55c9b86a8e4fac84d843e1dc2411c9.nq.gz
    ├── 0edb12b8acdb5ad12d6c5529e7c7ce5c8bb29056.nq.gz
    ├── 0f1e739137abe802d1780c3fa079fe702a18c759.nq.gz
    ├── 0f6a49a6cc0465042d15dd6b51a2a3707975fc12.nq.gz
    ├── 10beb74a3ca54e9cacc66588fa3a2c990187e8de.nq.gz
    ├── 118c546414961bd9b417303c7faa9ca8f85a1f0c.nq.gz
    ├── 1253c6105a083d42ea247083200558c40f5703e9.nq.gz
    ├── 12e74f392cf55a168a1c2598d5e651593c9e7b93.nq.gz
    ├── 12f26bef733cc1f54fae4b124821d66bf25feaa6.nq.gz
    ├── 130c0d4c5f051e96214f6555aa6a4f991d1257ec.nq.gz
    ├── 13bcfc404330f437da556d6c615eb71ae988eaf5.nq.gz
    ├── 1519be4dae9d0cdd30dff49f058527abf6d77a71.nq.gz
    ├── 1591a863753ed05e74f535b6f08aecec1f0da54c.nq.gz
    ├── 15b8244372daa15dafed418920e4c73b6eda75f4.nq.gz
    ├── 15bc16e943c77d537ffc6e635c008423b24b044a.nq.gz
    ├── 1733bb0a7e95ce2519ed598de58e1d4997d15018.nq.gz
    ├── 184334d699f7f808426ad970bfdf2409badebd86.nq.gz
    ├── 18722f6c6723652807444ab678ff8f793096666a.nq.gz
    ├── 188310eb51aa5fddc661e814ee1d21ede1b19779.nq.gz
    ├── 192b17084022659efd74c9cde494cf5b708ac89c.nq.gz
    ├── 19a1d4b753f1270c42931ec7c15a7a61720d78d5.nq.gz
    ├── 19def4e80e10968900b576c6a859dfaa2dc4f254.nq.gz
    ├── 1af105be5a487619bcd94dfd4f6c99249227083f.nq.gz
    ├── 1b31954eef0de7cd9211fd76cb8829ce9244bad7.nq.gz
    ├── 1b5c745808e7c4fc420fae78c2cdf2d0a566e49d.nq.gz
    ├── 1c16046d4603fdad97973b3abde4c2e4fa7b822f.nq.gz
    ├── 1c1db43c1e47cf8f2d476e010d23fd45cad93d2b.nq.gz
    ├── 1cb88f11acb0cb6d1a8595517fdf42955abf07fd.nq.gz
    ├── 1cba055f81371fef6fe4dcaae8e1995f708693e0.nq.gz
    ├── 1cedabe28e47122a52977b3ef91153898844a0d1.nq.gz
    ├── 1cfff21e65502266cd6d793f12a0f62ec122c076.nq.gz
    ├── 1dea2d06d012a215543034964d6a186d0a35ea7b.nq.gz
    ├── 1e846867dd06a95ed70240d6cc32254a9dface3d.nq.gz
    ├── 1eab655d13315b7c9f363ea89a30631f8111634c.nq.gz
    ├── 1ec472e8e94e2e60e85eb1a985871a251d2b01fc.nq.gz
    ├── 1ede8c21448e01ea594da39c7ecfcf1f7847c5c4.nq.gz
    ├── 1f3225f5915f40892279c69fe346f6be853e22cd.nq.gz
    ├── 2140205b8c81bba83ba156e27b92780d8ce2b063.nq.gz
    ├── 2140954bd4f8dd18d266fde74715b9f6722dfc8d.nq.gz
    ├── 21a5a3e7fabe8c5acdd7d3b431a0cdf5cd1c22bc.nq.gz
    ├── 21bc9dcb6ca44fa5af8e244a11b13fa6976f9b36.nq.gz
    ├── 21cb4a3cb37526c95475a474b3e02efc325ffe8d.nq.gz
    ├── 222cda004edb34eb00bc90a9e3be6d0cf134237a.nq.gz
    ├── 2260230a44c40c49b031876fa5814cf732b6c26a.nq.gz
    ├── 22cac32642dd2ffe664c40cb4592a52533186218.nq.gz
    ├── 23a03c3582dd3f576f0751a02e788586d097d8db.nq.gz
    ├── 2448254a20f5b66aa9436ad7280abedb3f7f06b5.nq.gz
    ├── 2456d719cf93ef390bba3420358769056f72dd5e.nq.gz
    ├── 24ecae5d2dae12869e5c4557c8048569e584d53e.nq.gz
    ├── 28143d08aed9d52320c7e2f157b5211a37ae6611.nq.gz
    ├── 282bad5bd9d8f9810e168b428d2c160c6b955bfa.nq.gz
    ├── 28a601d7c79c2d520240fdbdc0a52a781bf10876.nq.gz
    ├── 28d22f1eafcdd5a18a880429cc6d5c65e0933fab.nq.gz
    ├── 29f9f43554fdea1326059529fe51a390da62e1c3.nq.gz
    ├── 2a44aaaf8c5854e713164b8266fc9d64e46f5b15.nq.gz
    ├── 2afd7223427972a41d736832f506563b0a5e01ed.nq.gz
    ├── 2b4fe2e24dec925cfcde797cab239595540ae63c.nq.gz
    ├── 2b5cf9bd4416bb3861eef5e482704e37b0fca491.nq.gz
    ├── 2b9bc8433c9ba54dbbd39c8c0cdc1a3c6fd60e78.nq.gz
    ├── 2bbb70d7614bdc3251cdc7cefda3ac32a532299d.nq.gz
    ├── 2c29373b2294c91913d8b87cc365e48aa3608b65.nq.gz
    ├── 2c4378b5b2517cdbab0e3109b010c26da284395b.nq.gz
    ├── 2c4660a41c8c1d594a2e023b463eed7055beb10e.nq.gz
    ├── 2c4a67266f3e210af44bca15ebfe980708875e70.nq.gz
    ├── 2d05f6b43f66d2d40dde5d15e09aef83a32f482c.nq.gz
    ├── 2d3a3a9c68ae99de5d4832937ba1d02c9c637fe0.nq.gz
    ├── 2d417dcea0e17dc5550100e2c1fc5d44e76ca144.nq.gz
    ├── 2e28d4be8aaac7a43ced3ddd92f16ee77740c39d.nq.gz
    ├── 2e7a5e36b8e1225e2c821c98e7f7ff4e888b3bbf.nq.gz
    ├── 2e8df8887d507ecbf2787373ee02c49136b676d4.nq.gz
    ├── 2e9220c91dfcc4cbbe4ccd18f22ae5255f1f26b4.nq.gz
    ├── 2f27701098ab2a038f9d62d21fda39099a964790.nq.gz
    ├── 2fc806241c1a100787cacc4a8837c5eeadde7fc3.nq.gz
    ├── 2fcd606c9da9799166d77b18e42a09d1d93c7ba7.nq.gz
    ├── 301abaa75442d1685b05ce4a2f44f8f601156a4d.nq.gz
    ├── 303b7ad2f7efce13a646459c0032ce1d96e73536.nq.gz
    ├── 31dba2ef443b9e136444109cb440cad3877e1960.nq.gz
    ├── 33a51fae2cf0dd8bcb5819ab6f84f34b08bc1a4a.nq.gz
    ├── 33b1f0324deeae74b21f7f89b0d614f55fbd17e1.nq.gz
    ├── 346e28592caecba240da379ded2ce1ebc8906292.nq.gz
    ├── 3538b5f84e97922eaeca3fe1732530c026772828.nq.gz
    ├── 36349b918aa3f79440fed5412d8fad99b7696a0f.nq.gz
    ├── 36abe7b6f4b8455a4709b32dbfcdb083201c0001.nq.gz
    ├── 36be1c2385e63785be05c8eebd9023b3b2504005.nq.gz
    ├── 36be7983d4e93c2b6ed116e9f0d625b259cf78c7.nq.gz
    ├── 374cab8a196c429e82b566feb2038fe7d3ce3006.nq.gz
    ├── 37870706d3b3c2bf0c8fec86bd75b82f4051f684.nq.gz
    ├── 378a5d6ccac13d1c6bc2b3ddce09b129f35dcc61.nq.gz
    ├── 37a0b3127cb685c84f3f32bc4b236b433fc978ef.nq.gz
    ├── 3a692e7a111080d1520e3c624e6461311edcb624.nq.gz
    ├── 3ae49f54ea98392d9d3f14566a31a553271d54db.nq.gz
    ├── 3af03a025db3617b12e3b329a488fb57fa2f7dc3.nq.gz
    ├── 3b188986f1bbf85c3b128eacf11d9541d8346982.nq.gz
    ├── 3c05fb479fe1cb750a1637ad98e06184cfaffc02.nq.gz
    ├── 3c3f675148102247c5b5ee778994f74c1b43b8af.nq.gz
    ├── 3d50ffa3ebe4f7071f603414d78f34cc9d7637a6.nq.gz
    ├── 3d59f2dc5a5cb088732cd8ae4ca5e70edd46738d.nq.gz
    ├── 3d64ffb73937176f5be9491c2dc27fec2be51a15.nq.gz
    ├── 3e98635eaeec24995c55b9af2b3b597e8cddad83.nq.gz
    ├── 3f5376c8fd27a3f43a1cbeeb6002c8762a99d5de.nq.gz
    ├── 4026e18d82ae0b12b026664cb3425749276d7e9f.nq.gz
    ├── 41ca57d26fc01aa9782229f4cdadfeae64add11c.nq.gz
    ├── 4244a45a2312dc549cca802ccc040ae31533385a.nq.gz
    ├── 4260e1d4c4bc4d048fb2cb098465e3b0f6683da3.nq.gz
    ├── 432c65531e4a9467c9097d2f175fce6da4ac6495.nq.gz
    ├── 4342906c2be2cde293b9e89cc54154bd8d7ff440.nq.gz
    ├── 439063a55d37145de05049d388f07a95d9f49bff.nq.gz
    ├── 45628b9130381d3b648836db7a9c36a6c1df62cd.nq.gz
    ├── 460cd6b658eb2c7838fc42018f5d05fc7a51e6d1.nq.gz
    ├── 462069894702d6dfcbeb48b45784a48808482807.nq.gz
    ├── 465906b7b947463727f1d51291f77774fb2437c5.nq.gz
    ├── 4666816530e8650e75331106a5df6738fbf88c85.nq.gz
    ├── 469b8e02d93efc22d397fa96f3981cbd560ae726.nq.gz
    ├── 46a0d76a8e3fc8160cfdf1f8e09330815fffdaec.nq.gz
    ├── 47e13197228c51656aec921fd4846f26e57668b4.nq.gz
    ├── 47eee7a281fcce088264420ac72b168ef415f4e2.nq.gz
    ├── 48235d3a39c68dac7e183013f59d57c4a7c41b25.nq.gz
    ├── 4885f3ab0e274a2081cbdc1f0b2b3a52e93cb4c5.nq.gz
    ├── 49222c59c50240c0b66390568eabd5a598543879.nq.gz
    ├── 49db83e5b44ab0c6f5a81ea637148e5c84d8423f.nq.gz
    ├── 4a69fe4394ad40ac9919b3cf0016a9e899d4ec32.nq.gz
    ├── 4a9676dd361a2dc489ba1e2b9304a20925a0badf.nq.gz
    ├── 4bbf63fec0bda4a68a9a25123f2dac4c819a444d.nq.gz
    ├── 4be1ba43c4eca8431cdc8523917e181242e1aae4.nq.gz
    ├── 4d12a2f5adc4acb7ca46829aa03278342a45e61a.nq.gz
    ├── 4eb05273bef34fe9e73b2a4285931b02ba85aafd.nq.gz
    ├── 4eff97441b3a4d429160f911290268ff6b43eb8f.nq.gz
    ├── 5075efb5e20fb5c4e69f22057c72162db05fc690.nq.gz
    ├── 510093f7354dc5b422b3333bd09c7e53798a361c.nq.gz
    ├── 514ad4511a5aa178302679cf44fbe62b195d754d.nq.gz
    ├── 51efb2a1e87d53365a1be458b1f4b7341278a464.nq.gz
    ├── 52f0fc3438a1bfe833e4258c692ce61e9f6b67f9.nq.gz
    ├── 538334abfed92eaaf7637905c45114dea872a468.nq.gz
    ├── 53d5fcd72129aec85e731676e03cd12c67f84621.nq.gz
    ├── 5480afa96eb08add971d3d74556d0511d2c7c14a.nq.gz
    ├── 54e9636a6e2a8759e11965016ad22d034ba1c41c.nq.gz
    ├── 55406d948c5a9f4c44595e24f130544a3f7e61c9.nq.gz
    ├── 556882ae05b4d4ad0228a0b09621f53b0cb6c3d9.nq.gz
    ├── 565b9d7b4ae9b806fe6ee4eae5884b61bc02a78f.nq.gz
    ├── 56d7ddac8c4ffd7f9a0222aa070de4133fd3a5ec.nq.gz
    ├── 57695a153bc4b7a30f21397499933b6322e364a6.nq.gz
    ├── 58560114bf2e6be3134e8b37254f3f588283bb73.nq.gz
    ├── 588cfd374768a52ae9832362cef1bc8b60fa4ce6.nq.gz
    ├── 5948275c6057f1b75cb34f4f45ac8da3f9400662.nq.gz
    ├── 5a18c39577ea7b9a1bc6983e7b963ab05caaab37.nq.gz
    ├── 5b91b0e898e10ceb8ba6d212527ec4c774879d8d.nq.gz
    ├── 5b9d44636558c81167e8aad8e221729f126af4ec.nq.gz
    ├── 5be3dd47f7afc28736a19c4e53dae84d0db35d68.nq.gz
    ├── 5c2984d01b8eeacb508b23f7b2180d18b640e72e.nq.gz
    ├── 5d4699e82ce880bf60204006b9e92592ed65997d.nq.gz
    ├── 5e04ea879579072986a942db6a8bda3dc6fd2d73.nq.gz
    ├── 5e14140af0facbf00c1a3eda9cea5b30e8f56f09.nq.gz
    ├── 5e3a86e8917d83bdf0df3368adb9675b89db23ee.nq.gz
    ├── 5eadcc364002f0e0709ed008bdf628fd79302749.nq.gz
    ├── 5f0f52791692e92103aacd8418b108d4ddfd33a8.nq.gz
    ├── 5f6dc8c657cc0320dbf2e7d49375617f7043562a.nq.gz
    ├── 60bcdb1c5e152cc811c9f971ef64966008aa1ef9.nq.gz
    ├── 6101a51b02f94c5dd20e6a4ee8b5086096f0b883.nq.gz
    ├── 65138003e5c73fff7372f95a4e2694dc2215b32d.nq.gz
    ├── 65677989d87c2077d075c9181644f560bcb2f1f5.nq.gz
    ├── 66a00331bda949866e6d68bf9931f30313da746c.nq.gz
    └── 671be8c651999918c44b25073b7734b17c686c03.nq.gz

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

[scikit-learn-contrib/category_encoders](https://github.com/scikit-learn-contrib/category_encoders)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
