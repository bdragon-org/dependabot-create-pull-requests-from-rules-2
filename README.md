# bdragon-org/dependabot-create-pull-requests-from-rules-2

Dependabot security updates: disabled

Dependabot alerts: enabled

Alert rules:

1. [Dismiss low-moderate alerts for npm dev dependencies](https://github.com/bdragon-org/dependabot-create-pull-requests-from-rules-2/settings/dependabot_rules/edit/358)
2. [Dismiss until patch then open PR for npm runtime dependencies](https://github.com/bdragon-org/dependabot-create-pull-requests-from-rules-2/settings/dependabot_rules/edit/359)

Manifest files:

* package.json
* package-lock.json

| dependency | advisory | severity | affected | patched | rule | expect PR? |
|---|---|---|---|---|---|---|
| sails | [CVE-2023-38504](https://github.com/advisories/GHSA-gpw9-fwm8-7rx7) | high | `< 1.5.7` | `1.5.7` | 2. | yes |
| zod | [CVE-2023-4316](https://github.com/advisories/GHSA-m95q-7qp3-xv42) | low | `<= 3.22.2` | `3.22.3` | 1. | no |

