# Contributing

Thank you for helping review the observed `ct.ws` subdomain list.

This repository is intended for public review, validation, correction, and documentation of observed `ct.ws` subdomains.

## How to Suggest a Change

Please open a GitHub Issue if you want to report:

- A false positive
- A missing subdomain
- A duplicate entry
- A typo
- A hostname that should be removed
- Additional context about an entry
- A suggested improvement to the repository documentation

Pull requests are also welcome for clean corrections.

## TXT File Format

The main TXT file should follow this format:

- One hostname per line
- Lowercase only
- No `http://` or `https://`
- No URL paths
- No query strings
- No ports
- No comments inside the TXT file
- No blank lines unless intentionally used at the end of the file
- Sorted alphabetically when practical
- Deduplicated

Correct format:

```text
example.ct.ws
subdomain.ct.ws
```

Incorrect format:

```text
https://example.ct.ws
example.ct.ws/login
example.ct.ws:443
Example.CT.WS
```

## Submitting an Issue

When opening an issue, please use this format:

```text
Hostname:
Requested change:
Reason:
Evidence or notes:
```

Example:

```text
Hostname: example.ct.ws
Requested change: Remove
Reason: Appears to be a false positive
Evidence or notes: I could not verify this hostname through current DNS records or other public sources.
```

## Submitting a Pull Request

Before submitting a pull request:

1. Keep the TXT file clean and machine-readable.
2. Do not add commentary directly inside the TXT file.
3. Make sure added hostnames are lowercase.
4. Remove duplicates.
5. Keep the list sorted alphabetically when practical.
6. Explain the reason for the change in the pull request description.

Good pull request description:

```text
Adds 3 newly observed ct.ws subdomains and removes 1 duplicate entry.
```

## Scope

This repository is only for documenting observed subdomains associated with `ct.ws`.

Inclusion in the list means only that the hostname was observed during research. It does not automatically imply:

- Ownership
- Active use
- Abuse
- Compromise
- Malicious activity
- Endorsement
- Affiliation

## Acceptable Contributions

Acceptable contributions include:

- Verified additions
- Verified removals
- Duplicate cleanup
- Typo corrections
- Formatting cleanup
- Documentation improvements
- Review notes
- Source or methodology clarification

## Not Acceptable

Please do not submit:

- Instructions for unauthorized access
- Exploit instructions
- Credential dumps
- Private personal information
- Harassment or targeting requests
- Claims of malicious activity without evidence
- Automated bulk changes without explanation

## Review Notes

All changes may be reviewed before being accepted.

A hostname may remain in the list even if it is no longer active, as long as it was previously observed and the repository notes make that clear.

## Disclaimer

This repository is provided for informational and research purposes only. Do not use this list for unauthorized access attempts, harassment, abuse, scanning against systems you do not own or have permission to test, or any activity that violates applicable laws or terms of service.
