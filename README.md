# MIS Stake Pool

**Moniversive Invariant Static (MIS)** — Creator **Chandler William Ferguson**

MIS-only (`.mis`). Compiler `bin/misc`. Settlement **clrty-1 / chain 1202**. Embed gates **3..=6**.

Backlinked to [https://github.com/clarity-fintech/moniversive_invariant_static_ML](https://github.com/clarity-fintech/moniversive_invariant_static_ML), [https://github.com/clarity-fintech/CLRTY-MIS-Kernel](https://github.com/clarity-fintech/CLRTY-MIS-Kernel), and CLRTY-1 MIS catalogs.

## Layout

- `mis/kernel/MisStakePoolKernel.mis`
- `mis/packs/` — 5 packs × 20 = **100** invariants
- `mis/sections/` — MIS + CLRTY-1 architecture backlinks
- `mis/backlinks/MisBacklinkIndex.mis`
- `manifests/`

## Compile

```bash
bin/misc mis/kernel/MisStakePoolKernel.mis --check --compact-letters
find mis -name '*.mis' -print0 | xargs -0 -n1 bin/misc --check --compact-letters
```

## Org

[clarity-fintech/mis-stake-pool](https://github.com/clarity-fintech/mis-stake-pool)
