# alzanalyz
## Predictive models and Feature analysis for ALZ-SRI-HC-SUM21

### About Research
- Multidisciplinary Research Group of undergraduate and postgraduate students 
- Biochemistry and Data Science teams focused on the inhibition of Amyloid Beta 1-42 aggregation through computational, in vitro and in vivo analysis
- 10 week Research term aiding Dr. Paul Martino's ongoing Alzheimer's Research for drug repurposing 
- Multi-level screening of small molecule drug candidates to increase efficiency, success and cost effectiveness

### Data Science Workflow 
Literature reviews, database screening and domain knowledge was necessary to complete before writing code and doing analysis. A exhaustive list of small molecules ( x < 500 MW) was compilied and then run through Autodock Vina 1.2 documentation software against Amyloid Beta 1-42 peptides. This provided affinity scores for the strongest binding between ligand and protein receptors. The top scoring candidates from the batch runs were then put through sequential runs to get an overall top score. These molecules were then passed along to be tested through lab experimentation. 

Although this methodology was useful, the Data Science team expanded the search for small molecules and contributing factors to Alzheimer's disease by conducting and exploratory and predictive analysis. Several proposals were sent out and ultimately led to the use of ADNI data from LONI (http://adni.loni.usc.edu/about/). Two workflows are being conducted, an exploratory longitudinal study and a exploratory instance analysis. These differ by looking at survival rates over the entire ADNI study cohorts (1, Go, 2 and 3) and top performing features that contribute to a diagnosis of AD. 

About Code 
This code is for the instance analysis of AD. Multiple multiclass predictive models are used (Logistic regression, random forest, SVM, DTs to name a few). Additionally, feature selection, importance and extraction are all done through a variety of models including RFE, RF and ETC. The code is run from a singular jupyter notebook, but I may break them up by models in the future. 

Results 
