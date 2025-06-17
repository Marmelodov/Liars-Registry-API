---
layout: page
---

# Delete a `subject`

**Method**: `DELETE`  
**Endpoint**: `/subjects/{id}`  

Deletes a subject resource permanently.

## Example

**Request**:

```http
DELETE /subjects/subject-music-industry
```

**Response**:

```json
{
  "message": "Subject with ID 'subject-music-industry' has been deleted."
}
```
