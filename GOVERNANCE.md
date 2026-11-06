# Project roles

| Scope | Person | Role |
| --- | --- | --- |
| Soytec organization | [zeSchlausKwab](https://github.com/zeSchlausKwab) | Owner; inherited Admin access to all organization repositories. |
| soyLI | [hzrd149](https://github.com/hzrd149) | Project lead, with repository Admin access through `soyli-maintainers` once the organization invitation is accepted. |
| napplet.soy shell and Studio | [hzrd149](https://github.com/hzrd149) | Repository Maintain access on `soytec/napplet-soy`; the `shell-maintainers` team carries the same role after organization membership is accepted. |
| Organization profile and governance | [zeSchlausKwab](https://github.com/zeSchlausKwab) | Maintains this repository. |

`hzrd149` is invited as an organization Member, not an organization Owner. Project leadership and repository Admin access do not grant organization ownership.

## Migration status

- Standalone CLI source is now in [soytec/soyli](https://github.com/soytec/soyli). Its [migration notes](https://github.com/soytec/soyli/blob/main/docs/MIGRATION.md) distinguish source extraction from release-channel migration; the shell and hosted services still need a supported consumer interface.
- The existing repository transferred to `soytec/napplet-soy` after publishing and testing soyLI 0.31.1 updater compatibility. Its history, issues, pull requests and releases are preserved.
- Hosted Studio and other backend services remain in `napplet-soy` pending the proposed extraction into [napplet-services](https://github.com/soytec/napplet-services). The browser Studio UI stays with the shell. See [Architecture](ARCHITECTURE.md) for the proposed boundaries and review questions.
- `napplet-services` is a repository bootstrap. Service maintainers and production deployment access still need an explicit assignment; this documentation does not change existing permissions.

