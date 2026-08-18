# Security Policy

## Reporting a vulnerability

Please **do not** open a public issue or a pull request for a security problem, and
please do not contact package maintainers listed on npm directly: those are personal
accounts and they are not monitored for security reports.

Report vulnerabilities through GitHub instead:

1. Open the affected repository under [diplodoc-platform](https://github.com/diplodoc-platform).
2. Go to the **Security** tab and press **Report a vulnerability**.
3. Fill in the form. The report stays private and is visible only to the maintainers.

A report is most useful when it includes:

- the affected package and version (for example `@diplodoc/search-extension@3.0.2`);
- steps to reproduce, ideally with a minimal example;
- the impact you expect an attacker to achieve.

We aim to acknowledge a report within 5 working days. Once the issue is confirmed, we
fix it in a private fork, release a patched version and publish a security advisory
with a CVE. Reporters are credited in the advisory unless they ask otherwise.

## Supported versions

Security fixes are released for the latest major version of each `@diplodoc/*` package.
Older majors are not patched, so please upgrade before reporting an issue that is
already fixed in a newer release.
