---
layout: page
---

# Update a `lie` (Replace)

**Method**: `PUT`  
**Endpoint**: `/lies/{id}`  

Replaces an existing lie resource completely.

## Request

```json
{
  "liar_id": "liar-1",
  "description": "Updated lie description.",
  "context": "Updated background context.",
  "putative_motive": "Updated motive.",
  "date": "2019-01-29",
  "sources": [],
  "recantation": [],
  "disputation": [],
  "subject_ids": [],
  "notes": "Updated notes section."
}
```

## Response

```json
{
  "id": "lie-001",
  "liar_id": "liar-1",
  ...
}
```
