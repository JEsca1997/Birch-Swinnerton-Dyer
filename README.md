# Birch–Swinnerton-Dyer Conjecture — Proof for All Analytic Ranks

**Author:** Joseph Robert Escamilla
**Status:** Preprint — complete manuscript, not yet formally peer-reviewed
**Patent:** US 11,954,561 B2 (Reissue Pending)
**Repository:** https://github.com/JEsca1997/Birch-Swinnerton-Dyer

---

## Statement

The BSD conjecture asserts that for every elliptic curve E/Q, the analytic
rank r_an = ord_{s=1} L(E,s) equals the Mordell–Weil rank r = rank E(Q),
and that the leading coefficient of L(E,s) at s=1 is given by the BSD
leading-coefficient formula involving the regulator, the Tate–Shafarevich
group, and the periods.

## Synopsis

This repository contains a proof of both parts of the BSD conjecture for
every elliptic curve E/Q at every analytic rank.

**BSD-1 (Rank formula and finiteness of Sha):**
Proved unconditionally for all analytic ranks via the Iwasawa Main Conjecture,
with the OFI framework organizing the descent from the Iwasawa algebra to the
classical L-value.

**BSD-2 (Leading coefficient formula):**
Proved via the OFI commutator identity [I∘D, D∘I] = 1/12, which identifies
the OFI regulator term (I-arm) with the classical BSD regulator and the OFI
L-value term (D-arm) with the leading coefficient, establishing exact equality.

The Tate–Shafarevich group is shown to be finite for all ranks as a
consequence of the Iwasawa structure.

## Contents

| File | Description |
|---|---|
| `BSD.pdf` | Complete preprint manuscript (all analytic ranks) |

## OFI Framework

This proof depends on the OFI commutator identity [I∘D, D∘I] = 1/12 and the
Riesz potential semigroup. See the [OFI repository](https://github.com/JEsca1997/OFI)
for the foundational theory.

## Patent Notice

The Ordered Fractional Integration framework and its applications are covered
by **US Patent No. 11,954,561 B2** (Application 17/099,574), with a broadening
reissue currently pending before the USPTO. The mathematical results in this
repository are provided for academic and research use under CC BY-NC 4.0.
See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md).

## Citation

```bibtex
@misc{escamilla2026bsd,
  author       = {Escamilla, Joseph Robert},
  title        = {Proof of the {Birch--Swinnerton-Dyer} Conjecture
                  for All Analytic Ranks},
  year         = {2026},
  howpublished = {\url{https://github.com/JEsca1997/Birch-Swinnerton-Dyer}},
  note         = {Related patent: US~11,954,561~B2}
}
```

## License

[CC BY-NC 4.0](LICENSE) — Free for academic and research use with attribution.
Commercial use requires a separate written license. See [ACCEPTABLE_USE_POLICY.md](ACCEPTABLE_USE_POLICY.md).
