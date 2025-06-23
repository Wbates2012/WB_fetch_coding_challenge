# Coding Exercise

Thank you for reading my submission for the Analytics Engineer Coding Exercise.

## First: Review Existing Unstructured Data and Diagram a New Structured Relational Data Model
You can find my ER diagram [here](https://github.com/Wbates2012/WB_fetch_coding_challenge/blob/main/ER_diagram.png). I used the website draw.io to build it.

## Second: Write Queries that Directly Answer Predetermined Questions from a Business Stakeholder
I wrote the SQLite queries after cleaning the data and building the database so that it would be more efficient and robust. You can find the queries at the end of [this notebook](https://github.com/Wbates2012/WB_fetch_coding_challenge/blob/main/fetch%20coding%20test.ipynb).

## Third: Evaluate Data Quality Issues in the Data Provided
I evaluated data quality issues in the same notebook, found [here](https://github.com/Wbates2012/WB_fetch_coding_challenge/blob/main/fetch%20coding%20test.ipynb). I used Python for this part of the exercise.

## Fouth: Communicate with Stakeholders
Below is a sample email to a product or business leader regarding the data quality and structure.

Good afternoon,
I have a few questions about the data I received. 
1. In the receipts dataset, there are some inconsistencies with the quantityPurchased and totalSpent columns and the items on the receipt. Where do these fields come from, and is there a reason to use them over just adding up the items on the receipt?
2. In the brands dataset, some barcodes correspond to multiple brand IDs. Should that be allowed or is a data quality issue? Regardless, I would like more information on the origin of the brands data so I can better understand what each field represents and what information it should hold.
3. In the users dataset, there were many rows that contained duplicate data. For performance and scaling reasons, in addition to database practices, I would like to find a way to address this issue. That could mean automatically removing duplicate entries, or, if there is a reason for them to be there, adding another distinguishing column to reflect those differences.
I appreciate you taking the time to respond to these concerns.
Best,
Will Bates
