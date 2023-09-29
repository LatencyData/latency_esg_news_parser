# Automatic processing and consolidation of ESG information based on open web sources

This system has been developed in the framework of the 3rd call of the NGI project (See details here)[https://ngi-search-3rd-open-call.fundingbox.com/]

The system is a structured information retrieval algorithm that takes as input news articles, extracts the information they contain in an structured manner and consolidates the information into a dataset of company based information. The use case of this project is Environmental, Sustainability and Governance information of such companies.

## System inputs

The system takes as input a corpus of news articles provided by the user, formats them, determines whether they talk about ESG indicators of private companies and extract such information from them. Once extracted, the system consolidates all the ESG information for each company into a single output file.

### Some news sources
* [EU Startups](https://www.eu-startups.com/)
* [Hacker NEws](https://news.ycombinator.com/news)
* [Inside VC](https://inside.com/vc)
* [Silicon Canals](https://siliconcanals.com/)
* [Silicon News](https://www.silicon.news/)
* [Tech EU](https://tech.eu/)
* [Venture Beat](https://venturebeat.com/)


## System outputs

The output is a tabular file that contains as columns Standard ESG indicators about companies and a row for each company.
