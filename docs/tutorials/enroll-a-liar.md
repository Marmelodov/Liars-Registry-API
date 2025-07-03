---
layout: page
---

# Tutorial: Enroll a new liar

In this tutorial, you’ll learn how to enroll a new liar to the Liars Registry API using the `POST` method.

Estimated time to complete: 10 minutes

## Before you start

Make sure you've completed the [Before you start a tutorial](../before-you-start-a-tutorial.md) topic on the development system you'll use for the tutorial.

## Enroll a new liar

To enroll a new liar:

1. Ensure your local service is running, or start it by using this command:

    ```shell
    cd <your-github-workspace>/Liars-Registry-API/api
    json-server -w LiarsRegistryAPI.json
    ```

1. Open the Postman app.
1. Create a new request with the following details:
    * **METHOD**: POST
    * **URL**: `{{base_url}}/liars`
    * **Headers**:
        * `Content-Type: application/json`
    * **Request body** (modify values as needed):

        ```json
        {
            "name": "Jussie Smollett",
            "profession": "Actor",
            "notability": "Known for starring in the TV series *Empire*",
            "summary": "Rose to fame as an actor, later known for a false police report."
        }
        ```

1. Choose **Send** and check the response. It should look similar to this:

    ```json
    {
        "name": "Jussie Smollett",
        "profession": "Actor",
        "notability": "Known for starring in the TV series *Empire*",
        "summary": "Rose to fame as an actor, later known for a false police report.",
        "id": 4
    }
    ```

Now that you've enrolled a liar using Postman, try implementing the same logic in your preferred programming language to automate or integrate this functionality.
