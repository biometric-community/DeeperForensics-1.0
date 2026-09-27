# DeeperForensics-1.0

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FDeeperForensics--1.0-181717?logo=github)](https://github.com/biometric-community/DeeperForensics-1.0)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://github.com/EndlessSora/DeeperForensics-1.0)

**DeeperForensics-1.0** — tbiom catalog packaging for `deeperforensics` (deepfake; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/DeeperForensics-1.0
- **Upstream source**: https://github.com/EndlessSora/DeeperForensics-1.0
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `deeperforensics` |
| Category | `deepfake` |
| Access | `register` |
| Upstream homepage | https://github.com/EndlessSora/DeeperForensics-1.0 |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Request access via project page.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/DeeperForensics-1.0.git
cd DeeperForensics-1.0
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_deeperforensics.sh
```

Place licensed archives under `projects/datasets/deeperforensics/` (gitignored).

## Dataset structure

```text
DeeperForensics-1.0/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://github.com/EndlessSora/DeeperForensics-1.0
- Packaging: https://github.com/biometric-community/DeeperForensics-1.0/issues
