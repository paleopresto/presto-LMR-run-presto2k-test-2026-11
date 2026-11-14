# Test: PReSto LMR run on the revised Presto2k (PAGES 2k criteria)

A test, not a Presto2k version. Presto2k is being revised to follow the PAGES 2k (2017) criteria, temperature only, with annual uninterpreted coral and sclerosponge temperature proxies admitted with the sign their proxy implies (presto-recipes branch `presto2k-pages2k`).

- Data: presto-recipes pre-release [pools-2026-11-03b-test1](https://github.com/paleopresto/presto-recipes/releases/tag/pools-2026-11-03b-test1), pool [`presto2k_test_lmr`](https://github.com/paleopresto/presto-recipes/blob/pools-2026-11-03b-test1/pools/config/presto2k_test_lmr.yml): the 716 records presto-LMR can assimilate, from LiPDverse export 2026-11-03b. 113 records carry a sign implied by their proxy, written into the bundled files as interpretations, which the interpretation screen enforces.
- Code and config: those of [presto-LMR-run-presto2k-0_1_0](https://github.com/paleopresto/presto-LMR-run-presto2k-0_1_0), unchanged, so this run differs from that one only in its data.

Committing `query_params.json` triggers the reconstruction workflow.
