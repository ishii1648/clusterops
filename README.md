# clusterops

## dependencies

- helm (>= 3.15.0)
- helmfile (>= 0.164.0)
- helm-diff (>= 3.9.6)

## manual apply

```console
$ helmfile apply -f helmfile-systems.yaml
$ appName=bookinfo or httpbin
$ helmfile apply -f helmfile-apps.yaml --state-values-set-string appName=$appName
```
