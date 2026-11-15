# Country App Opportunity Framework

This is the reusable operating framework for the repository. It starts with a required country, researches local evidence, identifies customer/problem domains, proposes app concepts only for promising domains, screens fatal risks, maps first-customer routes, and selects a low-cost experiment.

## How to use it

1. Read [`SKILL.md`](SKILL.md) for the operating rules and workflow modes.
2. For a new market scan, load [`references/country-market-scan.md`](references/country-market-scan.md), then the references listed by `discover` in the skill.
3. Use [`references/output-contract.md`](references/output-contract.md) for the decision-led report.
4. When structured assessment data is available, the helper scripts can check scoring arithmetic and packet consistency:

   ```sh
   python scripts/score_opportunities.py INPUT.json
   python scripts/validate_packet.py PACKET.json
   ```

The scripts do arithmetic and structural checks only. They do not research markets, decide whether a source is credible, assign semantic scores, or determine whether an app will succeed.

## Origin and adaptation

The core opportunity-discovery workflow and helper scripts are adapted from [`highstat/product-opportunity`](https://github.com/highstat/product-opportunity), a Codex skill released under the MIT License. The upstream repository was archived on October 22, 2026. This adaptation retains the upstream license and adds a country-first market scan, opportunity-domain step, and local-source coverage requirements. See [`LICENSE`](LICENSE).

Upstream strengths retained include claim/evidence provenance, explicit counter-evidence, source fitness, first-customer route checks, fatal gates before scoring, objective-specific weights, score ranges, and decision-changing experiment design. The country/context workflow in this repository is an extension and should not be attributed to the upstream authors.

## Limits

This is a research and decision aid. It cannot guarantee revenue, demand, product-market fit, legal compliance, or investment suitability. Current country, competitor, price, policy, and legal claims must be rechecked for each analysis.
