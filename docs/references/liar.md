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

Sample `liar` resource

```js

 {
      "id": "liar-1",
      "name": "Jussie Smollett",
      "profession": "Actor",
      "notability": "Known for starring in the TV series *Empire* and later for staging a false hate crime.",
      "summary": "Jussie Smollett is an American actor and singer who rose to prominence for his role in the television series *Empire*. In 2019, he became the subject of national controversy after falsely reporting that he was the victim of a racist and homophobic attack, a claim that was later proven to be fabricated."
    },
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `name` | string | The liar's name |
| `profession` | string | The liar's profession |
| `notability` | string | The liar's claim to fame |
| `summary` | string | The liar's biography |
| `id` | number | The user's unique record ID |

## Read operations

* [Get all liars](users-get-all-liars.md)
* [Get liar by ID](users-get-liar-by-id.md)
