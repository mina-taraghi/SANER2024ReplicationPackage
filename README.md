# Replication Package for Submission to SANER 2024
## Deep Learning Model Reuse in the HuggingFace Community: Challenges, Benefit and Trends" ##
---
The directory *Replication Package* is structured as follows:
## Mined Data
Contains the processed dataframes in CSV format.
### Discussion Forums
1. **Forums_Posts_Processed_DataFrame.csv**: (RQ3) Contains the details for each post per row for a total of 34,019 rows of data.
2. **Forums_Topics_Corpus.csv**:			 (RQ3) Contains the whole text of each topic per row. The text is a concatenation of the texts of all the posts in each topic for 11,175 topics in the data.
3. **Forums_Model_mentions_Over_Time.csv**:  (RQ3) Contains the number of topics containing the mention of each model, per month, based on the creation date of each topic for 147 models and 35 months (The last column/month was not counted due to not having the data for the whole month). The data for 50 models with names that could have other meaning has been manually verified.

### Model Hub:
1. **Hub_models_last_modified_modelId.csv**: (RQ3) Contains the details (last modified date, model type, model ID) for each model per row for a total of 239,422 rows of data.
2. **Hub_models_cardData_dates_created_at.csv**:		 (RQ3) Contains the information about each model per row (model ID, existence of card data, last modified date and month, owner and model name, and creation month) for 239,422 models.
3. **Hub_Model_Types_Over_Time_Created.csv**:  (RQ3) Contains the number of models with a certain base model, per month, based on the last modified date of each model for 171 models and 38 months (The last column/month was not counted due to not having the data for the whole month).
4. **card_data_stats_months_created.csv**: (RQ3) Contains the number of models created, the number of models created that have a card, and the ratio of models created with cards to the whole number of models created per month in each row for 42 rows.
---
## Codebooks:
1. Contains codebooks for codes for "Challenges" (RQ1), and "Benefits" (RQ2). Each codebook contains the code name, the definition and an example.
---
## Coded Data:
Contains the coded data for the topics in discussion forums  and for the root cause analysis (RQ1). 
1. **All_Codes.csv**: (RQ1 and RQ2) The topic Number, the tag (category on the forums) and the code are specified per row for 1,189 unique rows.
2. **Root_Causes.csv**: (RQ1) The information about accepted answers (Topic number, Catgeort of Topic on Discourse, category and subcategory of answer question in our codes, the code for the question and answer, and the code for root cause) per row for 72 rows.
---
## Affinity Diagram:

1. Contains a text file containing the link to the affinity diagrams for challenges, benefits and root causes (RQ1 and RQ2) on Miro. 
2. A picture of the high-level structure of the affinity diagrams is also included.
---
## Charts:
Contains: 
1. sunburst diagrams showing the categories and subcategories for challenges, benefits and root causes (RQ1 and RQ2), 
2. Some line charts for trends for RQ3. 
3. The dicrectory others also contains some extra bar charts that are self-explanatory.
---
A file containing two extra examples related to section III-C-3, showing examples of questions that could have been asked in a more precise category but has been asked in the beginner category.
