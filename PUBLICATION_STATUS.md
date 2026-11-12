# No.65 v1.0: publication gates and evidence scope

12 November 2026 (JST). Ryutaro Yonezu - Independent Researcher.
Copyright (c) 2026 Ryutaro Yonezu. All rights reserved.

This document records preparation checks. Successful external publication
must be established by the actual repository, Release and Zenodo record;
their URLs and the final publication receipt are recorded separately.

## Mandatory wording

- Independent AI-assisted and SMT verification within the documented scope
- Windows PowerShell 5.1 reproduction PASS (author-run)
- NOVELTY INCONCLUSIVE
- REFERENCES PARTIAL
- Not peer-reviewed
- All rights reserved

## Prepublication gates

| Gate | Verdict | Evidence and boundary |
| --- | --- | --- |
| G1 Original and provenance | PASS | v0.12 manifest 25 files; embedded v0.11 19/19 bytes and its 18-file manifest; supplemental SMT 7-file manifest. Ten selected public computational files byte-identical. |
| G2 Mathematical consistency | PASS within documented AI/SMT scope | v0.9 full theorem and v0.11 explicit A/C details transcribed. All three seed bands, value 4, two no-seed endpoints, unique chain, large-c boundary and final exceptional point included. Base and full mex encodings mapped to arbitrary parameters and legal predecessors. SMT conclusions conditional on encoding and solver correctness. |
| G3 Reproducibility | PASS | Fresh Linux executions match 2 UNSAT, 3 SAT, direct-mex and structural counts. Supplied Windows v0.11 evidence and separate author-reported Windows SMT output distinguished from fresh execution. |
| G4 Editorial and PDF | PASS | Public TeX compiled directly into a six-page PDF. All pages rendered and checked; no missing or unresolved cross-references, clipped equations, missing symbols, or overflow. Full expanded theorem retained. |
| G5 Privacy | PASS for selected files | No raw Windows logs, private integrated/frozen ZIPs, private email, home/workstation paths, machine name, credential, or third-party full text in the public selection. PDF metadata checked. Rights notice newly written; no old research-review-only license reused. |
| G6 Prior art and disclosure | PASS for the disclosure gate | Ho arXiv v3 Theorem 5/Table 8, Zhang author revision Remark 7, and both prior author manuscripts compared. Known base and observed period-two behavior credited. Flammenkamp expanded book remains unchecked. REFERENCES PARTIAL / NOVELTY INCONCLUSIVE; no priority claim. No fatal direct containment identified in the compared scope. |
| G7 Public package integrity | PASS | Separate public ZIP, relative-path manifests, Python SHA256 and independent sha256sum checks; ZIP re-extracted and verified. PDF/TeX/ZIP/README/LICENSE/citation information consistent. |

## Individual axes

| Axis | Verdict | Meaning |
| --- | --- | --- |
| MODEL | PASS | Standard one-pile normal-play mex. Odd a>=3, odd c>=L+1 only. |
| PROOF-BASE | PASS, conditional machine-certificate scope | Exact-rational guarded affine certificate and separate universal SMT mex check; translation documented. Ho's known base not claimed new. |
| PROOF-A | PASS within AI-assisted examination | Final base block u=3 yields exactly five sites and exhaustive predecessor window. |
| PROOF-B | PASS within AI-assisted examination and SMT closure | All four first-3a cases, seed values 3/4/3, partner and endpoints present. |
| PROOF-C | PASS within AI-assisted examination and SMT closure | Separation bounds; exhaustive a and 3a directed edges; no 2a+1 edge; unique terminating chain. |
| PROOF-D | PASS within AI-assisted examination | Final E3 value stays 2 or 3, with all later values binary parity. |
| MINIMALITY | PASS | Last nonbinary point forbids any earlier eventual-period onset; alternating suffix has least period 2. |
| COMPUTATION | PASS within stated finite ranges | C++ 2,588 pairs / 101,872,020 generated mex positions; Python 1,455 pairs / 16,739,670 positions; supplemental Python 790 pairs / 2,677,220 positions; A/C 102 odd a. Ranges overlap. C++ extension comparison starts at n=c. |
| SMT | PASS, conditional on encoding and solver correctness | Fresh system Z3 4.13.3: base/full controls UNSAT, all three mutations SAT. No second solver or proof-assistant verification. |
| WINDOWS | PASS (author-run) | Sanitized supplied v0.11 evidence plus separate author report for SMT package z3-solver 5.4.1.0 / displayed Z3 5.4.1. No independent witness or editor Windows execution. |
| PACKAGE | PASS | Selected source bytes, inventories, hashes, clean re-extraction. |
| PRIVACY | PASS for selected files | Private source bundles and raw logs excluded; no private paths, emails or credentials found. |
| REFERENCES | PARTIAL | Ho, Zhang, No.63/64 compared; expanded Flammenkamp book unchecked in full. |
| NOVELTY | INCONCLUSIVE | No worldwide priority or exhaustive non-overlap claim. |
| EDITORIAL | PASS | v1.0 carries the expanded theorem, correct status and rights; frozen history unchanged. |

## Mathematical source crosswalk

| Frozen source | Public manuscript |
| --- | --- |
| THEOREM_BROAD_BAND_V09.md: definitions, three bands, u_i/v_i, complete word | Section 1, Theorem 1, equations (2)-(9) |
| NO65_PROOF_DRAFT_EN_V03.md: base word and large-c proof | Sections 1-2 and 4 |
| LEMMA_AC_EXPLICIT_PROOF_V11.md: terminal window and exhaustive edges | Sections 3.1 and 3.3 |
| THEOREM_BROAD_BAND_V09.md: seed and partner | Section 3.2, with v0.11 supporting clarification |
| Frozen Lemma D | Section 4: last E3 and least preperiod/period |
| Separate SMT files | Section 5: arbitrary-parameter domain and predecessor correspondence |

No mathematics, existing computational source, or historical audit record
in the frozen private originals was overwritten. This editorial document
does not convert finite tests into universal proofs, a solver result into
human peer review, or unresolved literature into novelty PASS.
