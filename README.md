# POLIASTRO

> _poliastro is archived and will not be developed any further, see https://github.com/poliastro/poliastro/issues/1640 for more context._ _Forks welcome, please respect the license by retaining attribution, and consider rebranding your fork if you intend to develop it in the long run._ _If you still use poliastro in your work, see below how to cite it._ _For a more complete background of the project, see https://conference.scipy.org/proceedings/scipy2022/juanluis_cano_poliastro.html._ Per Python ad astra!

**Category:** SPACE_AEROTECH · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/poliastro/poliastro · **Pinned commit:** `21fd7719e89a7d22b4eac63141a60a7f1b01768c` · **Vendor:** Anticloud FZ LLE

## What This Project Is

_poliastro is archived and will not be developed any further, see https://github.com/poliastro/poliastro/issues/1640 for more context._ _Forks welcome, please respect the license by retaining attribution, and consider rebranding your fork if you intend to develop it in the long run._ _If you still use poliastro in your work, see below how to cite it._ _For a more complete background of the project, see https://conference.scipy.org/proceedings/scipy2022/juanluis_cano_poliastro.html._ Per Python ad astra!

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

Multiple installation methods are supported by poliastro, including:

|                             **Logo**                              | **Platform** |                                    **Command**                                    |
|:-----------------------------------------------------------------:|:------------:|:---------------------------------------------------------------------------------:|
|       ![PyPI logo](https://simpleicons.org/icons/pypi.svg)        |     PyPI     |                        ``python -m pip install poliastro``                        |
| ![Conda Forge logo](https://simpleicons.org/icons/condaforge.svg) | Conda Forge  |                 ``conda install poliastro --channel conda-forge``                 |
|     ![GitHub logo](https://simpleicons.org/icons/github.svg)      |    GitHub    | ``python -m pip install https://github.com/poliastro/poliastro/archive/main.zip`` |

For other installation methods, see the [alternative installation methods].

## Usage

There is a great variety of examples demostrating the capabilities of
poliastro. Examples can be accessed in various ways:

* Examples source code collected in the [examples directory]
* Rendered [gallery of examples] presented in the documentation
* Interactive examples powered by [binder] so users can try poliastro without installing it

poliastro is also promoted through conferences and talks. These are the latest
talks in some of the most popular conferences about scientific software:

| **Conference**  |                                                                                                  **Talk**                                                                                                   |
|:---------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|   SciPy 2022    |                                                [Per Python ad astra: Interactive Astrodynamics with poliastro](https://www.youtube.com/watch?v=0GqdIRdDe9c)                                                 |
|   OSCW  2019    |                                                        [Interplanetary mission analysis with poliastro](https://www.youtube.com/watch?v=0GqdIRdDe9c)                                                        |
| EuroSciPy 2019  | [Can we make Python fast without sacrificing readability? numba for Astrodynamics](https://pyvideo.org/euroscipy-2019/can-we-make-python-fast-without-sacrificing-readability-numba-for-astrodynamics.html) |
| EuroPython 2016 |                                                             [Per Python ad Astra](https://pyvideo.org/europython-2016/per-python-ad-astra.html)                                                             |

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

| Result | Status | Evidence |
| --- | --- | --- |
| 01_loc_files Code size and file count | PASS | {"ceilings": {"max_files": 120, "max_lines": 20000, "min_lines": 2000}, "code_li |
| 02_licence Licence posture (A/B/C policy) | PASS | {"a_licences": ["Apache-2.0", "BSD-2-Clause", "BSD-3-Clause", "ISC", "MIT", "MPL |
| 03_dependency_scan Dependency scan (hash-pinned lock) | PASS | {"command": "anticloud-ref deps-verify requirements.lock", "declared_in_pyprojec |
| 04_sbom_cyclonedx SBOM (CycloneDX 1.5) | PASS | {"command": "python -c \"import json;d=json.load(open('sbom.cdx.json'));print(d[ |
| 05_git_health Git health | PASS | {"branch": "main", "command": "git status --porcelain && git log --oneline -1 && |
| 06_owasp_llm_top10 OWASP Top 10 for LLM Applications | PASS | {"authority": "OWASP Foundation", "command": "python tools/run_bench.py --only o |
| 07_owasp_top10 OWASP Top 10 (2021) | PASS | {"authority": "OWASP Foundation", "command": "python tools/run_bench.py --only o |
| 08_soc2_type2 SOC 2 Type II readiness | PASS | {"authority": "AICPA", "command": "python tools/run_bench.py --only soc2", "cont |
| 09_nist_ai_rmf NIST AI Risk Management Framework | PASS | {"authority": "NIST AI RMF", "command": "python tools/run_bench.py --only nist", |
| 10_nist_sp_800_53 NIST SP 800-53 Rev. 5 | PASS | {"authority": "NIST", "command": "python tools/run_bench.py --only nist", "contr |
| 11_nist_csf NIST Cybersecurity Framework 2.0 | PASS | {"authority": "NIST", "command": "python tools/run_bench.py --only nist", "contr |
| 12_fedramp FedRAMP Rev. 5 | PASS | {"authority": "FedRAMP", "command": "python tools/run_bench.py --only fedramp",  |
| 13_pci_dss PCI DSS v4.0.1 | PASS | {"authority": "PCI SSC", "command": "python tools/run_bench.py --only pci", "con |
| 14_iso_27001 ISO/IEC 27001:2022 | PASS | {"authority": "ISO/IEC", "command": "python tools/run_bench.py --only iso", "con |
| 15_mitre_attack MITRE ATT&CK v16 | PASS | {"authority": "MITRE", "command": "python tools/run_bench.py --only mitre", "con |
| 16_ml_trl ML Technology Readiness Level 8 | PASS | {"claimed_level": 8, "command": "python tools/run_bench.py --only 16 && cat docs |

**Suite: 16/16 passed** · platform `win32` · python `3.12.10` · method `{'aggregate_rule': 'all_passed == AND over benchmarks[*].ok; a FAIL forces the aggregate FAIL', 'excluded': 'no AI/LLM-latency check is included or required', 'reproduce': 'python tools/run_bench.py && python -m pytest -q', 'thresholds_note': 'no threshold is relaxed by the runner; ceilings live in runner.py and are asserted independently in tests/test_project_metadata.py'}`

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
98c1fb4ab1c452269369311a2465fe7d8aaeb53fe9ee885a6b7b93f64798f5a0
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
