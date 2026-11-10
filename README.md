# ci-templates

Shared build template for the Lockbox example A live run (project-lockbox/core#536).

`.github/workflows/lockbox-build.yml` is a verbatim copy of Lockbox's GitHub Actions template
(`integrations/github-actions/lockbox-build.yml` in project-lockbox/core at commit
`11c9465d15c90faef4075e0c8b91be6203fd52d5`, template v3.0.1 for GitHub).

Callers pin it by the full commit SHA of the merge that adds or changes it, never by branch or tag,
and that SHA goes on Lockbox's trusted-templates allow-list. `main` is protected: change it only by
pull request.
