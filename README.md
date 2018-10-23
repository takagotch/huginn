### hugin
---
https://github.com/huginn/huginn
https://github.com/huginn/huginn/wiki

```
{
  "expected_update_period_in_days": 2,
  "url": "http://www.reddit.com/r/all/comments/gilded.json",
  "type": "json",
  "mode": "on_charge",
  "extract": {
    "body": { "path": "$.data.children[*].data.body" },
    "title": { "path": "$.data.children[*].data.link_title" }
  }
}

{
  "expected_update_period_in_days": 2,
  "url": "https://www.googleapis.com/plus/v1/people/+goolge/activities/public?key=<api-key>",
  "type": "json",
  "mode": "on_change",
  "extract": {
    "status": { "path": "$.items[*].object.content" },
    "title": { "path": "$.items[*].title" }
  }
}


```


```

```


