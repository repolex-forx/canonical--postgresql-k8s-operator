# Repolex Knowledge Graph of canonical/postgresql-k8s-operator

RDF knowledge graph data for [canonical/postgresql-k8s-operator](https://github.com/canonical/postgresql-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/postgresql-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b682ac1b3342de02933a512f4eee41f4845fa292
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b682ac1b3342de02933a512f4eee41f4845fa292
│           └── chunk-001.nq.gz
├── blob
│   ├── 032349b66e3853429183cb69965cfaaf7830d88e.nq.gz
│   ├── 047617ab39d9430a12f01326fe9957bc75aca082.nq.gz
│   ├── 087f6f3c58d5885b5ea92e0efbde8524c04b57a0.nq.gz
│   ├── 09449f03f75186a6d09d013f9aa09e378b70d2c6.nq.gz
│   ├── 096918629019ad243714dfecf2af3fcc483d7600.nq.gz
│   ├── 0a4c2522ffaefcdf5e4ab66b37870ea8870e643b.nq.gz
│   ├── 0c64fe771fdac3a7a111ca8dd3e5e79d84d4c571.nq.gz
│   ├── 0c956a4a883542e0a2f8d441b693e614e231267a.nq.gz
│   ├── 0caea30a724cef0331c79cdc47bacb50224e6665.nq.gz
│   ├── 0f2ad75cc330d7dfaa4ba4142d68def0a5f695b3.nq.gz
│   ├── 105dc192dff0ad0c5b20ef3751d84cdc3583d4a5.nq.gz
│   ├── 133d5e0b9604b85df810c8382398375f3abf6847.nq.gz
│   ├── 1341c5ad233e801167cb2d016f4ccbc054bc6782.nq.gz
│   ├── 13b51a3051b95ac5d9218b2da5db4d67fb77bf9d.nq.gz
│   ├── 15adc9d768f3edc9be2e31def0b05384aec9d470.nq.gz
│   ├── 1659a0c0ac40a79e44d228af8675da31e195cc76.nq.gz
│   ├── 16666b1eb06c23fe23b79dea30b077ae47fc5f5f.nq.gz
│   ├── 175110d514772923300d6795a5d76159103be0b5.nq.gz
│   ├── 18b3e1857c07e0c0bacd42e75bc5a290eccb2f1d.nq.gz
│   ├── 1a35fe81f9775265256aebed2262d14145798439.nq.gz
│   ├── 1acd09b36a7ce6bc3a79c65edce97ca89c2e6dff.nq.gz
│   ├── 1b8f8a5e4851ac9d25cf33fe7cea8a89d8a87fe1.nq.gz
│   ├── 1ca75497f53ad0883d3ca3723825b6c9ca4cc095.nq.gz
│   ├── 1cf6db799680f0af8ff10cd9b8df87b9def96213.nq.gz
│   ├── 1f201494256d629e74ea24236de96319b4f22812.nq.gz
│   ├── 203076951beb406c399d0d2622c2579fc5674532.nq.gz
│   ├── 20e2514d56b173d0d77c2e66d64ad44d73c823c3.nq.gz
│   ├── 22336bfea3408dc65662d3a56bced5c6ae25d208.nq.gz
│   ├── 237cc3981b4548710e343f625dc4d6758aa366fa.nq.gz
│   ├── 24e4f1c7094c68579266053d0bb41405e337ce14.nq.gz
│   ├── 2706f27671643979e5f5c236e5e7b7b1e48ccdea.nq.gz
│   ├── 2a2ea2f866937ee3b69f7041ef82b5b33ec1c5ac.nq.gz
│   ├── 2a8bd7f5b4b3043b01daa88c5370253fc41b82a6.nq.gz
│   ├── 2acba4a9a57798326c6e3dd276c60843eec37e40.nq.gz
│   ├── 2cfeab1c4fabb0787efd3d3ff2ee1702d1ce741f.nq.gz
│   ├── 2e7f13b9839ea19b1f2a8e36d65ce17aa2630eee.nq.gz
│   ├── 2f74175997f7b9a1d80ace56017b71827e0bbdc2.nq.gz
│   ├── 334ecd0db888ee20f42fdee1ace15785b132fd53.nq.gz
│   ├── 34029366dea7c67e011aa0aa2ab0b748bd814536.nq.gz
│   ├── 340adeb44c9c6d6cfd70d48322e025f41ae8863d.nq.gz
│   ├── 34d8e180e168c4f4e8f22cd5f3c83ef2b45344ce.nq.gz
│   ├── 374b445c2d8ba795a2d9c188ed2f91d97b951e86.nq.gz
│   ├── 374cca79d5b4efef7ec6125bc40176e76a197378.nq.gz
│   ├── 376921513e10c43b4159096cd85d8933ca706a50.nq.gz
│   ├── 38d045b5b00beceaf38e002fecdcad7c33891779.nq.gz
│   ├── 3c4ade4203637169c124cc0182253f3ade22f911.nq.gz
│   ├── 3c7f76f3890d8c091f149aa047d13cb373c977e7.nq.gz
│   ├── 3d71c6f199a66adf6622bd7441e89000dba49c3a.nq.gz
│   ├── 3dc889c0edfe4e73fb208e7ba98b9188c00e59dd.nq.gz
│   ├── 3e2e9bd20b53779d85c8ff1f68e1773f406cd2c1.nq.gz
│   ├── 4004b0c6df2754c3ea7ddb31639805e6684d1750.nq.gz
│   ├── 4214a4ae11894783464898cf669bc7075128fb7e.nq.gz
│   ├── 439559b4e6ccb98b9f983ccdedc85a8ace67210e.nq.gz
│   ├── 4532290fd1fb5b6d9f67b2c8ed3e3afd0d4f6986.nq.gz
│   ├── 45b7bb64735c1dffc734b51110e2949e08e7a16e.nq.gz
│   ├── 4758a345896bee45b5da71270d5fdf7a692df1b2.nq.gz
│   ├── 4825675f4a24869307b36cef990d6149c838a23f.nq.gz
│   ├── 496688162cb4a1a8d2b8fd2073a109264a725442.nq.gz
│   ├── 4ac59fbf858cd5b70f3c3ed4fb2876e4ea989112.nq.gz
│   ├── 4ec72744f61559a6812f4f1320ab76ba6013866d.nq.gz
│   ├── 4f7b7cc2e24150f1c6ce2b305675911dec1512dd.nq.gz
│   ├── 4fbf3b6b367c37798e48c3136a0202be8b906bf3.nq.gz
│   ├── 51546f816a2133287181a4580758562c822b189e.nq.gz
│   ├── 519234c63a6f41cbe3ec1854a05042da3d5d46bb.nq.gz
│   ├── 52d2541baf071b8d14e7e58b6075cade82c30b3c.nq.gz
│   ├── 52d799c9d4a92e0d9a35ea19a65e6956c4693c58.nq.gz
│   ├── 537158e633fa5a53a0d96e3f94c0db09737c5e29.nq.gz
│   ├── 5471e10107cdd79be41351103738b78c6942f142.nq.gz
│   ├── 55ad32ae3651f38cdea5d7cc8cf848158c1b8485.nq.gz
│   ├── 566389ebf9ccceb1e143ed0c304d0c793d87f8c0.nq.gz
│   ├── 59d2636e951e0dc1888815b2f0697e1eaa7bc372.nq.gz
│   ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
│   ├── 5bf893e6639c7da46174b3ea2cfe9166ffe40a7c.nq.gz
│   ├── 5c9d33c7acaaf2208a30b1872ff1c8a696478dc7.nq.gz
│   ├── 5d051e9b5cee08646e9ede20a58e3d6e14e1c73a.nq.gz
│   ├── 5ea1f451d74e8fb167f21116002f37d9fc5fe24b.nq.gz
│   ├── 626d8adc6901dbd1d646ae1dde2a673471ad7cb6.nq.gz
│   ├── 62f6422ea795004701a304e397bd87ded91ce813.nq.gz
│   ├── 63a431d6d6b63617ca44acae223d137c5e51605e.nq.gz
│   ├── 659326801eba408e8f45fc1269846eafc509d4e4.nq.gz
│   ├── 661f5090923a3e26b1c41171830fa0c10ff34327.nq.gz
│   ├── 66ba661ffc5c7198fd7fc958fd04c30dd303193b.nq.gz
│   ├── 6b5af54263fd20f6c20e43a37d1919b0663bac4d.nq.gz
│   ├── 6b84b10ad38a7243057ca11032a265fab2ff6c0c.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6fa2f05709e24937619cebdda04134c07c5ddcea.nq.gz
│   ├── 736301125ec07c3b6b3b9d101b194485270b8e4f.nq.gz
│   ├── 76e0ca9878a3167660ce7fc032284a66bea8c0c5.nq.gz
│   ├── 783319272fc1e6a0aee7caa5846e0568926b45d6.nq.gz
│   ├── 79cb740e2cc8a6f5e486ce60b92e9e26319a4da1.nq.gz
│   ├── 7a52c7ae6ae553a06939c2ebd34dbc79aceee5cb.nq.gz
│   ├── 7ad681d8989dc839535fba3aa2989c13a9ad4b1e.nq.gz
│   ├── 7c967fde9623b7a8edd9b9cd2a82b7fd41c15adc.nq.gz
│   ├── 7eaaf03e3186f30c842b21324c58a9a32dbcb1d7.nq.gz
│   ├── 8023d85ddd50aaf00010d9f891a3a38180eed323.nq.gz
│   ├── 80f3d9e3e38524191e2a8e0948d394106095339b.nq.gz
│   ├── 8433d0194f9af948799ddf5c576fede56986118e.nq.gz
│   ├── 84da27b281b3c5484038aefa4038fb80333edb27.nq.gz
│   ├── 864c112c7c9ad31e035769c40b07d73b3c8e958b.nq.gz
│   ├── 8765f484eb6e31e039aa477b5d2539c3b9382616.nq.gz
│   ├── 876f50256cfa0ff336c4a7349238adc46b3dd1f3.nq.gz
│   ├── 87ff499a1abbcd93a7a56da7f8357d9180be22bb.nq.gz
│   ├── 8a96a6521228da4e898a6f1ed8efa4f10277020c.nq.gz
│   ├── 8e29d48146b3bfa7991861b289fb9f69d5c7ea7e.nq.gz
│   ├── 8fe80688a444c5181ab2c77753733ad24fb6c982.nq.gz
│   ├── 92219d71c83a39ce54b28b41c505260ffbdf0ebc.nq.gz
│   ├── 9472b349bab3e1da3887d79bcd263266b8014b3c.nq.gz
│   ├── 96450bdc32382abbcf9ade4798ce335b494b9dc6.nq.gz
│   ├── 98659556cf64f4237e9d631e70d6d4280461384e.nq.gz
│   ├── 9a15830dbd96a722a4525516b6dd569e73765177.nq.gz
│   ├── 9cbc84e43da784cbb6482a1e999193eadcae0058.nq.gz
│   ├── 9d0e927a51ad682ea8516dc324211a71c46dbdad.nq.gz
│   ├── 9de8b875949b82ba0c954651ef96bae1c55d8995.nq.gz
│   ├── 9ef36aca6d2980f250f98016204ad1e4b0f11d84.nq.gz
│   ├── a0601076454d9ba768acd0af1203cc516c152e1e.nq.gz
│   ├── a0e052a9257d0b32eb29c3b00fbf992aec822587.nq.gz
│   ├── a1c60423eb87f80831520f29f6e8aa38170854b1.nq.gz
│   ├── a2d250e4fc0751a0dfa4ef81594a6ea91f90e6c8.nq.gz
│   ├── a4c2bf639da003923edae21b5f1f49441255429e.nq.gz
│   ├── a605744913f35879364d53aa1d31acd8668a3125.nq.gz
│   ├── a63eb2144bf23572980191737e66127d7bc0a14f.nq.gz
│   ├── a6b31a59a693cd0006161fa0c888493b3acb1ba2.nq.gz
│   ├── a76f378af5953a32b6c56ffeae8350f46af0ffa8.nq.gz
│   ├── a88314a0a6e670a0266f7f9f7f785f533ac08597.nq.gz
│   ├── a9febc390d081bd79c5d991343c2dad258e2d4f0.nq.gz
│   ├── aa03ddad09f76dfae8db4269aefe751acaa98aed.nq.gz
│   ├── abf9e200258ebc4baae3a8e72174a3816d4517aa.nq.gz
│   ├── ad5513d3bebdfd935cff45acba6e28428fedf8cd.nq.gz
│   ├── ad75688087961e6ca5b1be05e34e7bc7ed40f78d.nq.gz
│   ├── ae2841bf464ce63f1d5c0c0866fb60ec74a11b33.nq.gz
│   ├── af7bbc9ab6789975e4a6bcb5a36a2e50114f033a.nq.gz
│   ├── b07369da3b4eca0852edb0e88eeefb4107c99c70.nq.gz
│   ├── b0fbb34478f1fbab8cd4e79f0f42987afbf911aa.nq.gz
│   ├── b3be366921d7e84f8302a2d33bdc3a9949a9edfe.nq.gz
│   ├── b49e7d97818ae2c3cd4ccc8e59572818c96f3981.nq.gz
│   ├── b587cad013b57fda11dc86f5e2d0786742eab051.nq.gz
│   ├── b6df6e4badccbd36335e8de0fcb8bc474ff9bcd0.nq.gz
│   ├── b9f4b158de7b890be838cc8375ca38b09123f29c.nq.gz
│   ├── bac49699ea4d6726837627c96375831b2b016197.nq.gz
│   ├── bb25408356caf893318bd8518432ac85de478d8b.nq.gz
│   ├── bd3eff59544303307d47b98fa1b3bc6fb6da222e.nq.gz
│   ├── bff0e492b316537a6d1483b618cd296d62301d13.nq.gz
│   ├── c0dc3ac9768e0b342f4926fbf8b0e7d12fe3c07d.nq.gz
│   ├── c245e5c532b6a4c4674b40de60787b6fadf36b21.nq.gz
│   ├── c25a54620f755bd770740c47c4a4aeccd70ec54e.nq.gz
│   ├── c335cf19adc66ef52bea30f87e9fac84429880c1.nq.gz
│   ├── c5c714405a6984950a12c9b0e78b1d90ab803b50.nq.gz
│   ├── c61278ac974b1a2e982f6d4b9c2ee032600c757e.nq.gz
│   ├── c7eb54123240bf682582aa975f35ae84770136d3.nq.gz
│   ├── c882a3e1acb45dfd78b0c36ff766c7a351bdd339.nq.gz
│   ├── cc87a5817dc374860b27502284201e9563917790.nq.gz
│   ├── cd2a08cb7d7d8fbae65c21de70c621e4ef85b8c0.nq.gz
│   ├── cd477b2f5f249c15622b37e8995a00d5f75d4a26.nq.gz
│   ├── cf069ab2e31e0bc00e91379b7b654734cb6bc72e.nq.gz
│   ├── d2fe9793d13e83ff23b232e3722795f83b89b026.nq.gz
│   ├── d3ef440161d6841feb1fa268383fd21ea7d91981.nq.gz
│   ├── d58e5b22edfecceb0fb17b2e822a79b7f00c571f.nq.gz
│   ├── d5c2aa1692cb82028dac4c84b5eb6c515894d785.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d787175d1ef6763d3017d4f33c2bad7b0471c9f6.nq.gz
│   ├── d85d820bc7ae0bf1845090b5feda8b07561b1711.nq.gz
│   ├── db977655f984e8a8defb10b2dffa6032e562e197.nq.gz
│   ├── dbf4d5bb721e2c91fc81ad9e7bc352896740ad17.nq.gz
│   ├── e06e899c08a2e37fc44b0ec115f1d34c5baa1f2c.nq.gz
│   ├── e0d16e9735177a15c95a0d7e0d4210c362cdae2b.nq.gz
│   ├── e1b55ab3b25e27bb4cd41fb5813e92139af70416.nq.gz
│   ├── e2ef431791aa5f17bb7fdaf67ab00239bbe7bfdd.nq.gz
│   ├── e3457ef6176e1928319fe4c2424492e6b458c3b7.nq.gz
│   ├── e39e19dfd781e788448e8598b620c74baa3fa8f6.nq.gz
│   ├── e52d509a01b809d7d1ea04a9fb75f13c1937be33.nq.gz
│   ├── e64cd17e9ad8ad191bb3843e557200c5d6e8ef97.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a02d4eea4a9b477c99e0d058eb4c2df636cdc2.nq.gz
│   ├── e8fac0da2a17bef62a8a7cebd3640c820f3587a6.nq.gz
│   ├── e9dce8e28fd4efcb2f50bbfd9f270d7727fece7e.nq.gz
│   ├── eb154f729e8faf91a836b6e397c04e3e1f162313.nq.gz
│   ├── ec41d94b9ce8b454b393855e71a3c7a2490589b5.nq.gz
│   ├── ec98be38d6462cb55b112315daf385eb429ee0a6.nq.gz
│   ├── ecedd5aa928d0d3ee2a94ab5d6362062c5403f00.nq.gz
│   ├── ee4a5e32013cdf5465cf8a556e8296376b4509aa.nq.gz
│   ├── eff2025d3102d4fa3bbb985239ed6b286afcdea9.nq.gz
│   ├── f3297f9de8c8c6567fee30f0131f6c352c61814a.nq.gz
│   ├── f330f89b38fc50328df7cb8547409644f212eb72.nq.gz
│   ├── f36849851afcec92cfb730e8cdf0c3f2824a0472.nq.gz
│   ├── f3ecdf027561701e8d67ecc51f50f18bf5ae6944.nq.gz
│   ├── f4d7cbe9f33b7f5a666afd32b49f97c2d9892bc3.nq.gz
│   ├── f655f28c5a268271b215b47f5d89eb8359986f0e.nq.gz
│   ├── f675de7c9a8add24c48c47fdca9ef2593e452c10.nq.gz
│   ├── f6e44a6f6eedce8f23828460f8897c13c5665425.nq.gz
│   ├── f9ee650010f7a64b1e5e5f0c64abf4d1af2e6a96.nq.gz
│   ├── fa89e9d7f0a34f12feec51eb28b9208c96d0494e.nq.gz
│   ├── fada7cb4fbc9b0533b148b4aeb17b671902b044e.nq.gz
│   ├── fde16d68eb0be32a8ab39bf9387542ea6d61fe7c.nq.gz
│   ├── fe41f85c06a1ae3ee9bd0d6f5d6795fd4a6b64be.nq.gz
│   ├── fe434609f1264b072173630cb88e75f8f3069b0e.nq.gz
│   └── fef9e6fbddd8bfd57ce465c17719a73b9ac1ef68.nq.gz
├── branch
│   └── branch.nq.gz
└── commit
    └── commit.nq.gz

9 directories, 200 files
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

[canonical/postgresql-k8s-operator](https://github.com/canonical/postgresql-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
