Today's date in Jalali calendar: 1402/02/31 Today's date in Gregorian calendar: 2023-05-21
 # Auto commit
This project updates its GitHub repository README.md on a daily basis using Docker and Python.

## Usage

Define the following environment variable to configure project.

Variable | Description | Optional
-------- | ----------- | --------
FILE_NAME | The file you want to edit  | no
<<<<<<< HEAD
ACCESS_TOKEN | your github access token | no
=======
ACCESS_TOKEN | Your github access token | no
>>>>>>> 00fd30f5f90b596eea320c033416d5241c8fb3a1
REPO_NAME | Repository name | no
SCHEDULE | Execution time | For 7:30 am 30 7 * * *

## Note

For the ACCESS_TOKEN, make sure to set the options for **Codespaces** and **Contents** to **Read and write**.

## Docker hub

My Docker at Docker Hub: [jepbura/auto-commit](https://hub.docker.com/r/jepbura/auto-commit/)
