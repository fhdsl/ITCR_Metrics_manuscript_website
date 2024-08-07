### **Overview**

This website is dedicated to the presentation of analyses pertaining to the manuscript "Best practices to evaluate the impact of biomedical research software-metric collection beyond citations" published by Bioinformatics (https://pubmed.ncbi.nlm.nih.gov/39067017/), which was previously titled "Impact of Software Desiged for Biomedical Research: are we measuring what's important?" as a preprint (https://arxiv.org/abs/2306.03255). The analyses are based on the software evaluation practices and infrastructure used by developers in the Informatics Technology for Cancer Research (ITCR) program.

To better understand how developers approach software evaluation and the infrastructure typically used to support this process, our research team conducted two analyses. 

  - In order to learn more about their attitudes and behaviors regarding software development, maintenance, and outreach, we first polled 48 ITCR participants. The survey asked a variety of questions. The results of this survey are described (along with the R-code) in the **Survey Results** page.

  - Furthermore, we manually reviewed 44 different tools, including those supported by the Cancer Target Discovery and Development (CTD$^2$) Network and the ITCR program, and looked into different aspects of these tools. For this, we queried the SoftwareKG-PMC-Analysis database using R and developed a query function that returns all articles in a specific mention category that mention a specific keyword (in this case, the name of the software) (allusion, usage, or deposition). A total of 60,970 unique articles for 36 ITCR tool name keywords were produced as a result of this process, producing 73,095 article-level mentions of any type. However, eight tools were missing, possibly as a result of the tools' recent release, the complexity of the tool name, or inaccuracies or gaps in SoftwareKG and/or PubMed Central. The results of this analysis are described (along with the R-code) in the **Tool Infrastructure and Citation Analysis** page.
  
  
All results are presented on our website in an understandable and instructive way. We hope that our study makes a significant contribution to the study of software evaluation and development. For any questions and concerns please refer to contact information given in the **Contact** page.

#### Data Statement

- All analysis codes and data are publicly accessible in the **[github repository](https://github.com/fhdsl/ITCR_Metrics_manuscript_website)**.

- Due to the conditions of the IRB approval, the **survey data set** was kept private and was not made available to the public.
