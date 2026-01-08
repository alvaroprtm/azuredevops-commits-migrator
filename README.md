# Azure DevOps to GitHub Migration Tool

Github profile is so boring when no activity is there when you work at a company that use Azure Devops.

This project helps users automate the migration of commits and Pull Requests (PRs) from an Azure DevOps repository to a GitHub repository. It uses a GitHub workflow to automate the migration process.


# Getting Started
1. Fork this repository\
  Click the Fork button in the top-right corner of this page to fork the master repository.

2. Go to forked repo in your repository

3. Add secrets:\
  settings -> Actions secrets and variables -> Repository secrets -> New repository secrets
  ![alt text](resources/image.png)

    ```bash
    PAT  # Your Azure PAT, you'll know how to get it below

    USER_EMAIL  # Your GITHUB user email

    USER_NAME # Your GITHUB user name

    AZURE_NAME  # YOUR username on Azure

    # Set this number to 1, unless you want to fetch all the previous history
    DAYS_LOOKUP

    # This is Github PAT, you'll know how to set below
    GH_WRITE_TOKEN

    # Your Azure DevOps Organization name (e.g. `dev.azure.com/abcd` abcd is the value)
    ORG
    
    # Your destination Github Repository e.g. `Iwan-LMX/azuredevops-commits-migrator` is the value, see below for setting it
    TRACKER_REPO
    ```
6. Run the workflow\
	Actions -> Sync commits with azure devops -> run workflow
	![alt text](resources/image2.png)

## Set Github PAT
Click your avatar in github, find settings -> Develop settings -> Personal access tokens (classic) / Fine-grained personal access tokens -> make sure the your target github repo is covered in the `Repository access`. [Add token](https://github.com/settings/personal-access-tokens).

## Set Azure PAT
user settings (in your project right top) -> Personal access tokens -> New token (Simply give all access)

## For the TRACKER_REPO
For this repo you can choose private or public as you want. But this default branch name should be `master`

<!-- Written by [Iwan Li](https://github.com/Iwan-LMX) -->### _2025-12-22 09:12:00_ **[HRMSPayrollUI] Merged PR 393: PR: build v10.1.23** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1df14e0742a5e5c2d4adeb9ad435c21af1505b5b))

### _2025-12-23 03:12:00_ **[HRMSPayrollUI] Merged PR 394: PR: build v10.1.23** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/03f5d310d51d699d692b37f126987e761353587b))

### _2025-12-23 03:12:00_ **[HRMSPayrollUI] Merged PR 396: PR: Remove JQuery 89 files** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/30e12a44b011bdd662822cc052ef5f477dd006b0))

### _2026-01-05 04:01:00_ **[HRMSPayrollUI] Merged PR 404: PR: build v10.1.29** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/b726cd0b72706837ad4e52daf1287e16aa7b4bf0))

### _2026-01-08 04:01:00_ **[HRMSPayrollUI] Merged PR 434: PR: Remove All JQuery Components** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/4e8af2540200e19c17d64d58af04a8e01df6d727))

### _2026-01-08 09:01:00_ **[HRMSPayrollUI] Merged PR 439: PR: build v10.1.30** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/d57f813c9e41a3a8fde92d79f8ae23d39437c2bc))

