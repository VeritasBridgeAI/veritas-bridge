# Security Policy

Veritas Bridge is proprietary software. This public repository contains documentation and media only; it is not the production source repository.

## Reporting a security issue

Please **do not open a public GitHub issue** for suspected vulnerabilities, exposed credentials, private endpoints, authentication weaknesses, or other security-sensitive findings.

Send security-sensitive reports privately to:

**thomas@veritasbridgeai.com**

Suggested subject:

`Veritas Bridge security report`

Please include, where safe to do so:

- a concise description of the issue;
- the affected public page, artifact, or release identifier;
- reproduction steps that do not expose secrets publicly;
- expected versus observed behavior;
- potential impact;
- any screenshots or logs with credentials, tokens, personal data, and private paths removed.

## Scope of this public repository

This repository intentionally excludes:

- production source code;
- credentials, API keys, signatures, and approval material;
- private prompts and user-memory contents;
- protected controller and review implementation;
- private machine paths and internal endpoints;
- raw protected qualification logs;
- security-sensitive deployment recipes.

If you believe any of those materials have been accidentally published, please report it privately and avoid redistributing the material.

## Responsible disclosure

Please allow reasonable time to investigate and address a report before public disclosure. Veritas Bridge LLC may request additional information needed to reproduce or understand the issue.

No bug bounty or reward program is currently promised by this policy.

## Security claims

Public qualification evidence demonstrates specific tested authority and access boundaries. It does **not** claim universal containment, immunity from privileged-host compromise, resistance to every prompt-injection path, or complete coverage of every future model, browser, plugin, launcher, or integration.
