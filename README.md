# Research No.65 - Preprint v1.0

**Exact Nim-Words and Sharp Preperiods in an Infinite Two-Parameter Four-Move Subtraction Family**

Ryutaro Yonezu - Independent Researcher. 12 November 2026.

Research correspondence: [yonezaemon1+research@gmail.com](mailto:yonezaemon1+research@gmail.com)
Copyright (c) 2026 Ryutaro Yonezu. **All rights reserved.**

For every odd a>=3 and odd c>=L+1, where L=(a-1)(2a+1), this preprint gives
the complete Sprague-Grundy word for the normal-play subtraction set
{a,2a+1,3a,c}. It includes the v0.9 three-phase corrections in
L+1<=c<=L+3a, including a seed of value 4 in the middle band. The least
preperiod is c+L-3a=c+2a^2-4a-1; the least eventual period is 2.
The uncorrected earlier formula applies for c>=L+3a and agrees at the
shared boundary. No optimality of the lower c cutoff is claimed.

## Status

- Independent AI-assisted and SMT verification within the documented scope
- Windows PowerShell 5.1 reproduction PASS (author-run)
- NOVELTY INCONCLUSIVE
- REFERENCES PARTIAL
- Not peer-reviewed
- All rights reserved

This is an unrefereed mathematical preprint. Independent AI-assisted
examination and SMT-based checks have been performed within the documented
scope, with author-run Windows reproduction. The SMT conclusion is conditional
on the faithfulness of the encoding and solver correctness. No human peer
review or full formal proof in a proof assistant has been completed. Novelty
is inconclusive; references are partially verified. Copyright (c) 2026
Ryutaro Yonezu. All rights reserved.

## Public files

- `No65_v1.0_PREPRINT.pdf`: matching typeset manuscript.
- `No65_v1.0_SOURCE.tex`: LaTeX source with the full expanded theorem.
- `No65_v1.0_REPRODUCIBILITY.zip`: selected unchanged Python/C++/SMT sources,
  clean expected output, provenance and relative-path checksums.
- `PUBLICATION_STATUS.md`: gate results and evidence boundaries.
- `SHA256SUMS.txt`, `CITATION.cff`, `LICENSE`: integrity, citation, rights.

The private integrated research archives, raw Windows logs, workstation
paths, account data, credentials, and third-party paper full texts are excluded.
Frozen script comments and printed candidate/HOLD labels are historical;
their computational code has not been altered for publication.

## Reproduction and verification scope

Extract the reproduction ZIP and run `python -B verify_repro.py`. See its
README for Python 3.10+, C++17, and free Z3 installation requirements and
commands. No paid API or cloud service is required.

Publication preparation reran all selected supplied checkers unchanged in
a clean Linux environment: both SMT controls UNSAT, all three intentional
SMT mutations SAT; supplemental direct mex 790 pairs / 2,677,220 positions;
boundary-band Python 1,455 pairs / 16,739,670 positions; C++17 2,588 pairs /
101,872,020 generated positions; structural A/C regression for 102 odd a;
exact affine base certificate 12/27/16 local cases, zero bad, with coverage
and mutation controls. C++ compares the closed extension from n=c onward;
its total includes generated prefix values. Test ranges overlap. Finite
counts do not prove the universal theorem or novelty. The paper explains
the all-parameter encoding and analytic proof.

The Linux SMT rerun used system Z3 4.13.3. The separate author-reported
Windows SMT run used z3-solver 5.4.1.0 (displayed Z3 5.4.1). The v0.12
sanitized Windows record reports the unchanged v0.11 computations, including
the 2,588-pair C++ total. These author runs were not independently witnessed;
the publication editor did not run Windows. They are not second-solver
verification or human peer review.

## Prior art and relation to earlier papers

Ho (2015), Theorem 5 and Table 8 (directly compared via arXiv:1202.2986v3),
already supplies the three-move base arrangement for odd a>=5. Zhang (2024;
author revision 30 July 2025), Remark 7, explicitly records bounded
period-two observations on the same four-move family. Those facts are not
claimed new. Flammenkamp's separately expanded 1997 book, ISBN
3-932136-10-1, remains unchecked in full. The inspected sources did not
establish fatal direct containment, but this is not a novelty certificate.

No.63 (a=3) is included here for c>=15, with least preperiod c+5. No.64
(a=5) is included for c>=45, agreeing with its seven finite cases c=45..57
and its uniform c>=59 word, with least preperiod c+29. The earlier papers'
smaller-c classifications remain outside this theorem's scope. No.64's
wider quadratic expression was explicitly a computational conjecture;
this preprint treats the stated all-odd-a range and boundary corrections.

## Source integrity

The private v0.12 source ZIP SHA256 is
`20f19be1a96b595a4a724bedd21f2b7d4f59176032712cd1337b13394a3aff2a`.
All 19 embedded v0.11 entries matched the original embedded ZIP byte for byte.
All supplied manifests passed. The public kit's ten selected computational
files are byte-identical to their respective frozen sources; mathematical
claims in this editorial TeX follow the v0.9 theorem with v0.11 A/C details.


## Publication links

- GitHub repository: https://github.com/yonezaemon1-hub/no65-four-move-subtraction-nimwords
- Release v1.0: https://github.com/yonezaemon1-hub/no65-four-move-subtraction-nimwords/releases/tag/v1.0
- Release commit: f5a31a85be8a5b8662a79a4cd1e4b5dcf68e4356
- Zenodo Preprint record: https://zenodo.org/records/24162911
- Version DOI: https://doi.org/10.5281/zenodo.24162911
- Concept DOI: https://doi.org/10.5281/zenodo.24162910

These publication links were added to main after the deposit. The eight
Release/Zenodo v1.0 assets retain their original hashes; PDF, TeX and the
reproducibility ZIP are unchanged. The deposited PDF does not print a DOI;
its title, author, date and version agree with the DOI record.

| Core asset | SHA256 |
| --- | --- |
| No65_v1.0_PREPRINT.pdf | `d13f4930767f8d906a0e895015e9ab931e426655c199edf3c5e22438ca1020ad` |
| No65_v1.0_SOURCE.tex | `147b7642ba39c9877eecdcfec687e98eb37d3dd00a17f0ac0671d42d91f721ef` |
| No65_v1.0_REPRODUCIBILITY.zip | `9254e0062ecbec474477a4c09823123939fe6e2e009fe2042a5e278dfa9c3f14` |
