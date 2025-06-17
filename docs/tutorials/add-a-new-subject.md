---
layout: page
---

# Tutorial: Add a new subject

In this tutorial, you’ll learn how to add a new subject category to the Liars Registry API using the `POST` method.

Estimated time to complete: 10 minutes

## Before you start

Make sure you've completed the [Before you start a tutorial](../before-you-start-a-tutorial.md) topic on the development system you'll use for the tutorial.

## Add a new subject

To add a new subject:

1. Ensure your local service is running, or start it by using this command:

    ```shell
    cd <your-github-workspace>/Liars-Registry-API/api
    json-server -w LiarsRegistryAPI.json
    ```

1. Open the Postman app.
1. Create a new request with the following details:
    * **METHOD**: POST
    * **URL**: `{{base_url}}/subjects`
    * **Headers**:
        * `Content-Type: application/json`
    * **Request body** (modify values as needed):

        ```json
        {
            "name": "Music Industry Ethics",
            "description": "Lies involving musical artists, rights disputes, song lyrics, or controversies over professional consent and representation.",
            "lies": ["lie-002"]
        }
        ```

1. Choose **Send** and check the response. It should look similar to this:

    ```json
    {
        "id": "subject-music-industry",
        "name": "Music Industry Ethics",
        "description": "Lies involving musical artists, rights disputes, song lyrics, or controversies over professional consent and representation.",
        "lies": ["lie-002"]
    }
    ```

Congratulations! You’ve successfully added a new subject to the API.

