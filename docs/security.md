# Security and responsible publication

## Before publishing
1. Inspect every file and image for API keys, bearer tokens, cloud tenant/subscription identifiers, personal email, machine paths, private repositories, internal hostnames and customer information.
2. Never commit `.env`, local `.squad` history/memory/logs, authentication files, or real secrets.
3. Review framework licensing before copying agent charters, generated templates, or setup source.
4. Check Git history too: deleting a secret from the latest commit does not remove it from previous commits.
5. Keep production changes behind explicit human approval; never run AI-generated infrastructure commands without independent verification.

## Demo boundaries
The uploaded transcript describes a read-only exercise. Some tool calls were denied for lack of interactive approval; no changes to Azure resources were reported. A returned recommendation is not proof that the root cause was established.
