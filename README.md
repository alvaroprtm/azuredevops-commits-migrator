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

### _2026-03-04 08:03:00_ **[eprocapi] Merged PR 900: Feat: New Negotiation Winners API and isTemplate field in Vendor Performance Detail** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/5baf2d8150283df8a9782cf403adbac32891658e))

### _2026-03-04 10:03:00_ **[Eproc] Merged PR 904: PR: Contract Management and Vendor Evaluation Form** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/a34ff5b9d8870ba546c2483f829a08f7e62364de))

### _2026-03-05 05:03:00_ **[eprocapi] Merged PR 906: feat: Enrich Tender Negotiation Winners API Response with Tender Data** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/40a036098fbaa093727964cff04e6808d4658d58))

### _2026-03-06 09:03:00_ **[eprocapi] Merged PR 917: feat: Performance Template Lines API** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/569a725a4c3a10b95d80cbf00151c8101e6046a0))

### _2026-03-09 09:03:00_ **[eprocapi] Merged PR 931: PR: Vendor Performance Evaluation Email Feature** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/160cd672ff9897cdc4b779232dde97c391914068))

### _2026-03-09 13:03:00_ **[Eproc] Merged PR 934: PR: Vendor Evaluation Enhancement and Add Broadcast Feedback Email** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/98b91131a862eb3b59a1ef431a240357587cb0c8))

### _2026-03-10 14:03:00_ **[eprocapi] Merged PR 945: feat: Questionnaire Token isUsed and Update Performance Template Lines** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/766cabdbfd4c7f315ebf1c72469b2228b02316b4))

### _2026-03-11 10:03:00_ **[Eproc] Merged PR 954: PR: Contract and Vendor Performance Evaluation** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/6fa83f8ecc8a76da24ee7a1b8bfe134707374a23))

### _2026-03-11 19:03:00_ **[eprocapi] Merged PR 953: feat: Update Vendor Tender Contract Status API** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/ca055dc7915c0130d68c68e39712e47a38a4c326))

### _2026-03-12 09:03:00_ **[eprocapi] Merged PR 966: feat: Scoring Table and Lines CRUD API** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/0846cd93f0098f19b9afa81e9c25c3c72a883456))

### _2026-03-12 11:03:00_ **[Eproc] Merged PR 967: feat: Scoring Template Menu** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/9261e50781a9051eeee19d026a3cb846b93d1149))

### _2026-03-13 10:03:00_ **[eprocapi] Merged PR 976: fix: scoring template table and lines update functionality API** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/eprocapi/commit/f60652dfd7f00f235d97030bb4f58d3139b6a63b))

### _2026-03-13 10:03:00_ **[Eproc] Merged PR 977: feat: Scoring Template Lines Form** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/38fd58d17f5ddd60904ae5c2de58bdc1ddf352af))

### _2026-03-16 09:03:00_ **[Plato] Merged PR 991: feat: New Default Month Column in HcmContractTerms** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/ac2a5aa92b805367cf2790f4a845d82c6c6e4fc5))

### _2026-03-16 10:03:00_ **[HRMSPayrollUI] Merged PR 992: PR: build v10.2.19** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/18f844c0736300ba8c458be1dd22b007c3d4d059))

### _2026-03-18 02:03:00_ **[HRMSPayrollUI] Merged PR 1001: PR: build v10.2.21** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a90e9050df3e068d13ad9c5880c7aaec55272dfb))

### _2026-03-25 13:03:00_ **[Plato] Merged PR 1014: feat: Add Overtime Request Form field in absenceparameter table** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/f2158d5bc5d3d470a4515e4d7258770fb3aeaa96))

### _2026-03-26 04:03:00_ **[HRMSPayrollUI] Merged PR 1026: PR: build v10.2.22** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/30acc4d750aaa12586ca66336ab17e05e573857b))

### _2026-03-26 12:03:00_ **[HRMSPayrollUI] Merged PR 1033: PR: build v10.2.25** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/d7ddf75b033699d9329c89348715ed7b2ffb7896))

### _2026-03-27 04:03:00_ **[Plato] Merged PR 1040: PR: modifiedfinancialdimension field in Personnel Action Type** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/065dfb2f5e0db48a892ea741ae2ee28dfa34a6a3))

### _2026-03-27 23:03:00_ **[HRMSPayrollUI] Merged PR 1046: PR: build v10.2.26** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/08e86ce34eae890eb9b31791889122a970e6200c))

### _2026-03-30 02:03:00_ **[HRMSPayrollUI] Merged PR 1054: PR: build v10.2.27** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/f44adb996d20f6362cdadf0c8077a9208d948d64))

### _2026-03-30 10:03:00_ **[HRMSPayrollUI] Merged PR 1064: PR: build v10.2.29** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/5f44ee242e55996998e3252171741b288ecb8bbc))

### _2026-03-31 01:03:00_ **[HRMSPayrollUI] Merged PR 1066: PR: build v10.2.30** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/65998ea72b6c38847f99f463085cd8c10d442632))

### _2026-03-31 09:03:00_ **[HRMSPayrollUI] Merged PR 1077: PR: build v10.2.31** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/9d7484b5483f6d04673a438a8750c4a9e7279d24))

### _2026-03-31 11:03:00_ **[HRMSPayrollUI] Merged PR 1078: PR: build v10.2.32** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/920220e4592d43f351937f809e6ca06c91bc91da))

### _2026-03-31 15:03:00_ **[HRMSPayrollUI] Merged PR 1083: PR: Overtime Request Delete Bug** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/f09bf23bae1b0b82daae2a87e0cc717db837ab31))

### _2026-04-02 08:04:00_ **[HRMSPayrollUI] Merged PR 1103: PR: build v10.2.33** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/cfa7765568662eeda832224a84619fa8da015f3a))

### _2026-04-06 04:04:00_ **[HRMSPayrollUI] Merged PR 1117: fix: reference error in worker action detail #3783** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/edf776b92c1d0cbbd67e0540cf606ee29b98ae80))

### _2026-04-06 10:04:00_ **[HRMSPayrollUI] Merged PR 1118: PR: build v10.2.36** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a59b9b85d73cb5f1d96de76ed55621acb57e17eb))

### _2026-04-08 16:04:00_ **[HRMSPayrollUI] Merged PR 1153: PR: build v10.2.37** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/7b5a3570e22df11cb64932958315dc36c89d5ff0))

### _2026-04-09 08:04:00_ **[HRMSPayrollUI] Merged PR 1158: PR: build v10.2.38** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/e746a545dd300e31de40a6d83a313ba48518c264))

### _2026-04-10 12:04:00_ **[HRMSPayrollUI] Merged PR 1170: PR: build v10.2.39** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/4a0d130166e2d99d125ff8490bc27c0288a136ec))

### _2026-04-13 04:04:00_ **[HRMSPayrollUI] Merged PR 1187: PR: build v10.2.40** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/ca6376011a3e6621197c33de516fe7ff2659d94f))

### _2026-04-14 10:04:00_ **[HRMSPayrollUI] Merged PR 1201: PR: build v10.2.41** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1453e59b6239189962d3237dafd4ae45e694198e))

### _2026-04-15 07:04:00_ **[Plato] Merged PR 1227: fix: insert update absence status detail API #3832** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/dcbc0cef49b7a26d326e9251ecd4cefe292e196d))

### _2026-04-15 08:04:00_ **[Plato] Merged PR 1228: fix: add absence status detail issue #3836** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/0d6df4f12f7fa7df608128690a4af306de9d608d))

### _2026-04-15 09:04:00_ **[HRMSPayrollUI] Merged PR 1229: PR: build v10.3.3** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/56f9903e7916993f4fb3fbbffb25a937aababb29))

### _2026-04-16 04:04:00_ **[Plato] Merged PR 1254: Allow ExecuteWFActionBulkForAllWorkflow to process every action type #3857** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/633511ddba017cdab3b9fc4fd946a1334f8693cd))

### _2026-04-16 09:04:00_ **[Plato] Merged PR 1261: feat: New API for Overtime Classification Form #3380** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/8a884dbfafc7275230c30916418120ac0cba3864))

### _2026-04-17 07:04:00_ **[Plato] Merged PR 1275: feat: OTFormType in tmotrequest Insert Payload #3380** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/b0a9f0a91e2239861e74179e8c4431eefc182788))

### _2026-04-17 07:04:00_ **[Plato] Merged PR 1279: feat: GetOTClassificationFormByReqNumber Implementation #3380** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/edd1049aca968cdc89cfa99debca23e840067535))

### _2026-04-17 12:04:00_ **[HRMSPayrollUI] Merged PR 1280: PR: build v10.3.4** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/65789e75d64c6b6364c8d2839b758181693d0d08))

### _2026-04-20 10:04:00_ **[Plato] Merged PR 1319: feat: Enhance GetOTClassificationForm API #3380** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/31daeda8bd195408a2ef184878c4adb11402ff16))

### _2026-04-20 11:04:00_ **[HRMSPayrollUI] Merged PR 1320: PR: build v10.3.5** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/40f6ef8ab68d55e69d8b2c09f95db6791c962086))

### _2026-04-21 20:04:00_ **[Eproc] Merged PR 1353: feat: Vendor Evaluation Result Summary and Modal Upload Document with History** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/abbf8a08b7d766007557ec1b6728b2733565862e))

### _2026-04-22 05:04:00_ **[Eproc] Merged PR 1368: feat:  Vendor Contract Page and Evaluation Template Lookup** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/117db36647dbb6207eaeeab06d71bf730089a1d0))

### _2026-04-23 04:04:00_ **[Eproc] Merged PR 1375: Vendor Evaluation Section and Reviewer Participation** ([link](https://dev.azure.com/WCSProdDevelopment/Eproc/_git/Eproc/commit/b0cbdc9e951c2d5ccdebe21d2df617fae245f6b0))

### _2026-04-23 14:04:00_ **[HRMSPayrollUI] Merged PR 1386: PR: build v10.3.7** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a17dddfd0317619b307c6e18c7635a3ced091888))

### _2026-04-27 04:04:00_ **[HRMSPayrollUI] Merged PR 1398: PR: Fix Cherry Picking Issues** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/fbc19d384e33f4085142107acb44e30f06e8e4b7))

### _2026-05-05 10:05:00_ **[Plato] Merged PR 1431: PR: Overtime Bulk Request** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/71b75ea274cab7d12e36708ba48dea7c1769c1a7))

### _2026-05-07 17:05:00_ **[Plato] Merged PR 1444: feat: enhanced OT bulk request #3864** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/9480a9e6fb17d613dcb3d498a731611298a355a9))

### _2026-05-08 23:05:00_ **[HRMSPayrollUI] Merged PR 1448: PR: build v10.3.22** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/95a3baa25a99906b0283c959e0e7a3782a0efc61))

### _2026-05-11 13:05:00_ **[HRMSPayrollUI] Merged PR 1456: PR: build v11.0.1** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/3fc1ab5694b1bd08bfc8de820a63120cbb276b17))

### _2026-05-12 04:05:00_ **[Plato] Merged PR 1474: refactor: disabled halfday emergency leave request validation** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/c58391293c0b4bccaa41d86ff5f2056261a4f48d))

### _2026-05-17 08:05:00_ **[Plato] Merged PR 1492: PR: Update DayType on OT Request Approval #3864** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/6df5f8813ec0aaa48cd7df8ba2e4450530a17e04))

### _2026-05-18 03:05:00_ **[HRMSPayrollUI] Merged PR 1498: build v11.0.12** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/44a2169853a0f316dad8e0067dc32b0a53915aec))

### _2026-05-18 10:05:00_ **[Plato] Merged PR 1502: feat: Update daytype on workflow approval for OT bulk request and attendance correction** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/1c1a375def7e74e96c9d2e3e2193e4bc3f540301))

### _2026-05-18 11:05:00_ **[HRMSPayrollUI] Merged PR 1503: PR: build v11.0.14** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/9b70535abf9018136429e6c39368e1b824484bf9))

### _2026-05-19 07:05:00_ **[Plato] Merged PR 1504: fix: UpdateWorkerAttendanceTransOnApproval and duplicate records in GetWFAssignedToMe** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/f2c141109ba0e48bb62b1bb630e3a57de3950e23))

### _2026-05-20 11:05:00_ **[HRMSPayrollUI] Merged PR 1516: PR: build v11.0.19** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/580d4ddd34f2a105a1828102c990f36f34a1e848))

### _2026-05-21 04:05:00_ **[Plato] Merged PR 1521: fix: ExportAttachmentTrxExp 'Index was outside the bounds of the array'** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/dd15044d1f2952d7c8be99e06139b1e9c5863177))

### _2026-05-21 11:05:00_ **[HRMSPayrollUI] Merged PR 1526: feat: build v11.0.22** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/823ff9f4ee337652533547b221fc4dfb1f7f8799))

### _2026-05-22 09:05:00_ **[HRMSPayrollUI] Merged PR 1529: PR: build v11.0.23** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1eec01c774535cbf7032bc90ffa39223efdfc281))

### _2026-05-25 08:05:00_ **[Plato] Merged PR 1530: feat: Reprocess attendance transaction by hitting GenerateWoowtimeAbsence** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/ff326258d97139dfcc5b337d604d80f05f3848d1))

### _2026-05-25 10:05:00_ **[HRMSPayrollUI] Merged PR 1546: PR: build v11.0.26** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/0438a2a581f9a586479df37d7e04944c2f7cf7c8))

### _2026-05-26 05:05:00_ **[HRMSPayrollUI] Merged PR 1549: PR: build v11.0.27** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/e6c439787da1005a33025acfdfc74cef920f371b))

### _2026-05-26 18:05:00_ **[Plato] Merged PR 1551: feat: update schedule handling and bulk request validations in overtimebulkrequestmanager** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/460d786cfba1febb943bc61a6f39cd33d7cfa8ad))

### _2026-05-26 21:05:00_ **[HRMSPayrollUI] Merged PR 1552: PR: build v11.0.28** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/053fe52853fd2cf9bc347de81fa3cef8622c2e8f))

### _2026-05-27 01:05:00_ **[HRMSPayrollUI] Merged PR 1553: PR: build v11.0.29** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/a04731344e20abfff0a0f4fbc701cceac1dbff4e))

### _2026-05-28 02:05:00_ **[Plato] Merged PR 1555: feat: replace schedule validation with timeplan validation and add worker data to bulk headers** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/7d679de3f03e2dc7a56db25e35b35a9affcae3b2))

### _2026-05-28 03:05:00_ **[Plato] Merged PR 1558: fix: IAbsenceEngineService wasn't registered in Plato.Service.Kankei.Api's DI container** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/1ed6f3c1bd96ae0e4ad7d3f0e9bf4db6bf2122ae))

### _2026-05-29 13:05:00_ **[Plato] Merged PR 1561: fix: attendance correction approval workflow** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/29a2ea24293e8436e0dfd36f71a485570e2f8b2b))

### _2026-06-02 04:06:00_ **[Plato] Merged PR 1565: fix: report API registration error** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/2ac2fa10273a813b15e6e933d6c1d303301d8918))

### _2026-06-02 06:06:00_ **[HRMSPayrollUI] Merged PR 1568: PR: build v11.1.6** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/218cc657615ca25a1aa68ade941f1d6f6f7d6d43))

### _2026-06-02 09:06:00_ **[Plato] Merged PR 1571: fix: register contract mapping issue & attendance correction approval** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/a4b472772554185f1aac583bec7168f64256c796))

### _2026-06-02 13:06:00_ **[HRMSPayrollUI] Merged PR 1575: PR: build v11.1.7** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/2ccec12196f63495d0a37d335cf8717d4d35a805))

### _2026-06-04 04:06:00_ **[Plato] Merged PR 1593: fix; Report API Errors** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/ef05dc3826d7cc1a8dc22008d6fc3175b368744a))

### _2026-06-04 08:06:00_ **[Plato] Merged PR 1595: Fix InsertUpdateAbsenceCorrection API and Dominos UAT Features** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/67e37a5c76551630f804abc3e5dcdf65d4bdfda7))

### _2026-06-09 07:06:00_ **[Plato] Merged PR 1622: PR: Add missing working daytype in tmworkerattendancetrans, revert GenerateWoowtimeAbsence and fix task list template** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/f6e95cad606ce95e28526ac57c9501764f4bfecd))

### _2026-06-09 12:06:00_ **[Plato] Merged PR 1628: fix: offboarding termination and last day work date filter to 0** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/b556efddaccea3d883177ba15068a8fb5f489d43))

### _2026-06-11 04:06:00_ **[Plato] Merged PR 1632: PR: backfill worker and workerdatahistory on absence correction lines #3888** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/165877e862a73738ef226a29f1a2de5e1aead327))

### _2026-06-11 09:06:00_ **[Plato] Merged PR 1639: feat: Combined same-worker/same-date overtime calculations into one row with summed totals and joined OTReqNumbers in CalculateOvertime #3379** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/Plato/commit/dc479cdb91279c0ca9ee7d714a5eb5b3721102ef))

### _2025-12-22 09:12:00_ **[HRMSPayrollUI] Merged PR 393: PR: build v10.1.23** ([link](https://dev.azure.com/WCSProdDevelopment/HRMS%20Payroll/_git/HRMSPayrollUI/commit/1df14e0742a5e5c2d4adeb9ad435c21af1505b5b))

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

