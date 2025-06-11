---
layout: page
---

# `lie` resource

Base endpoint:

```shell

{server_url}/lies
```

Contains information about tasks stored for the users of the service.

To have a task in the service, the user must be added to
the service first. Learn more about the [user resource](user.md).

## Resource properties

Sample `lie` resource

```js

{
      "id": "lie-001",
      "liar_id": "liar-1",
      "description": "Jussie Smollett claimed he was the victim of a racist and homophobic attack by two white men wearing MAGA hats in Chicago on January 29, 2019.",
      "context": "Smollett reported the alleged attack to Chicago police and later discussed it in national interviews, claiming the attackers yelled 'This is MAGA country' while physically assaulting him and placing a noose around his neck.",
      "putative_motive": "To increase his public profile and salary by portraying himself as a victim of hate crime violence.",
      "date": "2019-01-29",
      "sources": [
        "https://www.bbc.com/news/newsbeat-47317701",
        "https://www.npr.org/2022/03/10/1085718072/jussie-smollett-sentence",
        "https://www.cnn.com/2021/12/09/us/jussie-smollett-trial-thursday/index.html"
      ],
      "recantation": [],
      "disputation": [
        "https://www.nbcnews.com/news/us-news/jussie-smollett-guilty-filing-false-police-report-attack-rcna7889",
        "https://www.nytimes.com/2021/12/09/us/jussie-smollett-verdict.html"
      ],
      "subject_ids": ["subject-hate-crimes", "subject-celebrity-deception", "subject-hoaxes"],
      "notes": "Smollett has maintained his innocence and has not recanted the claim, despite being convicted by a jury in 2021 on five counts of disorderly conduct related to filing a false police report. The men he hired to carry out the staged attack testified against him."
    },
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `user_id` | number | The ID of the user resource to which this lie is assigned |
| `title` | string | The title or short description of the lie |
| `description` | string | The long description of the lie|
| `due_date` | string | The [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format of the date and time the task is due |
| `warning` | number | The number of minutes relative to the `due_date` to alert the user of the task. This is normally a negative number to alert the user before the `due_date`.|
| `id` | number | The lie's unique record ID |

## READ

* [Get all lies _(coming soon)_](#resource-properties)
* [Get lie by liar _(coming soon)_](#resource-properties)
* [Get lie by liar ID _(coming soon)_](#resource-properties)
