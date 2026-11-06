# Repolex Knowledge Graph of NousResearch/lm-eval-harness

RDF knowledge graph data for [NousResearch/lm-eval-harness](https://github.com/NousResearch/lm-eval-harness), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/lm-eval-harness
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 44840ee3d3b62fc04a3c25ddd3aa90750f4dc096
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 44840ee3d3b62fc04a3c25ddd3aa90750f4dc096
│           └── chunk-001.nq.gz
└── blob
    ├── 002ede9a82110e3679bf3e1e958ded4342e408e3.nq.gz
    ├── 0057e6b0cbfbd7a7663829a05e0d44d60c301d3f.nq.gz
    ├── 00789ddba9f13cec7bb4ba8a5bde837e3ae20660.nq.gz
    ├── 01792089a675f0cd17c28819e63212750815a554.nq.gz
    ├── 0182aedac757ee1008074e7a2b6b9a11444da874.nq.gz
    ├── 0296a0a548e1206f70627b4176d79aab7438db75.nq.gz
    ├── 02c7eebe8ac14e14781381235908eabcf446842a.nq.gz
    ├── 03117be5f165fd7edf40404bf9934b3753039f1d.nq.gz
    ├── 036b86192fcce6e3ab50cb62e00f96a698c9c30f.nq.gz
    ├── 036c7955722a470aa8c00d90b05b7d8af2a31426.nq.gz
    ├── 04d0bdd67114f3c0887979fdce210f0fa94616e7.nq.gz
    ├── 055b373565b3b0de730adaa7b6159a04400bc786.nq.gz
    ├── 063392eb2b559fbd04c5bcfa347c1eefb3d9f39a.nq.gz
    ├── 0641187b82aea23875e576e47e43ac55f0d7c2e8.nq.gz
    ├── 06ccf8f606fe9e0175b3e3b48eb3b45193f2c0c3.nq.gz
    ├── 080bc545cb3f9e0d6ac97f8d7004fc763c507ae8.nq.gz
    ├── 08c6e334c23f6f7f34a9f23c5e64acc7648dd3a7.nq.gz
    ├── 08fda55c8bba30023936fc11c2efa8de6007125c.nq.gz
    ├── 08fe0ed6c014ce69d7655c94ccd9dfdf029c8ce1.nq.gz
    ├── 0a22ab84293fdcdf9991cbca6ec33c70094615d3.nq.gz
    ├── 0bb80a3d2aeba5f3c3fb18d26867aacb858386ab.nq.gz
    ├── 0be19221b719c1f6d9885516a3e1c2972f2c9083.nq.gz
    ├── 0c8bd533b6a3d71e7c2f591ae7bd7e9c2f745787.nq.gz
    ├── 0cfd1dff148cedd50a3125222ea2076d5afe48aa.nq.gz
    ├── 0dd6aca0535d448d9269ae1959063d687955a17f.nq.gz
    ├── 0f4cc0066a1f5679d3529802fd5a9e561828e733.nq.gz
    ├── 0f66f8ec7803650ac5cff6a60dfc9bb9f8388fbe.nq.gz
    ├── 0fb527557dd3906b1ec51a83d0ddbfa48da815e2.nq.gz
    ├── 10d4db0d87c9bab0d6d0ce6760ae4e2b24010753.nq.gz
    ├── 11a057d8ed756f0d2e697c459be49f22b57dde94.nq.gz
    ├── 1268962e3109170d8c4fb1c52240b7221c8853d8.nq.gz
    ├── 12d90b97f710ef2d2691931b2670792d431b101e.nq.gz
    ├── 13b2ccc4f939876616ceeda42d211e96347ce060.nq.gz
    ├── 1409aebfab9a95e84a54899d7e958445400cd535.nq.gz
    ├── 147fe567486cd59fdb817d6448ffa3e6e4d6969a.nq.gz
    ├── 1497c7802888d83da4c99cb1c0845e15da887584.nq.gz
    ├── 14df221ad80450fe05fcf458954607b10eae024c.nq.gz
    ├── 1560b84f682493ef53a9c26ae1d36ac520ff46c7.nq.gz
    ├── 15eb02afb6d8ca7f18cdcf56136615d51e24b199.nq.gz
    ├── 16132ff497c3f01a43b977b107a77365b9888b9a.nq.gz
    ├── 16a337dbc2a8568cc36245f34b7eccaf28ed2548.nq.gz
    ├── 1793811014790e678822f1c27fbf0908b00e8ce7.nq.gz
    ├── 187b79e94c9ec4c378da110948775afc8be14920.nq.gz
    ├── 193a064c984f847b6dc679cffa6cc0223fa30738.nq.gz
    ├── 197072536a06a3215c90bd0b34d50dbb93f4c38c.nq.gz
    ├── 199aa2c8dae8553f22f2f15ec72acedf1e09bdb4.nq.gz
    ├── 19ca656c800f3d00332c6fdb4fbe493fb46f96df.nq.gz
    ├── 1a3b08ca6c4db099c156f4cc2277e408c8cee6a4.nq.gz
    ├── 1acbf4e1cf204dde35904ae0d547be3b81e10271.nq.gz
    ├── 1b576f9fb3d0ce1d21e8d7543b56a539300be36a.nq.gz
    ├── 1d6bea95e1001e7e8986a48afda483ba9dc1933b.nq.gz
    ├── 1d78c711d12290e871d5fb08ec110800bd610761.nq.gz
    ├── 1e97c6adfd7372ca59a36dd3ea684d6596a9519d.nq.gz
    ├── 1f95457249b51a31d715ed22a9b39a37d39ee93f.nq.gz
    ├── 1fa6b5d23cd039f9b3e194620cd0c1dd84f5c7c9.nq.gz
    ├── 20267adc68ecfb59a514dd71cc6940ca0fe80bcb.nq.gz
    ├── 2099e0a12de41328eed39ebafb5ec940ee4aac5a.nq.gz
    ├── 20f8d99f9f2c1653fd7b87aa48eaeb259daad54c.nq.gz
    ├── 210ffd8feb379377d5613aea89d98240c387a94f.nq.gz
    ├── 21a39c51b7d246c3dd49e47ee0f5dd1865059c36.nq.gz
    ├── 2487f15a4a75ede35ab29300b6764fabd325e139.nq.gz
    ├── 24ad69b90df35e1318e65e061e31066c67615cf6.nq.gz
    ├── 24bc43eda3eaa1815919c9abc7d05697f53be309.nq.gz
    ├── 259534b9ad217196da25ef9397e136bbcfbfce0b.nq.gz
    ├── 25f30a368d61f9a6a240db0b657a262718ab43a6.nq.gz
    ├── 26b232a879778b6d7eee8bedfdbe7e758acba9aa.nq.gz
    ├── 276dd00a32cda56c82a76efc73185bd7a581e9ae.nq.gz
    ├── 27c60fb72194325e51647ce0fe137710df6dff86.nq.gz
    ├── 27d6ad70067badc93a406bda2a06cd5d66d9ab55.nq.gz
    ├── 2833840644b75044470a2dfb133d0afd43da105c.nq.gz
    ├── 28a63b1b9106219486b5487b24396baf44179276.nq.gz
    ├── 28dbddf78eaf47e21ddeea2f69eca240d4139343.nq.gz
    ├── 28dd6af64ecd6344146a790a57cfc43ccf2eb3a2.nq.gz
    ├── 294c3c5dbd6e7a5fffb62ea28de6045d2f70fbc7.nq.gz
    ├── 294e99a46b2b81da8daf02a143f35bcaab85d6ad.nq.gz
    ├── 29bb6cc6c054d114da89a59478cb8f195e7a87d7.nq.gz
    ├── 2a397baf1e40185883569b53ffc9bb82265b4257.nq.gz
    ├── 2a654fe86568bf5c602d7be916450d54d6ad42a9.nq.gz
    ├── 2c04bf5a4da9fa65ffebca5c3d042cd0412e841b.nq.gz
    ├── 2c366fdac6ac9d5feaee18273118dbba21c3c97a.nq.gz
    ├── 2dc83089094d69a5872cd596374c7ef9d3707ac2.nq.gz
    ├── 2e0deaf93cc2afb28abe2172730c8c32231687dd.nq.gz
    ├── 2ead0f6c11557f972900bbc21a4a94e578e73d93.nq.gz
    ├── 2ecf2e8e7014784d6a6f644894d719b6a36f3df0.nq.gz
    ├── 2ee32742aabdb8b810669bcac2fa07f95a8c21e3.nq.gz
    ├── 2faf735c7dc365b0d4561223cb0f5327c5c4e5cd.nq.gz
    ├── 300de6771aad1aae4994c08dc77ffeb78c3fc1d9.nq.gz
    ├── 3074e09e14cf0763aa58e8fe2801337da805b734.nq.gz
    ├── 32112d3c8b6ee26ee786439053c2d1f1da5b04c2.nq.gz
    ├── 32cacffea668b3cd783bbc3f05d8445009dd9c3d.nq.gz
    ├── 3393c36805d6b29cd3d59481b11c8b8dd45e2910.nq.gz
    ├── 3435604a4159ffb2fa425813997bf38343a3f27b.nq.gz
    ├── 34e99ea0f47b7017206bd6e9078ca7a5c2b25f0e.nq.gz
    ├── 3543486b113bdc0a56ac96feadbbc1f3a8ed997b.nq.gz
    ├── 355053b25b7236db96c18061c5bbb405bbeb79b2.nq.gz
    ├── 35514b83405b51cb2870c012a443c2a11ed47983.nq.gz
    ├── 362b4dbd13e1db423fb30a11b60720c10f37473f.nq.gz
    ├── 364e159b03bf738ec612523b268443ce5490a1ee.nq.gz
    ├── 3687d569e9243d3ce45d662e45c97ea83c3aef0f.nq.gz
    ├── 36c235feefd1548320400e7e8d9f3e03f2d478d0.nq.gz
    ├── 3715aca53b7bd9d4af3c95a95fa5ebdd8e7e000e.nq.gz
    ├── 37183dc793c238e307ebf03cec66000336f50a45.nq.gz
    ├── 37683c46e237fd3fcfc9e79cb6e861d089484090.nq.gz
    ├── 38706977649f0c27b555b6e4887d9b24ca7ef19d.nq.gz
    ├── 38f799060fa6901b890d3a87d8aa9b9444d34b57.nq.gz
    ├── 390cbc02770f8834623caa7aaadc61673b8b1316.nq.gz
    ├── 393c080c17ba34ae9a79bbca62460334a3606366.nq.gz
    ├── 3959f00620ba302b1ea7ae28622c4d551219f445.nq.gz
    ├── 3976de43ace0048784a0c802777fd815976571ba.nq.gz
    ├── 39fe15a2bd819eef516f62dcb4582a2d0044414c.nq.gz
    ├── 3aa1d8c7349449271fbd81fbbc06fde47a116028.nq.gz
    ├── 3c0e9d17db10f4e69d1c44d5a127f2bbe1f4e279.nq.gz
    ├── 3cce25c098de00ed09758aa874658822776f0b7c.nq.gz
    ├── 3d0d4c5c59ed00554e2ffa4590552692986b7be7.nq.gz
    ├── 3dfc0ad3621e939c13d4839eb7425c13b33c6320.nq.gz
    ├── 3ef5fd615fb7524534c9bf3bfe896efe72363ceb.nq.gz
    ├── 3f035787e33118323fd2c91698c4a6282fe858b6.nq.gz
    ├── 3f04fbcd1d67b57abe5b074acad4becc413143bc.nq.gz
    ├── 3f0e914c87cb31eea9b9524c4552eca2234eadce.nq.gz
    ├── 3f1b6d70e022414b7d370635daa49e3a9a8649c2.nq.gz
    ├── 3f1e7fa1bffacd485db4c9d5c556e331c63c7abe.nq.gz
    ├── 410a9ad13b794ee6459343ee0f0c469b62633843.nq.gz
    ├── 41306b4fa5c220be9661bf20a73f96ec08205837.nq.gz
    ├── 41767099ef9b26a721904b97516b1dba49a0e991.nq.gz
    ├── 424c23c284c7df240f9e50ce6b95573c627b87a5.nq.gz
    ├── 435388fd74b86392fe4b4124056f34590528d726.nq.gz
    ├── 4512e9176f98a9f2ec3f53de15657b97274809fb.nq.gz
    ├── 4575ca044297eff4da62096a1f4911349c559940.nq.gz
    ├── 459442d4407db3572ea4fa340c0494686d7691c5.nq.gz
    ├── 45cf8f13408cdae93860e78c260b92a162c93fb3.nq.gz
    ├── 4605a4a15f2e84c4572388192fc1e51d717f70b1.nq.gz
    ├── 46861fdc1149b72d4ac3f347c0e09f679f6c6e54.nq.gz
    ├── 46f94b9c284cb5a998ffe75c06abebbec4ccac09.nq.gz
    ├── 477b6cf9cfcb367942135c16d59f0e59c805d14c.nq.gz
    ├── 47a301cf705d5abc403ddfa122b989bef2e82099.nq.gz
    ├── 47e49ded46082847d73fce85e2db37556fafa877.nq.gz
    ├── 48b5c332c22c50306f00f36bd3004db4393a49df.nq.gz
    ├── 48c339d7439af8e827aef5ec0e0a8391209f86bf.nq.gz
    ├── 48ec0e75d852057e4080f3dc4ea84c417beafaf7.nq.gz
    ├── 4950a8996806739858b4261f9d0b005cd508fafe.nq.gz
    ├── 497b9b01e352d37ad1a5fd52757130d19933810e.nq.gz
    ├── 4a861454776d977ecc8e21d70cb0b852b98fbd8d.nq.gz
    ├── 4b869606048121292efb01118ccde1cb13387a06.nq.gz
    ├── 4d084034da2abd8306485999ff67596a618c742f.nq.gz
    ├── 4d63541e54cfd1b7510214450591404f8da4dc18.nq.gz
    ├── 4dc7c8c0095ba06391579b7d78671b7d17b1f4e4.nq.gz
    ├── 4e9810083eccde3b43f2a00df4fbd3e2dc4b2992.nq.gz
    ├── 4ea308da21fc68715e6fa7f6b38e2adba20c547e.nq.gz
    ├── 4f0612acaf264f77f63d96fd2ca62ace587a2c76.nq.gz
    ├── 4f74c68d721adfb24bcc078b1e866372155038e3.nq.gz
    ├── 4f7d8b5a1c730bdb1131db0e92a078061e0112c4.nq.gz
    ├── 500f1921bec3db0d1282b8501b7a0841ebbb79c4.nq.gz
    ├── 50225ab5f34367f75ede434f7e5f687045f84eb4.nq.gz
    ├── 507a41bdc9cafa30afd3ecd2e9a50d089d1c4ee9.nq.gz
    ├── 507fab8693c7962e681e58bcf64b76d8b0da8649.nq.gz
    ├── 5199d5941097180227eafa5b5a3fb36e149c620b.nq.gz
    ├── 51ade42184fcf5b554bfebe8882748dfb2ca3600.nq.gz
    ├── 522bd1230362f30851187def4a3bb4205f83aab1.nq.gz
    ├── 534d90f70dd08313f6f9a0cb68f5571f689e8569.nq.gz
    ├── 539f8da66b7f6ad9bdb4e75ba746477b492de91e.nq.gz
    ├── 53b52e96edcbc0ba14701c764dd9d46863c54083.nq.gz
    ├── 53b52f4d3ff79686c1018b6d8706685710316d02.nq.gz
    ├── 5411e8c4793ffbdb4cbf5aca045b822685d9b5e7.nq.gz
    ├── 5448baa47394fd79fd7aa472cfc1c155069da575.nq.gz
    ├── 54c15d66e5659537fdd0aba7eed741dcd5fd538e.nq.gz
    ├── 54f4367d010fb4ae5b0fe6b8a120f139b39cb0ab.nq.gz
    ├── 551a0f8da6f8e35b523756572f73bf7a2e0bb27e.nq.gz
    ├── 552eae1f79a6ee641151aaa8211d4c67fff072a8.nq.gz
    ├── 5565ab7e07e1abd157021091a0dfa115995ed4ab.nq.gz
    ├── 56358fe789834a394bea785e64dc49183cf080cb.nq.gz
    ├── 57667edc254ffa8c3b3406f30d2fb891e18377f9.nq.gz
    ├── 57b13f05b85c70dff2e30ff66bcb01feb6512846.nq.gz
    ├── 583e29b103756dc04cd851e4b77302596a1637c9.nq.gz
    ├── 58dfee1ee1fe6b7d56ef283caa8e809875763d64.nq.gz
    ├── 596d69375d64438f70093658783ae167ca236d0a.nq.gz
    ├── 59e147aea00069f3138f1ad8c1a561d641755854.nq.gz
    ├── 59e4fc3f2bb68f45cd4ff9c158b82b4cd0032241.nq.gz
    ├── 5a23a990afe0abf5b354a15dfec3b5bbd2775fc9.nq.gz
    ├── 5a48eab7e2f642e3fa930f7b016235e58f8c13d9.nq.gz
    ├── 5ad9a8f2c886e189c380b9f01104fca11a2ef529.nq.gz
    ├── 5b134fd9b929e1be7402ce6180da86f1a9c89a6c.nq.gz
    ├── 5b8ee96f09618fa6f2fbd3ba4aea6ecffaacacc3.nq.gz
    ├── 5c5babd4d87f2b0a8bc7fe5e822c535318bc925c.nq.gz
    ├── 5d1791bdb4f8ae06cf4168dcdfa4c6a5a9bbc823.nq.gz
    ├── 5e5fa30806275cc5c615d58537fe7470e16adf45.nq.gz
    ├── 5f0e57052c224bf00637d7a40474506d6e31ce29.nq.gz
    ├── 5f6a78544ae48d546707ffb653af03ccc3916ff9.nq.gz
    ├── 5f7b73ea5fa64072648fcedf88406a66b695ca74.nq.gz
    ├── 60425fadc666754f055eed2a79d47ee69a5dbdc0.nq.gz
    ├── 60806afc61e6e35998b3c96d2631b01b66121923.nq.gz
    ├── 608f8d5206b71a33db3dbb68f3c84a4f790d7280.nq.gz
    ├── 611211bec04bc5833413b1ea21baf5f216b2cb3b.nq.gz
    ├── 61521c91da4d5597aa1c31450e1b18a0115f9771.nq.gz
    ├── 6213d280b995bbc25881afcc989969965cce1308.nq.gz
    ├── 6259126e0c687ab6c50d27051524cadcc10368e4.nq.gz
    ├── 6299c4d06d84c7d3360771c6ca633b3230196b10.nq.gz
    ├── 62dd5197439239a86c7d044d28fd936226481a02.nq.gz
    └── 62f9874e63885c9ffbeedde8a4af4d13a8f06792.nq.gz

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

[NousResearch/lm-eval-harness](https://github.com/NousResearch/lm-eval-harness)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
