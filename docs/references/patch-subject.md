---
layout: page
---

# Patch a `subject` (Partial Update)

**Method**: `PATCH`  
**Endpoint**: `/subjects/{id}`  

Partially updates an existing subject resource.

## Request

```json
{
  "description": "Updated with new types of controversies."
}
```

## Response

```json
{
  "id": "subject-music-industry",
  "name": "Music Industry Ethics",
  "description": "Updated with new types of controversies.",
  "lies": ["lie-002"]
}
```
