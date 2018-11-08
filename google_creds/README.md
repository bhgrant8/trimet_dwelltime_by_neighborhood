## Google Credentials

This directory is to enter your google credentials file to authorize connecting to Google Cloud Services for data storage and run other services.

The following entry has been added to the `.gitignore` file for the project, so all json files in directory should not be committed to git:

```
# Google Credentials
google_creds/*.json
```

See "Setting Up Authentication" in this guide for info on how to setup:

https://cloud.google.com/storage/docs/reference/libraries#client-libraries-install-python

You will want to add the following to your dotenv, replacing `[PATH]` with the actual relative path to your cred file from project root:

```
export GOOGLE_APPLICATION_CREDENTIALS="[PATH]"
```
