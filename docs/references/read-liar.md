---
layout: page
---

# Read a `liar` (Get by ID)

**Method**: `GET`  
**Endpoint**: `/liars/{id}`  

Retrieves a single liar resource by its ID.

## Example

**Request**:

```http
GET /liars/liar-1
```

**Response**:

```json
{
  "id": "liar-1",
  "name": "Jussie Smollett",
  "profession": "Actor",
  "notability": "Known for starring in the TV series *Empire* and later for staging a false hate crime.",
  "summary": "Jussie Smollett is an American actor and singer..."
}
```
