# 4mCBERT  
Background:N4-methylcytosine (4mC) is one of the important DNA chemical modification patterns, formed by transferring the exocyclic NH2 groups to the 4-th position of the pyrimidine ring in cytosine catalyzed by methyltransferases, which is a new methylation modification discovered recent year and plays vital roles to regulate gene expression, defend against invading genetic elements, genomic imprinting, cell differentiation and so on. Identifying 4mC site from DNA sequence segment can contribute to discovering more novel modification patterns.  
Results: In this paper, we propose a model called 4mCBERT by integrating sequence features (EIIP, Binary, NCP, Word2vec) and chemical information (PCP, CBERT) to encode a DNA sequence segment and utilizes CatBoost to construct a prediction model. The PCP and CBERT features are firstly constructed and applied to predict 4mC site and show positive contribution to identifying 4mC. The comparison results show that 4mCBERT achieves significant improvements on several benchmark datasets. The Matthew’s Correlation Coefficient (MCC) of 4mCBERT substantially outperformed the other models on A. thaliana, C. elegans, D. melanogaster, E. coli, G. Pickering and G. subterraneous independent benchmark datasets by 4.32% to 24.39%, 2.52% to 31.65%, 2% to 16.49%, 6.63% to 35.15, 8.59% to 61.85% and 10.68% to 34.45%, respectively. Moreover, we provide 4mCBERT software with graphical user interface to predict 4mC sites and retrain 4mC prediction models for other species.  
Conclusions: Based on the comparison results, 4mCBERT shows higher performance on multiple benchmark datasets by incorporating sequence and chemical information features. Besides, a user-friendly graphical user interface software is developed for academics at http://cczubio.top/4mCBERT. 

