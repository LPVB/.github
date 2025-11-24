# .github

This is the special `.github` repository for the LPVB organization on GitHub. This repository serves as a central location for organization-wide configuration, community health files, and reusable workflow templates.

## Purpose

The `.github` repository is a special repository recognized by GitHub that allows organizations to:

- **Define default community health files** that apply to all repositories in the organization
- **Store reusable workflow templates** for GitHub Actions
- **Create an organization profile** that appears on the organization's main page
- **Centralize organization-wide documentation** and guidelines

## Repository Structure

This repository can contain the following directories and files:

### `profile/`
- `README.md` - Organization profile that appears on `github.com/LPVB`

### `workflow-templates/`
- Reusable GitHub Actions workflow templates available to all repositories

### Community Health Files
The following files, when placed in the root or `.github/` directory, serve as defaults for all repositories in the organization (unless overridden in individual repositories):

- `CODE_OF_CONDUCT.md` - Code of conduct for the organization
- `CONTRIBUTING.md` - Contribution guidelines
- `FUNDING.yml` - Funding information
- `ISSUE_TEMPLATE/` - Default issue templates
- `PULL_REQUEST_TEMPLATE.md` - Default pull request template
- `SECURITY.md` - Security policy
- `SUPPORT.md` - Support resources

## Usage

Any community health file added to this repository will automatically be used as a default for all public repositories in the LPVB organization that don't have their own version of that file.

## Contributing

To add or update organization-wide defaults:

1. Create a new branch
2. Add or modify the relevant files
3. Submit a pull request for review
4. Once merged, changes will automatically apply to all organization repositories

## Learn More

- [About default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [Workflow templates for organizations](https://docs.github.com/en/actions/learn-github-actions/creating-workflow-templates-for-your-organization)