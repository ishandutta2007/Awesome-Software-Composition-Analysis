# Awesome-Software-Composition-Analysis

## Top Software Composition Analysis (SCA) Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Dependency Vulnerability Scanning, License Compliance, SBOM Generation & Supply-Chain Risk*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Software Composition Analysis (SCA)**. These tools identify known vulnerabilities, malicious packages, and license risks in open-source and third-party dependencies, generate Software Bills of Materials (SBOMs), enforce policies, and help remediate issues across the software development lifecycle.



**Examples** include Snyk, Mend, Sonatype Lifecycle, JFrog Xray, Black Duck, FOSSA, Socket, Anchore, Endor Labs, Deps.dev, Phylum, Google OSV-Scanner, Debricked, and Checkmarx SCA (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, SBOM generation, vulnerability matching, continuous monitoring, and open dependency scanning — ideal for security teams, DevSecOps engineers, and organizations building transparent, vendor-independent SCA capabilities.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Snyk](https://snyk.io/)**  

  Developer-first SCA platform with IDE and PR integrations, reachability analysis, auto-fix pull requests, and broad language/ecosystem coverage.



- **[Mend.io](https://www.mend.io/)**  

  Enterprise SCA solution (formerly WhiteSource) offering vulnerability detection, license compliance, automated remediation via Renovate, and policy enforcement.



- **[Sonatype Lifecycle](https://www.sonatype.com/products/lifecycle)**  

  Component intelligence and policy engine that blocks risky open-source components at the repository and build stages with deep supply-chain insights.



- **[JFrog Xray](https://jfrog.com/xray/)**  

  Universal SCA deeply integrated with Artifactory for scanning binaries, packages, containers, and dependencies with contextual risk analysis.



- **[Black Duck](https://www.blackduck.com/)**  

  Compliance-focused SCA platform with one of the deepest open-source license knowledge bases, SBOM capabilities, and strong audit/reporting features.



- **[FOSSA](https://fossa.com/)**  

  License compliance and SBOM platform specialized in open-source policy enforcement, audit-ready reporting, and dependency risk management.



- **[Socket](https://socket.dev/)**  

  Supply-chain security platform that detects malicious packages through behavioral analysis rather than relying solely on known CVE databases.



- **[Anchore](https://anchore.com/)**  

  Container and SBOM-centric platform providing vulnerability scanning, policy enforcement, and continuous monitoring for images and dependencies.



- **[Endor Labs](https://www.endorlabs.com/)**  

  Reachability-focused SCA that uses function-level analysis to dramatically reduce noise and prioritize truly exploitable dependency vulnerabilities.



- **[Deps.dev](https://deps.dev/)**  

  Google-backed public service providing dependency insights, advisories, and supply-chain metadata across major package ecosystems.



- **[Phylum](https://www.phylum.io/)**  

  Software supply-chain risk platform specializing in malicious package detection and behavioral analysis of open-source dependencies.



- **[Google OSV-Scanner](https://google.github.io/osv-scanner/)**  

  Official scanner for the OSV vulnerability database, offering accurate lockfile-driven scanning across many ecosystems (also available as open source).



- **[Debricked](https://debricked.com/)**  

  SCA platform focused on dependency risk, license compliance, and developer-friendly remediation guidance.



- **[Checkmarx SCA](https://checkmarx.com/)**  

  Part of the Checkmarx AppSec platform, delivering software composition analysis alongside SAST with reachability and policy features.



## Open-Source GitHub Projects



- **[Trivy](https://github.com/aquasecurity/trivy)**  

  Comprehensive all-in-one scanner for dependencies, containers, filesystems, IaC, secrets, and SBOM generation (Aqua Security).



- **[Syft](https://github.com/anchore/syft)**  

  Fast CLI and library for generating CycloneDX and SPDX SBOMs from container images, filesystems, and archives (Anchore).



- **[Grype](https://github.com/anchore/grype)**  

  Vulnerability scanner for container images and SBOMs with multi-source CVE matching and relatively low false positives (Anchore).



- **[Dependency-Track](https://github.com/DependencyTrack/dependency-track)**  

  OWASP flagship continuous SBOM monitoring and component analysis platform that correlates against NVD, OSV, GitHub Advisories, and more.



- **[OSV-Scanner](https://github.com/google/osv-scanner)**  

  Google-backed open-source scanner that queries the OSV database for accurate, ecosystem-aware vulnerability detection.



- **[OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck)**  

  Classic multi-language SCA tool that identifies known vulnerable components using the NVD and other vulnerability data sources.



- **[cdxgen](https://github.com/CycloneDX/cdxgen)**  

  Universal CycloneDX SBOM generator supporting 20+ languages and build systems with rich dependency graph output.



- **[Renovate](https://github.com/renovatebot/renovate)**  

  Automated dependency update bot that opens pull requests for outdated or vulnerable packages across 90+ package managers.



- **[Dependabot](https://github.com/dependabot)**  

  GitHub-native dependency security and version update system supporting dozens of ecosystems with automated fix PRs.



- **[bomber](https://github.com/devops-kung-fu/bomber)**  

  Lightweight tool that scans SBOMs for vulnerabilities using multiple data sources.



- **[OpenSCA](https://github.com/XmirrorSecurity/OpenSCA-cli)**  

  Open-source SCA engine for detecting third-party component vulnerabilities and license risks.



- **[Semgrep Supply Chain](https://semgrep.dev/products/semgrep-supply-chain)**  

  Reachability-aware dependency scanning integrated with the Semgrep platform (community/open rules available).



### Additional Strong Open-Source Options



- **Ecosystem-native scanners**: npm audit, pip-audit, bundler-audit, cargo-audit, Safety, Retire.js, and similar lockfile tools.

- **SBOM tooling**: CycloneDX CLI, SPDX tools, sbom-tool, and format converters.

- **Policy & continuous monitoring**: Dependency-Track policies, OPA/Gatekeeper rules for dependency gates.

- **Malicious package detection** community projects and OSV malicious packages feed integrations.

- Many language-specific **audit** CLIs and **SBOM** generators maintained by ecosystems.



**Frameworks for building custom systems**: Combine **Syft + Grype** (or **Trivy**), **OSV-Scanner**, **Dependency-Track** for continuous monitoring, **cdxgen** for SBOMs, and **Renovate/Dependabot** for remediation into a complete open-source SCA pipeline.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- SCA tools must be kept updated with current vulnerability databases and should be combined with reachability, policy, and remediation processes.

- Self-hosted open-source solutions require proper operational security, database freshness, and auditability.



---



**Made for AppSec engineers, DevSecOps teams, platform security, and software supply-chain practitioners.**  

Let's make software composition analysis more transparent, accurate, and accessible.
