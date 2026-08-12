# UMBRALNET

> **Security without spectacle. Capability without attribution.**

Umbralnet is an independent security engineering organization focused on infrastructure, adversary simulation, cloud security, network defense, automation, and offensive-security research.

Much of what we build is intentionally quiet.

Some projects are public.
Some are experimental.
Some exist only to solve a very specific problem.

We are interested in systems that sit close to the boundary between **defense, infrastructure, intelligence, and engineering**.

---

## `// MISSION`

Umbralnet exists to explore, build, and harden systems operating in hostile or uncertain environments.

Primary areas of interest include:

```text
[ CLOUD ]        Azure / Cloud Security / IaC
[ NETWORK ]      Routing / Firewalls / Segmentation / VPN
[ SECURITY ]     Detection / Adversary Simulation / Research
[ AUTOMATION ]   Bicep / GitHub Actions / Security Engineering
[ SYSTEMS ]      Linux / Infrastructure / Low-Level Tooling
[ INTELLIGENCE ] Signals / Telemetry / Analysis / Correlation
```

The objective is not simply to deploy infrastructure.

It is to understand how it behaves when assumptions fail.

---

## `// OPERATING PRINCIPLES`

**Observe first.**

Telemetry is part of the system, not an afterthought.

**Assume compromise.**

Trust boundaries should be explicit, narrow, and continuously challenged.

**Automate repeatable operations.**

Infrastructure should be reproducible, reviewable, and disposable.

**Minimize exposure.**

Services should reveal only what they need to reveal.

**Design for failure.**

Networks fail. Credentials leak. Dependencies disappear. Humans make mistakes.

Good systems remain understandable when that happens.

---

## `// CAPABILITIES`

```text
                 ┌───────────────────────┐
                 │       UMBRALNET       │
                 └───────────┬───────────┘
                             │
         ┌───────────────────┼───────────────────┐
         │                   │                   │
         ▼                   ▼                   ▼
   CLOUD SECURITY      NETWORK SECURITY     SECURITY R&D
         │                   │                   │
   IaC / Identity      Routing / VPN       Tooling / PoCs
   Azure / CI/CD       Firewalls / DNS     Detection Research
   Policy / RBAC       Segmentation        Adversary Simulation
```

Public repositories may include:

* infrastructure-as-code
* security automation
* lab environments
* network tooling
* defensive utilities
* research prototypes
* detection engineering
* operational documentation
* small tools built to answer unusually specific questions

Not every repository should be interpreted as a product.

Some are experiments.

Some are building blocks.

Some are simply evidence that a problem was interesting enough to investigate.

---

## `// INFRASTRUCTURE`

Umbralnet infrastructure follows an infrastructure-as-code-first model.

```text
change
  │
  ▼
feature branch
  │
  ▼
pull request
  │
  ├── lint
  ├── validate
  ├── security review
  └── what-if
       │
       ▼
     merge
       │
       ▼
   deployment
```

Where possible:

```text
manual configuration  → eliminated
long-lived secrets    → avoided
implicit trust        → reduced
changes without review→ discouraged
```

GitHub Actions, workload identity federation, Bicep, policy, and scoped cloud identities are preferred over static credentials and manual deployment.

---

## `// RESEARCH`

Areas that currently attract our attention:

```text
Cloud attack paths
Identity boundaries
Azure networking
Firewall automation
Detection engineering
Protocol behaviour
Infrastructure failure modes
Adversary tradecraft
Linux internals
DNS
VPN technologies
Security telemetry
Automation under constrained trust
```

Research may involve reproducing known techniques, building controlled proofs of concept, studying defensive visibility, or testing assumptions in isolated environments.

The goal is understanding.

Not noise.

---

## `// DISCLOSURE`

Security research conducted under the Umbralnet name is intended for authorized environments, controlled laboratories, defensive analysis, or responsible disclosure.

If a vulnerability affecting a third party is identified, disclosure should be coordinated with the affected vendor or maintainer before technical details are released publicly.

See [`SECURITY.md`](SECURITY.md) where present.

---

## `// ACCESS`

Public repositories represent only the externally visible portion of Umbralnet.

Repository visibility should not be interpreted as an inventory of active systems, capabilities, infrastructure, research, or operations.

Absence of documentation is not necessarily absence of capability.

---

## `// STATUS`

```text
ORGANIZATION   UMBRALNET
DOMAIN         SECURITY ENGINEERING
POSTURE        LOW VISIBILITY
DEPLOYMENT     DISTRIBUTED
AUTOMATION     PREFERRED
TRUST          MINIMAL
TELEMETRY      ENABLED
STATUS         OPERATIONAL
```

---

### UMBRALNET

**We build systems for the part of the network nobody notices until something goes wrong.**

