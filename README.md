# paypya-gating
> The central repository of Gating GitHub Actions

## Usage
The following example workflow step
```yaml
jobs:
  check-dependencies:
    name: Check dependencies
    uses: paypay/paypay-gating/.github/workflows/reusable-workflow.yml@releases/v1
```