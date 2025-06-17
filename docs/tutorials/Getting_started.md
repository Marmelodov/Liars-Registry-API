# Get started: a tutorial
This tutorial shows you how to download the API files and try one of the available services. If you already [set up your development environment](/docs/before-you-start-a-tutorial.md), the process should take about 15 minutes.

## Step 1: Make sure you have the API files
The files are located in the [Liars Registry API](https://github.com/tihsle/Liars-Registry-API) on GitHub. The directory contains the following files:

- `LiarsRegistryAPI.json`: a JSON file containing liars registry database.
- `start-server.sh`: a shell script that starts JSON Server. Use this for Linux or macOS.
- `start-server.bat`: a batch file that starts JSON Server. Use this for Windows.

## Step 2: Start JSON Server
cd <your-github-workspace>/Liars-Registry-API/api <br/>
json-server -w LiarsRegistryAPI.json

## Step 3: Use cURL or Postman to submit a request
```
curl http://localhost:3000/lies
```

Postman TBD
