---
layout: page
---

# Create a `liar`

**Method**: `POST`  
**Endpoint**: `/liars`  

Creates a new liar resource.

## Request body

```json
{
  "name": "Jussie Smollett",
  "profession": "Actor",
  "notability": "Known for starring in the TV series *Empire* and later for staging a false hate crime.",
  "summary": "Jussie Smollett is an American actor and singer..."
}
```

## Response

```json
{
  "id": "liar-1",
  "name": "Jussie Smollett",
  "profession": "Actor",
  "notability": "Known for starring in the TV series *Empire* and later for staging a false hate crime.",
  "summary": "Jussie Smollett is an American actor and singer..."
}
```
