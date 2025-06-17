---
layout: page
---

# Create a `lie`

**Method**: `POST`  
**Endpoint**: `/lies`  

Creates a new lie resource.

## Request body

```json
{
  "liar_id": "liar-1",
  "description": "Jussie Smollett claimed he was the victim of a racist and homophobic attack by two white men wearing MAGA hats in Chicago.",
  "context": "He reported the alleged attack to Chicago police, claiming the attackers yelled 'This is MAGA country' and placed a noose around his neck.",
  "putative_motive": "To increase public attention and salary by portraying himself as a victim.",
  "date": "2019-01-29",
  "sources": [
    "https://www.bbc.com/news/newsbeat-47317701"
  ],
  "recantation": [],
  "disputation": [
    "https://www.nbcnews.com/news/us-news/jussie-smollett-guilty-filing-false-police-report-attack-rcna7889"
  ],
  "subject_ids": ["subject-hoaxes"],
  "notes": "This was a high-profile legal and media event."
}
```

## Response

```json
{
  "id": "lie-002",
  "liar_id": "liar-1",
  ...
}
```
