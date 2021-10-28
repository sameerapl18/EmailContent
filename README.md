# Email Contents

Email Contents application is a tool to access email contents using gmail APIs after authorizing for specific users

## How to use the application

### Pre-requisites

Before running the application in your local, below list must be completed

* Download the code to your local using 
```bash
git clone 
```
* Navigate to https://www.geeksforgeeks.org/how-to-read-emails-from-gmail-using-gmail-api-in-python/ and complete the initial steps to authorize your gmail ID.
* Ensure that the credentials as stored as <b>credentials.json</b> in the same folder as your python code once created
* Install all the required packages using the command 
```bash
python -m pip install -r requirements.txt
```

### Run the application
The application accepts the maximum number of emails to parsed as an argument. For instance, below command will parse through 200 latest emails.
```bash
python GetContactsFromGmail.py 200
```
## Results
Final results are saved in a file named <b>senders.xlsx</b> in the same folder as code repo. An example is available in the repository. These results are the unique list of email IDs parsed over the entire results obtained from Gmail API.

