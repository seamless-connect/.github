# Seamless

Open infrastructure for secure, interoperable connections across services, domains, providers, and agents.

[Website](https://seamlessconnect.org/) · [Sponsorship](https://seamlessconnect.org/sponsors/)

Seamless Connect is a public-benefit, open-source project, with nonprofit governance provided by the [Foundation for Agentic Networks](https://www.agenticnet.org/), a 501(c)(3) nonprofit and home of the MIT-originated Project NANDA.

## Why this exists

Connecting a service still requires too many manual steps, proprietary integrations, and provider-specific workflows. That fragmentation creates cost, support burden, security risk, and lock-in for service platforms, infrastructure providers, developers, and users.

Seamless is building a neutral connection layer that makes configuration, discovery, and verification open, reliable, and auditable. The project begins with domain and DNS configuration, but its scope is intentionally broader: the same open approach can support non-DNS connections between services and across the emerging agentic web.

## Initial focus: domain operations

The core maintainers of [Domain Connect](https://www.domainconnect.org/) have joined Seamless. The project is initially focused on operationalizing Domain Connect as broadly usable infrastructure while the [IETF DCONN Working Group](https://datatracker.ietf.org/wg/dconn/about/) advances the protocol on the standards track.

Service Providers can send the same Domain Connect request they use today through Seamless Connect to a supported DNS Provider:

**Domain Connect request → Seamless Connect → supported DNS Provider**

Seamless Connect handles provider discovery; template retrieval, validation, and approval; provider capability and policy evaluation; Domain Owner authorization; provider-specific execution; synchronous and asynchronous operation handling; retries and durable state; outcome verification; and normalized completion and status. This gives Service Providers a consistent integration while allowing DNS Providers to retain their own APIs, policies, and authorization models.

The work is delivered as neutral hosted infrastructure with open APIs, SDKs, command-line tooling, shared validation and conformance tools, documentation, examples, and reusable onboarding assets.

## Standards first

Seamless Connect uses existing open standards wherever they cover the use case, including Domain Connect for standardized DNS configuration flows. Where gaps exist, the project may prototype explicit, deterministic interfaces in the open, with the goal of interoperable standards rather than proprietary protocols.

## Integration guides

- [Service Provider Integration Checklist](https://github.com/seamless-connect/docs/blob/main/integration-checklists/service-provider-integration-checklist.md)
- [DNS Provider Integration Checklist](https://github.com/seamless-connect/docs/blob/main/integration-checklists/dns-provider-integration-checklist.md)
- [Registrar Integration Checklist](https://github.com/seamless-connect/docs/blob/main/integration-checklists/registrar-integration-checklist.md)

## Agentic operations

Agentic support means that agents can initiate and monitor the same explicit, authorized, deterministic operations available to other clients. Seamless Connect provides durable coordination for asynchronous and multi-provider workflows, including state, retries, verification, and normalized status.

Over time, the same standards-first approach can support broader connections between services and agents without requiring those connections to be DNS-based. This is a central area of collaboration with the Foundation for Agentic Networks and its work on an open, interoperable agentic web.

## What we believe

Connections should be:

- **open** — based on public standards and reusable infrastructure
- **neutral** — governed for the benefit of the full ecosystem
- **simple** — easy for developers, providers, services, agents, and users
- **secure** — scoped, authorized, and designed to minimize risk
- **interoperable** — portable across platforms and implementation technologies
- **auditable and deterministic** — explicit and predictable about requested changes, authorization, and results
- **extensible** — able to support both DNS and non-DNS connection mechanisms

## Get involved

Seamless is forming its launch community and welcomes:

- service platforms, DNS providers, registrars, and infrastructure vendors
- agentic-web projects, researchers, and standards participants
- open-source maintainers and technical contributors
- member organizations, sponsors, and design partners

Technical participation is open and independent of sponsorship. Visit [seamlessconnect.org](https://seamlessconnect.org/), review the [sponsorship program](https://seamlessconnect.org/sponsors/), or explore the repositories in this organization to participate.

## License

Unless otherwise noted, code in this organization is licensed under the **Apache License 2.0**.
