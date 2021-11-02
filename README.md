# Awesome AppScan
A collection of useful examples, libraries, and other resources related to HCL AppScan.

## Contents
- [AppScan on Cloud (ASoC)](#appscan-on-cloud-asoc)
  - [ASoC Build Plugins](#asoc-build-plugins)
  - [ASoC Wrappers / Libraries / Etc](#asoc-wrappers--libraries--etc)
  - [ASoC Usage Examples](#asoc-usage-examples)
  - [ASoC Tools](#asoc-tools)
- [AppScan Enterprise (ASE)](#appscan-enterprise-ase)
  - [ASE Build Plugins](#ase-build-plugins)
  - [ASE Wrappers / Libraries / Etc](#ase-wrappers--libraries--etc)
- [AppScan Source (AS)](#appscan-source-as)
  - [AS Build Plugins](#as-build-plugins)
- [Miscellaneous Tools](#miscellaneous-tools)
- [Media](#media)
- [Other Links](#other-links)

## AppScan on Cloud (ASoC)
### ASoC Build Plugins
- [ASoC Jenkins plugin (.java)](https://github.com/jenkinsci/appscan-plugin) - Integrate ASoC SAST and DAST security testing in Jenkins.
- [ASoC Bamboo Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-bamboo-plugin) - Integrate ASoC security scanning into Atlassian Bamboo builds.
- [ASoC GoCD Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-gocd-plugin) - Integrate ASoC security scanning into a GoCD pipeline.
- [ASoC Maven Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-maven-plugin) - Integrate SAST Security testing into your Maven build.
- [ASoC Gradle Plugin (.groovy)](https://github.com/HCL-TECH-SOFTWARE/appscan-gradle-plugin) - Gradle plugin for integrating with HCL AppScan on Cloud. 
- [CodeSweep GitHub Extension (.yml)](https://github.com/HCL-TECH-SOFTWARE/appscan-codesweep-action) - Run the CodeSweep scan engine as a github action.
### ASoC Wrappers / Libraries / Etc
- [AppScan SDK (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-sdk) - SDK for interacting with ASoC.
- [IAST Automation (.py)](https://github.com/HCL-TECH-SOFTWARE/asoc_automation_iast) - Python tools for ASoC IAST automation.
- [Python SAClientUtil (.py)](https://github.com/cwtravis/python-saclient-wrapper) - Python wrapper around ASoC SAClientUtil command line utility. 
- [AppScan Automation Framework (.js)](https://github.com/HCL-TECH-SOFTWARE/appscan-automation-framework) - Node.js wrappers around many ASoC APIs.
- [AppScan Issue Gateway (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-issue-gateway) - Service to sychronize issues between ASoC and issue managment systems including Jira, RTC, and Azure DevOps.
### ASoC Usage Examples
- [Bitbucket ASoC SAST (.py, .yml)](https://github.com/HCL-TECH-SOFTWARE/bitbucket-asoc-sast) - Run an ASoC SAST scan in a bitbucket pipeline.
- [AppScan Presence Dockerfile (.md)](https://github.com/jrocia/AppScanPresence-Dockerfile) - Configure ASoC Appscan Presence to run inside a container.
- [ASoC Automation Snippets (.py, .bat)](https://github.com/HCL-TECH-SOFTWARE/asoc-automation-snippets) - Example code snippets for programmatically interacting with ASoC.
- [ASoC SAST Linux (.py)](https://github.com/cwtravis/asoc-sast-linux) - Run an ASoC SAST scan on a linux machine.
- [AltoroJ ASoC GitHub Action (.yml)](https://github.com/cwtravis/AltoroJ-Github-Actions) - Example using GitHub Actions to run a SAST scan on the AltoroJ 3.2 codebase.
- [ASoC GitHub Action Demo (.yml)](https://github.com/antonychiu2/ASoC_Demo) - End-to-end walkthrough of ASoC SAST via GitHub Actions.
- [ASoC Apex Scanning (.yml)](https://github.com/cwtravis/asoc-apex-demo) - Uses GitHub Actions to initate ASoC SAST scan of Apex code.
- [ASoC DAST Scheduling (.py)](https://github.com/dwwatk02/automation) - Run a list of configured scans.
- [Expanded Github Action Demo](https://github.com/glhcl/ASoCActionDemo) - Multiple examples including CodeSweep for VS Code and GitHub, and ASoC GitHub action demo.
### ASoC Tools
- [ASoC Webhook Proxy (.py)](https://github.com/cwtravis/asoc-wehbook-proxy) - Capture, modfiy, and reroute ASoC Webhook requests to send alerts to Discord, Slack, etc.
- [Auto XML Config (.py)](https://github.com/alexhcl/autoxmlconfig) - Programatically generate an ASoC appscan-config.xml file for a given a list of target files.

## AppScan Enterprise (ASE)
### ASE Build Plugins
- [AppScan Jenkins plugin (.java)](https://github.com/jenkinsci/appscan-plugin) - Integrate ASE DAST security testing in Jenkins.
### ASE Wrappers / Libraries / Etc
- [AppScan SDK (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-sdk) - SDK for interacting with AppScan Enterprise ADAC jobs.
- [AppScan Automation Framework (.js)](https://github.com/HCL-TECH-SOFTWARE/appscan-automation-framework) - Node.js wrappers around many ASE APIs.
- [AppScan Issue Gateway (.java)](https://github.com/HCL-TECH-SOFTWARE/appscan-issue-gateway) - Service to sychronize issues between ASE and issues managment systems including Jira, RTC, and Azure DevOps.
- [ASE APIs (.py)](https://github.com/sperlis/ase-apis) - Python tools to interact with ASE APIs.

## AppScan Source (AS)
### AS Build Plugins
- [AppScan Source Gradle Plugin (.groovy)](https://github.com/HCL-TECH-SOFTWARE/appscan-source-gradle-plugin) - Gradle plugin for integrating via the AppScan Source CLI.
- [AppScan Source Maven Plugin (.java)](https://github.com/HCL-TECH-SOFTWARE/ounce-maven-plugin) - Integrate SAST security testing into your Maven build.

## Miscellaneous Tools
- [AppScan Langs (.py)](https://github.com/gledonne/appscanlangs) - Programatically get a list of languages supported by AppScan SAST tools.
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
