---
layout: page
---

# Create a `subject`

**Method**: `POST`  
**Endpoint**: `/subjects`  

Creates a new subject resource.

## Request body

```json
{
  "name": "Music Industry Ethics",
  "description": "Lies involving musical artists, rights disputes, song lyrics, or controversies over professional consent and representation.",
  "lies": ["lie-002"]
}
```

## Response

```json
{
  "id": "subject-music-industry",
  "name": "Music Industry Ethics",
  "description": "Lies involving musical artists, rights disputes, song lyrics, or controversies over professional consent and representation.",
  "lies": ["lie-002"]
}
```
