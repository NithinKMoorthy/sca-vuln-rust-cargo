# sca-vuln-rust-cargo

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** Cargo (Rust)

## Expected findings (non-exhaustive)
- hyper 0.12.35: RUSTSEC-2021-0078, RUSTSEC-2021-0079
- smallvec 0.6.9: RUSTSEC-2019-0009, RUSTSEC-2021-0003
- time 0.1.42: RUSTSEC-2020-0071
- chrono 0.4.19: RUSTSEC-2020-0159
- tokio 0.2.21: RUSTSEC-2021-0124
- regex 1.5.4: CVE-2022-24713
- openssl 0.10.24: RUSTSEC-2023-0044 and others
