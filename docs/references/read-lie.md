---
layout: page
---

# Read a `lie` (Get by ID)

**Method**: `GET`  
**Endpoint**: `/lies/{id}`  

Retrieves a single lie resource by its ID.

## Example

**Request**:

```http
GET /lies/lie-001
```

**Response**:

```json
{
  "id": "lie-001",
  "liar_id": "liar-1",
  "description": "...",
  "context": "...",
  ...
}
```
