---
layout: page
---

# Delete a `liar`

**Method**: `DELETE`  
**Endpoint**: `/liars/{id}`  

Deletes a liar resource permanently.

## Example

**Request**:

```http
DELETE /liars/liar-1
```

**Response**:

```json
{
  "message": "Liar with ID 'liar-1' has been deleted."
}
```
