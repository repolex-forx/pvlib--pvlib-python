# Repolex Knowledge Graph of pvlib/pvlib-python

RDF knowledge graph data for [pvlib/pvlib-python](https://github.com/pvlib/pvlib-python), parsed by [repolex](https://repolex.ai).

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
rlex download pvlib/pvlib-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 49530b4dc49bdf401e198ba99218802b2f85df44
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 49530b4dc49bdf401e198ba99218802b2f85df44
│           └── chunk-001.nq.gz
└── blob
    ├── 004e0d6c5017b0dc473461360020aa18504dd3db.nq.gz
    ├── 006cb284b20637b96e162d91fbed0570364455c7.nq.gz
    ├── 0088ade1b8f76e962d9899a33ccf8089df683cb2.nq.gz
    ├── 00daed3a0f4c5c006dd53f2ab5e683e667247495.nq.gz
    ├── 00e117b86bdc23675c1e9643ac29254a5e16cef2.nq.gz
    ├── 01612b2fad5f8323f995b67ee7e9f5db21201fc8.nq.gz
    ├── 01c87c180ab6ebcd38bf69c8ea0b70bed6af59dd.nq.gz
    ├── 0258b3975cfe4d467cddb8ac06feb715eecf154a.nq.gz
    ├── 0287fd8fd2c95bd8c905ef46a12f164c5cfc57fb.nq.gz
    ├── 02ffe7042f819c347447cb86fc3dac2b8a13fce4.nq.gz
    ├── 03e10d4c9434700bde3681c897ec0c9f81824962.nq.gz
    ├── 05b06587a85f0c5eb9adc951b06370e3afd7c751.nq.gz
    ├── 05f7d72b2ca79ddc7acfc520c63d5f3eccb08605.nq.gz
    ├── 05fcbf12a3a0b8ec0e85279281d37d3f1be2a850.nq.gz
    ├── 066b2d920a28db73b4ba3a0b35e6905eeeef5772.nq.gz
    ├── 071d9e4d2c41e1a3eaf19a28823d7b6c96a1e6a7.nq.gz
    ├── 077cdb16ee79c6ba5221607bb28831dfc014c8e2.nq.gz
    ├── 079dad2091d290b6ad895f1c633f37900ab5bdfe.nq.gz
    ├── 095006018b866f935651b9016bbc5d6d5982da25.nq.gz
    ├── 099fffefe5e5c6805f0b94754fbfa5de4f6d933b.nq.gz
    ├── 09f142d3d02e7d801812f38b648d602e10866693.nq.gz
    ├── 0a6c56de14f41e7982523e44dad02f55df1c55dd.nq.gz
    ├── 0a921aaf79f5876dc997f2332ba52516241b2b1d.nq.gz
    ├── 0ade84c4d3d1d160ea70aa36aaebae5cb47ba8f6.nq.gz
    ├── 0ae5fe2b9a2aa0628dc55e6c06ab3141af458558.nq.gz
    ├── 0bba4c69d1d7efb5673e07e3d0c32af48d8da67c.nq.gz
    ├── 0ccb379d8c43827c2d74a2b4defe583530316ea7.nq.gz
    ├── 0db64aa0465503bce20ccd1f1df769afc14974ab.nq.gz
    ├── 0e49b32911a17bcf2e5db0fb806f0753324b2c19.nq.gz
    ├── 0ec63fbc56cafa7ff391b0c4232dc75e1ae7197a.nq.gz
    ├── 10b589b1b1fd121446c738053aa486babd4d0678.nq.gz
    ├── 10b89eaaeac20ea5f97c88e5523ab854c838cdd7.nq.gz
    ├── 1113abb3f43d43dcf256d3059a8135dc52b25293.nq.gz
    ├── 11718c37a42ef3e7e6ee9be704640a6ee3b84861.nq.gz
    ├── 14fd32a638e3fd9522c11a3e38bfc2d5e5f8f0be.nq.gz
    ├── 15964aa6ce9a70ec2f55156c4637ff46182e8506.nq.gz
    ├── 1647fc79a79aa1a1c56ef9ec690443ef11247368.nq.gz
    ├── 16b801b3c6912218742810ad878a2452e2165c9b.nq.gz
    ├── 1734398c47755a38f545609c0288dd9ebee965b5.nq.gz
    ├── 1738ce09f818765b3a293706e8a23f8dd26c6761.nq.gz
    ├── 18570b9c6d93e92002861081ea09edd5cbc59f49.nq.gz
    ├── 19b9117bc7d224fda737d8204a8653fb044bb04b.nq.gz
    ├── 1aac0651d335ed658eb2708eaf10351a2c8b94a8.nq.gz
    ├── 1bd2ecc9960657d16e2c70608293b775a84a6dfa.nq.gz
    ├── 1c29b82ead93a578e4a841353c4ef80f03a4506e.nq.gz
    ├── 1c52f32d01c9a0358f54e17e98898ae93d16e48d.nq.gz
    ├── 1c5a8ab3e24c8e842b29e6c97b97c0eb77136e54.nq.gz
    ├── 1cd6c57325e50d0137455db8a58a00647d142abc.nq.gz
    ├── 1cea3732add75ef9f76d27e8840456f3ecf90c72.nq.gz
    ├── 1d9db70369dabaeda8861bd9e905c93adf51c475.nq.gz
    ├── 1e551c83fa83c3c6b2724659eab7ba21b90f1227.nq.gz
    ├── 1e737b0d279fa30e009617782e6a33a200594830.nq.gz
    ├── 1ebf3a73b5490111fc36a700dd6a170b8c8fd48e.nq.gz
    ├── 1ff5fa1df4313237ef0496ab2a8b565dd9200a9b.nq.gz
    ├── 20e776bf2f7ee7a8580a8987ae73a219141f1874.nq.gz
    ├── 20fe093d177cfb27b4f85da989f0ad72ed615b3d.nq.gz
    ├── 213b0c6870e36e7fdbb90046596004c5342979ac.nq.gz
    ├── 236e91e390626a01f21730df5d892157a178b45b.nq.gz
    ├── 23989ecb2ec038670df7a138c86e08aab60c8f58.nq.gz
    ├── 25023dcaee8b1b317c41708d60a28e40788f5cba.nq.gz
    ├── 251d8b5eb8a0d0b8a6d0078eec35be7f683a544f.nq.gz
    ├── 256a93b99f015242944f92d5d7105064c81bd3f4.nq.gz
    ├── 26edcd1bb1e661d135ff04dbe175402dec519751.nq.gz
    ├── 281f0954b5f34f7df828003a957587f8241bd254.nq.gz
    ├── 282a8dee43766205696e1d8ef7910a9edc861825.nq.gz
    ├── 2885bc1f6e1090d489a596d4fbe7334b3e4d0ad0.nq.gz
    ├── 28b06110c210a4d2afe963e44a129da38a151c8a.nq.gz
    ├── 28b4630b01f60441def0369dafef7b4189fe8b28.nq.gz
    ├── 28d20ffc2d556c5e7e05fde77d9c221ea1dc26af.nq.gz
    ├── 292123321251d214bdc8142f0fdf4715a33f1963.nq.gz
    ├── 29f5ac4c6ebab2efb551fa9dcaadd8d3d73ba58d.nq.gz
    ├── 2a0f98c655ddba9718fa83521fd774458eb159a0.nq.gz
    ├── 2a1793633b1c4d7e765e494a793ba9e21f17c8ad.nq.gz
    ├── 2a6150559b594457412c07f68a6aa994fdaebc99.nq.gz
    ├── 2b8034387df28e1ef041bf299ea94fa8dbaefe93.nq.gz
    ├── 2bb8b9876bcbb4bc9cc651df9e8c4eb7a2466ea2.nq.gz
    ├── 2bc8363674681724f2df370e6ab564be375d9a40.nq.gz
    ├── 2c1569c57b48d3b097e6824120b2899973b075a6.nq.gz
    ├── 2c7124bbf18e6d86727d00bdf54def3585898ef5.nq.gz
    ├── 2d0b94547f454d6fd5fb59c2654c62335f0c5b38.nq.gz
    ├── 2dca47ef3d5a0e477b011baedd9f72e628098a0b.nq.gz
    ├── 2e15b4cafb039b5e284ea9690caff828cdbebe77.nq.gz
    ├── 2e88590ddd58e6f830deda109d62786e1476ccf7.nq.gz
    ├── 2f5728b11f13c7765ef259c1fb7389a828a7c1fe.nq.gz
    ├── 2ffe572dcec693d236ee853dd22e52a6a34e69dc.nq.gz
    ├── 3097164604142dbbfa61a660ec3893ba819d5e0b.nq.gz
    ├── 309cc42799555165aecc6f6e8e735dfc9046a242.nq.gz
    ├── 30b16e43d3c3f4796a9e30e4fe25e4653ad97d36.nq.gz
    ├── 31263c8a25e8ee201e207fa313baea4b6bb461eb.nq.gz
    ├── 31c76521cf7509868658c6962b252106bb00d196.nq.gz
    ├── 31e80bd9a2f9bbcea6d951a498023d716960087a.nq.gz
    ├── 322374a9f7c1275bb2cddc386d69e75a9678b038.nq.gz
    ├── 32af129fd7bac065886a72d54fcf6cf353774dd6.nq.gz
    ├── 32b0d53f6e90727c1892fad4b144c8ddeda44156.nq.gz
    ├── 32b4a70e53a783a697772013fe622ba4baad7d08.nq.gz
    ├── 32d820faaee9ddb5aae910e38c86333462b0f68a.nq.gz
    ├── 332e49d65e2be08810b5eb0a366d67aefca4494f.nq.gz
    ├── 34aa38ad0cc0467b22f07f4953bcda3094df674b.nq.gz
    ├── 34f1ad3a5c53739cf45eda0c1841a6192b931557.nq.gz
    ├── 350ed8ed415ec7ebf40a7056c7556f1df43df2ce.nq.gz
    ├── 3608d43344f08caa834084be479229ae31973efd.nq.gz
    ├── 36db1b3b909e83df353dbb52f7229eefaabd8570.nq.gz
    ├── 375c7ed3e8ead1cd1a7df891d91e8194c0e034e1.nq.gz
    ├── 380744f626583f0ad6d0a6ddc004558f8e0380aa.nq.gz
    ├── 38496b88d11fff422dd28269f32ddfebf671b1a9.nq.gz
    ├── 385fe8dcbb9bb301a0f68b570bb31a6ab12ca8d1.nq.gz
    ├── 387ef026f218fd0a2e56614d6b59b654a7aa3f17.nq.gz
    ├── 38bf122b9105a31ca63d8aa0e5cb8a5c79e27173.nq.gz
    ├── 391558591fa557903c221ae9526999041ef058b0.nq.gz
    ├── 3936e3c1ce7d068c6177af833472698e85e7997a.nq.gz
    ├── 3941672c8ffc033bb33f179b49710e891c0707a2.nq.gz
    ├── 395678d49c25351537ee04315373d671639dfa17.nq.gz
    ├── 3b62d9463f07c1bc8c86cd8e3d1d8630a6b3f6aa.nq.gz
    ├── 3b6c564f6f08adeace340e8936428bd7b116ffd4.nq.gz
    ├── 3b8f29d0b2a3de8a4ca5642aa2a694a0416b7dd0.nq.gz
    ├── 3e6e56b817e52cc5d62e2a5ffe9af12467245c84.nq.gz
    ├── 3eab4f17f3d34e4232d0a9adaabe8efe537cba9d.nq.gz
    ├── 40680f24b2daa90b84b056ee654b45db55fe8ff8.nq.gz
    ├── 41d515b8561ce86c5b5dfdf9be594581f5c5756b.nq.gz
    ├── 41df67ac85f441533ffc9cea68503ceec52f8def.nq.gz
    ├── 42d709c8085051034e4a052462992018c930cfdd.nq.gz
    ├── 4441ed01f129e89e268604427408650aec031baa.nq.gz
    ├── 44ae3517cde465caece9f9a7d4b19a853d85904c.nq.gz
    ├── 451ef585617e5a20d3200d02c1f01680a86d2894.nq.gz
    ├── 47409e9dfbb416506c4db27aa572727fae19b031.nq.gz
    ├── 47fa9b464847c9bcd45fa99dffc43cc8f0d03918.nq.gz
    ├── 48f455f38da71bba0f4a5d292271b4be42783580.nq.gz
    ├── 4a28b03cb6323da18d5aa295d55cdd8101fa0712.nq.gz
    ├── 4a9c63ebcd8f9b3bad12c6f5f3361f0378eb6735.nq.gz
    ├── 4ac113dbf8bb1226169195398efcb8c1ec2883a4.nq.gz
    ├── 4b3cf3bc9d06767a181ba06d6559389ba9f84b36.nq.gz
    ├── 4b733ad711b558825e020947592c28abfa86a5a3.nq.gz
    ├── 4c0c7c596b3f887e3a55387db38e7fec908b5e44.nq.gz
    ├── 4c6f0febf3986b1c8a2ecab9611308e0b7430642.nq.gz
    ├── 4d7c4b1a507c0950d289edb4b4eda0ae13d8c7bb.nq.gz
    ├── 4df1dbbeb40b61f70ccb5d8d6678cf5525d6e285.nq.gz
    ├── 4e85ffa3de02c7dfeb0a4cf13be52d646da2a2e4.nq.gz
    ├── 4f7d62cb80f978f951a1189390d0d9d0a6900d44.nq.gz
    ├── 5177a66ac8bbaf5ad24e60975a9a3fde1d9e9719.nq.gz
    ├── 51d06dbf9d31a93f07631ec36e03577f4cc62ed7.nq.gz
    ├── 5215ba81b78eb6e50cfb7fcbc711f98b6e26a0e1.nq.gz
    ├── 53acc1c723396fff5beb0fd51de6628371e7e375.nq.gz
    ├── 53e75cadc1022e005fbf90457ced168efc655fe1.nq.gz
    ├── 54216a7ab0d30d1ca076f0f3a2f8b3c1b7a018c6.nq.gz
    ├── 55222c0fb13c0486453a51fdad34cd7b345fac30.nq.gz
    ├── 555f7d31c0377c72e211fc4e762dd27c5420f014.nq.gz
    ├── 55c9d6440e7f233b62a604b12125888772e6ea25.nq.gz
    ├── 55e1d40e3666d34ff967c154b8c8673a0fa47eb2.nq.gz
    ├── 56c0cfccd835e9dae925dbe6f92cd3edda73a2a3.nq.gz
    ├── 573a68f7a24904f2a3bd2e80bb7dd819c7492455.nq.gz
    ├── 57918da3b568870ba480d436c2200beeaddaa581.nq.gz
    ├── 5794669ec996a3aaf6ce798fccbfe8d16ee8e6eb.nq.gz
    ├── 57ce12584645acdb889ab18bc6022eaaa422e4ea.nq.gz
    ├── 5804459549ad304664f7103416583ad0cb56ac86.nq.gz
    ├── 5845691d3432fccd58107e1f4cf7309d4574edd2.nq.gz
    ├── 58c5dabcab377aca6970f83a88063b6facebdb60.nq.gz
    ├── 59ce66b2692c2523c5f381c713163b00c3498228.nq.gz
    ├── 5a4546baae0f3d72bb7514e617c06743a769d0f1.nq.gz
    ├── 5b292b9f2c3d7fc23a29b5468a4afda20f649d35.nq.gz
    ├── 5cd2f5cb410777f93900a5aa18dbb6c5e4391fb5.nq.gz
    ├── 5d4c277eb1f6c23e26dd418c9aea29398a44013a.nq.gz
    ├── 5e4c35258a144b7016284eb38949006896d4f293.nq.gz
    ├── 5e9b09f25fd9e4b15625b8a6bc8740304dd3d06d.nq.gz
    ├── 5ebda621b6d594d4df7434cf78ce67793dbc721d.nq.gz
    ├── 5eeb27ca362ebb384d9c9c70a78af7ff770287ac.nq.gz
    ├── 5f9c7103b723d36c1cf0a34f7c4e58e2d05f2814.nq.gz
    ├── 60ca0f2f2c18bf4c0d3e801835ede28991c193c0.nq.gz
    ├── 60d1a5e8bac1a2c2711dda69f832368f6e7fb732.nq.gz
    ├── 61f3eff6956b4fd7c206f42b00c5d3af51ff5006.nq.gz
    ├── 622fb9b9584c72e51432b1e7284bee821c8a8f66.nq.gz
    ├── 6236fe5ab0767fe560f7840867c42275ecb4522e.nq.gz
    ├── 630da2cff1515915aedca6747d6bfc7bcd9d335d.nq.gz
    ├── 6326129a5116993807f2e93c880028a9ec16dac6.nq.gz
    ├── 634438018f5c7a02d39e9849af0c6e4895b8a7cf.nq.gz
    ├── 634af079330a81b3bf3e1468bf28c57af670fc8f.nq.gz
    ├── 6565679f6d5fb445e2e0b3b1f31ca24fad3bc525.nq.gz
    ├── 6577f8e0cb855c5b8a4dd038072750edfcdf27a3.nq.gz
    ├── 65f43597ed166690fe8a4ee00812bd9870161660.nq.gz
    ├── 66109676b9a634e3ce0490ca38ebe8f95d080c48.nq.gz
    ├── 66456484370f09516232022c484335a960b931d2.nq.gz
    ├── 6897f12283f7da69ebcabec72fc85fc931214003.nq.gz
    ├── 693d9f6bffd15d648c45780dbae2b04fbccc2a95.nq.gz
    ├── 69a9c28d4d8ce76b9097ac7f0dc963e6ebd36fc0.nq.gz
    ├── 69c0079a20e620e81f9919dc37a82d6e1e2bd1fd.nq.gz
    ├── 6b0ec78ab3ae18e3be86945a1caf9bf70e12268c.nq.gz
    ├── 6b5b6208e34072a330bedc436b98de5e7c7a7f93.nq.gz
    ├── 6b5f3568362a56455bd8b8c3081c3365b9c4adac.nq.gz
    ├── 6ce74bc0144f2a971f6734086759bfb5b6f504a3.nq.gz
    ├── 6e0703be285d67ac5c2a3a89a3028d165d58a377.nq.gz
    ├── 6e4ac8e0ca5271727ed1186916545982b0ab0384.nq.gz
    ├── 6ea6545572ce139419d4f8670b71b4fbe6736484.nq.gz
    ├── 6f73de334f0ed308b75305a622a6763dc5390526.nq.gz
    ├── 6feb84423a2672afd750c374fc730cfd3e66b5b3.nq.gz
    ├── 710bf15d51bbad5b3c01953ad911164caada8fc1.nq.gz
    ├── 71a515ab03c80f307fe571cb91fe1543b700c179.nq.gz
    ├── 71c4f2345ebeb52fef960564eb617913ed58d8d3.nq.gz
    ├── 71dd1d35425bd97eb09855b8cb53ebfc26da6bda.nq.gz
    └── 7206740e575bfaa742cf9c90be207f21afd23368.nq.gz

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

[pvlib/pvlib-python](https://github.com/pvlib/pvlib-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
