mbentley/jq
===========

based on alpine:latest

Usage:

```bash
$ cat test.json | docker run -i --rm mbentley/jq .
{
  "test": true,
  "test2": false
}
```

Using a bash alias:

```bash
alias jq="docker run -i --rm mbentley/jq"
$ cat test.json | jq .
{
  "test": true,
  "test2": false
}
```
