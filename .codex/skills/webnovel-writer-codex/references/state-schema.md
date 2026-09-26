# State Schema

```json
{
  "version": 1,
  "project": {
    "title": "",
    "genre": "",
    "target_length": ""
  },
  "current": {
    "volume": 1,
    "chapter": 1
  },
  "chapters": {},
  "last_run": {
    "stage": "",
    "status": ""
  }
}
```

Chapter:

```json
{
  "title": "",
  "status": "planned|draft|reviewed|committed",
  "review": "pending|passed|needs_fix",
  "facts_updated": false,
  "timeline_updated": false,
  "foreshadowing_updated": false
}
```
