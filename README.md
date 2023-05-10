# Analyzing the network structure of public procurement in Germany: Implications for corruption risk using single bidder rates

```
network-analysis-EU-procurements/
├───data                    
│   ├───processed                     - processed data
│   └───raw                           - `contracts` and `aggregated_country_year` datasets
├───notebooks                         - Jupyter notebooks
├───output
│   ├───figures                       - plots and charts
│   └───tables                        - tables of descriptive statistics
├───reference                         - reference paper
├─.gitignore                          - .gitignore files
├─environment.yml                     - create environment
├─README.md
├─Arbo_MaAdelleGia_Assignment2.pdf    - final paper submission for Assignment 2 
└─Arbo_MaAdelleGia_Assignment3.pptx   - final presentation for Assignment 3
```

## Background and motivation
Public procurement contracts are an essential part of the public sector. They are a critical instrument for governments to acquire goods and services are essential for ensuring public services are delivered effectively. However, these contracts can be susceptible to corruption, fraud, and other forms of misconduct, which can result in significant financial losses for the government and undermine public trust.

In recent years, there has been a growing interest in understanding and preventing corruption in public procurement (see Wachs et al., 2021). The availability of administrative datasets from European Union member states has enabled researchers to analyze large volumes of data and identify patterns and trends related to corruption risk.

This paper focuses on the use of a competitive measure called single bidding rate as a proxy of corruption risk. Single bidding rate is quantified as the rate at which a contract attracted only a single bidder. While this measure is used as an effective proxy for corruption, it is essential to note that the presence of single bidding does not necessarily indicate corruption, as there may be valid reasons why only one bidder participated in a tender.

The results of this paper have many implications. For instance, under the competition lens, new approaches using the network data can be developed and utilized for detecting signals of bid-rigging activities to aid the enforcement arm of antitrust authorities.

## Research objectives
This paper builds on the study of [Wachs et al. (2021)](https://link.springer.com/article/10.1007/s41060-019-00204-1), which analyzed the relationship between the degree of centralization of a market and its corruption risk, and investigate whether centralization induces corruption. The goal of this paper is to primarily visualize and describe the network of public procurement contracts in Germany from 2008 to 2016. Specifically, it focuses on understanding the structure of the German market in relation to corruption risk across years. 

To achieve these objectives, data science tools are applied to conduct network-based approaches such as R-A clustering, degree distributions, k-core decomposition, modularity maximization, and measurement of nodal centrality.


## Data
For this paper, a bipartite network of public procurement contracts awarded by the European Union from 2008 to 2016 was utilized. The data was collected from Tenders Electronic Daily (TED) and is available on [Netzschleuder](https://networks.skewed.de/net/eu_procurements). The dataset has been further processed by Wachs et al. (2021) to include country estimates of corruption risk. The current analysis used the same two datasets: contract-level tidy data (`contracts`) and aggregated country-year corruption indicators data (`aggregated_country_year`). Both datasets along with their data dictionary are available [here](https://zenodo.org/record/3537986#.Xis4mC2ZNGV).

To replicate this study, please save the `contracts` and `aggregated_country_year` .csv datasets in `./data/raw`.

## Author

Ma. Adelle Gia Arbo ([GitHub](https://github.com/adellegia), [LinkedIn](https://www.linkedin.com/in/ma-adelle-gia-arbo/))

## License

The material in this repository is made available under the [MIT license](http://opensource.org/licenses/mit-license.php). 
