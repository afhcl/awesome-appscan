# awesome-appscan
A collection of useful examples, libraries, and other resources related to HCL AppScan.

## Contents
- [Build Plugins](#build-plugins)
- [Wrappers / Libraries / Etc](#wrappers--libraries--etc)
- [Usage Examples](#usage-examples)
- [Miscellaneous Tools](#miscellaneous-tools)
- [Media](#media)
- [Other Links](#other-links)

### Build Plugins
- [Official ASoC Gradle Plugin (.groovy)](https://github.com/HCL-TECH-SOFTWARE/appscan-gradle-plugin) - 
**[ASoC]** Gradle plugin for integrating with HCL AppScan on Cloud. 
- [Official AppScan Source Gradle Plugin (.groovy)](https://github.com/HCL-TECH-SOFTWARE/appscan-source-gradle-plugin) - **[ASA]** Gradle plugin for integrating via the AppScan Source CLI.
- [Official AppScan Jenkins plugin (.java)](https://github.com/jenkinsci/appscan-plugin) - **[ASoC,ASE]** Integrate security testing in Jenkins with ASoC (SAST, DAST) and ASE (DAST).
- [Official ASoC Maven Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-maven-plugin) - **[ASoC]** Integrate SAST Security testing into your Maven build.
- [Official AppScan Source Maven Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/ounce-maven-plugin) - **[ASA]** Integrate SAST security testing into you Maven build.
- [Official CodeSweep GitHub Extension (.yml)](https://github.com/HCL-TECH-SOFTWARE/appscan-codesweep-action) - **[ASoc]** Run the CodeSweep scan engine as a github action.
- [Official ASoC GoCD Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-gocd-plugin) - **[ASoC]** Integrate ASoC security scanning into a GoCD pipeline.
- [Official ASoC Bamboo Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-bamboo-plugin) - **[ASoC]** Integrate ASoC security scanning into Atlassian Bamboo builds.

 ### Wrappers / Libraries / Etc
- [ASoC SDK (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-sdk) - **[ASoC, ASE]** SDK for interacting with AppScan on Cloud and AppScan Enterprise ADAC jobs.
- [IAST Automation (.py)](https://github.com/HCL-TECH-SOFTWARE/asoc_automation_iast) - **[ASoC]** IAST automation examples with Python.
- [Python SAClientUtil (.py)](https://github.com/cwtravis/python-saclient-wrapper) - **[ASoc]** Python wrapper around ASoC SAClientUtil command line utility. 
- [AppScan Automation Framework (.js)](https://github.com/HCL-TECH-SOFTWARE/appscan-automation-framework) - **[ASoC,ASE]** - Node.js wrappers around many ASoC and ASE APIs.
- [AppScan Issue Gateway (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-issue-gateway) - **[ASoC,ASE]** Service to sychronize issues between ASoC or ASE and issues managment systems including Jira, RTC, and Azure DevOps.
- [ASE APIs (.py)](https://github.com/sperlis/ase-apis) - **[ASE]** Python to interact with ASE APIs.

### Usage examples
- [Bitbucket ASoC SAST (.py, .yml)](https://github.com/HCL-TECH-SOFTWARE/bitbucket-asoc-sast) - **[ASoC]** Run an ASoC SAST scan in a bitbucket pipeline.
- [AppScan Presence Dockerfile (.md)](https://github.com/jrocia/AppScanPresence-Dockerfile) - **[ASoC]** Configure ASoC Appscan Presence to run inside a container.
- [ASoC Automation Snippets (.py, .bat)](https://github.com/HCL-TECH-SOFTWARE/asoc-automation-snippets) - **[ASoC]** Example code snippets for programmatically interacting with ASoC.
- [ASoC SAST Linux (.py)](https://github.com/cwtravis/asoc-sast-linux) - **[ASoc]** Run an ASoC SAST scan on a linux machine.
- [ASoC GitHub Action Demo (.yml)](https://github.com/antonychiu2/ASoC_Demo) - End-to-end walkthrough of ASoC SAST via GitHub Actions.
- [ASoC Apex Scanning (.yml)](https://github.com/cwtravis/asoc-apex-demo) - **[ASoc]** Uses GitHub Actions to initate ASoC SAST scan of Apex code.


### Miscellaneous Tools
- [AppScan Langs (.py)](https://github.com/gledonne/appscanlangs) - **[ASoC,ASA]** Programatically get a list of languages supported by AppScan SAST tools. 
- [ASoC Webhook Proxy (.py)](https://github.com/cwtravis/asoc-wehbook-proxy) - **[ASoC]** Capture, modfiy, and reroute ASoC Webhook requests to send alerts to Discord, Slack, etc.
- [Auto XML Config (.py)](https://github.com/alexhcl/autoxmlconfig) - **[ASoC]** Programatically generate an ASoC appscan-config.xml file for a given a list of target files.
- [AIMG Client (.py)](https://github.com/cwtravis/AIMG_Client) - Generic client for creating tickets with The AppScan Issue Gateway service.
- [AppScan 2 Excel (.py)](https://github.com/masquerad3r/Appscan2Excel) - Merge data from AppScan DAST scan log and .XML report and output .xlsx file.
- [AppScan to Archer (.py)](https://github.com/smit1759/appscan-to-archer) - Import AppScan results into RSA Archer.

### Media
- [Application Paranoia Podcast](https://appscan.buzzsprout.com/) - Twice-monthly podcast about Applicaiton Security, DevSecOps, and AppScan.
- [AppScan Tuesdays Archive](https://www.youtube.com/channel/UCzizunEqoF1e-pHd04JAZ2Q) - Weekly Video AppScan Podcast.
- [HCL Software YouTube](https://www.youtube.com/playlist?list=PL2tETTrnR4wvtkgR6ILKOdoQIP_o9MF1u) - Playlist of AppScan content on main HCL Software YouTube channel.

### Other Links
- [AppScan Documentation](https://help.hcltechsw.com/appscan/Welcome.html) - Offical documentation page for all AppScan products.
clod
- [AppScan on Cloud Plugins & APIs](https://cloud.appscan.com/plugins) - Updated list of ASoC plugins and APIs.
- [Altoro Mutual (.java/.js)](https://github.com/HCL-TECH-SOFTWARE/AltoroJ) - Intentionally vulnerable application often used to demo AppScan products.


&nbsp; 

&nbsp;
#### <u>Product Abbreviations</u>
- **ASoC** - AppScan on Cloud
- **ASE** - AppScan Enterprise
- **ASA** - AppScan Source
- **ASD** - AppScan Standard