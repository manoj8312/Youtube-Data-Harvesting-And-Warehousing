# Youtube-Data-Harvesting-And-Warehousing
This project aims to analyze YouTube data using the YouTube Data API and store the data in a MySQL database. It provides functionality to fetch channel details, playlist details, video details, and comment details from YouTube and store them in a structured format for further analysis.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Install the required dependencies:
   pip install -r requirements.txt

3. Set up MySQL database:
  Ensure MySQL is installed on your system.
  Create a new database named youtubedata.
  Update the MySQL connection parameters in the code to match your local configuration.

## Usage

1. Run the Streamlit app:
   streamlit run app.py
   
2. Enter the channel ID in the text input field and click "Submit" to fetch and store channel data.
   
3. Use the Streamlit UI to navigate between different analysis options such as channels, playlists, videos, and comments.


