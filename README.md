# KhulnaSoft Shared GitHub Actions Workflows

GitHub Actions shared within the `khulnasoft-lab` organization.

To use one of these workflows:

```yaml
jobs:
  call-workflow-passing-data:
    uses: khulnasoft-lab/shared-workflows/.github/workflows/reusable-workflow.yml@main
    secrets: inherit
```
