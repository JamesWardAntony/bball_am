# GENERAL INFORMATION

1. Title of Dataset: Long-term, multi-event surprise enhances autobiographical memory

2. Author Information
	A. Principal Investigator Contact Information
		Name: James Antony / Kelly Bennion 
		Institution: California Polytechnic State University
		Email: james.ward.antony@gmail.com

3. Date(s) of data collection: 2/10/2021 - 11/17/2021

4. Geographic location of data collection: San Luis Obispo, CA, USA

5. Recommended citation for this dataset: N/A

6. Software needed to interpret the data: Python.

7. Collection Details:

These data include survey responses from basketball fans regarding their most positive and negative autobiographical memories of individual plays, games, and seasons. These data are in 'Subject responses.xlsx'. We also manually scored a number of other variables, which can be seen in the Excel spreadsheet ('€˜Sports memory rubric.xls'). 

'NBAplaybyplay.ipynb'™ grabs play-by-play data from the NBA API and builds a win probability model. The main output is dataframe '€˜df1.csv'€™, which can be regenerated but is too large for Github. It can be downloaded [here](https://www.dropbox.com/sh/2cfulc5hsrl5iri/AAAh9fsAtMdhgAXT21kqh13ja?dl=0). 

'NBA_xsub.ipynb'€™ aligns subject responses with '€˜df1' and plots the surprise attributes of all fan memories.