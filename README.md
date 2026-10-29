# qiskit-community.github.io

This repository allows us to set up client-side redirects in GitHub Pages for repositories that moved from the qiskit-community organization to Qiskit.

The redirects live in this organization-level site rather than in a repository named after the project, so that the GitHub-level redirect for `github.com/qiskit-community/<repo-name>` keeps working.

## How to add a new project

```bash
./generate-redirects.py <repo-name>
```

`<repo-name>` should be a value like `fulqrum`. This script assumes that the repository name has not changed, only the GitHub organization.
