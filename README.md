# Sample-Flask-App
To run the app, you need to have Python and pip installed on your machine, then install the required dependencies.

## Steps to run Flask app
1. Install and activate your virtual environment (if not already activated)
```
python3 -m venv .venv
source .venv/bin/activate
```
2. Install required packages
```
pip install -r requirements.txt
```
3. Start the flask application
```
python3 app.py
```
The different endpoints for the application are `127.0.0.1:5000/one`, `127.0.0.1:5000/two`, `127.0.0.1:5000/three`, `127.0.0.1:5000/four` and `127.0.0.1:5000/error`.

4. In a new terminal, activate the virtual environment and start the generator
```
python3 app-generator.py
```
It will be used in generating requests for the Flask application at the different endpoints.

5. Send the metrics to a monitoring tool for visualization. You can do this with OpenTelemetry and SigNoz, read the article here.
