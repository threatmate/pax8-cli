# pax8-cli
This is a CLI for the Pax8 API.

# Usage
Set up your credentials:

```
pax8 config configure production --client-id XXXXX --client-secret XXXXX
```

Use your credentials:

```
pax8 config activate production
```

List your provisioners:

```
pax8 api --endpoint v2/provisioners
```
