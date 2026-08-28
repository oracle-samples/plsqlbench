<!--
A Benchmark for Real-World Enterprise Text-to-PLSQL Workflows

Copyright © 2026, Oracle and/or its affiliates.
Licensed under the Creative Commons Attribution-ShareAlike 4.0 International
License (CC BY-SA 4.0) except where otherwise noted.
Third-party datasets, code, and other materials included in or referenced by
this repository remain subject to their original licenses. See Attribution.txt
for source-specific copyright, attribution, and modification information. See
Third-Party-Licenses.txt for full-license reproduction.
-->

# Contributing to PLSQLBench

We welcome documentation improvements, bug reports, and proposals for dataset
corrections or additions.

## Opening issues

For bugs or enhancement requests, file a GitHub issue unless it is security
related. Include the affected benchmark, public instance ID, expected behavior,
and enough information to reproduce the problem. Do not include private
holdout data, credentials, personal information, confidential information, or
data that you do not have permission to share.

If you think you have found a security vulnerability, do not raise a GitHub
issue. Follow the instructions in our [security policy](./SECURITY.md).

## Contributing code

Before submitting a pull request, you must sign the
[Oracle Contributor Agreement][OCA] (OCA). Each commit must include the
following line, using the name and email address used to sign the OCA:

```text
Signed-off-by: Your Name <you@example.org>
```

Add the line automatically by committing with `--signoff` or `-s`, for example:

```text
git commit --signoff
```

Only pull requests from contributors who can be verified as having signed the
OCA can be accepted.

The public release is a generated, read-only snapshot. Do not directly edit
generated dataset, metadata, DDL, or DML files. Report data corrections with
their public instance IDs and provenance so maintainers can review them in the
canonical source and include them in a later generated release. Pull requests
for public documentation may update the applicable Markdown files directly.

## Pull request process

1. Create an issue to discuss the fix or enhancement.
2. Fork the repository and create a focused branch.
3. Make the smallest change needed to resolve the issue.
4. Update relevant documentation and attribution information.
5. Confirm that no private holdout content, credentials, or unapproved
   third-party material is included.
6. Submit a signed-off pull request that references the issue and describes how
   maintainers can validate the change.

## Code of conduct

Follow the [Golden Rule](https://en.wikipedia.org/wiki/Golden_Rule). For more
specific guidelines, see the [Contributor Covenant Code of Conduct][COC].

[OCA]: https://oca.opensource.oracle.com
[COC]: https://www.contributor-covenant.org/version/1/4/code-of-conduct/
