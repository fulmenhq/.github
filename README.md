# fulmenhq GitHub community files

This repository maintains the [fulmenhq organization profile](profile/README.md)
and shared contributor guidance for [fulmenhq](https://github.com/fulmenhq).

## Contents

- `profile/README.md`: public organization introduction.
- `CONTRIBUTING.md`, `SUPPORT.md`, `SECURITY.md`, and `CODE_OF_CONDUCT.md`: community defaults.
- `.github/ISSUE_TEMPLATE/` and `.github/PULL_REQUEST_TEMPLATE.md`: issue and pull request templates adapted from [3 Leaps OSS policies](https://github.com/3leaps/oss-policies).

GitHub displays the profile and supplies community defaults when this
repository is public. A project's own corresponding files take precedence.
Defaults are not copied into downstream clones; each project keeps its own
license files. See [GitHub's community-file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Maintaining the profile

List only public projects. Describe what each project does, and link to its
README for current capabilities and maturity. Use **Fulmen** as the display
brand and **fulmenhq** as the GitHub organization. Product names stay with the
projects; this organization is the publisher, not a SKU.

When reviewing the published organization page, select **View as: Public**
to check the profile and pinned repositories as visitors will see them.

There is no curated Fulmen wordmark in this repository yet. Keep the profile
text-first until official artwork is published. If artwork is added later, use
absolute public URLs so they also work on the organization overview.

Run `make check` and `make quality` before proposing changes. Organization
settings, repository descriptions, topics, and pins are managed separately
from these files.

## Governing policies

This repository follows the [Sensitive Local Data policy](https://github.com/3leaps/oss-policies/blob/main/SENSITIVE-LOCAL-DATA.md):
keep proprietary material outside the repository, including its commit
messages, pull requests, and branch names. See also the
[Trademark Policy](https://github.com/3leaps/oss-policies/blob/main/TRADEMARK-POLICY.md)
for brand usage and [LICENSE](LICENSE) for this repository's licensing.
