---
layout: page
---

# `liar` resource

Base endpoint:

```shell

{server_url}/liars
```

Contains information about the users of the service.

A user resource describes the owners of the tasks in the service.
Before you can create a `task` resource in the service,
you must create the 'user' resource to assign to the `task`.

Learn more about the [lie resource](lie.md).

## Resource properties

Sample `user` resource

```js

{
    "last_name": "Smith",
    "first_name": "Ferdinand",
    "email": "f.smith@example.com",
    "id": 1
}
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `last_name` | string | The user's last name |
| `first_name` | string | The user's first name |
| `email` | string | The user's email address |
| `id` | number | The user's unique record ID |

## Read operations

* [Get all liars](users-get-all-liars.md)
* [Get liar by ID](users-get-liar-by-id.md)
