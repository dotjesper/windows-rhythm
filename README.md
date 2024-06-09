---
Title: README
Date: June 5, 2024
Author: dotjesper
Status: In development
---

# Windows rhythm

This repository contains the source code for Windows rhythm.

> [!NOTE] 
> If you are looking for the Windows Desired State Configuration solution, the project has been rebranded as [Windows Gecko](https://github.com/dotjesper/windows-gecko "Windows Gecko").

[![Built for Windows 11](https://img.shields.io/badge/Built%20for%20Windows%2011-Yes-blue?style=flat)](https://windows.com/ "Built for Windows 11")
[![Built for Windows 10](https://img.shields.io/badge/Built%20for%20Windows%2010-Yes-blue?style=flat)](https://windows.com/ "Built for Windows 10")

> [!IMPORTANT]  
> Due to a local disk failure, we had to recreate this project from scratch, meaning if you have starred and/or followed the project, we kindly ask you to help us spread the word, and re-star and re-follow the repository. Thanks.

According to Wikipedia, Rhythm means a *"movement marked by the regulated succession of strong and weak elements, or of opposite or different conditions"*.

> Rhythm is related to and distinguished from pulse, meter, and beats.

Windows rhythm is exactly that, a set of Baseline Settings, designed to add pulse to Windows management beats.

This repository is under development and alive and for the most, kicking - I welcome any feedback or suggestions for improvement. Reach out on [Twitter](https://twitter.com/dotjesper "dotjesper"), I read Direct Messages (DMs) and allow them from people I do not follow. For other means of contact, please visit [https://dotjesper.com/contact/](https://dotjesper.com/contact/ "Contact")

Do not hesitate to reach out if issues arise or new functionality and improvement comes to mind.

Feel free to fork and build.

This is a personal development, please respect the community sharing philosophy and be nice!

## The Art of Balancing Windows Security and Usability

In today's world, organizations face a constant challenge of Balancing Security and Usability in IT systems. Security is essential to protect data, assets, and reputation from cyber threats, but it can also impose restrictions and limitations on the users, affecting their productivity, satisfaction, and performance.

If the usability of application security features is weak, users will try to avoid or bypass them. However, if done correctly, security does not impact usability, on the contrary, usability increases security.

This delicate equilibrium is particularly crucial in the realm of the Modern Workplace, where security protocols are paramount to safeguard sensitive data and systems. Unfortunately, when forming the Modern Workplace, organizations are often met by strict self-propelled security requirements. We, however, propose to aim to follow the usability trio principle, often referred to as the usability triangle:

- Usability
- Security
- Manageability

The tree areas are all equally important, despite security measures often getting the “most airtime” we have focus on usability, pursuing goals to meet and exceed productivity requirements as well as deliver on expectations for more personal computing on the devices in use.

The art of balancing Windows Security and Usability, go headfirst into the intricate dynamics of the perpetual struggle between security and the pursuit of a great end-user experience.

The answer is a Policy Framework that doesn't just focus on security settings, but also very much include settings to ensure the uest User experience.

### The Benefits of a Policy Framework

A Policy Framework that integrates security and usability settings can bring many benefits to your organization, such as:

- **Enhanced Security**: A Policy Framework can help you to apply the latest Security Baselines and Best Practices to your Windows platform, reducing the attack surface and mitigating the risks of breaches, data loss, and compliance violations. A Policy Framework can also help you to monitor and audit your security posture, detecting and responding to any anomalies or incidents.
- **Improved usability**: A Policy Framework can help you to customize and optimize your Windows platform to suit the needs and preferences of your users, increasing their productivity, satisfaction, and performance. A Policy Framework can help you to manage and update your Usability Settings, ensuring that they are consistent and compatible across your devices and applications and platforms.
- **Reduced costs**: A Policy Framework can help you to save time and money by automating and streamlining your Windows platform configuration, management, and maintenance. A Policy Framework can also help you to avoid errors and conflicts that can cause downtime, disruptions, and rework.
- **Increased agility**: A Policy Framework can help you to adapt and evolve your Windows platform to the changing needs and demands of your business and users, enabling you to introduce new features, functionalities, and innovations faster and easier.

The Policy Framework is a set of rules and guidelines that help you manage and optimize your devices and applications. The policy framework policy naming has three types:

- **Endpoint Security policies**: These policies help you protect your devices from threats and vulnerabilities. Endpoint Security policies are based on Microsoft Defender features, such as BitLocker, Firewall, and Antivirus. For example, the policy `C-Microsoft-Defender-BitLocker-settings` enables BitLocker encryption on your devices and configures the recovery options. 
- **Configuration Settings policies**: These policies help you customize the user experience and functionality of your devices and applications. Configuration Settings policies are based on your preferences and needs, and can include settings for appearance, language, accessibility, and performance. For example, the policy `U-Microsoft-Office-365-Word-configuration-settings` sets the default font, page layout, and spelling options for Word. 
- **Security Settings policies**: These policies help you enforce security best practices and compliance standards on your devices and applications. Security Settings policies are based on Microsoft Security Baselines, which are recommended configurations for Windows, Office, and other products. For example, the policy `U-Microsoft-Office-365-Word-security-settings` applies the security settings for Word, such as disabling macros and other recomended security settings.

Splitting the policies into these three types has several benefits, such as:

- **Simplifying the policy management and deployment process**. You can create, edit, and assign policies based on their type, and avoid conflicts and overlaps between policies. 
- **Improving the policy visibility and accountability**. You can easily monitor and audit the policies based on their type and impact and identify and resolve any issues or gaps. 
- **Enhancing the policy flexibility and scalability**. You can tailor the policies based on their type and target and adapt them to different scenarios and requirements. 
- **Facilitating the policy troubleshooting and testing**. You can isolate and diagnose the policies based on their type and behavior and perform waved or staged rollouts to evaluate the policy outcomes. 

### Recommended tools for managing Policy Frameworks

There are several tools that can help you with managing a Policy Framework, depending on your needs and preferences. Here are some of the tools that we recommend and what they can do for you: 

- [Policy Analyzer](https://www.microsoft.com/en-us/download/details.aspx?id=55319 "Policy Analyzer"): The Policy Analyzer is a simple tool for examining and comparing groups of Group Policy Objects (GPOs) and is part of the [Microsoft Security Compliance Toolkit](https://www.microsoft.com/en-us/download/details.aspx?id=55319 "Microsoft Security Compliance Toolkit"). It can show when a group of Policies has overlapping settings or internal conflicts and can show the changes between versions or groups of Policies. It can also compare one or more GPOs with the local effective state. You can export all its results to a Microsoft Excel spreadsheet. 
- [IntuneManagement](https://github.com/Micke-K/IntuneManagement "IntuneManagement"): I highly recommend using the IntuneManagement tool, a tool that can help you to apply, manage, and monitor policy framework settings for Microsoft Intune. The tool is used for import, export, assignment of Policy Framework settings in bulk. The tool can export and import objects including assignments and support import/export between tenants, creating migration tables during export and use that for importing assignments in other environments. It can create missing groups in the target environment during import. 
- PowerShell: Scripts to help you to import and export Policy Framework (GPOs) settings using PowerShell. You can use PowerShell commands to import policies settings from backup files. 

### Security frameworks

[Microsoft Security Baselines](https://www.microsoft.com/en-us/download/details.aspx?id=55319 "Microsoft Security Compliance Toolkit")

[DoD Cyper Exchange Group Policy Objects](https://public.cyber.mil/stigs/gpo/ "Group Policy Objects - DoD Cyper Exchange")

[National Cyber Security Centre (NCSC) Device Security Guidance](https://www.ncsc.gov.uk/collection/device-security-guidance/ "Device Security Guidance - NCSC.GOV.UK")

[Australian Signals Directorate](https://www.asd.gov.au/ "Australian Signals Directorate")

[CIS Center for Internet Security](https://www.cisecurity.org/ "CIS Center for Internet Security")

### Conclusion

In conclusion, having a Policy Framework that doesn't just focus on Security Settings, but also very much include settings to ensure the Best User Experience in the Windows platform can bring many benefits to your organization, such as enhanced security, improved usability, reduced costs, and increased agility.
To implement such a Policy Framework, you need to consider which Security Baselines and vendors that can help you to protect your Windows platform from various threats and risks, and the Usability Triangle that can help you to optimize your Windows platform for different dimensions of usability.

## Disclaimer

This is not an official repository, and is not affiliated with Microsoft, the **Windows rhythm** repository is not affiliated with, or endorsed by, Microsoft. The names of actual companies and products mentioned herein may be the trademarks of their respective owners. All trademarks are the property of their respective companies.

The configuration baseline provided in this document is intended to help you optimize the performance and security of your system. However, the use of this configuration baseline is at your own risk, and you are solely responsible for any consequences that may arise from applying it to your system. You should always perform a thorough test and validation of the configuration baseline before implementing it in your production environment. You should also backup your system and data before making any changes to your configuration settings.

We do not guarantee the accuracy, completeness, or suitability of the configuration baseline for any specific purpose. We do not assume any liability for any damages, losses, or expenses that may result from the use of the configuration baseline. We do not provide any warranty, express or implied, for the configuration baseline. We do not endorse or recommend any products, services, or vendors that may be mentioned or linked in the document.

By using the configuration baseline, you agree to abide by the terms and conditions of this disclaimer. If you do not agree with the disclaimer, do not use the configuration baseline.

## Legal and Licensing

**Windows rhythm** is licensed under the [MIT license](./LICENSE "MIT license").

The information and data of this repository and its contents are subject to change at any time without notice to you. This repository and its contents are provided AS IS without warranty of any kind and should not be interpreted as an offer or commitment on the part of the author(s). The descriptions are intended as brief highlights to aid understanding, rather than as thorough coverage.

- You should never assign these policies outside your pilot group.
- You should never import these policies using automatic assignment.
- You should never assign these policies without thoroughly test and validation.

This project is intended to serve as a foundation or starting point and should not be considered 'complete'. It has been made available to facilitate learning, development, and knowledge-sharing among communities. Please note that no liability is assumed for the usage or application of the settings within this project in production tenants.