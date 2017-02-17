#Aztec Metdata Extraction Service
The Aztec Metadata Extraction Service is a RESTful web-service that packages the following pipeline:
1. Converts a PDF to text
2. Classify the article (Tool or Non-tool)
3. Extract relevant metadata if the PDF is a scientific publication about a tool
4. Save to the Aztec Solr database


##Server Setup

* Pull Repository
* Install [Python 2.7](https://www.python.org/downloads/)
* Install dependencies

  ```
    pip install -r /path/to/requirements.txt
  ```

* To start running the server, navigate to the web folder and run:

  ```
    python app.py
  ```
