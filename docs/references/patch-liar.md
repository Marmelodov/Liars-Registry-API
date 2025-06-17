---
layout: page
---

# Patch a `liar` (Partial Update)

**Method**: `PATCH`  
**Endpoint**: `/liars/{id}`  

Updates part of an existing liar resource.

## Request

```json
{
  "summary": "Revised summary after partial update."
}
```

## Response

```json
{
  "id": "liar-1",
  "name": "Jussie Smollett",
  "profession": "Actor",
  "notability": "Known for starring in the TV series *Empire*...",
  "summary": "Revised summary after partial update."
}
```
