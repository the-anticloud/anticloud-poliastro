# POLIASTRO

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-space_aerotech-lightgrey)

> Anticloud-hardened packaging of the upstream project `POLIASTRO` in category **SPACE AEROTECH**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SPACE AEROTECH · **Upstream:** https://github.com/poliastro/poliastro · **Upstream pin:** `21fd7719e89a7d22b4eac63141a60a7f1b01768c` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

> _poliastro is archived and will not be developed any further, see https://github.com/poliastro/poliastro/issues/1640 for more context._
> _Forks welcome, please respect the license by retaining attribution, and consider rebranding your fork if you intend to develop it in the long run._
> _If you still use poliastro in your work, see below how to cite it._
> _For a more complete background of the project, see https://conference.scipy.org/proceedings/scipy2022/juanluis_cano_poliastro.html._
> Per Python ad astra!

[![poliastro Logo](https://raw.githubusercontent.com/poliastro/poliastro/main/docs/source/_static/logo_readme.png)](https://docs.poliastro.space/en/stable/)

| **Name**  |                        **Website**                         |                                                         **Authors**                                                       |                                      **Maintainers**                                      |                     **Version**                      |
|:---------:|:----------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------:|:----------------------------------------------------:|
| poliastro | [https://www.poliastro.space](https://www.poliastro.space) | [Juan Luis Cano Rodriguez](https://orcid.org/0000-0002-2187-161X) [Jorge Martinez](https://orcid.org/0000-0001-9622-2369) | [poliastro development team](https://github.com/poliastro/poliastro/blob/main/AUTHORS.md) | [0.18.dev0](https://github.com/poliastro/poliastro/) |

[![poliastro_badge]](https://github.com/poliastro/poliastro)
[![ci_badge]](https://circleci.com/gh/poliastro/poliastro/?branch=main)
[![docs_badge]](https://docs.poliastro.space/en/latest/?badge=latest)
[![coverage_badge]](https://codecov.io/github/poliastro/poliastro?branch=main) 
[![pre_commit_badge]](https://results.pre-commit.ci/latest/github/poliastro/poliastro/main) 
[![python_badge]](https://pypi.org/project/poliastro) 
[![pypi_badge]](https://pypi.org/project/poliastro) 
[![license_badge]](https://opensource.org/licenses/MIT) 
[![doi_badge]](https://zenodo.org/badge/latestdoi/11178845) 
[![astropy_badge]](https://zenodo.org/badge/latestdoi/11178845) 
[![mailing_badge]](https://groups.io/g/poliastro-dev) 
[![chat_badge]](http://chat.poliastro.space/) 
[![backers_badge]](https://opencollective.com/poliastro/) 
[![sponsors_badge]](https://opencollective.com/poliastro/) 
[![binder_badge]](https://mybinder.org/v2/gh/poliastro/poliastro/main?labpath=index.ipynb) 
[![code_badge]]()

poliastro is an open source ([MIT](#License)) pure Python library for interactive
Astrodynamics and Orbital Mechanics, with a focus on ease of use, speed, and
quick visualization. It provides a simple and intuitive API, and handles
physical quantities with units.

Some features include orbit propagation, solution of the Lambert\'s problem,
conversion between position and velocity vectors and classical orbital elements
and orbit plotting, among others.  It focuses on interplanetary applications,
but can also be used to analyze artificial satellites in Low-Earth Orbit (LEO).

If you use poliastro on your project, please [let us know]. Use the DOI to cite
poliastro in your publications:

    Juan Luis Cano Rodríguez, Jorge Martinez, et al.. (2023). poliastro: poliastro 0.17.0. Zenodo. 10.5281/zenodo.6817189

![Multiple examples image](https://github.com/poliastro/poliastro/raw/main/docs/source/_static/examples.png)

## Requirements

poliastro requires the following Python packages:

- [numpy](https://numpy.org/) for basic numerical routines
- [astropy](https://www.astropy.org/) for physical units and time handling
- [numba](https://numba.pydata.org/) for accelerating the code
- [jplephem](https://github.com/brandon-rhodes/python-jplephem) for the planetary ephemerides using SPICE kernels
- [matplotlib](https://matplotlib.org/) for orbit plotting
- [plotly](https://plotly.com/) for 2D and 3D interactive orbit plotting
- [scipy](https://scipy.org/) for root finding and numerical propagation

poliastro is supported on Linux, macOS and Windows on Python 3.8 to 3.10.

## Installation

Multiple installation methods are supported by poliastro, including:

|                             **Logo**                              | **Platform** |                                    **Command**                                    |
|:-----------------------------------------------------------------:|:------------:|:---------------------------------------------------------------------------------:|
|       ![PyPI logo](https://simpleicons.org/icons/pypi.svg)        |     PyPI     |                        ``python -m pip install poliastro``                        |
| ![Conda Forge logo](https://simpleicons.org/icons/condaforge.svg) | Conda Forge  |                 ``conda install poliastro --channel conda-forge``                 |
|     ![GitHub logo](https://simpleicons.org/icons/github.svg)      |    GitHub    | ``python -m pip install https://github.com/poliastro/poliastro/archive/main.zip`` |

For other installation methods, see the [alternative installation methods].

## Documentation

Complete documentation, including a [quickstart guide] and an [API reference], can
be read on the wonderful [Read the Docs]. Multi-version documentation includes:

* [Development documentation](https://docs.poliastro.space/en/latest/)
* [Stable documentation](https://docs.poliastro.space/en/stable/)

## Examples, background and talks

There is a great variety of examples demostrating the capabilities of
poliastro. Examples can be accessed in various ways:

* Examples source code collected in the [examples directory]
* Rendered [gallery of examples] presented in the

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `binder/`, `contrib/`, `src/`, `tests/`
- Snapshot size: **154 files**, **17695 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (122), `(none)` (7), `.md` (7), `.dat` (4), `.yml` (4), `.yaml` (3)
- Upstream commit pinned for this packaging: `21fd7719e89a7d22b4eac63141a60a7f1b01768c`

---

## Installation

Multiple installation methods are supported by poliastro, including:

|                             **Logo**                              | **Platform** |                                    **Command**                                    |
|:-----------------------------------------------------------------:|:------------:|:---------------------------------------------------------------------------------:|
|       ![PyPI logo](https://simpleicons.org/icons/pypi.svg)        |     PyPI     |                        ``python -m pip install poliastro``                        |
| ![Conda Forge logo](https://simpleicons.org/icons/condaforge.svg) | Conda Forge  |                 ``conda install poliastro --channel conda-forge``                 |
|     ![GitHub logo](https://simpleicons.org/icons/github.svg)      |    GitHub    | ``python -m pip install https://github.com/poliastro/poliastro/archive/main.zip`` |

For other installation methods, see the [alternative installation methods].

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

> _For a more complete background of the project, see https://conference.scipy.org/proceedings/scipy2022/juanluis_cano_poliastro.html._
> Per Python ad astra!

[![poliastro Logo](https://raw.githubusercontent.com/poliastro/poliastro/main/docs/source/_static/logo_readme.png)](https://docs.poliastro.space/en/stable/)

| **Name**  |                        **Website**                         |                                                         **Authors**                                                       |                                      **Maintainers**                                      |                     **Version**                      |
|:---------:|:----------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------:|:----------------------------------------------------:|
| poliastro | [https://www.poliastro.space](https://www.poliastro.space) | [Juan Luis Cano Rodriguez](https://orcid.org/0000-0002-2187-161X) [Jorge Martinez](https://orcid.org/0000-0001-9622-2369) | [poliastro development team](https://github.com/poliastro/poliastro/blob/main/AUTHORS.md) | [0.18.dev0](https://github.com/poliastro/poliastro/) |

[![poliastro_badge]](https://github.com/poliastro/poliastro)
[![ci_badge]](https://circleci.com/gh/poliastro/poliastro/?branch=main)
[![docs_badge]](https://docs.poliastro.space/en/latest/?badge=latest)
[![coverage_badge]](https://codecov.io/github/poliastro/poliastro?branch=main) 
[![pre_commit_badge]](https://results.pre-commit.ci/latest/github/poliastro/poliastro/main) 
[![python_badge]](https://pypi.org/project/poliastro) 
[![pypi_badge]](https://pypi.org/project/poliastro) 
[![license_badge]](https://opensource.org/licenses/MIT) 
[![doi_badge]](https://zenodo.org/badge/latestdoi/11178845) 
[![astropy_badge]](https://zenodo.org/badge/latestdoi/11178845) 
[![mailing_badge]](https://groups.io/g/poliastro-dev) 
[![chat_badge]](http://chat.poliastro.space/) 
[![backers_badge]](https://opencollective.com/poliastro/) 
[![sponsors_badge]](https://opencollective.com/poliastro/) 
[![binder_badge]](https://mybinder.org/v2/gh/poliastro/poliastro/main?labpath=index.ipynb) 
[![code_badge]]()

poliastro is an open source ([MIT](#License)) pure Python library for interactive
Astrodynamics and Orbital Mechanics, with a focus on ease of use, speed, and
quick visualization. It provides a simple and intuitive API, and handles
physical quantities with units.

Some features include orbit propagation, solution of the Lambert\'s problem,
conversion between position and velocity vectors and classical orbital elements
and orbit plotting, among others.  It focuses on interplanetary applications,
but can also be used to analyze artificial satellites in Low-Earth Orbit (LEO).

If you use poliastro on your project, please [let us know]. Use the DOI to cite
poliastro in your publications:

    Juan Luis Cano Rodríguez, Jorge Martinez, et al.. (2023). poliastro: poliastro 0.17.0. Zenodo. 10.5281/zenodo.6817189

![Multiple examples image](https://github.com/poliastro/poliastro/raw/main/docs/source/_static/examples.png)

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

physical quantities with units.

Some features include orbit propagation, solution of the Lambert\'s problem,
conversion between position and velocity vectors and classical orbital elements
and orbit plotting, among others.  It focuses on interplanetary applications,
but can also be used to analyze artificial satellites in Low-Earth Orbit (LEO).

If you use poliastro on your project, please [let us know]. Use the DOI to cite
poliastro in your publications:

    Juan Luis Cano Rodríguez, Jorge Martinez, et al.. (2023). poliastro: poliastro 0.17.0. Zenodo. 10.5281/zenodo.6817189

![Multiple examples image](https://github.com/poliastro/poliastro/raw/main/docs/source/_static/examples.png)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml |
| Files in snapshot | 154 |
| Lines of code | 17695 |
| Dependency references | 8 |
| Dependencies by ecosystem | conda: 2, pypi: 6 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| pypi | astropy | >=5.0 | pyproject.toml |
| pypi | astroquery | >=0.3.9 | pyproject.toml |
| pypi | jplephem | - | pyproject.toml |
| pypi | matplotlib | >=2.0 | pyproject.toml |
| pypi | numba | >=0.46 | pyproject.toml |
| pypi | 3.9 | - | pyproject.toml |
| conda | python | 3.10 | binder/environment.yml |
| conda | jupytext | - | binder/environment.yml |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `Makefile`
- `pyproject.toml`
- `tox.ini`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing

poliastro is a community project, all contributions are more than welcome!

## What you can do

### Report bugs

Not only things can break, but also different people have
different use cases for the project. If you find anything that doesn't
work as expected or have suggestions, please open a new issue on our
[issue tracker](https://github.com/poliastro/poliastro/issues).

### Participate in the chat

Most of the project discussions happen in [the project chat](http://chat.poliastro.space/),
where announcements are first made, newcomers ask questions,
and in general project users exchange all sorts of information.
[Join today!](http://chat.poliastro.space/)

### Improve the Documentation

Documentation can always be expanded and improved.
The docs are stored in text files under the `docs/source` directory,
and the Python classes and methods also feature inline docs
in the form of docstrings.

### Contribute your research scripts

We would love to give your Astrodynamics scripts a home!
Please head to [our `contrib/` directory](https://github.com/poliastro/poliastro/tree/main/contrib)
for further information.

### Fix bugs and add new features

Code contributions are welcome! If you are looking for a place to start,
check out the ["good-first-issue" label](https://github.com/poliastro/poliastro/labels/good%20first%20issue)
on our issue tracker. Those tasks should be easier to fix than the others
and require less knowledge about the library.

## How to contribute

### Work from GitHub

GitHub makes it very easy to make small contributions
directly from your browser, without having to install any additional software.
To get familiar with the process, you can do
[this interactive GitHub training](https://lab.github.com/githubtraining/introduction-to-github).
Once you have finished it, you can edit the poliastro source files
straight from GitHub and open pull requests from your browser.

### Work locally

For more complex contributions, it will be more effective
to set up a local development environment and work from your own computer.

The most important thing is to understand how Git works. Git is a decentralized
version control system that preserves the history of the software, helps
tracking changes and allows for multiple versions of the code to exist
at the same time. To learn more, you can have a look at
[this Getting Started guide](https://docs.github.com/en/get-started/getting-started-with-git).

Finally, you might want to have an Integ

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `COPYING` in the upstream snapshot).

License file excerpt:

```text
The MIT License (MIT)

Copyright (c) 2012 Juan Luis Cano Rodríguez, Jorge Martínez Garrido, and the poliastro development team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `POLIASTRO` (category: SPACE AEROTECH)
- **Upstream URL:** https://github.com/poliastro/poliastro
- **Pinned commit (SHA):** `21fd7719e89a7d22b4eac63141a60a7f1b01768c`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`5aa8714ca1ea6879e7f4dbdbb76beb1823b650f91be02644b4f4f81fdd067e57`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

