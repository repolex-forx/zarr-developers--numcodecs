# Repolex Knowledge Graph of zarr-developers/numcodecs

RDF knowledge graph data for [zarr-developers/numcodecs](https://github.com/zarr-developers/numcodecs), parsed by [repolex](https://repolex.ai).

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
rlex download zarr-developers/numcodecs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f83681cf310ac9aac8041ed6ff4a5dcc42a7aad
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f83681cf310ac9aac8041ed6ff4a5dcc42a7aad
│           └── chunk-001.nq.gz
└── blob
    ├── 01bad14a0483f2bbc1dda66476bb731cdbed319d.nq.gz
    ├── 027138833cce3b5e8687b8cc52267d7147c751f7.nq.gz
    ├── 02f3ac162903f7fac87e5b8fb2b7f0dd677239bb.nq.gz
    ├── 0349077763b00f795529619ee621306f34dddda8.nq.gz
    ├── 03e1f4d39bec6570e0beb80d49970c43ddbd8dfd.nq.gz
    ├── 06e15ea97a62992fa992fa8680487f5b6eeaa273.nq.gz
    ├── 06e42b719a5048bfc8eae85459bebcd740be5fe2.nq.gz
    ├── 06e63cb2495b346c5684493c5320a5b28e4e3ce3.nq.gz
    ├── 071e09db668029f60a5e81d51f8761d61aeb29d1.nq.gz
    ├── 07301d24fecb453fc9529ed6446cbf3d5c12dc9c.nq.gz
    ├── 075ad2ac80c31a85735a2de39c5b42b43c1a3fc2.nq.gz
    ├── 076ba5ad8944b3511d1ec4312e882d2705264dc3.nq.gz
    ├── 0787754df1494ad7cef9d36cb350a3890dc8834c.nq.gz
    ├── 080466849cf51d88d487f95bdcbb092aab077973.nq.gz
    ├── 0867acf3632f1c1a01699c5a627570a953d3c7b2.nq.gz
    ├── 09342088a80de049f0c148b06442ef45378665dc.nq.gz
    ├── 09ccfa92e192b7fba169f3e16ea063cfacca7f0b.nq.gz
    ├── 0ac19a7ea0a608f5ea0c9e418ef4c1b564c58041.nq.gz
    ├── 0b6f802032f53cbb99f4650252d44cb4823ec3a5.nq.gz
    ├── 0c338bad2c13f9c5b5f6feb26d9920b831c8a8b7.nq.gz
    ├── 0c423f2c4f2be0432a0638532efe23dc0ff6ba6c.nq.gz
    ├── 0ca9a6cd277fb5ab170bd3bbf50cf8e1433fbd78.nq.gz
    ├── 0cd25efd29a769b5b14b596b3233909dd38a1bb5.nq.gz
    ├── 0ce6032315cf1220062c60448889c7b97f2dbf68.nq.gz
    ├── 0cec36fb0330f334102fdd3aad68a71a8344d982.nq.gz
    ├── 0d171816197787e16b784253eb485b5651e6cdbf.nq.gz
    ├── 0d184d5e8a905db98665f49c50076992f0bfe7fc.nq.gz
    ├── 0d30cb6bb074146eb54af318b7fb5dd854f6149b.nq.gz
    ├── 0d4418352029f4dd0f6d8cd89c8caf505580d2c9.nq.gz
    ├── 0d5f2d74eeac102b55b20087f86fc33d54ee25c9.nq.gz
    ├── 0de76621bd50b3e0a4aced4ff2c7c8a671bf34bc.nq.gz
    ├── 0ec2791f60c886b0151dfb0cbdd0980dba9937ef.nq.gz
    ├── 0fa2dca1ecedf734b6b5457c84936c0c91283029.nq.gz
    ├── 10e10ea5506f9f2ab445c15a900a8077673a269e.nq.gz
    ├── 10fc09a5e77127d075792b2d190465719be74b58.nq.gz
    ├── 11a80d50d75596a043ac51b4407e2f990650b946.nq.gz
    ├── 1202b72aa290af3a270a60e01dd1aa9e1d0091ab.nq.gz
    ├── 1262a4e71eb2c9b3ad8107dac956a4fdf4f27792.nq.gz
    ├── 126361fbc7be08b5894d81c71bacc78bbcad2733.nq.gz
    ├── 12b5b0216b822fab269444b1f9550e8585373986.nq.gz
    ├── 12dc0c5a727c1dcd45a55c97ffe39f97c49e588b.nq.gz
    ├── 1367cf3c855be7dfc59883075a690e5d2e12c3dd.nq.gz
    ├── 1418a5fc0e94162273704eaa2e8d61040adccfe5.nq.gz
    ├── 142e64f30e6221ffc3f2921999fa17d8645e01a1.nq.gz
    ├── 16425c8f2a0ff7c104748bb2c32801d5e222c9da.nq.gz
    ├── 16e9543ddbfb7495ad15ce2da87942019952a65f.nq.gz
    ├── 1708f43cb26b437cd56dd557ed36096bb3ab0c21.nq.gz
    ├── 18612d90a0fd84334836d8ef64adca0cf27a2473.nq.gz
    ├── 186b7c84aad12d82e58dac458a1cab73f28b380a.nq.gz
    ├── 1941fee3fedefb7abc37d4ae17cbdbdff3a8f367.nq.gz
    ├── 1a59a9e86b37f7110688bbc0d7d87a0c702e56e3.nq.gz
    ├── 1a80b0e20c74d19131ba8115379f3a39070ac956.nq.gz
    ├── 1ad2e8d758ed2291cfd717e0feeab192db8b7152.nq.gz
    ├── 1b1b1be37b77f80cb77ef572e5e7466594547517.nq.gz
    ├── 1b43f182a22174d068149d3071df07e56cd13c4a.nq.gz
    ├── 1bf53cec8cf487764de8bb04a86c3251959a0194.nq.gz
    ├── 1c14b40c4151621e86487041a34bf86c173c39b8.nq.gz
    ├── 1d69698bf9f578c1ed50be556b12dfbf0caa77a2.nq.gz
    ├── 1d8a19c3c85b5fe9b243352e70f10cbc506ced8d.nq.gz
    ├── 1da97011f01e3a9367137a4212027e364e573841.nq.gz
    ├── 1ef844085524a1aad6de411da8f641cf255d5bfe.nq.gz
    ├── 1f7bdf173b11e07d3f283719d559ad2facf10c89.nq.gz
    ├── 20a67f203b687684e70eee1afaadf3558ab702af.nq.gz
    ├── 20b3e268cc838a5f659bc5df90fb83ae48504536.nq.gz
    ├── 20c6d5bdc81142f3653cae6df6d536d077232e00.nq.gz
    ├── 20cc87f445dc8b43d2d680b3df8c5c3ee8f70af1.nq.gz
    ├── 20db21f2aadb1863a7e26fde574958789155fc4d.nq.gz
    ├── 20e01858dd6d03bf95c272ce86077c84b74ce6b4.nq.gz
    ├── 22c72613ecc610c5ae1742a7892939bc3172479f.nq.gz
    ├── 235b73b5f047aad17438b5d8d8ed583414927677.nq.gz
    ├── 236d52dec94da5ca72b9622654faa45aae69dc0a.nq.gz
    ├── 24b6523c75fe27608715cf8fca4497254e975fdb.nq.gz
    ├── 24d9ed0bcd8b1202998273acc1a95d040abd5f4e.nq.gz
    ├── 25098366d6c32b194babc80991dc1a5fab743cdb.nq.gz
    ├── 2511afd17080056cc22ae76ce808132f502337d4.nq.gz
    ├── 2570617249697ee5373a1e1a59b64c3fd2af4120.nq.gz
    ├── 25768701f074a9ec848feaafa7ad87595e04c5a0.nq.gz
    ├── 261196706c39daa77a2cd12f597c1b97c3a2ca42.nq.gz
    ├── 265a8af3674b72626a46b3668ad0caeef58cf3a3.nq.gz
    ├── 26ff1a23fa6a7112368d424e9f57f100a5c51710.nq.gz
    ├── 27aa7746058ae732c9aa2ddd5f6ad31c9c8cb287.nq.gz
    ├── 27f8d865ee2956d654800501d89df3b1357b40b8.nq.gz
    ├── 29ae401914d1ffa49a4231097a89c0d949cf28c8.nq.gz
    ├── 29d2b7a9bbbc5ede1883712926a31a65d6047c48.nq.gz
    ├── 29ec33097c499597662777e8f486ced87bc7cc63.nq.gz
    ├── 2a6aa429eeebcf36636ea73589e9d311e415ce2e.nq.gz
    ├── 2aaf510e9b17c0251a0bc07ed4c85277e4a3d05c.nq.gz
    ├── 2b4f95f640452cc4219d5520d4afde1b473faba6.nq.gz
    ├── 2bce9a0608401963d2da3f4c7d0a7db32b7a876a.nq.gz
    ├── 2c14f66510c75eeb68526722625187afce7f1342.nq.gz
    ├── 2c2a0cd302d45ef8ad9474deca2507e1bb35736e.nq.gz
    ├── 2cc0ab31da92ad4a83d0420ec968ed029de379fb.nq.gz
    ├── 2d2a834d65ef159cd821e8bdc56569179379109f.nq.gz
    ├── 2d2ff3f934d69c0b8d76a6783c33f4b327ca5cd5.nq.gz
    ├── 2d349cd89affb56cbebe14df4383db182b3d7269.nq.gz
    ├── 2d5b8cb1fe2fc242b931b31903cdf6c5dcde9724.nq.gz
    ├── 2d60358d8f68b2748c296e7caec6bcc7269ac572.nq.gz
    ├── 2ef0141f028af2c086f1d1e1bcdfa5523fac5ee3.nq.gz
    ├── 30330b6bab476caf01619d198b2d76a5536eceda.nq.gz
    ├── 30494cdf4cb880eb6f91de9b10d3710e03ddf0f8.nq.gz
    ├── 31d1e097dad844fda8967e9f504ba1337e47ed77.nq.gz
    ├── 32c5165dcf2ecea5f08a94b653375b3b77214170.nq.gz
    ├── 337b6ec8d91052b8e508524d7e3964e9eaf50984.nq.gz
    ├── 3389af56a03396f2f3d476da6d310bf5c77a69da.nq.gz
    ├── 344c482caa9fd556e29189521676bf5b2e85a52a.nq.gz
    ├── 3498aaad4051dc445d6e66d8dda4d9df114038bd.nq.gz
    ├── 34d3a1c4106c51842c0ffae5e19c343517dadc90.nq.gz
    ├── 34db54e5f89cbb662d65f5f9443edb6b797fb0e1.nq.gz
    ├── 35abfff29727ea8961d87539d590df43813adf9c.nq.gz
    ├── 361cd900e0269e6bcc00e1c1e5dda144f8e5c9eb.nq.gz
    ├── 36a7b093c5e8bf1b696a41facdfc22ccbe244264.nq.gz
    ├── 395fb7d8550b0cc21fbbc7d0846553996c0ae656.nq.gz
    ├── 398335c3eef3589b17491150f40d125464b5fbeb.nq.gz
    ├── 39ed76b129d57e8bc095cbb03989f1982342ddf4.nq.gz
    ├── 3a7462d9e6ed1f7d1144baf219c10bacfb94c0d4.nq.gz
    ├── 3aae65e25e1b92fc34b6e5a16e15fcf3d07f5308.nq.gz
    ├── 3b452c67a58d450d41f2440b7bad1ff77d95315c.nq.gz
    ├── 3c2269f193adb66ac911f24a4b051aee34101f46.nq.gz
    ├── 3c228e8f651670c4f9feb87b88ab844aecd56c1b.nq.gz
    ├── 3c692161db251affb707096e81a61d0b39c05dff.nq.gz
    ├── 3d832be38fb53a2fcb9b1eb95cbf5aa1f10fb8ed.nq.gz
    ├── 3d99a6c8ee2df75e41f7e1563461d957e4045d24.nq.gz
    ├── 3da194d697c5074b53b0fc55f69ad7bdc45cb2de.nq.gz
    ├── 3e5fca82f7f7f9300542e7008e82db91c42a53f8.nq.gz
    ├── 3e611ebf7b25ff6c36bccd1b6bb3cb7b730d8775.nq.gz
    ├── 3e7715bfdb46a507f7f7f6aa3e40ad174cb0eb2e.nq.gz
    ├── 3ed4e54ead73318ef60080ec51b8c9326c219168.nq.gz
    ├── 40627db8b6ae5b834725fac73f80bc9698e0d4e4.nq.gz
    ├── 41d6749cea2d79b0e1aa87b1050e8f3a20a11e53.nq.gz
    ├── 4269bad93c8e346c03b056e19ef3b0de8a8cb6e3.nq.gz
    ├── 427c3e153266f140ded64865d9947128385e8e58.nq.gz
    ├── 4396fadaed61acde91b170f6237fc004db6766d3.nq.gz
    ├── 443547c75b67fb0c8f01140d83487e34431a6abd.nq.gz
    ├── 448784b12c5d3d4ceac75250127f61a93bce8eea.nq.gz
    ├── 44eedcce3e577a4a40a1564b0d5c01d6f2ee4a9a.nq.gz
    ├── 47235a0983088eb3832415cb20357b7b24b6c293.nq.gz
    ├── 4730037e1200a9f9fd769fa18138c588801870eb.nq.gz
    ├── 475dc53e73cd152d1b5327c7e4b17cca78ea753e.nq.gz
    ├── 476e7fdd3e6c61e38641f53ac94513ffa2f32eb8.nq.gz
    ├── 495deaee0fb3e78ddfa8e7a08bcc62d4a312e5a5.nq.gz
    ├── 4b5acf93f55d2f7470a3e790b8c371df5a40bac9.nq.gz
    ├── 4c2d7e2d95b6dde57b2aae6f4f92eeb051429887.nq.gz
    ├── 4ca3560d268ef0ab7bb54eeb73099dbec623a17a.nq.gz
    ├── 4cab838d1b15c56a79a6614b351c4b5a4e4c8c27.nq.gz
    ├── 4cb2e5dabc1612fbb72cecd583f496f2f86d2555.nq.gz
    ├── 4d89981b9750c6a0069011dba3962af32949bd54.nq.gz
    ├── 4dd5847e3670621651efedefff506495829bd9ea.nq.gz
    ├── 4e7e6bc43f54e3c6597e8c9eb38cd21af5323261.nq.gz
    ├── 4fe066812c0fb6f0cdec69dfc57116f62a082699.nq.gz
    ├── 503a429ec4329a08bc8eee509f028f12e9c33ec9.nq.gz
    ├── 50b19e012e281d9ac231576f3cd304682ba9cf24.nq.gz
    ├── 50c8fab8f25665db633c0949f0aac209f93e5738.nq.gz
    ├── 50e2c45f3964a55cfdd1aaf3d89ca2b967234630.nq.gz
    ├── 51b7acb693d76821b5c9682b1eba2e9890a8c026.nq.gz
    ├── 51bbbdb7d6fcf661ca7bdc4e3a65daeae904711b.nq.gz
    ├── 5206930ab0d71b45fe0d4e6192b835f4ff9dfeda.nq.gz
    ├── 521546c6fe6fef7fe1f475e3c43d0e863972623c.nq.gz
    ├── 521d193eed861d9c14dd22b1321502fc8e5ca8d7.nq.gz
    ├── 52b027d6119b6e7a75eb11931f617a08278233d0.nq.gz
    ├── 530f6ef9ac9f441d7da6e955cef6e1fa677c536f.nq.gz
    ├── 531d801cf695df50ccc1d9de93afe1a5d8099f17.nq.gz
    ├── 5356b9dc8c678a0b977da4f608dfe755667c17d7.nq.gz
    ├── 5499dd7c9e51576622f55392d0ab5a45ec435ada.nq.gz
    ├── 54bcd10dd5f5c35a718d5c36c9a62760a9be0038.nq.gz
    ├── 550b4aeebe86121a628fff48ab54045674c8f8d4.nq.gz
    ├── 57872d90ef884a1071a160c6e853a102a1ebe0bc.nq.gz
    ├── 57e198b0d18fd6df4d4799601ac77b5632f57b02.nq.gz
    ├── 5807ccf9a23acc13875baa303dd272315c1a1a86.nq.gz
    ├── 58e06f22cbca4153aedb7cda46b1ca765c313a50.nq.gz
    ├── 593e37366c8b57b51222f934fcf441d84fe2707e.nq.gz
    ├── 598368aa15fda15ada2ad03fd017c638c9e4cfbe.nq.gz
    ├── 59af9fe7a67121ffce1f8172eacd88fc7b4ed964.nq.gz
    ├── 5a396288bfcfb5375aa116be79900ddcf281e6cc.nq.gz
    ├── 5bc6fd5357b92473560329c0d035ffda234d2c38.nq.gz
    ├── 5d07e40791aae2b295fda589da2b9fc13e836c7f.nq.gz
    ├── 5f364788b82409516faa92762d48f642750c36f4.nq.gz
    ├── 6103af330bc7a70ee125c7d01e473a05ed36af85.nq.gz
    ├── 61ed9e6ec029b556c3c063826ddd452770d4a064.nq.gz
    ├── 62c22b6812d7ef4901fa8a1604904eb96b332d99.nq.gz
    ├── 6301a701e692097859e1b07359abc51b8c3412f7.nq.gz
    ├── 6346cf116aafb5968cea0a4cb476bdfbfd0eeb1a.nq.gz
    ├── 63969c51a5ef2ae61d033ce5408bf0fae2a836ba.nq.gz
    ├── 64293c71fc3188f79eff78ef5a8c945d04461e24.nq.gz
    ├── 644def39cad62808ed21a33fdb0fda06adb082a5.nq.gz
    ├── 64638bfec9a03447048ec969d6c133bf8dd07006.nq.gz
    ├── 65092ded18b6ef6f9c153f7c5ac13ca097683f82.nq.gz
    ├── 658ab67603230fce2dbe9e332fc223fad3348ade.nq.gz
    ├── 667beb5abf390bef6aeed420e4306fa475a02f61.nq.gz
    ├── 67081a1f6d161327d4aa22fcc9abd232b8ba9875.nq.gz
    ├── 67160b2d1c79a2f1d3b3190418ac07015db73e32.nq.gz
    ├── 6721a9246c50e55007be139499f3dc2b81c557e0.nq.gz
    ├── 67a6890927c038a23cf097de193b8d5022d5beb4.nq.gz
    ├── 6865df09ebc3d98ad5182255d3564d89c76ef232.nq.gz
    ├── 68870a4963fdad126da57e0acccb4409082fcb38.nq.gz
    ├── 6913bc0f6e89623129be1bd1fe98be416536d721.nq.gz
    ├── 6916e32ca1efe233eb073267c17c1ebe080183a8.nq.gz
    ├── 69a99f9a4d6b9f18862c9cb1b44b9264d21656a8.nq.gz
    └── 69e86715252583cf552005ec5f82e5a1def3c357.nq.gz

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

[zarr-developers/numcodecs](https://github.com/zarr-developers/numcodecs)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
