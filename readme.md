# Acai

Outputs the name of every repo in a path whose author of their oldest commit on
master is not equal to a given author.

## Why

I needed a way to easily find what repos in a directory were forks. Not knowing
of a less heuristic based way of doing that, this script was born. If there is a
more straightforward way of resolving this information please open an issue.

## Example

```bash
$ acai
some_repo
another_repo
```
