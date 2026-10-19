# Repolex Knowledge Graph of python-semantic-release/python-semantic-release

RDF knowledge graph data for [python-semantic-release/python-semantic-release](https://github.com/python-semantic-release/python-semantic-release), parsed by [repolex](https://repolex.ai).

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
rlex download python-semantic-release/python-semantic-release
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 60de8fcacea7fd5177f34368490677be5f098995
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 60de8fcacea7fd5177f34368490677be5f098995
│           └── chunk-001.nq.gz
└── blob
    ├── 002c45d509ddfc5c18b0ebb8c1d2ce8c154765f3.nq.gz
    ├── 0057cfcce2c8f7d19807b365b10edeb538eb17f7.nq.gz
    ├── 00d0b1d18c39c2bd7cb027bb343691f32c9bc783.nq.gz
    ├── 0119586d0680648fa3b55ef6d92d8c2141fa21d9.nq.gz
    ├── 04a5209ce41329426c9bdbc77960e5b9d8fe186b.nq.gz
    ├── 08032332d4c91edeaafacc17ed6ef0da690851a1.nq.gz
    ├── 0887a0668c37eb5eabcba8d3424be62a6271e0eb.nq.gz
    ├── 08c2aa6be34c638420c1072a8bc7c70fb7bcef27.nq.gz
    ├── 09929fe4369c3fb7055194ada0edabde29216d80.nq.gz
    ├── 0b7b651fa765d0d6b83d1a89a5175f7e14705820.nq.gz
    ├── 0b9137bdf60a74def663da7ef9a0047dc6b02952.nq.gz
    ├── 0d37bcf7a1b9ef88d3c5bec23d80096a6af0f6ef.nq.gz
    ├── 0ecf6ca58edb729284ca22a9c08172a675b12d30.nq.gz
    ├── 0ed421e66989b11aefca321dd8feba4633330ecc.nq.gz
    ├── 0eff0a430c1f60e5f15da0b31309c0c751713183.nq.gz
    ├── 0f0c82c1af82e7feeb6e096698b84edb279a7a62.nq.gz
    ├── 0f958aff32a8ff2afc4b3cf1a412f8d2c4836876.nq.gz
    ├── 0ff1bc7109797855f43ddc07cd7e4aeb04f072aa.nq.gz
    ├── 1044ae10d8c670ac33d756f03a9357f52692e432.nq.gz
    ├── 10c0d76e9371f005f20ec4e7e2a868ba8bd2913a.nq.gz
    ├── 115ef2f5c6ec5027a72993d04b3d913a69bdd567.nq.gz
    ├── 11c61d6de66571b7f5a3d4ff6e4deaf38128e149.nq.gz
    ├── 1297deb548640bbe938341d44231d32709b0acae.nq.gz
    ├── 13bfd66271e8065ce84ecf091cc3ee0496db4601.nq.gz
    ├── 13cc18fac9b89ed62b470f7acc5dc56a5cb7aee0.nq.gz
    ├── 1495b6dbd25ab2193f137d0ec07c9c412144043e.nq.gz
    ├── 14e7a5e2f82d58d45927f355a376362ee6c79d77.nq.gz
    ├── 15a96c17643d45735acf83559b7771a9223535a6.nq.gz
    ├── 164cc99a08f663a020bc7219ab4e5b815f0c31d6.nq.gz
    ├── 16d77fb8752aee2dba73f1bfe5209a197a06b057.nq.gz
    ├── 186a23013501724a030c8f7574b9764dbb9763d8.nq.gz
    ├── 18a938c43e196b2f6add8ee125a2c5c58b9b23a0.nq.gz
    ├── 198d22e005c4dfc509e2328d1f21bd61911136a9.nq.gz
    ├── 1cdea68a0665e85567b415f461443d779ed88ee2.nq.gz
    ├── 1d57d2e3ad03d9325927b61d649d876014ed0585.nq.gz
    ├── 1eefe69db4301ce5e4e2ff7de88e31ffb7ef5201.nq.gz
    ├── 1f173998c416cf3dcab96cca8a6ee0eba223d69c.nq.gz
    ├── 201cc9c8700241a4a56cf7f32a311c3073638e79.nq.gz
    ├── 202b2c3739401bd99dbd079a54bc8e398c5acf9a.nq.gz
    ├── 209651bfc467081aa1c71aad5e3bfd13f89259c8.nq.gz
    ├── 231e304663a5c3978c75ada757798bf6b8346f72.nq.gz
    ├── 23eb89bb0a553606fa0f02fd48770d3b06afc760.nq.gz
    ├── 241f7aabaecd28df60e5c55f231c17068cd681c4.nq.gz
    ├── 255ab77db30c20ccad66ba88625cc54bcb2b3571.nq.gz
    ├── 258e8224b228725dccf7963b2ab2fc5bfa45f48f.nq.gz
    ├── 25deef68677067b42084d88b47234f65c89f09bf.nq.gz
    ├── 268792f1b656e49901509a92eaffd10bd0aee577.nq.gz
    ├── 276561a35dce839f4ca9c9350dc7090b67950e7f.nq.gz
    ├── 296169c52c2acdaac768a65d65816de3d05e2706.nq.gz
    ├── 2aa90ba99994442553315bcfa76ccf576376d700.nq.gz
    ├── 2d0c630e0128e2ee1679da21d8770f0ddc470935.nq.gz
    ├── 2ee915c7a8b1abc83f8e9b71e96d99a3445eb687.nq.gz
    ├── 2f45bbfb8c0b3f5d552d60ad9f4725b71ebb945e.nq.gz
    ├── 3011de8bb15d364aeda74030e72468658e24d938.nq.gz
    ├── 303d6b183a1f8f5692b89d44daccd1995a3422f9.nq.gz
    ├── 3155cd0c763a45e13957b77204933111d6102f65.nq.gz
    ├── 31cd82bb1773b2deb24114ac1428785f2b433f08.nq.gz
    ├── 328718fa0a8d173619f52c3e5473780c8841a324.nq.gz
    ├── 32b5854449d73e06a93911461d071139acff23f2.nq.gz
    ├── 32c6ab4dc349170514577be4b6a44da0e11802be.nq.gz
    ├── 332f4283b96043de8cacc49916c81ceffc9e5326.nq.gz
    ├── 33665dcc48f2eab738f258570e2067851ed322cf.nq.gz
    ├── 384f9735b8ed77626a9139762b1519d9d881b5f1.nq.gz
    ├── 3878939748596a2265c16351364e6e5780bf9c46.nq.gz
    ├── 387bcc8851d583b7df07c5164c0f36e57a6f6e9b.nq.gz
    ├── 38ae8423736e59359e390ee7a52bb8f2e77cacb2.nq.gz
    ├── 3b951b37812b212b50ff7a6abbb417c18ab0b650.nq.gz
    ├── 3c3d8265bad2ab08c8286b3c65f6c06803911d4f.nq.gz
    ├── 3d7b07127b1b36d9decb79c4631d4f891b928dfe.nq.gz
    ├── 3d92e0d88ee5867b579d856350cc99937a724c0e.nq.gz
    ├── 3d99b13a5c869d84ee32270d761ec9684e9953d2.nq.gz
    ├── 3dc98ab928f778ac3a06204656c3b36f2f1f75fe.nq.gz
    ├── 3e97be9fe1ab357676de1d9f66df43d8a8c9069d.nq.gz
    ├── 3ea83fd61df248ae2521b29fb1b27141eee52ef4.nq.gz
    ├── 3fa8624137fbe39891b004078d23ce1d154b9d79.nq.gz
    ├── 411ac844bb0914b4032e8665cff4340111e91362.nq.gz
    ├── 418c9d881924d2ea6d47eb6a2390b4021fbb3b4d.nq.gz
    ├── 4696a7270e59a72e2d31a07d3deb83c40276d9e4.nq.gz
    ├── 475398244274c6fd0b907c7b2b286ab2a535a965.nq.gz
    ├── 488e6c28cee438e7602e841246547fe1f7de8a97.nq.gz
    ├── 48f0564f5793067c6b49e598f4beb290b434d2b9.nq.gz
    ├── 4925d807e69452e2b1a90cd79fd2f501d807a7f0.nq.gz
    ├── 4a7cb106475d32ce93750bf2fff600027aec5f09.nq.gz
    ├── 4b4c06767dfed9d254f728d463b4b63c42521c93.nq.gz
    ├── 4bbe464c90ab31093e9aeac98ca14f28e5efe3b4.nq.gz
    ├── 4c5c8f2e6cac500cf3270bbd0131cd104640667f.nq.gz
    ├── 4e211309c5bb28e346e1e49e3bdcea9e5e4c0e42.nq.gz
    ├── 4e2dcd597125f29a5a7e59e9214d6f797861ddcf.nq.gz
    ├── 502411f2be55099a5f93a93536777dd171292e04.nq.gz
    ├── 5026fd0894e9502265866f52892d85215c40d940.nq.gz
    ├── 50a7174293cc88a2c0f0a62350cd45470f6e71ce.nq.gz
    ├── 517f3e39b2ddf181d6cdd1e883124a71cdef8e2f.nq.gz
    ├── 55c14748455f6f993b9504525f03ed546159405d.nq.gz
    ├── 56661023f8459b3566cbb74b84a30b933972981f.nq.gz
    ├── 56bbbb9033fa692edad00d5b9d3e0d332d498533.nq.gz
    ├── 56d645f09ce59c73a10f643789b939fb0e4d13cc.nq.gz
    ├── 5739b8f3ba6326ba9539510aac754010cf3a50e2.nq.gz
    ├── 5743bcace7b90c02ab27f9d74a891e4b138c14c5.nq.gz
    ├── 58bfedf8143f9f26b8d42cef63648cefd0738ee2.nq.gz
    ├── 5aa199bcbcd79725278122e6f4a9277715365ace.nq.gz
    ├── 5ae875b90160dfb2b8b7ef6fe03248514d17ef03.nq.gz
    ├── 5bbb8ed52956241295328d29f881a7b4029e7290.nq.gz
    ├── 5c08066f7d42eae63feb38c9df91c16f3778951b.nq.gz
    ├── 5cab34c56c902ab38a51f08adf41f8e4c60a9254.nq.gz
    ├── 5cd7169e09d73fdd9bf772511385dfa988e2e3e6.nq.gz
    ├── 5cfa3b008e7604156336f774bf538fadd1b90a31.nq.gz
    ├── 5df443955d9913bdd5cc4a199a9bfebdd1c8ed6e.nq.gz
    ├── 5ec7ff6d0f409a7cb88d8d8759029821b5fe14e4.nq.gz
    ├── 5f8553a92e218ff81873e34fc8654f0a6b061ee6.nq.gz
    ├── 600106906a9d62b745944ac46b80294305af46b8.nq.gz
    ├── 600d8199e11422b6d1f2b71d0f13f5567f5dd5e1.nq.gz
    ├── 60ee68ce816089f798eee7d133df385ec793496e.nq.gz
    ├── 6473d81c877a28342d4a6eb589a1bb60ba2e71f5.nq.gz
    ├── 6b2746ba7880a4f5065efdc2d11494cf3bab8c4a.nq.gz
    ├── 6bdb9739cc5b9ff5bb80c3af1aa5e472a9b4c973.nq.gz
    ├── 6c9bc6113052fad7db2f43ad48dee79f58aca04d.nq.gz
    ├── 6cc799f18c8867cb1c01829ba298f00f599291f1.nq.gz
    ├── 6cdef2d1756ac863e163ff339c904bcb5e03a262.nq.gz
    ├── 6d519da7b3300105d1ab9c5871170f2f563813b4.nq.gz
    ├── 6f0bbc94ca8ee8f847e31993280aeb5a90c50616.nq.gz
    ├── 6fc7f90ffaac2dbc4f3d2dd678f0146e0f0f573d.nq.gz
    ├── 7147eeecee91cb60e800f2fcfe4d35b736bdb665.nq.gz
    ├── 71bc6e9c70dbc2d64002606e38fe62046b4c264a.nq.gz
    ├── 7498aa787b74a4e80c5b01696c6954de458f5812.nq.gz
    ├── 76693ecd3f4f8daacc6f6ec4067a4b4c4ea671d2.nq.gz
    ├── 783a65ccdbd8d97c83b2b44d8a0d04f8fa5ccee1.nq.gz
    ├── 79414655c6f1d5ff494c7c2c69e669a0fbd90196.nq.gz
    ├── 7ae58f68de4a495a3605d6b56387102573dd82d2.nq.gz
    ├── 7c46bf3f5f41a54c43f550086149e9e0d8dc14e3.nq.gz
    ├── 7c4761d14e85e451253d3dcb27d35daee044352c.nq.gz
    ├── 7cb4e03bed02f1f8f3ae219a87243c2081d98af7.nq.gz
    ├── 7ccbd3d40b6479904e8b590acb9d9e81c36984a6.nq.gz
    ├── 7d498b31e558ce2e250658fb2cb0453aca864129.nq.gz
    ├── 7d6c9732c260446b8a0c78c3c71e4b2241b5fe63.nq.gz
    ├── 7ec187797460585aa8a969a7f753c23c28513f2e.nq.gz
    ├── 7fe7d9228822f28758c346f4f9d05269d08c5eec.nq.gz
    ├── 81e5842ad2108b8279d38ca050df1759a47732fb.nq.gz
    ├── 829078cb0f9816e8e45de41d1ccc3dbaa7588edb.nq.gz
    ├── 83a442dff56787ad6798eaa3329ffdbeeb0b50f7.nq.gz
    ├── 848430f22ed687caf6d27d7d92020e2f71d0baab.nq.gz
    ├── 87b8515311568d3622053170462c3656db9a4d95.nq.gz
    ├── 8a8a2044d6e56169c7695317f6e301107fe8ea84.nq.gz
    ├── 8d10a1ad88b323c65ca20c7c555356030ffa7962.nq.gz
    ├── 8d479d1db66919b73c1251deb8fab22656dc7f32.nq.gz
    ├── 8ef83f9af139124dda1f3709222f73cc277c6ecc.nq.gz
    ├── 8f7e8dfc37d2b8723e17bb859aaa87e0ad04a3a2.nq.gz
    ├── 8ff97016fecd620cf056e3316a8d7b53152306e2.nq.gz
    ├── 9298c1f24908b14926a606489074b68f7cb85b58.nq.gz
    ├── 95aae72a992bbfd5f440130c06b2e64c66e557f4.nq.gz
    ├── 95abfd4a01207b4de65d757c9fc36a3332cc9b3c.nq.gz
    ├── 9751108c27b6895d5460babed267e0cfd9f36cb8.nq.gz
    ├── 97a158c8d3a0e3be6b5af10faf50286e4357b910.nq.gz
    ├── 97a92c06ae043538eb5e1ada7edf3f2ce9db70e6.nq.gz
    ├── 982226af7edcf58a61dcd04b4008ce61db705933.nq.gz
    ├── 98ff81f12de29533cd8e7024d4df5e2466f3c4aa.nq.gz
    ├── 994c2459ca1c7cc3527292c4d85507280db0afa0.nq.gz
    ├── 997357dddbb12e3ad3e3b98da416e46bc27c574b.nq.gz
    ├── 9b1c4c5272604f59ee7666dee304df68a2f12f39.nq.gz
    ├── 9b4027195666e1cdd41646e8a210ece3e6290d90.nq.gz
    ├── 9fb75eed6c57e26bd3952be9ccd640698f526452.nq.gz
    ├── a08f25e73c959bffe062687045eacdcc2d7b7828.nq.gz
    ├── a144e094585be28f6f4c7b025894769fbde3fa6d.nq.gz
    ├── a1c2e0a04e24d6237b8b4951b0eb73bfd3e7755e.nq.gz
    ├── a224aad47de2ec557991380716a41463381ba9d0.nq.gz
    ├── a2b29425a1369b91a3d82f5974b7ddd700609200.nq.gz
    ├── a36a5eb3f3b594f13b6a9a44b9494bd19f803626.nq.gz
    ├── a44dee64914f822d440813adf5d57c7b47786332.nq.gz
    ├── a5e09813e56317ea21fc975d768702f2ebed980a.nq.gz
    ├── a618f58b0c46d77e582755829bbcd275c599670d.nq.gz
    ├── a6d75b4fe2168985d1800de85d003f748b3e188f.nq.gz
    ├── a701b1b884f259388afae3b5a0ccabf71263152b.nq.gz
    ├── a7e1365de9e3438c1d8c7c430468e6b27fa86633.nq.gz
    ├── a853bf99f6c6bad7f24bea2802f370d4c1485471.nq.gz
    ├── ab2f9effaf7d924b6a644103e25f64fbfd8ba4fc.nq.gz
    ├── abfea6f4072ee64b0c5e0efac3dfa56220b4335a.nq.gz
    ├── ac64e2dbe6fc545aa970f70446d2f837e5bfd9bd.nq.gz
    ├── ac7b6bcf35e98139c791cb5c4b94f08849972d65.nq.gz
    ├── ac8f58759a201e96171455bd9e081e62fb96727b.nq.gz
    ├── afcd24d2ffb6c0625b5a312d7d5244c4133add44.nq.gz
    ├── b2c9e5be43f0a64bb0d73c62f8294f2f0d583e7a.nq.gz
    ├── b3953f43ea05d116def0a13ddd337510669da829.nq.gz
    ├── b61f70367475937d5e99da36ef70a9dd9fadbc16.nq.gz
    ├── b6c8e330cadfb48892346ce3ada22a39c579651f.nq.gz
    ├── b6d2024d4fd7154a91a1cc1471c0071281283cb9.nq.gz
    ├── b947a66add3967c2693d235e0127689fbc2b9081.nq.gz
    ├── b9a3d562edebe7d890b980eaf8664f092c18537c.nq.gz
    ├── b9e5e23678250b6c767da5755096150696529829.nq.gz
    ├── ba6bd820a3d3ded436863ec6649bc6d7e6af94da.nq.gz
    ├── baed8fe9795ed1e651d70b1e7633d33a4d38146c.nq.gz
    ├── bb728da1d757d00dccbea592f721ffa59f30a01d.nq.gz
    ├── bbccd9c86decc8d4f17c8bfd2fc6d7f1ea647c3a.nq.gz
    ├── bc6ec4f7a1e9b2c7068ebf2c9fc0efc380c7df77.nq.gz
    ├── bcf0fc180753ae3e4738224676c5f8d3d5110c55.nq.gz
    ├── bdd8015226f4186f238e60a67b76553cdb1a7b46.nq.gz
    ├── bf57fb8da869385826c9e799f282fdd0d2a18057.nq.gz
    ├── bfddc1c82a9aa8d017b2c988aa34755516be2863.nq.gz
    ├── c182a22f0482cb38bce0a7ce7c4777df513a0a1f.nq.gz
    └── c295d47f2fa530241a57d029871aef58ba4fb992.nq.gz

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

[python-semantic-release/python-semantic-release](https://github.com/python-semantic-release/python-semantic-release)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
