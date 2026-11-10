# ci-templates

Shared build template for the Lockbox example A live run (project-lockbox/core#536).

`.github/workflows/lockbox-build.yml` is a verbatim copy of Lockbox's GitHub Actions template
(`integrations/github-actions/lockbox-build.yml` in project-lockbox/core, template v3.0.2 for GitHub:
keyless provenance is attested with cosign, project-lockbox/core#537).

Callers pin it by the full commit SHA of the merge that adds or changes it, never by branch or tag,
and that SHA goes on Lockbox's trusted-templates allow-list. `main` is protected: change it only by
pull request.
