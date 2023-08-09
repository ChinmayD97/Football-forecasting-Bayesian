# Football-Bayesian
### Replication code for the article ''Real-time forecasting within soccer matches through a Bayesian lens"

The data used is publicly available on Kaggle (link: https://www.kaggle.com/datasets/hugomathien/soccer). We first extract the required data from the sqlite file on Kaggle using : extract_data_sqlite.R .
Further preprocessing is done on the data to get it into a usable format, with the output file to be used for implementing the models being: Finaldata4c_complete.csv .
The proposed model is provided in Model_code.Rmd. 
The comparative approaches used are provided in the codes Comparator I.Rmd , Comparator II.Rmd and Comparator III.Rmd, with the outputs being Comparator1.Rdata and Comparator3d.Rdata.
