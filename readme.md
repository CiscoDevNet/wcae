<seotitle>WCAE - Wireless Config Analyzer Express</seotitle>
<seodescription>Tool for Configuration auditing, Best Practices score, in-depth RF analysis and checking typical support issues.  Support for  AireOS and 9800 IOS-XE Controllers, availble in Mac OS, Windows 10 and Cloud versions. The tool will help on preventing TAC cases, and ensure you can detect the most common problem scenarios.</seodescription>

# Wireless Config Analyzer Express

* Support, Questions, Feature requests: [wcae@cisco.com](mailto:wcae@cisco.com)
* [Webex Teams Room](https://eurl.io/#R6RK2M73v)
* [Tool home page:](https://developer.cisco.com/docs/wireless-troubleshooting-tools/)

### [Cloud Version](https://cway.cisco.com/tools/WirelessAnalyzer/)

### [What is new](https://developer.cisco.com/docs/wireless-troubleshooting-tools/what-is-new-engine/)
### [Checks Available](https://developer.cisco.com/docs/wireless-troubleshooting-tools/checks-available-in-tool/)

### Downloads
* [Cloud Version](https://cway.cisco.com/tools/WirelessAnalyzer/)
* [Mac OS Apple Sillicon ](https://github.com/CiscoDevNet/wcae/blob/master/wcae-gui-mac-arm-signed-v12.zip)
* [Mac OS Intel ](https://github.com/CiscoDevNet/wcae/blob/master/wcae-gui-mac-intel-signed-v12.zip)
* [Windows 10/11 ](https://github.com/CiscoDevNet/wcae/blob/master/wcae-gui-win-v12.zip)
* [Direct Downloads](https://github.com/CiscoDevNet/wcae)  

    

## What is WCAE?
* Main Objective: Save time processing WLC configurations, provides information on common configuration errors and best practices
* Secondary Objectives: RF Analysis and  Audit config against a rule set
* Supports both 9800 and AireOS controller types
* New implementation for the WLC Config Analyzer (WLCCA). it is a new re-write of the application, with clean up and improved checks
* Two versions available: as Cloud, just upload your file and get a summary report, or as mini-Desktop application,  with more detailed information
* It is fully  offline to the controller, it does not store any data, or sends any data back
* It is not a TAC supported products, basically provided "as is"
* Support, Questions, Feature requests: [wcae@cisco.com](mailto:wcae@cisco.com)

## What is needed?

* if using AireOS controller: the output of the "show run-config" command. [How to collect](https://developer.cisco.com/docs/wireless-troubleshooting-tools/#!how-to-colletct-sh-run-config)
* if using IOS-XE controller: the output of "show tech wireless"
* It does not work with TFTP config backup, or sh tech
* For AireOS, the best way to collect is is using TFTP  with “transfer upload data run-conf”
* Alternatively: use  SSH with config paging disabled

## What is supported?
* Single WLC scenario. No support for multiple WLCs/files
* AireOS  version 8.0 and higher, any model
* IOS-XE version 16.11 and higher, any model
* All controller/Mobility Express (ME) and Embedded Wireless Controller hardware types


## Reports included
* Excel or text results file on same location as source
* WLC and AP check results
* Syslog summarization
* For 9800, Tag and Profile usage summarization
* RF Stats per band, Flex group, AP group/Tag
* RF Health per band
* Channel stats
* AP configuration summary
* Per AP RF health and stats
* Neighbor reports
* Flexconnect AP config verification


## [WCAE Cloud](https://cway.cisco.com/tools/WirelessAnalyzer/)
* Focus on Summaries not Details
* Provides around 190 automatic checks
* RF Stats, RF Health summarised per AP Group/Tag, Flex Group and controller
* No installation required
