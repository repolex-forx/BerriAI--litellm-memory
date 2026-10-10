# Repolex Knowledge Graph of BerriAI/litellm-memory

RDF knowledge graph data for [BerriAI/litellm-memory](https://github.com/BerriAI/litellm-memory), parsed by [repolex](https://repolex.ai).

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
rlex download BerriAI/litellm-memory
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 283454d0737ffd4286174f1207ba64ac9d2ea589
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 283454d0737ffd4286174f1207ba64ac9d2ea589
│           └── chunk-001.nq.gz
├── blob
│   ├── 04af25967223cebe29e17deba82cf79414cf5752.nq.gz
│   ├── 072cde019ccff9797851508bff919fbfd71c6780.nq.gz
│   ├── 07934d324ae1095b832330c39040d5965eadb639.nq.gz
│   ├── 090eff1e8d4df1387ef6911157999da06963496f.nq.gz
│   ├── 0a54bdbc1624664b865df6d33b424423012ad80a.nq.gz
│   ├── 0cb8d6ad10c84f23b55501a50495a411f2ccd75f.nq.gz
│   ├── 10b9fcaa39c847487d58ba445b003ca2f289ddf3.nq.gz
│   ├── 11aa3e31d6c53e35400e090e8e4e4a1f333d240e.nq.gz
│   ├── 12001b3e70813acf7b4df1474824b77e04dcf524.nq.gz
│   ├── 15bead6d850db5c8ce9a7ef676404a9088f34d93.nq.gz
│   ├── 19b552204ab7699d3fdedb62631a34a20c883850.nq.gz
│   ├── 1bb728bbfd6f4939eb6f53eb5b47be335998e87c.nq.gz
│   ├── 1d42aaaa7799c60606cc7ce6fe2a5c307895470e.nq.gz
│   ├── 1e0a36cd213c243dfb946f4769747c2153e3841c.nq.gz
│   ├── 2008a929f45e4f78c630c915df1fad7052c074b1.nq.gz
│   ├── 290497fa66ac634b39c65258e4e53704428fcafd.nq.gz
│   ├── 2a56b63db006219b4131c7ccc573468ca3362730.nq.gz
│   ├── 2b16dfb60c78bf3746074d5cde7d3981c56c8d66.nq.gz
│   ├── 306289481f68d9f526276363ffd8925e0aba804b.nq.gz
│   ├── 3372d9ec334eea83e8f4926db82774cfb5f970ff.nq.gz
│   ├── 344d4dba9015e1850b4a093032659b06065b6ac3.nq.gz
│   ├── 34537488267276ed39547c010d57f73d7a37f80e.nq.gz
│   ├── 36b7cd641018301450907da086e944952b4a0816.nq.gz
│   ├── 3795c1ad85d2e5bf8501ede379dddc8d6d751369.nq.gz
│   ├── 3b799eb7b938b8919197db0c605b0ed9d816e153.nq.gz
│   ├── 46d76e9f68827950658ea49b74f41e12cccaffb5.nq.gz
│   ├── 47f4d1060248ba59f2b729b2d24b217518d5980d.nq.gz
│   ├── 4d1d8c5481ee0923ec1d56869f1a8d6dba351962.nq.gz
│   ├── 53bda1cd09f3e9b63e9967a8a3e230d7cf7c7fb5.nq.gz
│   ├── 54ec936d4fb7a84d825e8f0fd36a7e07d5449f2b.nq.gz
│   ├── 5561824ce2a20f58893fea136b7466ea3ee7f252.nq.gz
│   ├── 57ca2e0c79ce744212cf6d1f819841924039b1df.nq.gz
│   ├── 5a4ad3a670f8ddb3eced5610a2df250a46d1cd22.nq.gz
│   ├── 5baf1b4334e141bab9cf5d2c3729dad2d95c905f.nq.gz
│   ├── 5dff0c6b4aea6be1d3a830dfdc0654cd640d00d6.nq.gz
│   ├── 5e8805ca8d7a75d28a1db75a2579fa6b6861d404.nq.gz
│   ├── 6226d0a2edfa341a81f58c74441ca516135ea445.nq.gz
│   ├── 62892554cab554b433b92e5f3daff4634251e3f4.nq.gz
│   ├── 6423e8bdd2fdd2e3945abd1b46a0189adb835a65.nq.gz
│   ├── 64737d300e18ddd75f7b131c6f51f2d0e4ffe4cd.nq.gz
│   ├── 675cb06ee8b3c3c8784eb30c15f37184ac424507.nq.gz
│   ├── 69f14a4bc9bcde6bebeff979394c5a27ce455baf.nq.gz
│   ├── 6faeca3e411bd4736c911fad8b22b4ca678bb7af.nq.gz
│   ├── 737355ec6b8ace3b474b4c127e9ccfc2bc26c0b5.nq.gz
│   ├── 767c291d5f3f515a080292027be88c7de7e1d9d2.nq.gz
│   ├── 76827101f80d3bebffcc31132e135a3aa835c1b2.nq.gz
│   ├── 786ace25c7043ec27d4664e24dd28e8e7397e527.nq.gz
│   ├── 79062255c6e3c1941af68e204e3d769ef003dc40.nq.gz
│   ├── 7b3a79f4bb484bebcf6ef342371f774b24981d82.nq.gz
│   ├── 7c682b3b4ed546ce1e6dca4ccc2ff7122880e10f.nq.gz
│   ├── 7f588861cf49d2a6f22c4d8a0f4dc1eed7f4a9f8.nq.gz
│   ├── 7fb6583ffc9df5892d73d19463f2a0972576e383.nq.gz
│   ├── 80746be7df9480f580c39434197baaf613d2df60.nq.gz
│   ├── 81ae1a680f7b5ed35813ab8e6da279272ec95038.nq.gz
│   ├── 83e342b2d8ab6da7ab7e451f3fa188972b8a7832.nq.gz
│   ├── 8435c8aa32b7f77b42cef9a8c48e3d61124ccd5a.nq.gz
│   ├── 8457cf012419e771c6cfef4e68f36af5ced1e595.nq.gz
│   ├── 85d53673015db050ed755ea26c200d10b865ba9b.nq.gz
│   ├── 85e0e55773912e1442390efc6754934a8c910939.nq.gz
│   ├── 864ddb3b1d736df944708048ce0c395229ffbafd.nq.gz
│   ├── 878cc8a23151b6ea583ef69b2d0f6e5c0c59a863.nq.gz
│   ├── 880a829b0f83669e7e00a55b3007919efe3f852e.nq.gz
│   ├── 89a5fd53a96a64dea78d4ae61dd4f0923b87cd14.nq.gz
│   ├── 8aa0a6c53ab1d02f8dc7920728ffcf60c4287a2d.nq.gz
│   ├── 8abf57b8bb9cfbe5e0c3b48ed7236f9d48218761.nq.gz
│   ├── 8b2fdf180ff1fadb9b8444c56ce91929cc4dffec.nq.gz
│   ├── 8cf626a4f9967cd93e370531272288210299202c.nq.gz
│   ├── 8d19d2f448d3a71f3ef8c825fb7f386efecc8be2.nq.gz
│   ├── 8e3563db890a3215e8c8127ea91225450f98d9dc.nq.gz
│   ├── 8fb6380ce84d1790695ca713121c19f0fe3787c5.nq.gz
│   ├── 92361187cf7142c69515a6b21f69260f1fdd1efa.nq.gz
│   ├── 98b8b06b3e441b912176d7f841e1b494eb3b98fa.nq.gz
│   ├── 9b024afc8d94e070aab7701aa801419245fb2d96.nq.gz
│   ├── 9cdc5ac8c02f0c3d51311680335695682265a50d.nq.gz
│   ├── 9d55310ad3ee1e3972035bee362da5b5e680b187.nq.gz
│   ├── 9fca3c7d78657650f4c0b902ff066004d113e059.nq.gz
│   ├── a0d14902f610a8bab19f0a7d08241a145849c6dc.nq.gz
│   ├── a13580b2cb0d8c3e587525f43a1a5fc8cb672f30.nq.gz
│   ├── a308a2e432ae0b46a958a01980ed181122098b4d.nq.gz
│   ├── a414fcfb531f38560ecf6858e04255df6493f440.nq.gz
│   ├── a85f7e16168c6979d38584e4010c70f67d49b261.nq.gz
│   ├── a9391dc914266bf3bd1d48de76f29eb5148be351.nq.gz
│   ├── aaacf930a750056bae3246d33951a89b82ef9bd8.nq.gz
│   ├── aae5c8ba24ae41db6b1c4260b662603ca80a328d.nq.gz
│   ├── abde993ffd143a1e40f8658cbb51c4c91b346ba3.nq.gz
│   ├── b4bffd29f67a5b9cc5090c23746a3ba19652f2fc.nq.gz
│   ├── b4d52e43ec9737e0e06ee07e0646312cc4bd5f4d.nq.gz
│   ├── b7ec9afd642a85be768a5b8693411184d5161f24.nq.gz
│   ├── b8e56ad9c2a6d9d34f488155d8b156763540910a.nq.gz
│   ├── b970902afd13ddb581297d58fdb9c71eadcdb0d3.nq.gz
│   ├── bbb9d4bfba42e3036aece7eb1a378d6c01c566f7.nq.gz
│   ├── be3f7b28e564e7dd05eaf59d64adba1a4065ac0e.nq.gz
│   ├── be64d897fb81271dc181b65b2a62771267207dc5.nq.gz
│   ├── bf6f670912bb942a3d60eec16e34ab46338243b7.nq.gz
│   ├── c01f803f54e68937c57195cf699558c7e0a5d09d.nq.gz
│   ├── c138de80d6eea5b313e21c20567bdb9fb8583b2b.nq.gz
│   ├── c504d63bdfeac04d0fea82be0df4409e5dc1ea76.nq.gz
│   ├── c51be3e94bdd31f7e513c86a2779d8118ffe8751.nq.gz
│   ├── c677b01bc1286b498a15036c6c4caba8917123d0.nq.gz
│   ├── c69b2e7d0f6adda0eb3246c8a818f930667650a7.nq.gz
│   ├── c7e5819d854adac4c298fdb9864a04fcd6a78e8c.nq.gz
│   ├── c80affb2c4ff36a5780e3dbdb2ff2a7d072cee91.nq.gz
│   ├── ccbbacdeb35d07bab25b7108d5e8c281f0ac2f5f.nq.gz
│   ├── cce57980017798e164092c2ae9d183358862ad4d.nq.gz
│   ├── cf9b1ccfb43eba15cdf256905fe26136c512d427.nq.gz
│   ├── cff4a0dfbbafe0b284beca0c297f9da3da339753.nq.gz
│   ├── d4044b37a3fdfdd2f8ea4f0764486015c664475f.nq.gz
│   ├── d704218aff4e43f1de58e27f3f457feba38d006f.nq.gz
│   ├── dacaa868a70bcf616a5543d4c455ef3c5071576e.nq.gz
│   ├── db0c83c960c637cb73fa3cbd9d40e2654865a1fd.nq.gz
│   ├── df1ee5465f96b4bf7b6c4dcfb9a5b6f3a1480a2a.nq.gz
│   ├── df80da57fb675aa59d179f1045863c2513d37691.nq.gz
│   ├── df9d8420d61ebfa9920cac91d75eacc58397de32.nq.gz
│   ├── e04ad20b8019325ba380474fea06d4891d966a58.nq.gz
│   ├── e1747633c306235435df3c3da4f2c2c09e1742da.nq.gz
│   ├── e5382a5cf81da44935ea0e735a96bde4e772b02b.nq.gz
│   ├── e7991568def470dc936b8cf0d3a84baa64ad4cee.nq.gz
│   ├── e7d11fa5a59b2d1b93642f6f1fbe9e225239b15c.nq.gz
│   ├── e8256558bd2975a51bdbf397f4460804fe2285b6.nq.gz
│   ├── e888e0a2b0ccf2eca62d5e22a20728b6b3e3b702.nq.gz
│   ├── ea1ce1cea347b02e6fd6790918dd7779248d66c9.nq.gz
│   ├── ec44a3d713e400d3b0ee81d1eea9067be7e67754.nq.gz
│   ├── eefbb6f0ce753a6e5f0d425d15248e8ca66d1dc7.nq.gz
│   ├── f017f2a17ebcf29aa08c662d77bffaf3e314e667.nq.gz
│   ├── f13910a0affc537799d199f363a73a052bec6f10.nq.gz
│   ├── f140c7be4d93ff2428d73aa3edb3a1ac439ed12a.nq.gz
│   ├── f273fa1ff0974960467947286657484868829cb2.nq.gz
│   ├── f9472afd84b03eff2cc4c0e59104536d673c2d2e.nq.gz
│   ├── fbfe00acb08c2b95183af361b87a88d3c1341e79.nq.gz
│   ├── fc0d1af0a697af82de61abf8936a9351baf44734.nq.gz
│   └── fdeada73b8be614442f8c61dc177413317ab477e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 283454d0737ffd4286174f1207ba64ac9d2ea589.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 138 files
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

[BerriAI/litellm-memory](https://github.com/BerriAI/litellm-memory)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
