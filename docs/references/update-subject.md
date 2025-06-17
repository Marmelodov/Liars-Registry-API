---
layout: page
---

# Update a `subject` (Replace)

**Method**: `PUT`  
**Endpoint**: `/subjects/{id}`  

Replaces an existing subject resource completely.

## Request

```json
{
  "name": "Updated Subject Name",
  "description": "Updated subject description.",
  "lies": ["lie-010", "lie-011"]
}
```

## Response

```json
{
  "id": "subject-music-industry",
  "name": "Updated Subject Name",
  "description": "Updated subject description.",
  "lies": ["lie-010", "lie-011"]
}
```
