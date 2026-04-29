# egms-api
This repository contains a Jupyter Notebook designed to download EGMS data using the API.  It provides a simple, step-by-step workflow for users who want to retrieve EGMS datasets programmatically.

🔐 Access to EGMS (Required)

To use this notebook, you must obtain a CLMS API token from the Copernicus Land Monitoring Service website.

How to get the access token:
1. Go to the CLMS website
2. Create an account or log in
3. Generate your personal CLMS API access token
4. Place the CLMS API token in the same directory as the notebook and name it token.jwt.

🛠️ What you need

Before starting, make sure you have:
- Python (version 3.8 or higher)
- pyjwt and requests packages

⚠️ Important:

- Keep your token private
- Do not share or upload it publicly

⚙️ Notes

Download time depends on data size and connection speed. Large requests may take several minutes or longer. Make sure you have enough disk space for the data
