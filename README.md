# Repolex Knowledge Graph of singingwolfboy/flask-dance

RDF knowledge graph data for [singingwolfboy/flask-dance](https://github.com/singingwolfboy/flask-dance), parsed by [repolex](https://repolex.ai).

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
rlex download singingwolfboy/flask-dance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 70f79fd9b633cea7b9742219888fac08069edc22
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 70f79fd9b633cea7b9742219888fac08069edc22
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ae7e7abd2a6da9aa516baa6d082b3373951901.nq.gz
│   ├── 03c78a60dad5a72f0ed8268f62b8b83754e1853b.nq.gz
│   ├── 0466be0cf19850530cba4852981eede0b47e9b26.nq.gz
│   ├── 07ab7fde1128121e73867d01439a8433057c6bb1.nq.gz
│   ├── 0926d583420da221fa48f14f3d2f382791853b76.nq.gz
│   ├── 09f29e1f3afdf15fda70bee2eb1421608279e23e.nq.gz
│   ├── 0a6dea9130027c68aaf2f7c12d6cb403d8ab5693.nq.gz
│   ├── 0c793d5c4c4ead956b6ea448bde3c537510310ab.nq.gz
│   ├── 0cbbc0d2ba60b7644b38eda2479b2363a9d9bb81.nq.gz
│   ├── 10cf307763dc12c9deeb4240eb495c9e0070c5a6.nq.gz
│   ├── 12f25716c07716925d307dffe3095f9b4216ea68.nq.gz
│   ├── 138d71b1871e8717d68680821c986b492dc409c4.nq.gz
│   ├── 1391cbb65e648d9925137b3e19b2b3ba6f759ead.nq.gz
│   ├── 16b7c9ec8429681d4f3454624856fd6910f4e262.nq.gz
│   ├── 1bb92c31c5e1ea0123615e748470215ecd9f17a9.nq.gz
│   ├── 22cdb99e3c453109a0a8078dd6ecf621c5fc2ef7.nq.gz
│   ├── 22edaff8f5329d340929d21338877373716aa3fd.nq.gz
│   ├── 24afa439aa4cbcf7f4ed4f2def13cd7ceaa0152d.nq.gz
│   ├── 2540e3da05416730336fbe2e7907db2e7acbb2fa.nq.gz
│   ├── 25cec90e0d20b5fc736854accd872fd7c44a7f68.nq.gz
│   ├── 271e3bf895d1b687a4c6765a567d5b629ef048d1.nq.gz
│   ├── 2b2d9d298a8f96c95b6be95c32ed7f1056e5e474.nq.gz
│   ├── 2d5f7301bff984e5585292b8e2e94e56390b0a43.nq.gz
│   ├── 2f28bf270b0619d774fe510f0e559361efdc3091.nq.gz
│   ├── 32711ece56153f54c033d81f308820b737ac5d1a.nq.gz
│   ├── 33bc3ac36aaee2010d37c7b11770bc22bf820bac.nq.gz
│   ├── 378706e7dc7b7a100bfdf2389105bbe92c076745.nq.gz
│   ├── 3d82ac36872d1972403e618d423d87581929a277.nq.gz
│   ├── 3d851b270627fc80a458678f1d496605334eeea3.nq.gz
│   ├── 3dd0c55adc35c435e9eb427f56fb625211c4948b.nq.gz
│   ├── 3ee5c7b7afac79ac00fe6108ef6eec5cc667469c.nq.gz
│   ├── 426503c812bce531d5f1cbea2b6fc684e80b1384.nq.gz
│   ├── 4a7e1495a22c55f37440c26bb7109d0f3e37865a.nq.gz
│   ├── 4bb8daaddc53b29ab29edb7824ae276c87d30d40.nq.gz
│   ├── 4c6bd388c4bd7a0bc6e57f420ba95df435eaf478.nq.gz
│   ├── 4da3332e9386bb9ee10f83eeb82d3f6673ca70e8.nq.gz
│   ├── 4db6cbbced47327ccc4b83fb8e1ea4f732cfc5d0.nq.gz
│   ├── 509e058816c33d83d3fc18240313738a445c0d33.nq.gz
│   ├── 53ad5f87e6688fbe50c791ae64c10b1ad3cd5fe6.nq.gz
│   ├── 54334d5e78da7e4de249c952f4366ffa9329892e.nq.gz
│   ├── 58a48b6ff49e9d6e3ecb3fa2d79d2871906b590d.nq.gz
│   ├── 58eccbfaa73e1ca0002cbf36cdf797666d549f47.nq.gz
│   ├── 5b5dabac383231c277c83e254e29f61790dcd180.nq.gz
│   ├── 5b9c643201c25a38c10af887a879a114293fbd61.nq.gz
│   ├── 5cc41ec540fe334f31ac7efde31bc4616d5c7eb4.nq.gz
│   ├── 5f1cac0e118ef9f9fff82ff7ecb4105c06bf7fa0.nq.gz
│   ├── 5ff84bd36f790809e46711110864d2a4a981a8ae.nq.gz
│   ├── 61d0dbccd8d366e14b8002a8310a9bf01bf948fd.nq.gz
│   ├── 63a15281ea10e075a35e9c1979d7368834783250.nq.gz
│   ├── 6412a598299c94728d34925579e07dc7610639fb.nq.gz
│   ├── 65b4cf65266d9b03aa101c30a0b97aba88b47768.nq.gz
│   ├── 65e10f50f2850e47fe08a2cc42e87ee72bfe098d.nq.gz
│   ├── 67b05e46d498ad63ff5384bc378b8931c44b533d.nq.gz
│   ├── 68521906a81547765f5bc7ebbd1bf6366dc6fd1a.nq.gz
│   ├── 706971a090a421e48c9ce1a25c299d342c20cd1e.nq.gz
│   ├── 718d642ce6998a32a84b09c7a04769539288f7e1.nq.gz
│   ├── 747d1a85614fd740dd7e6d88a8e12a2c075a17bc.nq.gz
│   ├── 78617d20f367767d9601631c5779d1b0a5befa81.nq.gz
│   ├── 8084522a39621f6e3bf117ddae7fde76ab3b786f.nq.gz
│   ├── 81e4753bb63354203100484b18e8ebbd51e6edfd.nq.gz
│   ├── 82bf95b1d9fc13c2f0c29415ee01609564e000e5.nq.gz
│   ├── 859a5e896a220c4629748a85535736e1539253ea.nq.gz
│   ├── 8c0ea719290b8ae723a9947bb54a6ed326a2e88d.nq.gz
│   ├── 8ca792e61e0fa4d690d9ecc99c40c7ac6bfa2e4d.nq.gz
│   ├── 8cb4107a00de376a0dd7907c75bc7c9b61f1af68.nq.gz
│   ├── 8fcc9d3e68afe4c969c0a74e979b4099ece9e405.nq.gz
│   ├── 912fa754a536cbbf3aa6219847eaf22b7e3c54bf.nq.gz
│   ├── 92f4cdd45f1227712cda979fd65dba9221f91418.nq.gz
│   ├── 9505ca4bf222c9cb4f524cf16a68babb3f660437.nq.gz
│   ├── 966fb597af910408060fd7d27d0d0da94d43b704.nq.gz
│   ├── 977ed5246dfe37c13ff59aa7679e9dd32526c720.nq.gz
│   ├── 9bc941acbb45bd6e07b4e6f32d4d91545f247bfd.nq.gz
│   ├── 9be47fbfccc0b324ec13455264cd8779a0169140.nq.gz
│   ├── 9e0cb675975c361b576d541ff62415ae8e1a056a.nq.gz
│   ├── 9f4f38911900da0344b45072fd7f3cac04a9d0f6.nq.gz
│   ├── a1cf148442f6e21d07bb68fe55053262e85c08ec.nq.gz
│   ├── a2fe0a314bd5db2e53915930716210be9798a08b.nq.gz
│   ├── a6a855813552c731d4d4ea97d56f08ed91687afe.nq.gz
│   ├── b40d2b5d6612384d23f9efe03cf7915cbda2ece0.nq.gz
│   ├── b4a2df5ba05bfa976ee74f2d55dab97b1c0a90e0.nq.gz
│   ├── b4edb7e44ad5a26774bae2d74fbf677e4e6b183f.nq.gz
│   ├── b77127fb523f4b1557b7e445ad8d9c1dd6c34ac0.nq.gz
│   ├── b782d6ededd3973f2c7c41afcb5e6ef4f86d3b6e.nq.gz
│   ├── b84af0544df32eb18008ec61ea6e08e77d45d393.nq.gz
│   ├── b88fa89f8c151fbe1204d1fa0ef2d1e52243e4bd.nq.gz
│   ├── bfc029fdb3f0c19f1c931bdc745b3ebd9cd555c2.nq.gz
│   ├── bff8283dcbe58bfaa614658e8d3a2a12d29a7d72.nq.gz
│   ├── c296acc973108a46fa44ed42db16c3f7248350c7.nq.gz
│   ├── c4fd34cdbdfa99389f89786a74a9507b310706e2.nq.gz
│   ├── c65dd78020e5bcfbd2bc819b6700d19edf6fb079.nq.gz
│   ├── cb257d61ffe503cce2844515e51996a96a9770e8.nq.gz
│   ├── d146039ac6206996bc88a76860c3940e5473d66f.nq.gz
│   ├── d184b9fc8fbed4719f9a3f5b24cdbc255365fd32.nq.gz
│   ├── d26e93f50f6c8e8bc28161c73f202570572ff482.nq.gz
│   ├── db3495bf0f75430d7c725182285de1e9c6fb75c3.nq.gz
│   ├── ddc4f721bc754f7c4e257d381a49ab2a106e17ef.nq.gz
│   ├── dfe3785eb3655d96f97ab983bcdd573bfbccf92d.nq.gz
│   ├── e006d31f1ed3c4ec7cb96cbba4a8866c00b6651e.nq.gz
│   ├── e31dc52e308fef5756d81bc969d3252634e4e4f9.nq.gz
│   ├── e3b49afb3076c2257fdc544135952c806ab367c2.nq.gz
│   ├── e4be8984900f5862094496330e32afdbd9d2f153.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a9e32902784ebf753235fcd6d3c496848ebac4.nq.gz
│   ├── e7d06ca9bd36ecc1f39ae7a250db5c219fb1bdf6.nq.gz
│   ├── ebee6f0fee7f4862710f72dd73cf3e15262ed4d4.nq.gz
│   ├── ed481c459f8318622480d2389011daa1c212f7e6.nq.gz
│   ├── f5ba45cb10c7dbf5bdd8335d015701badb03f695.nq.gz
│   ├── fca880f5a98d88cec7c7d8afcb65b5fde3b8d9ef.nq.gz
│   └── fe35a4203e0cb015dd04791e3e3884328e607b33.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 70f79fd9b633cea7b9742219888fac08069edc22.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 117 files
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

[singingwolfboy/flask-dance](https://github.com/singingwolfboy/flask-dance)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
