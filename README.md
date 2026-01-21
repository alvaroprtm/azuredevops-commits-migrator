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

### _2026-01-08 10:01:00_ **[HRMSPayrollUI] Merged PR 441: PR: build v10.1.31** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/e411050143d736f34f0f0004428f8342258b84e6))

### _2026-01-09 10:01:00_ **[HRMSPayrollUI] Merged PR 449: PR: build v10.1.32** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/132bd5921cda063f3c2fbab8aafc1373fa225aca))

### _2026-01-13 04:01:00_ **[HRMSPayrollUI] Merged PR 458: PR: build v10.1.33** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/f002e0f3e9b06754185a66e53fd5fcc006ba11e6))

### _2026-01-13 09:01:00_ **[HRMSPayrollUI] Merged PR 462: PR: Bug Fixes Following Pentest Remediation** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/f5e5b5ff6b0cf5572c3a000037fa9112c69c9c4e))

### _2026-01-14 11:01:00_ **[HRMSPayrollUI] Merged PR 470: PR: Pentest Bug Fixes in Payroll Menu** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/6b3dfb94c59f5349af18580a7007a594251ffe69))

### _2026-01-14 14:01:00_ **[HRMSPayrollUI] Merged PR 472: PR: build v10.1.34** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/53b960a16bdbee33286b760ebf3b236047a91627))

### _2026-01-15 07:01:00_ **[HRMSPayrollUI] Merged PR 481: PR: Fix Custom Modal Titles in Organization Administration Menu** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/e8cacd0e391e8923957f9d4e10c373c39d105845))

### _2026-01-15 08:01:00_ **[HRMSPayrollUI] Merged PR 483: PR: build v10.1.35** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/89c4e662ee3e95d43b6224f6415d5dc97ea5c595))

### _2026-01-19 04:01:00_ **[HRMSPayrollUI] Merged PR 492: PR: build v10.1.36** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/3618b80e448493e2ffb73a7c23017f4466b5404d))

### _2026-01-19 09:01:00_ **[HRMSPayrollUI] Merged PR 496: PR: Refactor Telerik Report into a React component** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1136f436ed053fb96ac882bb3eb7f197ae21254c))

### _2026-01-21 03:01:00_ **[HRMSPayrollUI] Merged PR 512: PR: build v10.1.37** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a6bb3d6d9758a5ebfeb69675e9f8244930462c7a))

### _2026-01-21 06:01:00_ **[HRMSPayrollUI] Merged PR 515: PR: Payroll Module bugs** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/5c04b2509f2fe76fba3819f6f9683913a820cbc4))

### _2026-01-21 10:01:00_ **[HRMSPayrollUI] Merged PR 518: PR: build v10.1.38** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/dcf4420ff0cffffccf4e9a1d287465dd12339a1a))

