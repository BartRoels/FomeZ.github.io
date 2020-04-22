---
layout: post
title: Azure Sentinel Learning Path
image: /img/WVD-Logo.jpg
published: true
---

# Azure Sentinel learning paths

# Table of contents
1. [Introduction](#introduction)
2. [Some paragraph](#paragraph1)
    1. [Sub paragraph](#subparagraph1)
3. [Another paragraph](#paragraph2)

## This is the introduction <a name="introduction"></a>
Some introduction text, formatted in heading 2 style

## Some paragraph <a name="paragraph1"></a>
The first paragraph text

### Sub paragraph <a name="subparagraph1"></a>
This is a sub paragraph, formatted in heading 3 style

## Another paragraph <a name="paragraph2"></a>
The second paragraph text

[Beginner (BDM, presales roles)](#_Beginner)

- Module 1: Technical overview

- Module 2: Azure Sentinel role

### Advanced (Security Analyst)

- Module 1: Technical overview

- Module 3: Cloud architecture and multi-worksapce/tenant support

- Module 12: Handling incidents

- Module 13: Hunting

### Expert (SOC engineer)

- Module 1: Technical overview

- Module 3: Cloud architecture and multi-worksapce/tenant support

- Module 7: KQL

- Module 8: Write rules

- Module 9: Creating playbooks

- Module 10: Developing workbooks

- Module 13: Hunting

<a name="Beginner"></a>
## Beginner (BDM, presales roles)

### Module 1: Technical overview

###


If you want to get an initial overview of Azure Sentinel&#39;s technical capabilities. The presentation also servers as the Azure Sentinel Level 200 presentation:

- Webinar: [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmggMkcVweWOqoxuN9), [YouTube](https://youtu.be/7An7BB-CcQI)
- [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmgjrN_zHpzbnfX_mX) (updated)

**Learn more**

You can read more about the features described in the Webinar here:

- [Using the new built-in URL detonation in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/using-the-new-built-in-url-detonation-in-azure-sentinel/ba-p/996229)

### Module 2: Azure Sentinel role

Still at level 200: what are the typical use for Azure Sentinel? What are customers finding in it, and also, how is it priced? All in this [presentation](https://techcommunity.microsoft.com/t5/forums/editpage/board-id/AzureSentinelBlog/message-id/243/is-draft/true?attachment-id=21924)

**Learn more** :

- [Azure Sentinel pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator/?service=azure-sentinel)
- [Azure Sentinel](https://azure.microsoft.com/en-us/pricing/details/azure-sentinel/) and [Log Analytics](https://azure.microsoft.com/en-us/pricing/details/monitor/) pricing pages

## Advanced (Security Analyst)

### Module 1: Technical overview

###


If you want to get an initial overview of Azure Sentinel&#39;s technical capabilities. The presentation also servers as the Azure Sentinel Level 200 presentation:

- Webinar: [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmggMkcVweWOqoxuN9), [YouTube](https://youtu.be/7An7BB-CcQI)
- [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmgjrN_zHpzbnfX_mX) (updated)

**Learn more**

You can read more about the features described in the Webinar here:

- [Using the new built-in URL detonation in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/using-the-new-built-in-url-detonation-in-azure-sentinel/ba-p/996229)

### Module 3: Cloud architecture and multi-worksapce/tenant support

An Azure Sentinel instance is called a workspace. Multiple workspaces are often necessary and can act together as a single Azure Sentinel system. The first half of the Webinar above discusses Azure Sentinel&#39;s workspace architecture.

###


- Webinar (includes Module 4): [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmggvs6o4EcxYTgvV6), [YouTube](https://youtu.be/_mm3GNwPBHU)
- [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmgjuszn8-jty5Gbx7) (includes Module 4)
- You may also want to register for the MSSP and distributed organization webinar on April 20th [here](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u).

**Learn more**

- Learn how to manage Azure Sentinel using CD/CI methodology and a GitHub repository in [Deploying and Managing Azure Sentinel as Code](https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928) as well as[ extend this capability across workspaces and tenants using Azure Lighthouse](https://techcommunity.microsoft.com/t5/azure-sentinel/combining-azure-lighthouse-with-sentinel-s-devops-capabilities/ba-p/1210966).
- Use [KQL queries in Azure Sentinel across workspaces](https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/cross-workspace-query) to combine multiple workspaces into a single system.
- Use[ resource RBAC](https://techcommunity.microsoft.com/t5/azure-sentinel/controlling-access-to-azure-sentinel-data-resource-rbac/ba-p/1301463) to enable multiple teams to use a single workspace.
- [Use Azure Lighthouse to extend multi-workspace capabilities across tenants.](https://techcommunity.microsoft.com/t5/azure-sentinel/using-azure-lighthouse-and-azure-sentinel-to-monitor-across/ba-p/1043899)

###

### Module 12: Handling incidents

After building your SOC, you need to start using it. Watch the day in a SOC analyst life to learn how to use Azure Sentinel in the SOC:

- Webinar: [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmghEg_9Z2NjQ_DDpo), [YouTube](https://youtu.be/HloK6Ay4h1M)
- [Presentation](https://1drv.ms/b/s%21AnEPjr8tHcNmghALzkfTkg-dTmfH)

### Module 13: Hunting

Whatever is your methodology and use case for hunting, Azure Sentinel is a great hunting platform.

- [Hunting and Notebooks feature overview presentation](https://techcommunity.microsoft.com/gxcuf89792/attachments/gxcuf89792/AzureSentinelBlog/243/3/L400-P8%20Notebooks%20and%20hunting.pdf).
- Threat hunting webinar ([MP4](https://1drv.ms/v/s!AnEPjr8tHcNmgVrt_iN5W4gt0WlG?e=fGhiyZ), [YouTube](https://youtu.be/Tiz-ftnlTg4)) and presentations [(Deck 1](https://1drv.ms/b/s!AnEPjr8tHcNmgVlNSw5ouPxYkVS0?e=j5l1hI), [Deck 2](https://1drv.ms/b/s!AnEPjr8tHcNmgWLisWDg0ha36wMd?e=YJWjQ7))
- Threat hunting revisited ([MP4](https://1drv.ms/v/s!AnEPjr8tHcNmghQwthryNWI5Yfuh), [YouTube](https://youtu.be/BTEV_b6-vtg), [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmghNdbqppq1myNzG_))
- Threat Hunting - AWS using Sentinel, webinar on April 22nd, register [here](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u).

**Learn more**

- [Why Use Jupyter for Security Investigations?](https://techcommunity.microsoft.com/t5/azure-sentinel/why-use-jupyter-for-security-investigations/ba-p/475729)
- [​​​​​​​](https://techcommunity.microsoft.com/t5/azure-sentinel/why-use-jupyter-for-security-investigations/ba-p/475729)Security Investigation with Azure Sentinel and Jupyter Notebooks ([part 1](https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/432921), [part 2](https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/483466), [part 3](https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/561413))
- [msticpy - Python Defender Tools](https://techcommunity.microsoft.com/t5/azure-sentinel/msticpy-python-defender-tools/ba-p/648929)
- [What am I looking at? - Using Notebooks to gain situational awareness](https://techcommunity.microsoft.com/t5/azure-sentinel/what-am-i-looking-at-using-notebooks-to-gain-situational/ba-p/891818)
- [Explorer Notebook Series: The Linux Host Explorer](https://techcommunity.microsoft.com/t5/azure-sentinel/explorer-notebook-series-the-linux-host-explorer/ba-p/1138273)
- [Using Threat Intelligence in your Jupyter Notebooks](https://techcommunity.microsoft.com/t5/azure-sentinel/using-threat-intelligence-in-your-jupyter-notebooks/ba-p/860239)

## Expert (SOC engineer)

### Module 1: Technical overview

###


If you want to get an initial overview of Azure Sentinel&#39;s technical capabilities. The presentation also servers as the Azure Sentinel Level 200 presentation:

- Webinar: [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmggMkcVweWOqoxuN9), [YouTube](https://youtu.be/7An7BB-CcQI)
- [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmgjrN_zHpzbnfX_mX) (updated)

**Learn more**

You can read more about the features described in the Webinar here:

- [Using the new built-in URL detonation in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/using-the-new-built-in-url-detonation-in-azure-sentinel/ba-p/996229)

###

### Module 3: Cloud architecture and multi-worksapce/tenant support

An Azure Sentinel instance is called a workspace. Multiple workspaces are often necessary and can act together as a single Azure Sentinel system. The first half of the Webinar above discusses Azure Sentinel&#39;s workspace architecture.

###


- Webinar (includes Module 4): [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmggvs6o4EcxYTgvV6), [YouTube](https://youtu.be/_mm3GNwPBHU)
- [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmgjuszn8-jty5Gbx7) (includes Module 4)
- You may also want to register for the MSSP and distributed organization webinar on April 20th [here](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u).

**Learn more**

- Learn how to manage Azure Sentinel using CD/CI methodology and a GitHub repository in [Deploying and Managing Azure Sentinel as Code](https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928) as well as[ extend this capability across workspaces and tenants using Azure Lighthouse](https://techcommunity.microsoft.com/t5/azure-sentinel/combining-azure-lighthouse-with-sentinel-s-devops-capabilities/ba-p/1210966).
- Use [KQL queries in Azure Sentinel across workspaces](https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/cross-workspace-query) to combine multiple workspaces into a single system.
- Use[ resource RBAC](https://techcommunity.microsoft.com/t5/azure-sentinel/controlling-access-to-azure-sentinel-data-resource-rbac/ba-p/1301463) to enable multiple teams to use a single workspace.
- [Use Azure Lighthouse to extend multi-workspace capabilities across tenants.](https://techcommunity.microsoft.com/t5/azure-sentinel/using-azure-lighthouse-and-azure-sentinel-to-monitor-across/ba-p/1043899)

###

### Module 7: KQL

Most Azure Sentinel capabilities use [KQL](https://docs.microsoft.com/en-us/azure/kusto/query/) or Kusto Query Language. When you search in your logs, write rules, creating hunting queries or create workbooks, you use KQL.

The KQL Webinar is planned for June 2nd. Meanwhile, to learn KQL, use these resources:

- [Pluralsight KQL course](https://www.pluralsight.com/courses/kusto-query-language-kql-from-scratch)
- [KQL Cheat Sheet](https://www.mbsecure.nl/blog/2019/12/kql-cheat-sheet)

In addition to KQL, to applying it to Azure Sentinel requires understanding the [table schemas used by Azure Sentinel](https://github.com/Azure/Azure-Sentinel/wiki/DataSource-Schema-Reference).

### Module 8: Write rules

- Webinar: [MP4](https://1drv.ms/v/s%21AnEPjr8tHcNmghlWrlBCPKwT5WTT), [YouTube](https://youtu.be/pJjljBT4ipQ)
- [Presentation](https://1drv.ms/b/s%21AnEPjr8tHcNmghhrDiXV1NeTZCZI)

**Learn more**

- [Azure Sentinel correlation rules: Active Lists out; make\_list() in, the AAD/AWS correlation example](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-correlation-rules-active-lists-out-make-list-in/ba-p/1029225)
- [Azure Sentinel correlation rules: the join KQL operator](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-correlation-rules-the-join-kql-operator/ba-p/1041500)
- [Implementing Lookups in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/implementing-lookups-in-azure-sentinel-part-1-reference-files/ba-p/1091306)
- [Using KQL functions to speed up analysis in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/using-kql-functions-to-speed-up-analysis-in-azure-sentinel/ba-p/712381)

Writing rules also requires understanding the [table schemas used by Azure Sentinel](https://github.com/Azure/Azure-Sentinel/wiki/DataSource-Schema-Reference).

### Module 9: Creating playbooks

Start with the [presentation](https://techcommunity.microsoft.com/t5/forums/editpage/board-id/AzureSentinelBlog/message-id/243/is-draft/true?attachment-id=21925).

**Learn more:**

- Read about [Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview), which is the core technology driving Azure Sentinel playbooks.
- [The Azure Sentinel Logic App connector](https://docs.microsoft.com/en-us/connectors/azuresentinel/) is link between Logic Apps and Azure Sentinel

### Module 10: Developing workbooks

As we work to develop training materials for workbooks, start with the [workbooks documentation](https://docs.microsoft.com/en-us/azure/azure-monitor/app/usage-workbooks).

You might also want to refer to these workbook examples:

- [How to use Azure Monitor Workbooks to map Sentinel data](https://techcommunity.microsoft.com/t5/azure-sentinel/how-to-use-azure-monitor-workbooks-to-map-sentinel-data/ba-p/971818)

##


### Module 13: Hunting

Whatever is your methodology and use case for hunting, Azure Sentinel is a great hunting platform.

- [Hunting and Notebooks feature overview presentation](https://techcommunity.microsoft.com/gxcuf89792/attachments/gxcuf89792/AzureSentinelBlog/243/3/L400-P8%20Notebooks%20and%20hunting.pdf).
- Threat hunting webinar ([MP4](https://1drv.ms/v/s!AnEPjr8tHcNmgVrt_iN5W4gt0WlG?e=fGhiyZ), [YouTube](https://youtu.be/Tiz-ftnlTg4)) and presentations [(Deck 1](https://1drv.ms/b/s!AnEPjr8tHcNmgVlNSw5ouPxYkVS0?e=j5l1hI), [Deck 2](https://1drv.ms/b/s!AnEPjr8tHcNmgWLisWDg0ha36wMd?e=YJWjQ7))
- Threat hunting revisited ([MP4](https://1drv.ms/v/s!AnEPjr8tHcNmghQwthryNWI5Yfuh), [YouTube](https://youtu.be/BTEV_b6-vtg), [Presentation](https://1drv.ms/b/s!AnEPjr8tHcNmghNdbqppq1myNzG_))
- Threat Hunting - AWS using Sentinel, webinar on April 22nd, register [here](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u).

**Learn more**

- [Why Use Jupyter for Security Investigations?](https://techcommunity.microsoft.com/t5/azure-sentinel/why-use-jupyter-for-security-investigations/ba-p/475729)
- [​​​​​​​](https://techcommunity.microsoft.com/t5/azure-sentinel/why-use-jupyter-for-security-investigations/ba-p/475729)Security Investigation with Azure Sentinel and Jupyter Notebooks ([part 1](https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/432921), [part 2](https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/483466), [part 3](https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/561413))
- [msticpy - Python Defender Tools](https://techcommunity.microsoft.com/t5/azure-sentinel/msticpy-python-defender-tools/ba-p/648929)
- [What am I looking at? - Using Notebooks to gain situational awareness](https://techcommunity.microsoft.com/t5/azure-sentinel/what-am-i-looking-at-using-notebooks-to-gain-situational/ba-p/891818)
- [Explorer Notebook Series: The Linux Host Explorer](https://techcommunity.microsoft.com/t5/azure-sentinel/explorer-notebook-series-the-linux-host-explorer/ba-p/1138273)
- [Using Threat Intelligence in your Jupyter Notebooks](https://techcommunity.microsoft.com/t5/azure-sentinel/using-threat-intelligence-in-your-jupyter-notebooks/ba-p/860239)

|
 |
 |
 |
| --- | --- | --- |
