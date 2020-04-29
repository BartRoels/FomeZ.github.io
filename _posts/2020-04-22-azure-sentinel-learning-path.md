---


---

<hr>
<h2 id="layout-posttitle-azure-sentinel-learning-paths-for-beginners-advanced-and-expertsimage-imgazuresentinel.pngpublished-true">layout: post<br>
title: ‘Azure Sentinel Learning paths for Beginners, Advanced and Experts’<br>
image: /img/AzureSentinel.png<br>
published: true</h2>
<p>This overview is based on the <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/become-an-azure-sentinel-ninja-the-complete-level-400-training/ba-p/1246310">Blog post</a>{:target="_blank"} “Become an Azure Sentinel Ninja: The Complete Level 400 Training created by <a href="https://www.linkedin.com/in/oshezaf/">Ofer Shezaf</a>{:target=”_blank"}</p>
<p>As not everyone has the same maturity level when starting their Azure Sentinel Learning Path, I created, with the help of <a href="https://www.linkedin.com/in/sorianojavier/">Javier Soriano</a>{:target="_blank"}, a 3 level (Beginner/Advanced/Expert) approach to get to the level you want, often related to your role in the organisation.</p>
<p><a></a></p>
<h2 id="table-of-contents">Table of contents</h2>
<p><a href="#Beginner">Beginner (BDM, presales roles)</a></p>
<ul>
<li>
<p>The Basics</p>
</li>
<li>
<p>Technical overview</p>
</li>
<li>
<p>Azure Sentinel role</p>
</li>
</ul>
<p><a href="#Advanced">Advanced (Security Analyst)</a></p>
<ul>
<li>
<p>Technical overview</p>
</li>
<li>
<p>Cloud architecture and multi-workspace/tenant support</p>
</li>
<li>
<p>Handling incidents</p>
</li>
<li>
<p>Hunting</p>
</li>
</ul>
<p><a href="#Expert">Expert (SOC engineer)</a></p>
<ul>
<li>
<p>Technical overview</p>
</li>
<li>
<p>Cloud architecture and multi-workspace/tenant support</p>
</li>
<li>
<p>KQL</p>
</li>
<li>
<p>Write rules</p>
</li>
<li>
<p>Creating playbooks</p>
</li>
<li>
<p>Developing workbooks</p>
</li>
<li>
<p>Hunting</p>
</li>
</ul>
<p><a href="#AdvancedTopics">Advanced Topics</a></p>
<ul>
<li>
<p>Automating and integrating</p>
</li>
<li>
<p>Deploying and Managing Azure Sentinel as Code</p>
</li>
<li>
<p>Roadmap - since it requires an NDA, contact your Microsoft contact for details.</p>
</li>
<li>
<p>Where to go next?</p>
</li>
<li>
<p>Extra Resources</p>
</li>
</ul>
<p>--------------------- <a></a></p>
<h2 id="beginner-bdm-presales-roles">Beginner (BDM, presales roles)</h2>
<h3 id="the-basics">The Basics</h3>
<ul>
<li>(The real beginning!) <a href="https://docs.microsoft.com/en-us/learn/paths/azure-fundamentals/">Azure Fundamentals Learning Path</a>{:target="_blank"}</li>
<li><a href="https://docs.microsoft.com/en-us/azure/sentinel/overview">What is Azure Sentinel?</a>{:target="_blank"} - Introduction <a href="https://www.youtube.com/watch?v=dRpOR2GpL1s">Video 1</a>{:target="_blank"}, <a href="https://www.youtube.com/watch?v=XXZp6LQZSJU">Video 2</a>{:target="_blank"}</li>
<li><a href="https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard#global-prerequisites">Global prerequisites</a>{:target="_blank"} + <a href="https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace">create a Log Analytics workspace</a>{:target="_blank"}</li>
<li><a href="https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard#enable-azure-sentinel-">Enable Azure Sentinel</a>{:target="_blank"}</li>
<li><a href="https://docs.microsoft.com/en-us/azure/sentinel/connect-data-sources">Connect data sources</a>{:target="_blank"}</li>
<li>Improve security with Azure Sentinel, <a href="https://www.youtube.com/watch?v=oiWInLYvnUk">a cloud-native SIEM and SOAR solution</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="technical-overview-level-200">Technical overview (Level 200)</h3>
<p>If you want to get an initial overview of Azure Sentinel’s technical capabilities</p>
<ul>
<li>Webinar: <a href="https://youtu.be/7An7BB-CcQI">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s!AnEPjr8tHcNmggKaEEBPHduhVbre">Presentation</a>{:target="_blank"} (updated)</li>
</ul>
<p><strong>Learn more</strong></p>
<p>You can read more about the features described in the Webinar here:</p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-the-new-built-in-url-detonation-in-azure-sentinel/ba-p/996229">Using the new built-in URL detonation in Azure Sentinel</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="azure-sentinel-role-level-200">Azure Sentinel role (Level 200)</h3>
<p>What is the typical use case for Azure Sentinel? What are customers finding in it, and also, how is it priced? All in this <a href="https://techcommunity.microsoft.com/gxcuf89792/attachments/gxcuf89792/AzureSentinelBlog/243/1/L400-P2%20Use%20cases.pdf">presentation</a>{:target="_blank"}</p>
<p><strong>Learn more</strong> :</p>
<ul>
<li><a href="https://azure.microsoft.com/en-us/pricing/calculator/?service=azure-sentinel">Azure Sentinel pricing calculator</a>{:target="_blank"}</li>
<li><a href="https://azure.microsoft.com/en-us/pricing/details/azure-sentinel/">Azure Sentinel</a> and <a href="https://azure.microsoft.com/en-us/pricing/details/monitor/">Log Analytics</a>{:target="_blank"} pricing pages</li>
</ul>
<p>--------------------- <a></a></p>
<p><a href="#TopOfPage">BackToTop</a></p>
<h2 id="advanced-security-analyst-a-nameadvanceda">Advanced (Security Analyst) <a></a></h2>
<h3 id="technical-overview-level-200-1">Technical overview (Level 200)</h3>
<p>If you want to get an initial overview of Azure Sentinel’s technical capabilities</p>
<ul>
<li>Webinar: <a href="https://youtu.be/7An7BB-CcQI">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s!AnEPjr8tHcNmggKaEEBPHduhVbre">Presentation</a>{:target="_blank"} (updated)</li>
</ul>
<p><strong>Learn more</strong></p>
<p>You can read more about the features described in the Webinar here:</p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-the-new-built-in-url-detonation-in-azure-sentinel/ba-p/996229">Using the new built-in URL detonation in Azure Sentinel</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="cloud-architecture-and-multi-workspacetenant-support">Cloud architecture and multi-workspace/tenant support</h3>
<p>An Azure Sentinel instance is called a workspace. Multiple workspaces are often necessary and can act together as a single Azure Sentinel system. The first half of the Webinar above discusses Azure Sentinel’s workspace architecture.</p>
<ul>
<li>Webinar: <a href="https://youtu.be/_mm3GNwPBHU">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgjuszn8-jty5Gbx7">Presentation</a>{:target="_blank"}</li>
<li>You may also want to register for the MSSP and distributed organization webinar on April 20th <a href="https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u">here</a>{:target="_blank"}</li>
</ul>
<p><strong>Learn more</strong></p>
<ul>
<li>Learn how to manage Azure Sentinel using CD/CI methodology and a GitHub repository in <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928">Deploying and Managing Azure Sentinel as Code</a>{:target="_blank"} as well as<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/combining-azure-lighthouse-with-sentinel-s-devops-capabilities/ba-p/1210966"> extend this capability across workspaces and tenants using Azure Lighthouse</a>{:target="_blank"}</li>
<li>Use <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/cross-workspace-query">KQL queries in Azure Sentinel across workspaces</a>{:target="_blank"} to combine multiple workspaces into a single system</li>
<li>Use<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/controlling-access-to-azure-sentinel-data-resource-rbac/ba-p/1301463"> resource RBAC</a>{:target="_blank"} to enable multiple teams to use a single workspace</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-azure-lighthouse-and-azure-sentinel-to-monitor-across/ba-p/1043899">Use Azure Lighthouse to extend multi-workspace capabilities across tenants.</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="handling-incidents">Handling incidents</h3>
<p>After building your SOC, you need to start using it. Watch the day in a SOC analyst life to learn how to use Azure Sentinel in the SOC:</p>
<ul>
<li>Webinar: <a href="https://youtu.be/HloK6Ay4h1M">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s%21AnEPjr8tHcNmghALzkfTkg-dTmfH">Presentation</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="hunting">Hunting</h3>
<p>Whatever is your methodology and use case for hunting, Azure Sentinel is a great hunting platform.</p>
<ul>
<li><a href="https://techcommunity.microsoft.com/gxcuf89792/attachments/gxcuf89792/AzureSentinelBlog/243/3/L400-P8%20Notebooks%20and%20hunting.pdf">Hunting and Notebooks feature overview presentation</a>{:target="_blank"}</li>
<li>Threat hunting webinar (<a href="https://youtu.be/Tiz-ftnlTg4">Video</a>{:target="_blank"}) and presentations <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgVlNSw5ouPxYkVS0?e=j5l1hI">(Presentation 1</a>{:target="_blank"}, <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgWLisWDg0ha36wMd?e=YJWjQ7">Presentation 2</a>{:target="_blank"})</li>
<li>Threat hunting revisited (<a href="https://youtu.be/BTEV_b6-vtg">Video</a>{:target="_blank"}, <a href="https://1drv.ms/b/s!AnEPjr8tHcNmghNdbqppq1myNzG_">Presentation</a>{:target="_blank"})</li>
<li>Threat Hunting - AWS using Sentinel, webinar on April 22nd, register <a href="https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u">here</a>{:target="_blank"}</li>
</ul>
<p><strong>Learn more</strong></p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/why-use-jupyter-for-security-investigations/ba-p/475729">Why Use Jupyter for Security Investigations?</a>{:target="_blank"}</li>
<li>Security Investigation with Azure Sentinel and Jupyter Notebooks (<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/432921">part 1</a>{:target="_blank"}, <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/483466">part 2</a>{:target="_blank"}, <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/561413">part 3</a>{:target="_blank"})</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/msticpy-python-defender-tools/ba-p/648929">msticpy - Python Defender Tools</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/what-am-i-looking-at-using-notebooks-to-gain-situational/ba-p/891818">What am I looking at? - Using Notebooks to gain situational awareness</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/explorer-notebook-series-the-linux-host-explorer/ba-p/1138273">Explorer Notebook Series: The Linux Host Explorer</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-threat-intelligence-in-your-jupyter-notebooks/ba-p/860239">Using Threat Intelligence in your Jupyter Notebooks</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<p>--------------------- <a></a></p>
<h2 id="expert-soc-engineer">Expert (SOC engineer)</h2>
<h3 id="technical-overview-level-200-2">Technical overview (Level 200)</h3>
<p>If you want to get an initial overview of Azure Sentinel’s technical capabilities</p>
<ul>
<li>Webinar: <a href="https://youtu.be/7An7BB-CcQI">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s!AnEPjr8tHcNmggKaEEBPHduhVbre">Presentation</a>{:target="_blank"} (updated)</li>
</ul>
<p><strong>Learn more</strong></p>
<p>You can read more about the features described in the Webinar here:</p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-the-new-built-in-url-detonation-in-azure-sentinel/ba-p/996229">Using the new built-in URL detonation in Azure Sentinel</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="cloud-architecture-and-multi-workspacetenant-support-1">Cloud architecture and multi-workspace/tenant support</h3>
<p>An Azure Sentinel instance is called a workspace. Multiple workspaces are often necessary and can act together as a single Azure Sentinel system. The first half of the Webinar above discusses Azure Sentinel’s workspace architecture.</p>
<ul>
<li>Webinar: <a href="https://youtu.be/_mm3GNwPBHU">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgjuszn8-jty5Gbx7">Presentation</a>{:target="_blank"}</li>
<li>You may also want to register for the MSSP and distributed organization webinar on April 20th <a href="https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u">here</a>{:target="_blank"}</li>
</ul>
<p><strong>Learn more</strong></p>
<ul>
<li>Learn how to manage Azure Sentinel using CD/CI methodology and a GitHub repository in <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928">Deploying and Managing Azure Sentinel as Code</a>{:target="_blank"} as well as<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/combining-azure-lighthouse-with-sentinel-s-devops-capabilities/ba-p/1210966"> extend this capability across workspaces and tenants using Azure Lighthouse</a>{:target="_blank"}</li>
<li>Use <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/cross-workspace-query">KQL queries in Azure Sentinel across workspaces</a>{:target="_blank"} to combine multiple workspaces into a single system</li>
<li>Use<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/controlling-access-to-azure-sentinel-data-resource-rbac/ba-p/1301463"> resource RBAC</a>{:target="_blank"} to enable multiple teams to use a single workspace</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-azure-lighthouse-and-azure-sentinel-to-monitor-across/ba-p/1043899">Use Azure Lighthouse to extend multi-workspace capabilities across tenants.</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="kql">KQL</h3>
<p>Most Azure Sentinel capabilities use <a href="https://docs.microsoft.com/en-us/azure/kusto/query/">KQL</a>{:target="_blank"} or Kusto Query Language. When you search in your logs, write rules, creating hunting queries or create workbooks, you use KQL.</p>
<p>The KQL Webinar is planned for June 2nd. Meanwhile, to learn KQL, use these resources:</p>
<ul>
<li><a href="https://www.pluralsight.com/courses/kusto-query-language-kql-from-scratch">Pluralsight KQL course</a>{:target="_blank"}</li>
<li><a href="https://www.mbsecure.nl/blog/2019/12/kql-cheat-sheet">KQL Cheat Sheet</a>{:target="_blank"}</li>
</ul>
<p>In addition to KQL, to applying it to Azure Sentinel requires understanding the <a href="https://github.com/Azure/Azure-Sentinel/wiki/DataSource-Schema-Reference">table schemas used by Azure Sentinel</a>{:target="_blank"}</p>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="write-rules">Write rules</h3>
<ul>
<li>Webinar: <a href="https://youtu.be/pJjljBT4ipQ">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s%21AnEPjr8tHcNmghhrDiXV1NeTZCZI">Presentation</a>{:target="_blank"}</li>
</ul>
<p><strong>Learn more</strong></p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-correlation-rules-active-lists-out-make-list-in/ba-p/1029225">Azure Sentinel correlation rules: Active Lists out; make_list() in, the AAD/AWS correlation example</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-correlation-rules-the-join-kql-operator/ba-p/1041500">Azure Sentinel correlation rules: the join KQL operator</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/implementing-lookups-in-azure-sentinel-part-1-reference-files/ba-p/1091306">Implementing Lookups in Azure Sentinel</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-kql-functions-to-speed-up-analysis-in-azure-sentinel/ba-p/712381">Using KQL functions to speed up analysis in Azure Sentinel</a>{:target="_blank"}</li>
</ul>
<p>Writing rules also requires understanding the <a href="https://github.com/Azure/Azure-Sentinel/wiki/DataSource-Schema-Reference">table schemas used by Azure Sentinel</a>{:target="_blank"}</p>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="creating-playbooks">Creating playbooks</h3>
<p>Start with the <a href="https://techcommunity.microsoft.com/t5/forums/editpage/board-id/AzureSentinelBlog/message-id/243/is-draft/true?attachment-id=21925">presentation</a>{:target="_blank"}</p>
<p><strong>Learn more:</strong></p>
<ul>
<li>Read about <a href="https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview">Logic Apps</a>{:target="_blank"}, which is the core technology driving Azure Sentinel playbooks.</li>
<li><a href="https://docs.microsoft.com/en-us/connectors/azuresentinel/">The Azure Sentinel Logic App connector</a>{:target="_blank"} is link between Logic Apps and Azure Sentinel</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="developing-workbooks">Developing workbooks</h3>
<p>As we work to develop training materials for workbooks, start with the <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/app/usage-workbooks">workbooks documentation</a>{:target="_blank"}</p>
<p>You might also want to refer to these workbook examples:</p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/how-to-use-azure-monitor-workbooks-to-map-sentinel-data/ba-p/971818">How to use Azure Monitor Workbooks to map Sentinel data</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="hunting-1">Hunting</h3>
<p>Whatever is your methodology and use case for hunting, Azure Sentinel is a great hunting platform.</p>
<ul>
<li><a href="https://techcommunity.microsoft.com/gxcuf89792/attachments/gxcuf89792/AzureSentinelBlog/243/3/L400-P8%20Notebooks%20and%20hunting.pdf">Hunting and Notebooks feature overview presentation</a>{:target="_blank"}</li>
<li>Threat hunting webinar (<a href="https://youtu.be/Tiz-ftnlTg4">Video</a>{:target="_blank"}) and presentations <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgVlNSw5ouPxYkVS0?e=j5l1hI">(Presentation 1</a>{:target="_blank"}, <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgWLisWDg0ha36wMd?e=YJWjQ7">Presentation 2</a>{:target="_blank"})</li>
<li>Threat hunting revisited (<a href="https://youtu.be/BTEV_b6-vtg">Video</a>{:target="_blank"}, <a href="https://1drv.ms/b/s!AnEPjr8tHcNmghNdbqppq1myNzG_">Presentation</a>{:target="_blank"})</li>
<li>Threat Hunting - AWS using Sentinel, webinar on April 22nd, register <a href="https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR_0A4IaJRDNBnp8pjCkWnwhUNlI1UjZJTzlCM0Q2M1dNMk1NQjJSTFM4OC4u">here</a>{:target="_blank"}</li>
</ul>
<p><strong>Learn more</strong></p>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/why-use-jupyter-for-security-investigations/ba-p/475729">Why Use Jupyter for Security Investigations?</a>{:target="_blank"}</li>
<li>Security Investigation with Azure Sentinel and Jupyter Notebooks (<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/432921">part 1</a>{:target="_blank"}, <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/483466">part 2</a>{:target="_blank"}, <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/security-investigation-with-azure-sentinel-and-jupyter-notebooks/ba-p/561413">part 3</a>{:target="_blank"})</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/msticpy-python-defender-tools/ba-p/648929">msticpy - Python Defender Tools</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/what-am-i-looking-at-using-notebooks-to-gain-situational/ba-p/891818">What am I looking at? - Using Notebooks to gain situational awareness</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/explorer-notebook-series-the-linux-host-explorer/ba-p/1138273">Explorer Notebook Series: The Linux Host Explorer</a>{:target="_blank"}</li>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/using-threat-intelligence-in-your-jupyter-notebooks/ba-p/860239">Using Threat Intelligence in your Jupyter Notebooks</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<p>--------------------- <a></a></p>
<h2 id="advanced-topics">Advanced Topics</h2>
<h3 id="extending-and-integrating-azure-sentinel">Extending and integrating Azure Sentinel</h3>
<ul>
<li>Webinar: <a href="https://youtu.be/Cu4dc88GH1k">Video</a>{:target="_blank"}</li>
<li>Webinar: <a href="https://1drv.ms/b/s!AnEPjr8tHcNmgjRd01jxCSmbydt0">Presentation</a>{:target="_blank"}</li>
<li>Blog post: <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/extending-azure-sentinel-apis-integration-and-management/ba-p/1116885">Extending Azure Sentinel</a>{:target="_blank"}: APIs, Integration and management automation</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="deploying-and-managing-azure-sentinel-as-code">Deploying and Managing Azure Sentinel as Code</h3>
<ul>
<li><a href="https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928">Blog</a>{:target="_blank"} by <a href="https://www.linkedin.com/in/sorianojavier/">Javier Soriano</a>{:target="_blank"} and <a href="https://www.linkedin.com/in/philippe-zenhaeusern/">Philippe Zenhaeusern</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="roadmap">Roadmap</h3>
<p>Since roadmap information is provided under NDA, please reach out to your Microsoft account team to discuss an Azure Sentinel roadmap presentation.</p>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="where-do-i-go-from-here">Where do I go from here?</h3>
<ul>
<li>Join our <a href="https://aka.ms/SecurityPrP">Private Previews</a>{:target="_blank"} program</li>
<li>Ask, or answer other on the <a href="https://techcommunity.microsoft.com/t5/Azure-Sentinel/bd-p/AzureSentinel">Azure Sentinel Tech Community</a>{:target="_blank"}</li>
<li>Submit feature requests using <a href="https://feedback.azure.com/forums/920458-azure-sentinel">User voice</a>{:target="_blank"}</li>
<li>Contribute or enhance rules, queries, workbooks, connectors and more to the community on the <a href="https://github.com/Azure/Azure-Sentinel/wiki">Azure Sentinel GitHub</a>{:target="_blank"}</li>
<li>As a last resort, send an e-mail to <a href="AzureSentinel@microsoft.com">AzureSentinel@microsoft.com</a>{:target="_blank"}</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>
<h3 id="extra-resources">Extra Resources</h3>
<ul>
<li>Build an Azure Sentinel Lab with prerecorded Data &amp; a Custom Logs Pipe via ARM Templates (<a href="https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-to-go-part1-a-lab-w-prerecorded-data-amp-a-custom/ba-p/1260191">Blog</a>{:target="_blank"})</li>
<li>Azure Sentinel’s Resources in one place! <a href="https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-resource-terminus-board-here/ba-p/1269252?_lrsc=7eb54028-6f6b-449d-8d31-f83f6a8f9cf2">Blog</a>{:target="_blank"}</li>
<li>Learn Azure Sentinel (<a href="https://www.packtpub.com/eu/security/learn-azure-sentinel">eBook/Print</a>{:target="_blank"})</li>
<li>Azure Sentinel Planning (<a href="https://www.microsoftpressstore.com/store/microsoft-azure-sentinel-planning-and-implementing-9780136485452">ebook/Print</a>{:target="_blank"})</li>
<li>Implementing and Administering Azure Sentinel (<a href="https://www.lynda.com/Azure-tutorials/Implementing-Administering-Azure-Sentinel/2813287-2.html">Lynda.com</a>{:target="_blank"})</li>
<li>Step-by-Step Guide to Deploy Azure Sentinel (<a href="https://www.infusedinnovations.com/blog/intelligent-cloud/step-by-step-guide-to-deploy-azure-sentinel">Blog</a>{:target="_blank"})</li>
</ul>
<p><a href="#TopOfPage">BackToTop</a></p>

