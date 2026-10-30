# VardrSec

Decoy-sensor research and open-source access-control tools.

## About VardrSec

**VardrSec** is an independent security research and tooling initiative focused on application security, API security, web application testing, and practical security automation. It also runs SSH and API decoy sensors and publishes what they record.

Founded by **Jorge Aquino**, VardrSec focuses on building security tools, studying real vulnerability classes, and documenting repeatable testing methods.

The project emphasizes issues that often require deeper manual analysis, including authorization flaws, business logic vulnerabilities, insecure API design, and weaknesses that automated scanners may miss.

---

## Platform distribution

[VardrSec](https://github.com/VardrSec/VardrSec) provides Docker Compose installation
and lifecycle management for the VardrMap, VardrRunner and VardrGate platform. It is
a source-built alpha targeting Ubuntu 24.04/amd64, not a published release. See the
[installation guide](https://github.com/VardrSec/VardrSec/blob/main/docs/installation.md).

## Open-source tools

| Tool | What it does | Language | License |
|---|---|---|---|
| [VardrGate](https://github.com/VardrSec/VardrGate) | Tests API authorization against a declared policy. It replays one request as every identity and reports where the result diverges from the policy. | Go | Apache-2.0 |
| [VardrMap](https://github.com/VardrSec/VardrMap) | Multi-tenant engagement platform that keeps scope, authorization and findings in one place. It starts scans and authorization tests through VardrRunner and VardrGate. | Python | AGPL-3.0 |
| [VardrRunner](https://github.com/VardrSec/VardrRunner) | Runs queued security jobs on the operator's machine and uploads the results to a backend. | Python | MIT |

In design: VardrScanner ([design docs](https://github.com/jorge-aquino/vardrscanner-docs)). It is not ready to use.

VardrForge is a private, unreleased CLI prototype for generating scoped security
tools and scripts.

Bug reports and pull requests are welcome on every repository. Report vulnerabilities in the tools privately to contact@vardrsec.com.

## Research

VardrSec runs SSH and API decoys and publishes delayed, sanitized snapshots of what they record in the [Threat Observatory](https://vardrsec.com/observatory.html). Public data omits source IP addresses and credentials. Write-ups are on the [blog](https://vardrsec.com/blog.html).

## Contact

- Website: [vardrsec.com](https://vardrsec.com)
- Email: contact@vardrsec.com
- Maintainer: [@jorge-aquino](https://github.com/jorge-aquino)
