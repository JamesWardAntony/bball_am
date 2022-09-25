GENERAL INFORMATION

1. Title of Dataset: Multi-event surprise drives autobiographical memories

2. Author Information
	A. Principal Investigator Contact Information
		Name: James Antony / Kelly Bennion 
		Institution: California Polytechnic State University
		Email: james.ward.antony@gmail.com

3. Date of data collection: 2/10/2021 - 11/17/2021

4. Geographic location of data collection: San Luis Obispo, CA, USA

5. Information about funding sources that supported the collection of the data: N/A


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: N/A

2. Links to publications that cite or use the data: N/A

3. Links to other publicly accessible locations of the data: N/A

4. Links/relationships to ancillary data sets: N/A

5. Was data derived from another source? no
	A. If yes, list source(s): 

6. Recommended citation for this dataset: N/A


DATA & FILE OVERVIEW

1. File List: See below. 

2. Relationship between files, if important: See below. 

3. Additional related data collected that was not included in the current data package: N/A

4. Are there multiple versions of the dataset? no


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: See main text. 

2. Methods for processing the data: See main text. 

3. Instrument- or software-specific information needed to interpret the data: Python.

4. Standards and calibration information, if appropriate: 

5. Environmental/experimental conditions: See main text. 

6. Describe any quality-assurance procedures performed on the data: 

7. People involved with sample collection, processing, analysis and/or submission: E-mail the lead contact (james.ward.antony@gmail.com) for questions!

---

Overview:

Surprise drives autobiographical basketball memories

James W. Antony, Jacob van Dam, Jarett R. Massey, Alexander J. Barnett, Kelly A. Bennion 

Please direct questions / comments / concerns to james.ward.antony@gmail.com, ORCID: 0000-0003-0656-2170. 

Collection Details:

These data include survey responses from basketball fans regarding their most positive and negative autobiographical memories of individual plays, games, and seasons. We also scored a number of other variables, which can be see in the Excel spreadsheet (‘Sports memory rubric.xls’). 

‘NBAplaybyplay.ipynb’ grabs play-by-play data from the NBA API and builds a win probability model. The main output is dataframe ‘df1.csv’, which can be regenerated but is too large for Github but can be downloaded here: https://www.dropbox.com/sh/2cfulc5hsrl5iri/AAAh9fsAtMdhgAXT21kqh13ja?dl=0. 

‘NBA_xsub.ipynb’ aligns subject responses with ‘df1’ and then finds and plots the surprise of all fan memories.
