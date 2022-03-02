# pandas-API-analysis

This repo contains the code and analysis used in [this blogpost](https://ponder.io/blog/pandas-api-analysis).

### Running data processing pipeline from raw corpus
If you are interested in running our complete analysis end-to-end, starting with the raw 1M+ notebook dataset, the dataset can be downloaded from the [UCSD Library Digital Collections](https://library.ucsd.edu/dc/collection/bb6931851t). Then you can follow the instructions at the top of `notebook/1-raw-notebook-processing.ipynb` to clean the data, or download the cleaned data via [Google Drive](https://drive.google.com/file/d/12M3n_gsejc1xmrFoAGwHUgFTpHIlfa2i/view?usp=sharing) and run the processing yourself. Note that the processing pipeline takes around 20 minutes to run.

### Running only the analysis notebook
If you are only interested in the analysis portion, we have distilled the dataset down to a smaller dataset that contains the count of pandas API usage across each notebook. This smaller dataset (`filtered_token_breakdown.csv`) can be downloaded at [this link](https://drive.google.com/file/d/1rw9txpiBs4Jgq_L4TWRA4br4U7VRZg1I/view?usp=sharing). Once you have downloaded the dataset, you can place it in the `data/` folder and follow the analysis in `notebook/2-pandas-usage-analysis.ipynb`.

### Questions?
If you have any questions or feedback on our blog post or analysis, please send us an email at [contact@ponder.io](mailto:contact@ponder.io).
