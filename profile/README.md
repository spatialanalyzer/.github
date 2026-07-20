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

The planned ecosystem includes:

- `briosa` — the gRPC server and core protocol
- `briosa-dotnet` — .NET client libraries
- `briosa-js` — JavaScript and TypeScript client libraries
- `briosa-py` — Python client libraries
- documentation, examples, and compatibility tests

## Project status

Briosa is in its founding and initial-development stage. APIs, supported
SpatialAnalyzer releases, versioning, and release policies are still being
established.

The project begins under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## SpatialAnalyzer requirement

Briosa is an integration layer; it does not include SpatialAnalyzer or replace
a SpatialAnalyzer license. You may download and start Briosa without an active
SpatialAnalyzer license, but Briosa requires access to a properly licensed and
functioning SpatialAnalyzer installation to perform SpatialAnalyzer
operations.

## Governance

The organization is currently independently administered and is being
developed with support from Hexagon. Its governance is intentionally
provisional while the founding maintainers establish the project's long-term
institutional and community model.

Read the public
[project charter and governance policies](https://github.com/spatialanalyzer/governance).

## Get involved

We are starting with a small founding team and intend to grow into a
manufacturing-industry community. As repositories become available, you will
be able to:

- try Briosa against supported SpatialAnalyzer releases;
- report bugs and propose improvements;
- contribute server, client, documentation, and example changes; and
- help shape a consistent automation interface across programming languages.

Watch this organization for the first Briosa repositories and releases.

---

SpatialAnalyzer is a Hexagon product. Briosa is not a replacement for official
Hexagon product support. Product and trademark usage is governed separately
from the open-source license.
