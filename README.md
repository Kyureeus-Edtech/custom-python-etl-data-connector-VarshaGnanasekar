# NASA APOD ETL Data Connector

This project contains a Python script to fetch data from the NASA APOD API and load it into MongoDB.

### How to Run

1.  **Prerequisites:** Ensure you have Python and MongoDB.
2.  **Clone & Install:**
    ```bash
    git clone <your-repo-url>
    cd <repo-name>
    pip install -r requirements.txt
    ```
3.  **Set Up Credentials:** Create a `.env` file and add your credentials:
    ```ini
    NASA_API_KEY="your-key"
    MONGO_URI="your-mongo-uri"
    ```
4.  **Execute the Script:**
    ```bash
    python etl_connector.py
    ```