# Paper 7: The Endemic Baseline

**Subtitle:** When $B_{reference}$ Was Never Set — Calibration Formation as a Primary Adaptive Mode

**Author:** Brandon Everett  
**ORCID:** [0000-0001-7521-5469](https://orcid.org/0000-0001-7521-5469)  
**Series:** Memory as Baseline Deviation — Computational Labs  
**Depends on:** [MBD-Framework](https://github.com/YellowHapax/MBD-Framework) (Papers 1–6)  
**Succeeded by:** [Suppressive and Emergent Phenomenon](https://github.com/YellowHapax/Suppressive-and-Emergent-Phenomenon) (Paper 8)

---

## Abstract

The MBD framework models cognition as deviation from a reference baseline. All
prior papers assume that $B_{reference}$ encodes a prior legitimate healthy state.
This paper addresses the foundational case that violates that assumption:
the **endemic baseline** — $B(0)$ constructed during chronic disruption. When an
organism has never occupied a stable healthy state, the reference vector does not
point toward health — it encodes the only conditions the system has ever known.

Three specific consequences are formalized:

1. **Healthy-input rejection:** the same positive input that moves a neurotypical
   agent toward health reads as maximally novel and maximally destabilizing for
   the storm-born agent — whose only attractor is the conditions they were formed in.

2. **Horizon invisibility:** the healthy region $H_{sunny}$ exists in
   $H_{accessible}$ but not in $H_{agent}$. The agent cannot deviate *toward* it
   because deviation requires two points and they only have one.

3. **Intervention failure:** standard restoration-to-baseline protocols
   predictably fail. The corrected framework — the **Re-zeroing Protocol** —
   replaces restoration with construction: scaffolded micro-excursions into the
   Horizon, κ-building before novelty exposure, and distress held as
   navigation cost rather than failure signal.

The paper and the labs are the same repository. The $\LaTeX$ mathematics and the
Python simulation are parallel expressions of the same claims.

---

## Contents

| File | Purpose |
|------|---------|
| `PAPER_7_THE_ENDEMIC_BASELINE.md` | Full paper with formal mathematics |
| `labs/paper7_endemic_baseline/phenomena_endemic.py` | Lab 7a — calibration formation under healthy input (P7a) |
| `labs/paper7_endemic_baseline/phenomena_rezeroing.py` | Lab 7b — Re-zeroing Protocol vs. flood vs. withdrawal (P7b) |

---

## Running the Labs

```bash
pip install -r requirements.txt

# Lab 7a: Three agents, identical healthy input, structural difference
python labs/paper7_endemic_baseline/phenomena_endemic.py

# Lab 7b: Re-zeroing vs. Flood vs. Withdrawal
python labs/paper7_endemic_baseline/phenomena_rezeroing.py
```

---

## Series Context

This is Paper 7 in the Memory as Baseline Deviation series:

| Paper | Title | Repo |
|-------|-------|------|
| 1–6 | Core framework | [MBD-Framework](https://github.com/YellowHapax/MBD-Framework) |
| **7** | **The Endemic Baseline** | **this repo** |
| 8 | The Suppressive and Emergent Phenomenon | [Suppressive-and-Emergent-Phenomenon](https://github.com/YellowHapax/Suppressive-and-Emergent-Phenomenon) |

Paper 8 builds directly on this paper's formalization of the Horizon $\mathcal{H}$
and the kappa-coupling threshold derivation.

---

## License

Code: Apache-2.0  
See `LICENSE` and `NOTICE`.
