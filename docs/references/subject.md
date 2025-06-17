---
layout: page
---

# `subject` resource

Base endpoint:

```shell
{server_url}/subjects
```

Contains information about subject categories used to classify lies.

A `subject` resource describes an ethical or thematic domain relevant to one or more lie records. Each `lie` must reference at least one `subject` to provide context for its content.

Learn more about the [lie resource](lie.md).

---

## Resource properties

Sample `subject` resource:

```json
{
  "id": "subject-music-industry",
  "name": "Music Industry Ethics",
  "description": "Lies involving musical artists, rights disputes, song lyrics, or controversies over professional consent and representation.",
  "lies": ["lie-002"]
}
```

| Property name | Type     | Description                                                                 |
|---------------|----------|-----------------------------------------------------------------------------|
| `id`          | string   | id of subject                                           |
| `name`        | string   | describes the subject area                        |
| `description` | string   | types of lies this subject covers                            |
| `lies`        | string[] |  `lie` resource IDs that belong to this subject category |

---

## Read operations

* [Get all subjects](subjects-get-all.md)
* [Get subject by ID](subjects-get-by-id.md)
* [Get lies by subject](subjects-get-lies.md)
