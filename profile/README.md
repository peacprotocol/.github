# PEAC Protocol

Programmable Environment for Agent Coordination

PEAC is an open protocol for verifiable receipts and policy aware access in digital interactions between agents, APIs, crawlers, web applications, and services.

It makes “who accessed what, under which terms, and with which payment rail” cryptographically verifiable, while staying neutral to any specific platform or vendor. The protocol is implemented as a small receipt envelope, payment evidence model, and a set of adapters that work with existing HTTP, payment, and agent stacks.

---

## What is PEAC Protocol

PEAC Protocol provides a standardized framework for:

- Verifiable receipts for AI and API traffic
- Policy aware access control for agents and crawlers
- Settlement aware HTTP 402 flows across multiple payment rails
- Attribution, consent, and compliance evidence that can be audited

On the web, PEAC can be paired with a machine readable policy surface such as `/.well-known/peac.txt`. This lives alongside existing files like `robots.txt`, `ai.txt`, `llm.txt`, or AIPREF style manifests. Policies declare what is allowed and under what terms. Receipts prove what actually happened.

---

## Who is PEAC for

PEAC is designed for infrastructure teams that need trusted proof around automated traffic:

- **API and SaaS providers** that want verifiable HTTP 402 billing and receipts for usage
- **Publishers and data owners** that want policy aware access and chargeable AI or crawler traffic
- **AI and agent platforms** that need a neutral receipts format across different rails and policies
- **Risk, legal, and compliance teams** that need cryptographic evidence for investigations and audits

PEAC does not replace your gateway, crawler rules, or billing system. It gives them a common receipts layer so that access, payment, and policy compliance can be proven, not just logged.

---

## Projects in this organization

This GitHub organization contains the reference implementation and related tooling for PEAC Protocol, including:

- Core specification artifacts and kernel constants
- TypeScript SDK for issuing and verifying receipts
- HTTP server and CLI for verification and integration
- Adapters for payment rails and agent protocols
- Early work on policy surfaces such as `peac.txt`

For full protocol documentation and examples, see the website at [https://peacprotocol.org](https://peacprotocol.org).

---

## Stewardship

PEAC Protocol is an open source project stewarded by contributors from [Originary](https://www.originary.xyz) and the wider community.

Originary focuses on receipts, policy, and settlement infrastructure for AI and API traffic, and PEAC is the protocol layer that keeps this work vendor neutral and independently implementable.

---

## Contributing

Contributions are welcome.

Please see the contribution guidelines in the main repository:

[https://github.com/peacprotocol/peac/blob/main/CONTRIBUTING.md](https://github.com/peacprotocol/peac/blob/main/CONTRIBUTING.md)

Issues and pull requests that improve the specification, reference implementation, examples, or documentation are all encouraged.

---

## License

PEAC Protocol is licensed under the Apache License 2.0.

See [LICENSE](https://github.com/peacprotocol/peac/blob/main/LICENSE) for details.

---

## Support and community

- **Issues**: Bug reports and feature requests via GitHub Issues on the relevant repository
- **Email**: support@peacprotocol.org  
- **Website**: [https://peacprotocol.org](https://peacprotocol.org)

If you are building your own implementation, SDK, adapter, or policy tooling around PEAC, open an issue in the main repository so it can be linked from ecosystem documentation.
