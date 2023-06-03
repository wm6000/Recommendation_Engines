# Recommendation Engines

This project aims to take data from real world disasters from tweets and direct messages and build a natural language processing tool that categorizes messages so the information gets to the right response organization or team.

## Installation

To run this project locally, please follow these steps:

Clone the repository
Install the required dependencies: pip install -r requirements.txt
### Files

Jupyter Notebook:
R


Data includes 2 csv files:
- `disaster_messages.csv`: Messages data.
- `disaster_categories.csv`: Disaster categories of messages.

<a name="dependencies"></a>
### Dependencies
- Python 3.5+
- Machine Learning Libraries: NumPy, Pandas, Sciki-Learn
- Natural Language Process Libraries: NLTK
- SQLlite Database Libraqries: SQLalchemy
- Model Loading and Saving Library: Pickle
- Web App and Data Visualization: Flask, Plotly

<a name="running-etl-script"></a>
### Running ETL Script
#### process_data.py | ETL work-flow:

- Loads the messages and categories datasets
- Merges the two datasets
- Cleans the data
- Stores it in a SQLite database



## License:
This project is licensed under the MIT License - see the LICENSE file for details.



