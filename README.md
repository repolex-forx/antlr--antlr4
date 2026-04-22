# Repolex Knowledge Graph of antlr/antlr4

RDF knowledge graph data for [antlr/antlr4](https://github.com/antlr/antlr4), parsed by [repolex](https://repolex.ai).

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
lexq download antlr/antlr4
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 10e7f2af3b215991e168e443225d1eb70bc618db
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 39e1719064f0b842884fa6afbe6848f027598b8e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 44d87bc1d130c88aa452894aa5f7e2f710f68253
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 5bd7f9ea4822b231a93f8b34e8c91a2387a0e208
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── bf0bbff4bff0c7fb33704ef7c4699314715efb2c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── c7567ba9bb40c361dda60e60e2bc932a16d2adf8
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── cd8f367ca010eb59defadf3df622793bc3a8afe2
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── d23f010a3642a650076caea5a03b586cba37d7a0
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   ├── 10e7f2af3b215991e168e443225d1eb70bc618db.nq.gz
│   │   ├── 39e1719064f0b842884fa6afbe6848f027598b8e.nq.gz
│   │   ├── 44d87bc1d130c88aa452894aa5f7e2f710f68253.nq.gz
│   │   ├── 5bd7f9ea4822b231a93f8b34e8c91a2387a0e208.nq.gz
│   │   ├── bf0bbff4bff0c7fb33704ef7c4699314715efb2c.nq.gz
│   │   ├── c7567ba9bb40c361dda60e60e2bc932a16d2adf8.nq.gz
│   │   ├── cd8f367ca010eb59defadf3df622793bc3a8afe2.nq.gz
│   │   └── d23f010a3642a650076caea5a03b586cba37d7a0.nq.gz
│   └── repolex
│       └── cd8f367ca010eb59defadf3df622793bc3a8afe2
│           └── chunk-001.nq.gz
└── blob
    ├── 0005d4bd9948182df0f48271016d671e3e9ead26.nq.gz
    ├── 0026fded92b6a41b120fc6f12ec7c1043bef4815.nq.gz
    ├── 00315d0c7f6100fc3a69993c4c16b4cf415d4d27.nq.gz
    ├── 004cf346559b059dc09c975e2b1cae48e5979e1e.nq.gz
    ├── 006d29ecf89902fd2dd8ef428dbeb831b8e36231.nq.gz
    ├── 0075ad510d97d6c0b8d86a86f7607175f2945c35.nq.gz
    ├── 00764bbfa0c0ef7047c4f1120fb5672b68c919e4.nq.gz
    ├── 008018df01b6d2688cab9693e77b665e3d800a54.nq.gz
    ├── 00812caad08923277efb80b072d952d89b591ef3.nq.gz
    ├── 008e7a7c561958795dd8134a81e64898b704f197.nq.gz
    ├── 00c1065461b12b7cefdecb23944d519e5cc25b05.nq.gz
    ├── 00e05b7cef11e59f295582daf1ba718a0e8f6ea1.nq.gz
    ├── 0105b80e74a5a79d9751e12336493c2acc16153c.nq.gz
    ├── 0105c71521798b2d612e394e2d0ab488be558007.nq.gz
    ├── 0111e9e792440f496e30dbfe60c9e31d59473f9c.nq.gz
    ├── 015f9d577c81a77843573409516eea0721028d51.nq.gz
    ├── 0173db74293853e21641b4cbf46ecff773bc358e.nq.gz
    ├── 0178dc5a78e8023bf145e47f35a582c9a55de566.nq.gz
    ├── 017f22bb6708cffa2ba3dff94e5cdba8fcd353c6.nq.gz
    ├── 019762d268c89a8bc821c9bd779cf77e7066e345.nq.gz
    ├── 019c34efdf7b22104d98fdab740bce881e22fad3.nq.gz
    ├── 01b976d4457faecf2a76bd19afe8d94866ac0325.nq.gz
    ├── 01c7a4a6255aa22603859750dccc2d2853175610.nq.gz
    ├── 01e76e617e34e48ed725fb8e6ff21570ff3d837a.nq.gz
    ├── 01e964261601f3e31a274d8d405fad45b3089b6b.nq.gz
    ├── 023dd671e5d646d4ce88209cc72f25ee56711fa8.nq.gz
    ├── 024bd4c0431fc995f8dcac05916ead918f1488b4.nq.gz
    ├── 025ae46d407303fe5ba95931a33c3ad9ed225a4c.nq.gz
    ├── 0265d56bc5ff08674265ad6851209cd209534a79.nq.gz
    ├── 0280ce846ccc7a16eeb9756ccab2c7e1edfce72e.nq.gz
    ├── 028e1a9d7f035ac0971557d63f536724109421ed.nq.gz
    ├── 02a56b69c948628093237850ba33cb6e1326f798.nq.gz
    ├── 02b433e98f56f48a4a1a8145c43c9ee75f92648d.nq.gz
    ├── 02b5ee51036c89a64175052987c40d2aabcf035b.nq.gz
    ├── 02edfb4919a05458314ca648a4000fbf3d3a5a7d.nq.gz
    ├── 02f5b39d051caac8a07a017e8b6f8d6a9f915eab.nq.gz
    ├── 031a35cbf7e873143485d3295a7c1a6cc5ed5c32.nq.gz
    ├── 034019f7bc8ac1f0747ebec7e2cacc060f0dd88e.nq.gz
    ├── 034ae46e22744f133e1d9645ccc88ca9d04678fa.nq.gz
    ├── 03a1e82fe0a83ebd2dbf08f09b1cae5690019029.nq.gz
    ├── 03a8d7c42b09bb8f30ad3940bce640e2011fced6.nq.gz
    ├── 03abf0237c8e800d0e7a5a25766bceb205dd7d38.nq.gz
    ├── 03aecdca9853355277620058d47d8470c9c4426c.nq.gz
    ├── 03b6101a98524693823e51786b6861b0394ef4f3.nq.gz
    ├── 03b6ebd3d89166a051bb34d2dec8928230fb608c.nq.gz
    ├── 03fd0aa281ef0e9a53f6c7870dec93407359ceb8.nq.gz
    ├── 04159db536cba871844c5b50a61601d1ca901a82.nq.gz
    ├── 04367523b5d48e40a920480ad990fa4abfe853d5.nq.gz
    ├── 0452b2bec9ef52bea513e39f7eb33f878e9fc728.nq.gz
    ├── 045bc121f1802a8474bcf544eb3d3512ae73c119.nq.gz
    ├── 04969927f32a0620a7c230cb1c7fb41627eb8dae.nq.gz
    ├── 049e28357ce5ab5deab249e7e3d36ef1355b5d03.nq.gz
    ├── 049f1d86166ead3dd737bede8bfbcd251d1aba85.nq.gz
    ├── 04af4bf1bdb609ec0356fa03e1107b7bd0bf2e82.nq.gz
    ├── 04b852d98608a9d77dc2969fb05595fe17a64816.nq.gz
    ├── 04be6f240d05a13c3972c0d51ca06354dbb54f5c.nq.gz
    ├── 04f2dcf506ac21ad6bfaffeee482766bedfbace8.nq.gz
    ├── 051a2a41530e3cd0e09b3c5dac63282e22bb3b8f.nq.gz
    ├── 053a357d8d3b497b65c3dff5e2ac5255052bff78.nq.gz
    ├── 0549dfa00fc3f1b39e7057b0072a7a9cb05839dc.nq.gz
    ├── 055f8bbdab9ff18b93870a304b994d33dfeae191.nq.gz
    ├── 056941dd6e7f0491a558ded65a01a5a9a85b7470.nq.gz
    ├── 056ea963a15eeecdcaedd7d96a11078227f08e19.nq.gz
    ├── 057d4ed8ba029e87985b03d705677dc887c68cc4.nq.gz
    ├── 058d98703e6381561b748c6853070595ff57578d.nq.gz
    ├── 05a19a7aa59a121de2819c008ce62ce1edae96cb.nq.gz
    ├── 05a51c7b3cd777be049060408aad68c44edf7f1b.nq.gz
    ├── 05b9638a0d261a431ae615e74aef618f2cc4221f.nq.gz
    ├── 05bf8eb6fcc4c49f0fa376175cef27b322db4898.nq.gz
    ├── 05bfbabf3e5414ac8e0b65d82655918c5112870e.nq.gz
    ├── 05d54d84509189c9d757f60b322554632a33b403.nq.gz
    ├── 05d804f63995ef34629d0aad99357ce07846aec3.nq.gz
    ├── 05da75acd2b5ba8de85e3a68b35c466323f58c7f.nq.gz
    ├── 05f137a03fbe8817b8e9ec80db30f8125682f59c.nq.gz
    ├── 060317920fb4dd90296ce33eb29fe51c9956e05e.nq.gz
    ├── 0606acf6afc8b4f3455d7f9e6241dd0ed6a2095b.nq.gz
    ├── 061e2ff69e9e41ecc1e333d33006a43f937052db.nq.gz
    ├── 062f2da1dc0cca8e9b4899face848a0ff8f83186.nq.gz
    ├── 0637ceed80246549c721dd00a11fd17ef37a8007.nq.gz
    ├── 065bc87a4721136222349d9bf7b770a3cd540a92.nq.gz
    ├── 067fa21cac5e6186ecb1969650b7ad17addbe66c.nq.gz
    ├── 069c6d612b1ed73cae6ab3f31a3c70e4730239f8.nq.gz
    ├── 069db0a830fe64dc2ca0f2a0151336870be95a3d.nq.gz
    ├── 069f58622f642ee6f84663498d2e4cf8e805b9e8.nq.gz
    ├── 06a5e0b5ece96c9e262dffef57253c27d2eb5c9f.nq.gz
    ├── 06d8a6f48ba7548737076ef0feaf4937e40d8978.nq.gz
    ├── 06dac1f243314050598a2f349bf9539df31d05ef.nq.gz
    ├── 06dc777133f4fc0c753b7d111053be4728e6a166.nq.gz
    ├── 06df74ddfbeda648eacebcedc773efa34df6fd3f.nq.gz
    ├── 06e1d41d9c240481f2c465eb165ea1a6137e8369.nq.gz
    ├── 06eacddfb1b5361189c6a101a20640ee473a647d.nq.gz
    ├── 06ece5d552df4725bb8d437e064ce81b718ebbe8.nq.gz
    ├── 0780b4c25db4f089de650d0f80cdcac16222cede.nq.gz
    ├── 0798c37b68f8dffdd543a726cda4c9abd2055f6d.nq.gz
    ├── 07ccf6d76ba04691c065c95b5d228a9a777af5e6.nq.gz
    ├── 07e142d4f2de20703405dadc1874928a76c25533.nq.gz
    ├── 081419a34f65463b370b848b141192bfe491befd.nq.gz
    ├── 08186b120f3a0080ff4568fe378d808cc3f6a414.nq.gz
    ├── 08232bd435d6fdc7f3d998469d86d1382a2e76cb.nq.gz
    ├── 082ce549597a4717a783d1241d65746a2d529d1b.nq.gz
    ├── 0866e20c501d4caa05aaec3d630a0b66db229248.nq.gz
    ├── 08670087a8e6d88514b06e5772dc84faa1054dab.nq.gz
    ├── 0892af9ca070f5cd11ca2ba7a98437412dd840dd.nq.gz
    ├── 0896e4874f2e0732139a47c0703f9c1fde2a8220.nq.gz
    ├── 08a093c4545aaf027ca63888349bde252373b1d7.nq.gz
    ├── 08a5fac119a9b2bb85fbe08064d7287545ef9830.nq.gz
    ├── 08c3fc16ce3755dd31d5e5278a99af6364d2676e.nq.gz
    ├── 08ce22bba39dc66a05099228a5a2c0c995e8d1f5.nq.gz
    ├── 08ef67c58f7c89e8259450ce0b160e3afdf5601c.nq.gz
    ├── 08fe7e5d1e6099a18f5d2aab112b4804f57e2882.nq.gz
    ├── 09072c9f7e38ce07c7a0f5eb5ac2201ec6c5e2ee.nq.gz
    ├── 0908de123d9b2d1c8ed1f457b0f55a0ff5ba098c.nq.gz
    ├── 0909c68a822d09741cd5149ed6149046d53fc184.nq.gz
    ├── 091b00455a7bf39ab077079b4fc57629aa09b129.nq.gz
    ├── 0930abf308a173f52b5f5204670da00af0d5e149.nq.gz
    ├── 0946880cec451ac5237532bbde607286de808fb9.nq.gz
    ├── 094eda52c7c7c75aadf0dc05e5bb73776b5019ab.nq.gz
    ├── 0986686745bf7ec6eb56ef29128ffda8f8395b18.nq.gz
    ├── 0986ac6c039ce412ed1df86c0a4c3c46eb35267d.nq.gz
    ├── 0993e386292d376f4c177a997a620ac18904b319.nq.gz
    ├── 09d97c7f1e49a0db8be5bbb36330f3491c9c55df.nq.gz
    ├── 0a0622e67ce186245c7a456b9b28e68aaba1ca47.nq.gz
    ├── 0a0d802dc0e66722c93ed21575d6215676dbab84.nq.gz
    ├── 0a2317bab396e362dd186e83c69b5834e57db983.nq.gz
    ├── 0a290c3e657d60b61f4dad7cbf60e507391682de.nq.gz
    ├── 0a5860edee67a0eaf2bfd53a86b58ea96dbe5dc6.nq.gz
    ├── 0a747c4c349e708232b69c0bc38c1fd3d3fcb467.nq.gz
    ├── 0a7b3564c0d24b203851659cabe0d625a0664b6e.nq.gz
    ├── 0ab2894551ee12bfa212e5a60e8ec02028aee293.nq.gz
    ├── 0ac117f5f22b090ec9b28a733aad5d6d6097ea2e.nq.gz
    ├── 0ac8f8c79f939621c3a9405e51e0fa0648109107.nq.gz
    ├── 0afad6065eac563b64428b5fdfa1d712db150e28.nq.gz
    ├── 0b031327bf194cf1eb89b1b154bfa27d7cce13c1.nq.gz
    ├── 0b13ea23c4303bcaaaa0b681b0a87fb1cf541b22.nq.gz
    ├── 0ba7804319097e41a56905167c461755d9e6b53a.nq.gz
    ├── 0bb12fd98b465e56914c1c7b131eae0b05723be3.nq.gz
    ├── 0bc4b86d15ee5fc1ad23504133a8ebef0b2646dc.nq.gz
    ├── 0bcaf07b54f020a727b8bcc162f9014c4c886528.nq.gz
    ├── 0bffcd235d600eea2abe9455fc9708328c781e4c.nq.gz
    ├── 0c232e641ccce22e04c0f8ca33de02b1071c9b34.nq.gz
    ├── 0c3b39c43375a0564dc416dc3b88b3d1241684c7.nq.gz
    ├── 0c5834034dfc7787a2e01a23f74dda9fbdd74e2c.nq.gz
    ├── 0c5e020a08affc5024339316face8506f170e102.nq.gz
    ├── 0c64b08cb8c00e5f6f277ff756949e851f21c793.nq.gz
    ├── 0c6b9afce71d4db9508979f1416ffe401437c672.nq.gz
    ├── 0c71e3942094e4a798a15e2a7ca342ac50c94cbf.nq.gz
    ├── 0ca7d3fd9c199d8780c3c760ebb3d7aa7a3e75b7.nq.gz
    ├── 0cd0b1f39e381eff3c93123e963c0eb38e6c9148.nq.gz
    ├── 0ce5a3aceea53e15ebc84cb63eeee43ebf87c723.nq.gz
    ├── 0cf1222e077a404082e2c4bc6962145e48b88fd3.nq.gz
    ├── 0d09ad78598de14f7a32d813c667e877ef1c0f6c.nq.gz
    ├── 0d142f306149418ac40705477860d38ca5d0d644.nq.gz
    ├── 0d1a494597e01ce21a63c63cf2e0a4bfb9815851.nq.gz
    ├── 0d396dfcbbb1413eab35d16e9236db9207f956d0.nq.gz
    ├── 0d41bb0ce1af3f3f753ef4c23cbcd031aa6ceaf6.nq.gz
    ├── 0d4eac698dcc708338b231474d142aac0867c37e.nq.gz
    ├── 0d6f62c5284b60e22b76251a5eb2f78c94d11b33.nq.gz
    ├── 0d76281263a0232e4021af33ad78afd6ea38a954.nq.gz
    ├── 0d7f923820ccb7b1b06c16e6ee1acb76e98d7f47.nq.gz
    ├── 0d880e3840f87833baabf72d7e0a71e2598811be.nq.gz
    ├── 0d8feb62141e70b987aa2f13ba9232b13bf3286d.nq.gz
    ├── 0db6f4d1fd04af04ec62fb7f8bf9b830fa737982.nq.gz
    ├── 0dc40841e6cee4e31e166b9e5ec2f2f83e6d54db.nq.gz
    ├── 0ddcdca335495a1ae27942913149b69a835265d5.nq.gz
    ├── 0de14834321ab1bbd507e3cfd086410e7434aa6c.nq.gz
    ├── 0def6a57ad03d68e383e73ca67feef576c704090.nq.gz
    ├── 0dff1f2b0232fffb9ba1dadf57c2877aab190c77.nq.gz
    ├── 0e27cd13e642d7856d92bdccfd0b7fce25626744.nq.gz
    ├── 0e44e009ad3129d5d6b6bfe7c70deafc059f5dfd.nq.gz
    ├── 0e5dd4c974b264f03ec8349ead7986537f4e60ad.nq.gz
    ├── 0eaffead020a1a32d52c42d13adefe66ed0bacbf.nq.gz
    ├── 0ec2a9359ec876e94198110f3d8649ddc94bcb76.nq.gz
    ├── 0f296978743adbde8f68bd382efa25add7b505d9.nq.gz
    ├── 0f2b65f7d269de46ce436d644b0369959cde788a.nq.gz
    └── 0f3e109b4b143ea1602481cbf9241d5a2e72b17d.nq.gz

15 directories, 200 files
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

[antlr/antlr4](https://github.com/antlr/antlr4)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
