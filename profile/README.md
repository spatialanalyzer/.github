<div align="center">

# SpatialAnalyzer Open Source

**Open integration tools for SpatialAnalyzer automation.**

</div>

The **SpatialAnalyzer** GitHub organization is building open-source tools,
libraries, documentation, and examples for the SpatialAnalyzer product
ecosystem.

Our first project family is **Briosa**: a modern, language-neutral bridge to
the SpatialAnalyzer SDK.

## Briosa

Briosa exposes SpatialAnalyzer Measurement Plan and SDK capabilities through a
clean gRPC API. Thin, idiomatic client libraries make that API feel natural in
each supported language.

```text
Your application
      ↓
.NET · JavaScript · Python · other clients
      ↓
    gRPC
      ↓
 Briosa server
      ↓
    SA SDK
      ↓
SpatialAnalyzer
```

The active ecosystem includes:

- [`briosa`](https://github.com/spatialanalyzer/briosa) — the gRPC server,
  exact-target protocol, command catalog, generators, and server tests
- [`briosa-dotnet`](https://github.com/spatialanalyzer/briosa-dotnet) — thin
  .NET client
- [`briosa-js`](https://github.com/spatialanalyzer/briosa-js) — thin
  JavaScript and TypeScript client
- [`briosa-py`](https://github.com/spatialanalyzer/briosa-py) — thin Python
  client
- [`community`](https://github.com/spatialanalyzer/community) — organization
  Discussions and community navigation
- [`governance`](https://github.com/spatialanalyzer/governance) — organization
  policy, stewardship, and open governance questions

## Project status

Briosa and its thin clients are in active early-stage development and have not
yet published stable releases. APIs, supported SpatialAnalyzer releases, and
release policies remain subject to review.

Follow cross-repository priorities in the
[Briosa Roadmap & Delivery project](https://github.com/orgs/spatialanalyzer/projects/1)
and architecture evidence in
[SpatialAnalyzer Discussions](https://github.com/orgs/spatialanalyzer/discussions),
beginning with
[Discussion #1](https://github.com/orgs/spatialanalyzer/discussions/1).

The project begins under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## SpatialAnalyzer requirement

Briosa is an integration layer; it does not include SpatialAnalyzer or replace
a SpatialAnalyzer license. You may download and start Briosa without an active
SpatialAnalyzer license, but Briosa requires access to a properly licensed and
functioning SpatialAnalyzer installation to perform SpatialAnalyzer
operations.

## Governance

The organization is currently independently administered. Its governance is
intentionally provisional while the founding maintainers establish the
project's long-term institutional and community model.

Read the public
[project charter and governance policies](https://github.com/spatialanalyzer/governance).

## Get involved

We are starting with a small founding team and intend to grow into a
manufacturing-industry community. You can:

- review the active roadmap and early-stage repositories;
- report bugs and propose improvements in the owning repository;
- contribute server, client, documentation, and example changes; and
- use Discussions to help shape a consistent automation interface across
  programming languages.

Watch the repositories for progress toward the first releases.

---

SpatialAnalyzer is a Hexagon product. These independently administered
open-source projects do not imply Hexagon affiliation, endorsement, or support,
and Briosa is not a replacement for official Hexagon product support. Product
and trademark usage is governed separately from the open-source license.
