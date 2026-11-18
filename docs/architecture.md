# Architecture and evidence boundaries

The project has a coordinator (Squad), seven active specialists, and four built-in support roles. `.squad/team.md` identifies the roster; `.squad/routing.md` documents task assignment and issue labels; Konrad's `charter.md` documents incident response and approval rules.

The routing policy directs Azure SRE/quota issues to Talos, network issues to Octavia, data issues to Variel, observability to Cyrion, incident documentation to Septimus, and independent review to Sevatar. Konrad coordinates cross-domain work. The human lead retains final authority.

**Observed:** a quota test invoked Talos, Sevatar, and Konrad in a revision loop. **Not observed:** a production deployment, comprehensive test of all seven active agents, or a live issue-driven workflow. See the example transcript.
