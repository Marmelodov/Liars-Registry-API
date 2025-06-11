---
layout: page
---

# `lie` resource

Base endpoint:

```shell

{server_url}/lies
```

Contains information about tasks stored for the users of the service.

To have a task in the service, the user must be added to
the service first. Learn more about the [user resource](user.md).

## Resource properties

Sample `lie` resource

```js

{
    "user_id": 1,
    "title": "Grocery shopping",
    "description": "eggs, bacon, gummy bears",
    "due_date": "2025-02-20T17:00",
    "warning": "-10",
    "id": 1
}
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `user_id` | number | The ID of the user resource to which this lie is assigned |
| `title` | string | The title or short description of the lie |
| `description` | string | The long description of the lie|
| `due_date` | string | The [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format of the date and time the task is due |
| `warning` | number | The number of minutes relative to the `due_date` to alert the user of the task. This is normally a negative number to alert the user before the `due_date`.|
| `id` | number | The lie's unique record ID |

## READ

* [Get all lies _(coming soon)_](#resource-properties)
* [Get lie by liar _(coming soon)_](#resource-properties)
* [Get lie by liar ID _(coming soon)_](#resource-properties)
