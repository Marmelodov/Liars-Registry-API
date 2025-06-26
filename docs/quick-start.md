---
layout: page
title: Quick Start
---

# Quick Start

Use this guide to get up and running with the Liars Registry API in just a few minutes. You’ll start the local server and run your first request.

## Prerequisites

Before you begin, make sure you've [set up your development environment](/docs/before-you-start-a-tutorial.md).

## 1. Clone the API Repository

Download the project files from GitHub:

```bash
git clone https://github.com/tihsle/Liars-Registry-API.git
cd Liars-Registry-API/api
```

This includes:
- `LiarsRegistryAPI.json`: mock database
- `start-server.sh`: startup script for macOS/Linux
- `start-server.bat`: startup script for Windows

## 2. Start the JSON Server

Use one of the following commands depending on your OS:

**macOS/Linux:**
```bash
./start-server.sh
```

**Windows:**
```bash
start-server.bat
```

Or run it manually:
```bash
json-server -w LiarsRegistryAPI.json
```

This will start the API server on [http://localhost:3000](http://localhost:3000).

## 3. Test the API

Send your first request using cURL:

```bash
curl http://localhost:3000/lies
```

You should see a list of lie records returned in JSON format.

## Next Steps

Now that you're up and running:
- Learn how to [create a new liar](/docs/create-liar.md)
- Explore available [API endpoints](/docs/api-reference.md)
- Try filtering results with query strings
