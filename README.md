# Analyzing the Network Structure of Public Procurement in Germany: Implications for Corruption Risk and Single Bidder Rates

```
network-analysis-EU-procurements/
├───data                    
│   ├───processed           - processed data
│   └───raw                 - `contracts` and `aggregated_country_year` datasets
├───notebooks               - Jupyter notebooks
├───output
│   ├───figures             - plots and charts
│   └───tables              - tables of descriptive statistics
├───reference               - reference paper
├─.gitignore               - .gitignore files
├─environment.yml          - install environment
├─README.md
└─Analyzing the Network Structure of Public Procurement in Germany_Arbo_MaAdelleGia.pdf 
```

## Motivation
Public procurement contracts are an essential part of the public sector. They are a critical instrument for governments to acquire goods and services are essential for ensuring public services are delivered effectively. However, these contracts can be susceptible to corruption, fraud, and other forms of misconduct, which can result in significant financial losses for the government and undermine public trust.

In recent years, there has been a growing interest in understanding and preventing corruption in public procurement (see Wachs et al., 2021). The availability of administrative datasets from European Union member states has enabled researchers to analyze large volumes of data and identify patterns and trends related to corruption risk.

This paper focuses on the use of a competitive measure called single bidding rate as a proxy of corruption risk. Single bidding rate is quantified as the rate at which a contract attracted only a single bidder. While this measure is used as an effective proxy for corruption, it is essential to note that the presence of single bidding does not necessarily indicate corruption, as there may be valid reasons why only one bidder participated in a tender.

The results of this paper have many implications. For instance, under the competition lens, new approaches using the network data can be developed and utilized for detecting signals of bid-rigging activities to aid the enforcement arm of antitrust authorities.

## Research objectives
This paper builds on the paper of Wachs et al. (2021), which aims to understand the relationship between the degree of centralization of a market and its corruption risk, and investigate whether centralization induces corruption by fostering corruption among core issuers and winners. The goal is to primarily visualize and describe the network of public procurement contracts in Germany from 2008 to 2016. Specifically, it focuses on understanding the structure of German procurement market in relation to corruption risk across years using a network approach. 

To achieve these objectives, data science tools are applied to conduct analysis methods including k-core decomposition and community detection, and measure centrality of the network.
