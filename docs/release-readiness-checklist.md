# Release Readiness Checklist

Use this checklist before approving a release to staging/production. Tailor items to your project as needed.

- [ ] All acceptance criteria for features in the release are met.
- [ ] All PRs merged are reviewed and pass CI (tests and lint).
- [ ] Security scans completed and any high/critical findings resolved or mitigated.
- [ ] Migration scripts reviewed and tested (if applicable).
- [ ] Backups/snapshots scheduled (if applicable).
- [ ] SRE/Platform validated deployment plan and rollback steps.
- [ ] Release notes drafted and reviewed.
- [ ] Monitoring/alerts configured for new behavior and validated.
- [ ] Post-deploy smoke tests defined and ready.
- [ ] Support runbook updated for known customer impact.
- [ ] Stakeholders notified of deployment window and expected impact.
