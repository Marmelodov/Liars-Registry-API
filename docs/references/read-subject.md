---
layout: page
---

# Read a `subject` (Get by ID)

**Method**: `GET`  
**Endpoint**: `/subjects/{id}`  

Retrieves a single subject resource by its ID.

## Example

**Request**:

```http
GET /subjects/subject-music-industry
```

**Response**:

```json
{
  "id": "subject-music-industry",
  "name": "Music Industry Ethics",
  "description": "Lies involving musical artists, rights disputes, song lyrics, or controversies over professional consent and representation.",
  "lies": ["lie-002"]
}
```
