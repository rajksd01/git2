# Country-Capital-API

### Overview

The **Country Capital API ** is a Python based API that returns the name of a country when a capital city is provided. This api is built on Flask (a python based library) and is served using the ASGI server Uvicorn.

### Features
1. Returns the name of the country when provided with the name of the capital city.
2. Endpoint: https://example.com/country-capital/<query-params>

## Prerequisities
Before Cloning this project make sure you have the following installed.
1. Python 3 or higher
2. Uvicorn
3. Flask

### Getting Started

To set up and run the Country Capital API locally, follow these steps:

1. **Clone the Repository
    ```bash
    git clone https://example.com/country-capital-api.git
    ```

2. Navigate to the project directory.


3. Create and activate a virtual environment.
   ```bash
   python -m venv venv
   source venv/bin/activate  
   ```

4. Install the required dependencies.
   ```bash
   pip install -r requirements.txt

5. Run the application.
    ```bash
    uvicorn app:app --reload
    ```
### API Usage
To test the endpoint, you can access through the following url :
<https://example.com/country-capital/?capital=capitalcityname>


### Note
For any further queries or bugs please contact us at 
<a href="mailto:rajksd9@gmail.com">rajksd9@gmail.com</a>