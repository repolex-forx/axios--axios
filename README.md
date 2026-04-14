# Repolex Knowledge Graph of axios/axios

RDF knowledge graph data for [axios/axios](https://github.com/axios/axios), parsed by [repolex](https://repolex.ai).

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
lexq download axios/axios
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 772a4e54ecc4cc2421e2b746daff0aca10f359d7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 772a4e54ecc4cc2421e2b746daff0aca10f359d7.nq.gz
│   └── repolex
│       └── 772a4e54ecc4cc2421e2b746daff0aca10f359d7
│           └── chunk-001.nq.gz
└── blob
    ├── 006c62b401e07a558891d1fa81e58e301aaab1c7.nq.gz
    ├── 00ab31fe2d49f84162e67b0ed0daa0f58a391daa.nq.gz
    ├── 014c55170d637d1b9648529b7fc1380adbf957a4.nq.gz
    ├── 0246f4798cf81eeb037401a2e9163c51326579e6.nq.gz
    ├── 027ab83b37261aab2533d579872d8c4dcfb98a84.nq.gz
    ├── 02d896897e7a21c21c4c4bd037972f19b76be4d1.nq.gz
    ├── 02e92b780741c8b6e080db59770eb842e0657bb7.nq.gz
    ├── 02ec2d7be002410ab31b6633806e0cd368d268a7.nq.gz
    ├── 0304ea2f2953f382b0062177296677f2acf9fd56.nq.gz
    ├── 032fba86c1f3b11301ee49febac1bceba11a70ef.nq.gz
    ├── 034e37addc8e3c575de4fd10af5a0d81a3bce7cc.nq.gz
    ├── 04e3012d479b0b239c2b8896818a6bb8480dec8e.nq.gz
    ├── 05006a51eb888282323883df740cd90ad72d0700.nq.gz
    ├── 059989c4ee9b4d537a9c9b27e6c9bd303d036084.nq.gz
    ├── 0667e7a36b121e4ecabdab5e1ec2cde96a60f726.nq.gz
    ├── 07c5c2439f1e6b002f2b2277ef5f89a051bc0b03.nq.gz
    ├── 07fd0842ee3f8da8b1892f4ffd69673886861386.nq.gz
    ├── 0879ccebf27e81d2a31650032ae98726c97e42f5.nq.gz
    ├── 08e5ccf55ab8cffb632fa44a1bae1b46897436d2.nq.gz
    ├── 095ab33c67e06a77fb428ff0624a812a58584a40.nq.gz
    ├── 0a6b9812490dbbab77065dcc0287f000a1383f96.nq.gz
    ├── 0ad64a7429314998e36d0cfb888eaabfd069bca3.nq.gz
    ├── 0b1e6b1407dc6afe70fa5f4092e54bffdc1be60c.nq.gz
    ├── 0c75de838ac3807ef94f5fb3980a735589696590.nq.gz
    ├── 0d7816313311f8f3b536e536ffe695ecdd9f3ab2.nq.gz
    ├── 0d7e39dc65b2f8290ca684a812afa1500d028f96.nq.gz
    ├── 0ee5519693db81f30b621ade7610a9adb0127d38.nq.gz
    ├── 0fcd9d2f1642e771e6c8a00516a73fc6f2f9d4da.nq.gz
    ├── 10f9522d8ab9c7c1f06a071eaf51b3feac359d86.nq.gz
    ├── 11f8c76a03234cc2ca647f5fdc26bb3477a37446.nq.gz
    ├── 123a768cad9811ca80f41af6220047eb1c424fb1.nq.gz
    ├── 12771a572d07695d66685ceb7e09e9b39379c0fb.nq.gz
    ├── 127eb2144772a8abff16195056defd22a8e71c59.nq.gz
    ├── 137f8ad1f131117e0039b398a53a4247b27e0077.nq.gz
    ├── 13e9a0d88c256cc5b1ccef41351a7cf00587f3e9.nq.gz
    ├── 143a205c6d3dbe0d92f3f1b57e2a9a94557578e2.nq.gz
    ├── 144c80642a48f8daa91af1e24220df9f0cff374d.nq.gz
    ├── 1553fb29a757138729802a697b232fd9d21a8bd1.nq.gz
    ├── 16021c91a6e13cc809c20e02020477ec9d17e5b1.nq.gz
    ├── 173f65a2b56f4f3d17f593a7de5ee0adac50ae8c.nq.gz
    ├── 184391dda012fcf7a8d33ef9822067a2db32565d.nq.gz
    ├── 1a61cb1364c20ad31f3524ba78f53f98a286f7e5.nq.gz
    ├── 1ad6658c0e268878dc4e22840e3d52ed48084f7f.nq.gz
    ├── 1b718f525e8a948d185d2681b823b21045404287.nq.gz
    ├── 1c65067cf89ab0cbdaf793ac19c5892583c95a3a.nq.gz
    ├── 1cd9403d7bd3a0bb1cf93c027a74d8570be125d1.nq.gz
    ├── 1d2c8375d8bedeb9bf9f492f5d7c7c90b464d583.nq.gz
    ├── 1e10ee1c197ee9015af531d516a0047a6911e3e9.nq.gz
    ├── 1e689254e1dcd7e5136710aeae11945942a63d1d.nq.gz
    ├── 1ed785405ae5ec1e7a9c5e401904ab848ac5af1b.nq.gz
    ├── 2015b5496b6c1fc15cc8a1d3fc064704709d7a9b.nq.gz
    ├── 2065e032f48d9c658936c33472c7d7d6d53f0e36.nq.gz
    ├── 210c429e3f3582d16d2f27d27bf510ef7ea330f9.nq.gz
    ├── 210f5bf69960de50e4ec64f74c2a9203051c21aa.nq.gz
    ├── 21f4bab136e42ed9d9afe59db28336c040f9d4b0.nq.gz
    ├── 2208ffaf76204c609152a8443be3cd6db6f63b41.nq.gz
    ├── 22798aa9a2b57f1cece48d29b53edf71287aca13.nq.gz
    ├── 2460695d334db68f7dcadca657cdf56d01819ac3.nq.gz
    ├── 25c73576a91c11e3722925603bbc31f784ecd778.nq.gz
    ├── 26c842d849e8de0514b1a63d77f5abb0f1a42e94.nq.gz
    ├── 270176290d7c39f25d08ab4c059fa6f66b278f32.nq.gz
    ├── 27a7d20f439cec99bc4de3268652aa7ce2b25ce6.nq.gz
    ├── 27dcd259b63a5451e79f840feecb530019e57a69.nq.gz
    ├── 2892e775b4e9b9fd939d075ed415f38e85ca9fca.nq.gz
    ├── 29d0d660da58e8dc44eb495fb8d622c8ff973938.nq.gz
    ├── 2a1c5f554462cc1db91ee73b3ecaea3c69760f18.nq.gz
    ├── 2a7fc4122bd122a9fbe45ae826caf6507acff35b.nq.gz
    ├── 2c6e3d0832c0686eb78b629fee1b041584c39882.nq.gz
    ├── 2c7f557b41a8719d99f607299a5a4a412cb79e19.nq.gz
    ├── 2c81c9a2a5c39757704f07694a8857ab5e74c095.nq.gz
    ├── 2e59d9d44583f16770e7fa9a22d71e619318d644.nq.gz
    ├── 2e72fc88f23fd7b3c4b516e5510c3eb9c82c384d.nq.gz
    ├── 2f213dce8b6d302a80cc91c6ac323e40c90ec6b6.nq.gz
    ├── 2f39008e5969bd3e9f440c51d8770bdac1ca2591.nq.gz
    ├── 3050bd64df3a2cd9ddca1a4206fc990b57c282ec.nq.gz
    ├── 306c466c6b310be69793b27474e27a3e58fed66f.nq.gz
    ├── 31a55ffe4e9d9c922c3282fa8ec027eef589d4bb.nq.gz
    ├── 32856029b1e0f4e85cc16a51bd5f4c2bbe8fcf92.nq.gz
    ├── 32af566dc483d75cbcaa5fc8bd3574566b87537d.nq.gz
    ├── 33128318b6b8b9b3a86e426264a52bcec5acd6c3.nq.gz
    ├── 357381ede41d736daa56556b004b7a4e1b15c2bb.nq.gz
    ├── 37880fc01c246c925c86b94958841287f9536539.nq.gz
    ├── 37b362728e416aac3473d8dcbaf367f0177adf73.nq.gz
    ├── 38ac341fe033266818eeba4f757f386c05641c9d.nq.gz
    ├── 397f09fa604f7e51fceac9370daa0b3f261c527a.nq.gz
    ├── 39debcbc571a3560d44221d4bbe90020daa96ab7.nq.gz
    ├── 39e4830023e6d1e644cc22120ae4abf4d46d441a.nq.gz
    ├── 3a23e048d0ed755340579f60cd139affbb2de109.nq.gz
    ├── 3aa62142f52a5742d6d142ee8dff64fe1e09980f.nq.gz
    ├── 3b9a59b0abd9ccba3b22c7afaf807d2775d6ceb2.nq.gz
    ├── 3bacd8fc1093f091d41c8ba14b9e554180dfbe23.nq.gz
    ├── 3bd39a2b7e21d385f8a280b4848bf20fb7ca154e.nq.gz
    ├── 3d902d1c611db4403a3cadb68db2a77ca9f93ee1.nq.gz
    ├── 3ecad7f255431a545aabdaf071cfebfe50172de5.nq.gz
    ├── 3f1e8813b5ef0f6100ba3502ba8c019fa0da374f.nq.gz
    ├── 40f8bca155d681959fe83b94ea83e30e5448630a.nq.gz
    ├── 411e17c495d00ae757d307fbc539c024cc03ac64.nq.gz
    ├── 4191b443bd976c458a459f1fc78f6b5b67e35eb5.nq.gz
    ├── 42dcc29b0d0405b402c2c206a0f20e6b2e27af63.nq.gz
    ├── 4322d22d031b42e3de38cbbdca3aaf8c56228e8b.nq.gz
    ├── 43f2101340dbd96ad201cf3f0c14bc22eb2c5289.nq.gz
    ├── 43fe7b791727fdd80b0b12a61ec1a0071ba03305.nq.gz
    ├── 449523e7272e31cf96420f23cf275ffd05d53ef0.nq.gz
    ├── 46509f57641eaa39b199e3220b3c902428fc93a8.nq.gz
    ├── 4ae34193a1edf855caaf3fc3a3700230934379af.nq.gz
    ├── 4ae60be32d486cd0e39d4ad67b68789adf69eff8.nq.gz
    ├── 4b1f72ee62de37ad25424668baa6221b6b23c624.nq.gz
    ├── 4b8ca409bb8ea5fef6dda23afc7fe66445a7261a.nq.gz
    ├── 4c0b2565d350bba9eddd44734e8b09c15bd7bb06.nq.gz
    ├── 4c1b4c2f75df5cdbabd3c03cb4ad03ba3a4290a4.nq.gz
    ├── 4c953a023b47457ca3e73f51ff6ef6a61c3027ac.nq.gz
    ├── 4e8e4846b9ee8ccb9de4252f4f72084d453fed80.nq.gz
    ├── 506121346288923b5f969fd3f339139279e1475f.nq.gz
    ├── 50af7c332a7db59e1e0c0581ad519ae377f847a8.nq.gz
    ├── 5150a8e4336efac83fd80fccc82cd84e4f7c736a.nq.gz
    ├── 531f57e6e107e9233b1c56f5efec92681c01eb91.nq.gz
    ├── 543015124fa143f4ffc637c4513b322e81007bb8.nq.gz
    ├── 5515bb2e627db2cef86ef34dcc138cab00b2cae5.nq.gz
    ├── 566a1fff8615290e1d57823ef468878cbeeb1e90.nq.gz
    ├── 56acec834a611e6876cb11d1cb5b8ef12091057e.nq.gz
    ├── 58b2ca267468f9e74f8b20c8d415f983e6451d09.nq.gz
    ├── 5a3a876c8e00aa563e84306fc89ae8e19b35bba2.nq.gz
    ├── 5b34bd382fef529a6ba145f54a613373c9f75695.nq.gz
    ├── 5bd97eae380365f6de5f070f3b4775661034978a.nq.gz
    ├── 5c56af3d72e98f6cd07ea06daa4e9e0bff88f8e3.nq.gz
    ├── 5d18745a7aeed24c13c84ccc5cecf6af534290a7.nq.gz
    ├── 601dad02ede927b04ef58961880ddac8a5ed8ddb.nq.gz
    ├── 60aba727f8bd2a12d37a592f133ec4f6a1f4238a.nq.gz
    ├── 60b23b5dcc8244031e8b33f3e8f091002e5a1e86.nq.gz
    ├── 6542974cd69ba2b81a4f172186dc62eb2b6d3e18.nq.gz
    ├── 6588ddf09009859c77409ba42b749c10eb57aa84.nq.gz
    ├── 66af27432d8fafaa6de062f97e429dea8e9647c6.nq.gz
    ├── 66f012cc29fc08a343c51e7f8b55bcdc874a5c57.nq.gz
    ├── 6711af5b39baffaee6869cf3c5c29abb4d066e30.nq.gz
    ├── 676ac6c739e50f9f93ee0cd80b1f9a7093d7ffdf.nq.gz
    ├── 685d309ab523805762f2954fda0c0abf9310155e.nq.gz
    ├── 688ffe284194d72cf95fc2b666b2cb1bd3d56dac.nq.gz
    ├── 68caf5dff326a25fb6d65804f16bcb61c0ef649d.nq.gz
    ├── 69393b83e001777e247f27347e26326900e6be15.nq.gz
    ├── 6993a2291a0fcc4693080c9c01d483d7d05d464b.nq.gz
    ├── 699fb5d6dfc102db8d4cb4c30bc312aebbf48c5d.nq.gz
    ├── 6a295f36118ec7064e3f068a6c92f3aee2bde693.nq.gz
    ├── 6a2a3e1c3dd26893717c0dc92c65371a52933bc8.nq.gz
    ├── 6a5084d6e2b14365a60d59f620c26af5a79cf731.nq.gz
    ├── 6b375ff93f05a2532401c40a2b3af4a4f492e163.nq.gz
    ├── 6d58c410e2e8847a56213940ac68cf1652fbf906.nq.gz
    ├── 6d7c5e539993505556b8174fd1c962181ad31fe5.nq.gz
    ├── 6d9b3a2d4e19c95416c98b66f23efca1e7d26503.nq.gz
    ├── 6f7bb779aa153feb789671c413b354f7b2e4f123.nq.gz
    ├── 6fbc5dcd28b5c10b82eb7ea226dff5a18c8826a5.nq.gz
    ├── 714b6644d1b646c64322d0bf7c637fc905ac46d2.nq.gz
    ├── 71608bdef50e1b8d508e762a34c53bd44896db20.nq.gz
    ├── 73c4f0d2cf03f286f6ae42c07ce8cc2231f7d707.nq.gz
    ├── 749e13a61624a73d6e556f6b17c349fc0d705761.nq.gz
    ├── 74e30f248a994dc9172be2cf22570284a32a8d45.nq.gz
    ├── 753d296b4c5ee3074a074faa18d975a7e494f6ba.nq.gz
    ├── 756aaf9133a41596c34125e52ff31fe0cc32876a.nq.gz
    ├── 7634b9474cc1bae0e73d51e570782265cd0942ec.nq.gz
    ├── 765acb0643210330a73792d0fd7de7fead5db73e.nq.gz
    ├── 76f2106a9b96f7e534a80c94f890ac0724932182.nq.gz
    ├── 77ec7ad0f0f69a377f77593783fc1e66799c07c1.nq.gz
    ├── 791c8dc1e7c301213b18a432ecc4968e6ceeed1f.nq.gz
    ├── 7979de81ef6aa8381452a556cc1feff4fcce061e.nq.gz
    ├── 7b2f1ef144e4b86824b9992d659e3bcf2688bc3f.nq.gz
    ├── 7dbe23b9b16816af7f364530f858abdf549ea937.nq.gz
    ├── 7eb07cb2f6ebf5d05910a0559d3098d6b21b0d68.nq.gz
    ├── 814a9dca05c54411a0d1b76304eb6d8b4211b14f.nq.gz
    ├── 84559ce7c8039363a0c08afc72590af0aa288979.nq.gz
    ├── 84a2a060e0e958ba753cd7cbdab6ae35f301dbf4.nq.gz
    ├── 8511175953c2ef062ebb6d073df7715a4037a7f6.nq.gz
    ├── 8629ad055baf306456c3d89acd1198bb99446c12.nq.gz
    ├── 862adb93c3df8de3c178325d090b7a5b1503274a.nq.gz
    ├── 8639986cfb4b08e97390830b4e5d1fd24b0da880.nq.gz
    ├── 87c388eef4ceaad18e0b340e4e4d269555b6f4a2.nq.gz
    ├── 87d0ea8d259daa6e1d2eee7b48799aca0076902d.nq.gz
    ├── 8a58f0aeaa8e86f93c0bd1e04f8bef8e43ac2a03.nq.gz
    ├── 8b9ed6dc44a5959ff6650eacd944c1c5d3fbac7d.nq.gz
    ├── 8bbd5c62b07c833f6b48b6392b5b3ebe52552dd2.nq.gz
    ├── 8d9dd97db5b076c89249a52d2f38d5c7826ef565.nq.gz
    ├── 8dfb2be15bd5c06d37b6cd17e648122e00013eaf.nq.gz
    ├── 8e5f99cffef7135c3f1d8f815aa0df244f4f0244.nq.gz
    ├── 8ed167cfe46a9aff28ceb52936cb941942100f5a.nq.gz
    ├── 90a4b5d2d6e6ff5e13551a75e3e3217a11b9d7f5.nq.gz
    ├── 91116a1cef014da5ae117357e9828d1c106685ef.nq.gz
    ├── 938da5c1640963c3727aaf7a85b9d148648eaedd.nq.gz
    ├── 94b7fe6e6d087cf52667f5900a1db049b8c15875.nq.gz
    ├── 95138f974b9d7441e30ed17e4277c8ed7ce04acd.nq.gz
    ├── 96cf658a2f5a6c78fdfa57553a2ad5053af2a000.nq.gz
    ├── 96e8acb0268374a2fc5ce623742ada3276015df1.nq.gz
    ├── 989a4178d50b272d73a1927b83bd1790f5ac8363.nq.gz
    ├── 992b307b8bb804a547ed892646a4914470f849d8.nq.gz
    ├── 9979a715f23136a5433f6aeef2f2dee6b06bf865.nq.gz
    ├── 9a0dea9ba8ad225cc66c182e0da5f6eb05dc3e00.nq.gz
    ├── 9bfc656a342f95633778dea648b7f59e61080c3d.nq.gz
    ├── 9c24b4808b3015280c0b6b14ba38a2166ac8cb54.nq.gz
    ├── 9ce05bf90f2791abc74ca41ef86b1ac244ad4363.nq.gz
    └── 9dc12f436a1b05990764d30e3d7db51fe5690cb7.nq.gz

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

[axios/axios](https://github.com/axios/axios)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
