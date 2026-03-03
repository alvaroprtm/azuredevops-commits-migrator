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

### _2026-01-22 03:01:00_ **[HRMSPayrollUI] Merged PR 522: PR: Pentest JQuery Bug Fixes in Recruitment Module** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/6712959115bcb91ed197b04fe9148f03c0c865f9))

### _2026-01-22 10:01:00_ **[HRMSPayrollUI] Merged PR 527: PR: build v10.1.39** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/249ea7eaa23028a6a5676e67949837da359af84d))

### _2026-01-23 09:01:00_ **[HRMSPayrollUI] Merged PR 533: PR: build v10.1.40** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/b04752908846c0d10f08f318a8989d014759d262))

### _2026-01-26 07:01:00_ **[HRMSPayrollUI] Merged PR 535: PR: build v10.1.41** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/ff469c3791d0e5428ea0c722585d8f9eadd40885))

### _2026-01-28 10:01:00_ **[HRMSPayrollUI] Merged PR 552: PR: build v10.1.42** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/e7c9e0a610ea86a4c5ec1b4722663a3d7317e108))

### _2026-01-28 13:01:00_ **[HRMSPayrollUI] Merged PR 553: PR: Pentest JQuery Bug Fixes in Performance, Talent, and Attendance Modules** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/382a92288fdba670e2f7b7eb96bcba97fddcbf7e))

### _2026-01-29 05:01:00_ **[HRMSPayrollUI] Merged PR 559: PR: JQuery Pentest Bug Fixes for Performance and Attendance Modules** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/0a4247ad4ef333603b3045db3cad8609207baf4d))

### _2026-01-29 07:01:00_ **[HRMSPayrollUI] Merged PR 560: PR: import absence and schedule in system administration bug fix** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1bcb6ab75c3887e2c70eff9c7ccdf86ea4d881b1))

### _2026-01-29 10:01:00_ **[HRMSPayrollUI] Merged PR 562: PR: overtime request to-do list time input validations** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/5fc4f7360d31ea1d7f019e62e40bc7c5ad04592b))

### _2026-01-30 09:01:00_ **[HRMSPayrollUI] Merged PR 578: PR: build v10.1.43** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/0c8f95a0e78e52ba2b8e78b45f1046183403df66))

### _2026-02-02 09:02:00_ **[HRMSPayrollUI] Merged PR 599: PR: build v10.1.44** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/d8ce6a488c6ddf2d02dd5760638889a508b1feb8))

### _2026-02-03 10:02:00_ **[HRMSPayrollUI] Merged PR 613: PR: build v10.1.45** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/434d241c5f3fb3399a33817dd98c590ae88377cf))

### _2026-02-09 05:02:00_ **[HRMSPayrollUI] Merged PR 665: PR: JQuery bug** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/bc450de2a8734445d7717b7a10d72a3d41c86725))

### _2026-02-11 04:02:00_ **[Eproc] Merged PR 680: PR: initial commit of adding contract management module** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/91ad4a837922e28440985591eb5c9d35bc2632d2))

### _2026-02-11 05:02:00_ **[HRMSPayrollUI] Merged PR 685: PR: Payslip Report Definition Bug** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/8ced692718247da6a935a9f29afce8db6b7275f4))

### _2026-02-12 09:02:00_ **[HRMSPayrollUI] Merged PR 718: PR: build v10.2.2** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a3f71391827e19873f6795ee2ef4086dfdaff93e))

### _2026-02-13 10:02:00_ **[HRMSPayrollUI] Merged PR 732: PR: build v10.2.3** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/d0efec4d53a26b3eb1f0465fa26f1f3d69ab2d3f))

### _2026-02-18 07:02:00_ **[Eproc] Merged PR 764: PR: Add Vendor Evaluation Module and Refactor Contract Form** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/7bfc157f3d8428c88954cbd670e00d3c7d725946))

### _2026-02-20 08:02:00_ **[HRMSPayrollUI] Merged PR 787: PR: build v10.2.4** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/4b70b58174db982b2d1ef658a94d798fa3762cfe))

### _2026-02-20 10:02:00_ **[HRMSPayrollUI] Merged PR 790: PR: build v10.2.5** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/bccf8f2ca4b314267a6d21a7c9a42b36a7b9c88b))

### _2026-02-23 10:02:00_ **[HRMSPayrollUI] Merged PR 798: PR: build v10.2.6** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a501ce05d14d20c76ebcd4b47100d72d98decc96))

### _2026-02-24 10:02:00_ **[Eproc] Merged PR 813: PR: Vendor Performance Evaluation API Integration** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/6fd547063ffae801ca2dd242c8344d562d683e4a))

### _2026-02-25 09:02:00_ **[Eproc] Merged PR 829: PR: Reviewer and Detail Page UI Enhancemnet in Vendor Evaluation** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/32bcb09df085e5fafe390d2846db8a5b604ac75c))

### _2026-02-26 08:02:00_ **[Eproc] Merged PR 841: PR: Notification Settings on NavBar** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/6cdfb0baf606d4e97bb07688a936f7136edf881a))

### _2026-02-26 09:02:00_ **[HRMSPayrollUI] Merged PR 842: PR: build v10.2.8** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a0d4e5a7371fd340314131e33aa3e9fa4b07ca6e))

### _2026-02-27 08:02:00_ **[HRMSPayrollUI] Merged PR 853: PR: build v10.2.9** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/2a8783a2f1c1e4a03f70bbb2ca9bbaa92f2a9afb))

### _2026-02-27 09:02:00_ **[HRMSPayrollUI] Merged PR 857: PR: build v10.2.10** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/27894f95d8c49f46ab37772c71a02a880f65f091))

### _2026-02-27 10:02:00_ **[HRMSPayrollUI] Merged PR 858: PR: build v10.2.11** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/3bc9586bf605c0a3a6274ab57220a3925022125e))

### _2026-02-27 12:02:00_ **[Eproc] Merged PR 860: PR: Integrating Vendor Dashboard API** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/de77622a6ce35fd35900462a1949465df391fb41))

### _2026-02-28 10:02:00_ **[HRMSPayrollUI] Merged PR 864: PR: build v10.2.12** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/f933ec41d6d3699ed4237b22891999095421d978))

### _2026-03-02 06:03:00_ **[Eproc] Merged PR 878: PR: Vendor Dashboard API Integration** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/140a1896c78d7489fc1137e9371978e446e94577))

### _2026-03-02 14:03:00_ **[HRMSPayrollUI] Merged PR 883: PR: build v10.2.14** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/bc6b5ed8395e7f7c164f746d56a5032824d634d2))

### _2026-03-03 05:03:00_ **[HRMSPayrollUI] Merged PR 889: PR: build v10.2.15** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1cadf457dafd9b9556f97709c6eb8e24a4477ead))

### _2026-03-03 10:03:00_ **[HRMSPayrollUI] Merged PR 896: PR: build v10.2.16** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/0a1ea489960c4b3b459ea73e5d1ff49e15cc78a6))

