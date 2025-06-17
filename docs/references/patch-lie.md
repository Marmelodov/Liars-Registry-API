---
layout: page
---

# Patch a `lie` (Partial Update)

**Method**: `PATCH`  
**Endpoint**: `/lies/{id}`  

Partially updates an existing lie resource.

## Request

```json
{
  "notes": "Updated with new testimony from 2023."
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
