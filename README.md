# Can a shared transit feed assign each notice to the right agency?

Help operators see which findings in a shared timetable belong to them.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/transit-feed-notices/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-transit-feed-notices/pulls)

## Why this matters

A single GTFS feed can serve more than one operator. A combined validation report makes it harder for each agency to find the notices it can act on. MobilityData is discussing how to attribute notices to agencies.

## What to contribute

Build a tiny synthetic feed with two agencies and draft the shape of a per-agency report. Include at least one notice that involves the whole feed.

## How reviewers check it

Show the fixture and command. The expected report assigns each attributable finding to the right agency and handles feed-wide findings explicitly.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/transit-feed-notices
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/transit-feed-notices/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-transit-feed-notices/security/advisories/new) for security reports.

## Sources

- [MobilityData issue \#2201](<https://github.com/MobilityData/gtfs-validator/issues/2201>)
- [GTFS Schedule reference](<https://gtfs.org/documentation/schedule/reference/>)
