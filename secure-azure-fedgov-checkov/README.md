
# Secure Azure FedGov Checkov Demo

This repository demonstrates the use of [Checkov](https://github.com/bridgecrewio/checkov) for scanning Terraform infrastructure as code for FedRAMP/FedGov compliance.

## Structure

- `main.tf` - Terraform configuration with intentional security issues for demo
- `.github/workflows/checkov.yml` - GitHub Actions pipeline that runs Checkov

## Usage

1. Install Checkov:
   ```
   pip install checkov
   ```

2. Run locally:
   ```
   checkov -d .
   ```

3. Push to GitHub and see results in GitHub Actions.
