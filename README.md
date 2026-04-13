# Repolex Knowledge Graph of davidhalter/jedi

RDF knowledge graph data for [davidhalter/jedi](https://github.com/davidhalter/jedi), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download davidhalter/jedi
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41e9e957e7fce02e63a41af66c9c891e33411569
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 41e9e957e7fce02e63a41af66c9c891e33411569.nq.gz
│   └── repolex
│       └── 41e9e957e7fce02e63a41af66c9c891e33411569
│           └── chunk-001.nq.gz
└── blob
    ├── 00a5717629c68aa786c40092417748b555b0a0ea.nq.gz
    ├── 01d56a78b8f75bcf58cbeb09a5ddc9743f6b6c15.nq.gz
    ├── 01fe535419658520fc79612e1e3fd66f26a2052a.nq.gz
    ├── 02a08c7d629fd9f760c787f0718b06615ad44c45.nq.gz
    ├── 0344f746975f4f6ceb1fca740e58d8baafd45406.nq.gz
    ├── 0364c05b632d0ec05f08eacfb69e4450c04a841b.nq.gz
    ├── 03c199eff4b5a1b13085b49483e120bcd36159fc.nq.gz
    ├── 03de11827b9ba46c4d345cf9efb27ee832fd914b.nq.gz
    ├── 057a23609d4c1d9b7555b036950e9e9de12861cd.nq.gz
    ├── 057c4b6231fb2c8f4e0415b6b718e6283975e4f4.nq.gz
    ├── 062a0aa3afc9edaf02e7bb49b1877aec84c540c2.nq.gz
    ├── 08dd4d095e9fa7ab27fab71af7e960bc7df78510.nq.gz
    ├── 09929fe4369c3fb7055194ada0edabde29216d80.nq.gz
    ├── 09ac19f97671e40ff5bd2ccbc20838cde962bcaf.nq.gz
    ├── 09ed1b64dce199308c5415c97e39a54215d52a93.nq.gz
    ├── 0a1303e38fde5cb2e72e55a9709627df9cc9b24d.nq.gz
    ├── 0a76a80ebf7f7f048df2b122bd116e6f088b6d79.nq.gz
    ├── 0a978a8f7d77e3bf81d5cb19ca1d900454b1f584.nq.gz
    ├── 0b910b80dfcb18f80624d51ada1406e0af8d34fd.nq.gz
    ├── 0c3dac5a381bd0d36e3e1b4e564f00247a7ebeea.nq.gz
    ├── 0e1e5e955f2ff654cd9707e245ef5dc7e2c81cc4.nq.gz
    ├── 0e344c2404f8f213cff1914b859f1c300d1f3f12.nq.gz
    ├── 0eae367dca22923d3184de05b44e938763f58251.nq.gz
    ├── 0f9111f49031a2e15d1633b76c9d8b44ca5a229f.nq.gz
    ├── 0fc5d1595f747c6a3ae9f9d6eea17809a0ed242e.nq.gz
    ├── 10cb62af1500616e150f5f2e73396241d8f6769f.nq.gz
    ├── 111f75b44705dfe1f8c9f9ac179874426fe39819.nq.gz
    ├── 11293b68e09d9d6e2d85a63066b113f0ac69e273.nq.gz
    ├── 11737cc97f5ee2a00bc6ddb774cb71be2645ebd3.nq.gz
    ├── 14a0ee4af40fd4e8c6908772906f7a2530651fe6.nq.gz
    ├── 14cfdf4bc552dad6e1a6ec0ff179a0e4072e6ada.nq.gz
    ├── 14ea9a7bf286a2671005ede65e5221de4d2b9172.nq.gz
    ├── 151fd8f662713c9856fafbd906e3715fcfb3dfbf.nq.gz
    ├── 1548d844dc350886e0cdd8de61613fd9accf74d6.nq.gz
    ├── 15a791744cebd146a7fa2b15f8581ee57e871e44.nq.gz
    ├── 16812136da027c3fc236da4b896999716e11b949.nq.gz
    ├── 18770a107d1aaa59e5a36ed458224b6e2ca07313.nq.gz
    ├── 19914f585c2ba279ea2095220fdaa30cfdb435c9.nq.gz
    ├── 1995784100e273fb8ba6b1e5a0553ec049ee4071.nq.gz
    ├── 19f3149db07934b572336a17709514b67b7100a5.nq.gz
    ├── 1a0c0453e1b8496019be32df35d34c02eb2321d6.nq.gz
    ├── 1a0fabea607e738e84c3ce5cb8a79dd1b11ca787.nq.gz
    ├── 1a48468a9ecb696040f1061a1e4e4113b58c93c6.nq.gz
    ├── 1a59e543c91e639f2873f2b32e1c8c20e101b691.nq.gz
    ├── 1a69d2ad5be7d0cb7032e58e749191c5bba0d38c.nq.gz
    ├── 1a77f3832d01b22260f666338ececd48afa94c07.nq.gz
    ├── 1aa027bf44178da06c1e27aae4ded5b4dc948639.nq.gz
    ├── 1bfa34056d58c33742475ce321321d9fd4946fc7.nq.gz
    ├── 1f296215d6685a1804dc61b8d79e828eab3f3aae.nq.gz
    ├── 1f31b54343b600d04c22893848ec121959fd0a6d.nq.gz
    ├── 1f52c4f2a66717b9c153dbcc27e9bd0c17bf622b.nq.gz
    ├── 1fb24e16a075892d633d61c5b339f34a6b74a0e7.nq.gz
    ├── 1ff452013f8bfa90753296dea65a79f4e56a2689.nq.gz
    ├── 213ef0be16403de4d0886a93246c6e7c2c345a0d.nq.gz
    ├── 21437bcec6c1abc4196ca5b3c79cfa193dbfa6dd.nq.gz
    ├── 223cc29283db594c641d643a4c8d31839732e0e1.nq.gz
    ├── 22f08a102062edfe006e7d540c723cccf84d55cf.nq.gz
    ├── 23370e0c859cdc68012194db2ca1518a17d94da7.nq.gz
    ├── 23b088c316096e8987e11aa1d3350087a4c5ea37.nq.gz
    ├── 24b22ba2f8430febc3a067879d3df1d344c391c6.nq.gz
    ├── 266e809370d1a95d141d93669d816e393dda93c3.nq.gz
    ├── 277f3220ce53dfa410033d2c5ef40c2f1a888652.nq.gz
    ├── 28481a0c21ab644ae1068a7be32e1da18db65528.nq.gz
    ├── 287a301ea44c37891af457efa9eee4f9a1a2a068.nq.gz
    ├── 2894b0e898668f50946648552166e7acfb368b02.nq.gz
    ├── 294fb7e4c9787514dfd0637c6df719b80c8ce9c5.nq.gz
    ├── 2a1d8700620ae8a07ea127779cf8c805bca632b8.nq.gz
    ├── 2a7ee64f7c1c4214662c6b88434015bf90b1eccc.nq.gz
    ├── 2bafad6a2f7f47cad8f662a3d3846adf91a32267.nq.gz
    ├── 2fc8e81d4a36cf196a273f0fffae3c8df0ffec8a.nq.gz
    ├── 3078d83f42686bba3268d40e9c9f89a7d5512a15.nq.gz
    ├── 3356150f13ec9f33813d3279c15d79a00c84003e.nq.gz
    ├── 343c9281ae3727489f28f9f5369dfb12b9cca88f.nq.gz
    ├── 34be43b55126bb8f8ad8de5baed9b1e4510899ff.nq.gz
    ├── 364dd0350008ff231e4de4e4f076b4bc1d707769.nq.gz
    ├── 3a03a829f6ff0415a1c12fcb0a67cb38360a6d17.nq.gz
    ├── 3a333e01a110bd090027ac48274b94cdd525460e.nq.gz
    ├── 3a6039f7486596aafbdc149e1fe0ed8a11c3123d.nq.gz
    ├── 3b04d93211b1b3a4d1dfad3a5403f01a0366c847.nq.gz
    ├── 3c1108d9112a29b786bf607bfdbea6e1da2c5238.nq.gz
    ├── 3c3782053b1016e73140b984947cfd91e428b714.nq.gz
    ├── 3cc01faffb258cad786f8cb9d33aac3b160d0184.nq.gz
    ├── 3ccb0a7cf31cf5d6bdcfa923607bddbb4e882e32.nq.gz
    ├── 3d1a12ee7d78d998ae89ba1994b66100903d83da.nq.gz
    ├── 3eebfe277584b42aa76b2a29596cd8d5541e2d12.nq.gz
    ├── 3f84fde046310c48b7072f5668eb98ae7c208164.nq.gz
    ├── 418e47a80da145ec5c19c18b8225afc8896848cc.nq.gz
    ├── 419c1bd7a6410e68c69a3cf35c8136ec0d7f3dda.nq.gz
    ├── 4201289b4ee55616ffe5e675b7eafed009b9444f.nq.gz
    ├── 42e33a76c0871c93427ae2cadab231774e9933cc.nq.gz
    ├── 44520b9f47e6d266093e8a6cdfaa56ae65e1bb66.nq.gz
    ├── 4466cbf4b3f065009ce49598d08083431c8aad71.nq.gz
    ├── 44690141666c0122ecde18e4886dd6bf00c0be80.nq.gz
    ├── 46e9bead210d817399113bed5db11e4e5e69e6cd.nq.gz
    ├── 480f22213d3c6d5cdac785c04f39c6174c13375d.nq.gz
    ├── 484c20ec24d35b9c5b0e11017cfe9bf96627ce1f.nq.gz
    ├── 48563d00ddd11b99961164df5924d5e19518f8c3.nq.gz
    ├── 492f652a5e4af00f95a32a482af435a36ce5630a.nq.gz
    ├── 4a1fcb62e56a5625684948e0f8fd3ed3446c4380.nq.gz
    ├── 4f2f423927da750339e5fb95920cde2ef7240bd4.nq.gz
    ├── 50217cd34b495d311cbe0ff1fad02bb4a613646e.nq.gz
    ├── 50c47b83ada57d04a1fce44919c68465bdf74c6b.nq.gz
    ├── 5374960aca56a45511c97f5a9b2b4a07de009d40.nq.gz
    ├── 53c44ca1bd3529aada2083e43f7a1078d073d73e.nq.gz
    ├── 53dc265360f90fbc6a66a82e183069cd782fc265.nq.gz
    ├── 53e0046c456c3f3d0dd5de01c70c16770cc22d98.nq.gz
    ├── 54821c9d5eb12fa7b609402f1496551854f8b335.nq.gz
    ├── 54b5b0a12e2852b5ea60312c5faa7c7c3b3984cc.nq.gz
    ├── 565a269b8caa8c9423f1acf5c6b1220c9d5b2755.nq.gz
    ├── 57098276fc23693c5c635a3d9ca6780aefd79a25.nq.gz
    ├── 58c40eae37e3d891413d3d138fdb065a3dac36ac.nq.gz
    ├── 58ccd2d69829c615067f2374c212d9a0034ffb6d.nq.gz
    ├── 59aa4f6cc1f09a67844e1a9965f66480bb971382.nq.gz
    ├── 5bc6b99412810e9dab5a365465bd13c04c8f9eda.nq.gz
    ├── 5c86b7b349988f5dd5e0e6c3e957c59918ff997d.nq.gz
    ├── 5cbbcd7d1b1269ce2ce28dd89b6c594ed1791f1d.nq.gz
    ├── 5ce051774b63f68660a717ac8e424957f818b8b2.nq.gz
    ├── 5e2797780ef4c99cd482b83d49dca64bb5a512e5.nq.gz
    ├── 5eac8a2f48d45dd8bb647556e986d836d421cd98.nq.gz
    ├── 5ef1a7490218aeb2d3dc39026ab912a34990a55c.nq.gz
    ├── 6109703e4af92dd779158256ac380ce137ca99fc.nq.gz
    ├── 611ff01de31a4501910c6da261d7bfd188a83523.nq.gz
    ├── 61cc3839e6b48d71eb4beed422e559fbbd771010.nq.gz
    ├── 61eb1928321c20f95ec0eec145f358a3334ef318.nq.gz
    ├── 621642155ba588bb518b369aa4123be5c25e5c06.nq.gz
    ├── 621fcb8ee77a9a60d01b34b17bd1245708a1acf9.nq.gz
    ├── 62782334b68d20ba1730d0b69c1e7f35a5689373.nq.gz
    ├── 63f220e0af0cbfd3b8022f038182415317d2b13f.nq.gz
    ├── 640a110a7ec7239aef6e954fff9f2f7303486c1a.nq.gz
    ├── 6461cb4bcd06eea355b02c08b962c014f16b3d9d.nq.gz
    ├── 64b318e1ff7a3302155136afcccb0cca05b78fd1.nq.gz
    ├── 64f9c22e198138c530d04fb87d9e18ecffa4ecfe.nq.gz
    ├── 6629f9aecf55bc7419c76252d75460cca31d8f59.nq.gz
    ├── 668dd9b62ce676a03fd0853eb7655643c614f61a.nq.gz
    ├── 681a312bfa2370eb82588b47ccd92f5f484e64d3.nq.gz
    ├── 69c4cb6ae6cee72f686091c8c99da455e645863c.nq.gz
    ├── 69e91354cec72aa6042a68026cb2f0ad49ba67d7.nq.gz
    ├── 6b00aa1e23efeaa37bacc640ac190c8aa912b2a8.nq.gz
    ├── 6b19f90b4b5ab87fee46b217b9f2cc49ad5eca53.nq.gz
    ├── 6b4425333e2a33c3a89318da6b25dd7c4cc666d5.nq.gz
    ├── 6c143ff7fb00104c6e554d38669c7040896439d9.nq.gz
    ├── 6d0cdf7487e182ca8c5b3273bb4a6bd5d0d5b195.nq.gz
    ├── 6d1eefe35dfe74263b955351ee4e285c120dcca2.nq.gz
    ├── 6d49aa7734087ebc0e954f934b9a6ad1623f1831.nq.gz
    ├── 6e27dc2aa7d9cd5b3e0a1f9c3a293362ff6a08e7.nq.gz
    ├── 6e7df7e13b6a0b0f75fe7b31890aae65b6bc43e0.nq.gz
    ├── 7054788e3fe19f3892513d1430a2fb79808d9eb8.nq.gz
    ├── 70b184ac0e3c587993eed620d03c60a951a5c761.nq.gz
    ├── 70b24ae4fabfa8a754fb6391d5486cddd9fa90f9.nq.gz
    ├── 71c66e1fe93ac414377a555549dbe010aa791f98.nq.gz
    ├── 71ea7093808a97fbacd895badba27aed575faba6.nq.gz
    ├── 722adb21ca4ae2970fc4cccccf90c763f9ae1d4b.nq.gz
    ├── 74f0a3d856f73e3d3eaaeae04f9ba08944f06e8d.nq.gz
    ├── 7598bc7deda93bc2236215f1cca2533ed7942030.nq.gz
    ├── 75a895c67e5187ec7b6bbb01514a24fb9e4d1a8d.nq.gz
    ├── 75dac3246e6d69b5793cce3d4d979ec8a9219fbe.nq.gz
    ├── 76bc2c84e0da53d4cad399415bac2e25f35e9b3a.nq.gz
    ├── 77968fc9588f1877b408ad093c4193521f43a79c.nq.gz
    ├── 77cf2466a54d96c4ee4745edeba26c62356ea8f7.nq.gz
    ├── 78435fbf34a7633faf390edfde67fe72fb00592d.nq.gz
    ├── 7850142c5e1470a0c6c2a3313f205defbd35fb85.nq.gz
    ├── 7890e53cdeb64c784ca502507b0ae635f82b1ec3.nq.gz
    ├── 7924f30cc27e9a4220bdd143337b81fee4434ca7.nq.gz
    ├── 79b35a589979d7abcbfd3577e833204531cb3807.nq.gz
    ├── 7a34c4e3953160c69bcdaa779115f7b06cd0b7f1.nq.gz
    ├── 7a9a6156b3eea9a6cac15a83ce39b9d886a4758f.nq.gz
    ├── 7bbcad2b54f39f11caf657dd0015b9f4005d3c69.nq.gz
    ├── 7c4aad5fdcb30ce568ed8e073e4171d34087389b.nq.gz
    ├── 7cc37173dd262a13060736196739065bb548d02d.nq.gz
    ├── 7ceb9397238f486b96dd5d1f66c9860ced11b285.nq.gz
    ├── 7ead7382db9e2778764d6793b12da324fa411e67.nq.gz
    ├── 7fce91da7971ba6dfebc841994053630f4c294d8.nq.gz
    ├── 8058f05cccae9e09e20ffc793176c8092fcb7639.nq.gz
    ├── 8067676d03ee07725b5aa44e99303701381dc224.nq.gz
    ├── 809974f3778a64c6d28d1f420fad1dce7504c478.nq.gz
    ├── 80ff13c3c08f55be529061472c41f6d83240d3e4.nq.gz
    ├── 834704b3af6971e8cf69abb93143536a42d0d9c9.nq.gz
    ├── 8360a42a4f51210657dc1c7ad54b7926183f1911.nq.gz
    ├── 843047034b259a5406f297ab3409b0a024ae627d.nq.gz
    ├── 84d2783812751684ab03c5d5ad9661fd97a03cc0.nq.gz
    ├── 85a0765a2793633cf4c9cac1fd0f21aaddc91051.nq.gz
    ├── 8602f494d8bd3dcfb46bcd9f7ad4e4341f29a954.nq.gz
    ├── 864032b82be4788204df5049fc9a5e02bca62003.nq.gz
    ├── 86caca65d90dbcb85aef45728b413fb493a57712.nq.gz
    ├── 8701b112414f03ee1e5665ed80e0bdd45897073a.nq.gz
    ├── 879b2ec5d47eca5053f80af3c65a6103920e7afe.nq.gz
    ├── 880b528c0a1cea07584225c0c9d4e47dfb22c5db.nq.gz
    ├── 8849c6e9e31502e5200fff5200bd01b4a55d1d8f.nq.gz
    ├── 885016822399e5d281def1a5c97953f2a981bf35.nq.gz
    ├── 8927e7ea27276def440aa92c1ca7f371e405f46c.nq.gz
    ├── 8940f07ed6a9733adeba001cc53265caa82a1446.nq.gz
    ├── 8943d8df22cdbea267028e769b0fab2c195cf1fb.nq.gz
    ├── 896ff4516ff614222eb9c32d05543c70e4228d3f.nq.gz
    ├── 89bfe578dfcb4dd2770c6218ed32d374639910fb.nq.gz
    ├── 8afffb40efb2391ba520bf502da953b38e33ead7.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    └── 8bcde9d20269eaa689c81f65c642a0a6025f8c0b.nq.gz

8 directories, 200 files
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

## Source repository

[davidhalter/jedi](https://github.com/davidhalter/jedi)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
