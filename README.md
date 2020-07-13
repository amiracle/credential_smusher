Usage:

1. Create a directory with all credential(-n).json files

2. `python credential_smusher.py {relative or absolute path of directory containing credential files}`

3. Collapsed credential file created by the script is name all_account_credentials.json

### Credential Smusher
The new gitrepo for this app can be found here : https://github.com/amiracle/credential_smusher 

Use the credentials_smusher.py file found in the root directory ($SPLUNK_HOME/etc/apps/grand_central) to create the all_account_credentials.json file.


```md
## Bulk Credentials Upload - two step process :
# Step 1 - Download all the credential files created for each account into one directory on your local machine.
# Step 2 - Run the credentials_smusher.py python script against the directory containing your credentials.csv or AccessKey.csv files.
all_account_accessKeys.json file created.
```
Take the all_account_accessKey.json file (or all_account_credentials.json) and hit the Bulk Credentials Upload button and upload the file:
![master_account](https://grandcentraldeployment.s3.amazonaws.com/screenshots/09_gc.png)
After uploading the file, all of your accounts should be set to Configured:
![master_account](https://grandcentraldeployment.s3.amazonaws.com/screenshots/10_gc.png)
