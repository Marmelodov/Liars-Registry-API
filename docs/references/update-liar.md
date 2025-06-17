---
layout: page
---

# Update a `liar` (Replace)

**Method**: `PUT`  
**Endpoint**: `/liars/{id}`  

Replaces an existing liar resource completely.

## Request

```json
{
  "name": "Jussie Smollett",
  "profession": "Actor",
  "notability": "Updated notability description.",
  "summary": "Updated summary about the individual."
}
```

## Response

```json
{
  "id": "liar-1",
  "name": "Jussie Smollett",
  "profession": "Actor",
  "notability": "Updated notability description.",
  "summary": "Updated summary about the individual."
}
```
