# OpenRTMP Community

The central community hub for all OpenRTMP projects.

Use this repository for bug reports, feature requests, interoperability reports, questions, ideas, and cross-project discussions. Source code and pull requests stay in the repository that owns the implementation.

## Start here

- [Report a bug or request a feature](https://github.com/OpenRTMP/community/issues/new/choose)
- [Browse existing issues](https://github.com/OpenRTMP/community/issues)
- [Ask a question or start a discussion](https://github.com/OpenRTMP/community/discussions)
- [OpenRTMP documentation](https://openrtmp.org/docs/)
- [Contributing guide](https://github.com/OpenRTMP/.github/blob/main/CONTRIBUTING.md)
- [Security policy](https://github.com/OpenRTMP/.github/blob/main/SECURITY.md)

## Which component is affected?

Choose the closest component when opening an issue. It is fine if you are unsure; the purpose of this repository is to avoid making users determine the exact code owner before they can ask for help.

| Component | What it covers | Source repository |
|---|---|---|
| `librtmp2` | RTMP/RTMPS protocol, sessions, relay behavior, parsers, Enhanced RTMP, C FFI | [`OpenRTMP/librtmp2`](https://github.com/OpenRTMP/librtmp2) |
| `librtmp2-server` | Server API, SQLite, stream keys, statistics, listeners, clustering, server image | [`OpenRTMP/librtmp2-server`](https://github.com/OpenRTMP/librtmp2-server) |
| `librtmp2-server-panel` | Web UI, authentication, API client, copied URLs, live statistics, panel image | [`OpenRTMP/librtmp2-server-panel`](https://github.com/OpenRTMP/librtmp2-server-panel) |
| `packages` | Debian, Ubuntu, Alpine packages and package repository automation | [`OpenRTMP/packages`](https://github.com/OpenRTMP/packages) |
| `openrtmp.org` | Website, documentation presentation, quickstart and guides | [`OpenRTMP/openrtmp.org`](https://github.com/OpenRTMP/openrtmp.org) |
| `organization/community` | Shared project policy, community process or cross-project topics | [`OpenRTMP/.github`](https://github.com/OpenRTMP/.github) |

## Issues vs. Discussions

Open an **issue** when there is an actionable bug, feature request, packaging problem, documentation problem, or interoperability report that can be tracked to completion.

Use **Discussions** for setup help, usage questions, architecture ideas, feedback, proposals that are not yet actionable, and general OpenRTMP conversation.

Large or cross-project changes should normally start in Discussions or a central tracking issue before implementation begins.

## Contributing code

Pull requests belong in the source repository that owns the change. If a change spans multiple repositories, use one issue in this community repository to track the work and link the related pull requests and merge order.

Before contributing, read the organization-wide [CONTRIBUTING.md](https://github.com/OpenRTMP/.github/blob/main/CONTRIBUTING.md).

## Security

Do **not** report security vulnerabilities in public issues or discussions. Follow the [OpenRTMP security policy](https://github.com/OpenRTMP/.github/blob/main/SECURITY.md) and use private vulnerability reporting for the affected source repository when available.

## Project status

OpenRTMP is community-maintained active alpha software. Response times are not guaranteed. Pin versions and validate your complete workflow before critical production use.
