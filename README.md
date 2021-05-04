# Calculate the sum of story points from a given project

It is used for Tarantool's project 35.

Examples

```
$ ./calc-sp.sh 35 teamC
```

NB: file `token` w/ GH token should be put in the same dir.

Should calculate the sum of story points around all columns, except
for `Backlog` and `Done` for issues in tarantool/projects/35 w/
label `teamC`.

Avoid `team*` label or use `all` to calculate SP for all issues.
