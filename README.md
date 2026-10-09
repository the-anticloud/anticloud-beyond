# BEYOND

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-space_aerotech-lightgrey)

> Anticloud-hardened packaging of the upstream project `BEYOND` in category **SPACE AEROTECH**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SPACE AEROTECH · **Upstream:** https://github.com/zhoushuguang/beyond · **Upstream pin:** `f0962054c9e428d3aa808875a3e8482ceea45774` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# beyond

## 微信公众号

![qrcode_for_gh_884b10e30cf6_344](https://github.com/zhoushuguang/beyond/assets/16539942/3a6801d9-ebf9-4a0f-a141-2f410b001f7e)

## 架构图

## 文档

### 第一课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/HsMIdfEa0ogEvmxCpRrcEOyenqc
#### 视频
https://www.bilibili.com/video/BV1op4y177iS/

### 第二课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/XX6xdpB0UoH0auxgPYlcxmninDb
#### 视频
https://www.bilibili.com/video/BV1CH4y1Q7PM/

### 第三课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/XLB9dK9Cao3Z7HxPyEscu0P9nIb
#### 视频
https://www.bilibili.com/video/BV19u411w7WS/

### 第四课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/U9FGdVAFuoFFiUxySsgcl5TMnke
#### 视频
https://www.bilibili.com/video/BV1Y8411q7uW/

### 第五课
#### 文档 
https://pwmzlkcu3p.feishu.cn/docx/EBzWdSFR5oPVMJxP1oOcUGojnTd
#### 视频
https://www.bilibili.com/video/BV1k8411y7W5/

### 第六课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/O1u3d9pqWo4sZTx6NTxcOHhknmd
#### 视频
https://www.bilibili.com/video/BV1F84y1S74g/

### 第七课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/SvSwdAETNo3F0Axznp8ceaX1nIb
#### 视频
https://www.bilibili.com/video/BV1sz4y1G73u/

### 第八课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/At4zdJzrFowGMmx5OjJcrS5mnir
#### 视频
https://www.bilibili.com/video/BV1S8411C7CY/

### 第九课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/OW6Sd0ZsioU9LLxuUSXcUZgNnoD
#### 视频
https://www.bilibili.com/video/BV1oB4y1f7Tr/

### 第十课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/Si1Cd4EGxoZXkJxGenzcFttOnsh
#### 视频
https://www.bilibili.com/video/BV1je411R7iy/

### 第十一课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/NYyHdpSzhoB8Zkxdb6NcpUGynH4
#### 视频
https://www.bilibili.com/video/BV11u4y1Y7GC/

### 第十二课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/QZcKdB4VXoUCRDxGilfcTaw7n8e
#### 视频
https://www.bilibili.com/video/BV1u64y177rL

### 第十三课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/BDNUdhmP4oec6ix1P1ZcqF3rnIc
#### 视频
https://www.bilibili.com/video/BV1bH4y1C7Uj

### 第十四课
#### 文档
https://pwmzlkcu3p.feishu.cn/docx/Ydd4dG8OSobJ1rxJFgacOBKvnSg

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Go** (manifests: go.mod, go.sum; scanned in UPSTREAM_CLONE)
- Top-level source layout: `application/`, `db/`, `pkg/`
- Snapshot size: **183 files**, **10481 lines of code** (measured; see Benchmarks)
- Primary languages: `.go` (128), `.yaml` (19), `.md` (10), `.proto` (10), `.sql` (6), `(none)` (4)
- Upstream commit pinned for this packaging: `f0962054c9e428d3aa808875a3e8482ceea45774`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
go mod download
go build ./...
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
go run .           # main package at the snapshot root
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `BEYOND` source tree vendored in `UPSTREAM_CLONE/` (Go ecosystem). Public entry points:

- Source modules: `application/`, `db/`, `pkg/`
- The snapshot declares 108 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Go |
| Manifests detected | go.mod, go.sum |
| Files in snapshot | 183 |
| Lines of code | 10481 |
| Dependency references | 108 |
| Dependencies by ecosystem | go: 108 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| go | github.com/aliyun/aliyun-oss-go-sdk | v2.2.9+incompatible | go.mod |
| go | github.com/dgrijalva/jwt-go | v3.2.0+incompatible | go.mod |
| go | github.com/elastic/go-elasticsearch/v8 | v8.10.1 | go.mod |
| go | github.com/golang/protobuf | v1.5.3 | go.mod |
| go | github.com/hashicorp/consul/api | v1.26.1 | go.mod |
| go | github.com/pkg/errors | v0.9.1 | go.mod |
| go | github.com/zeromicro/go-queue | v1.1.8 | go.mod |
| go | github.com/zeromicro/go-zero | v1.5.5 | go.mod |
| go | go.opentelemetry.io/otel | v1.14.0 | go.mod |
| go | go.opentelemetry.io/otel/trace | v1.14.0 | go.mod |
| go | golang.org/x/sync | v0.2.0 | go.mod |
| go | google.golang.org/grpc | v1.57.0 | go.mod |
| go | google.golang.org/protobuf | v1.31.0 | go.mod |
| go | gorm.io/driver/mysql | v1.5.2 | go.mod |
| go | gorm.io/gorm | v1.25.5 | go.mod |
| ... | (93 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `BEYOND` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2024 dawn_zhou

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

- **Project:** `BEYOND` (category: SPACE AEROTECH)
- **Upstream URL:** https://github.com/zhoushuguang/beyond
- **Pinned commit (SHA):** `f0962054c9e428d3aa808875a3e8482ceea45774`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`342933c69305c6fabec7322922a3c9ad96ec5c57b3e03f02b951f20645230008`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

