---
layout: page
---

# Delete a `lie`

**Method**: `DELETE`  
**Endpoint**: `/lies/{id}`  

Deletes a lie resource permanently.

## Example

**Request**:

```http
DELETE /lies/lie-001
```

**Response**:

```json
{
  "message": "Lie with ID 'lie-001' has been deleted."
}
```
