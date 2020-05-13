# Overvew
This is simply a Helm Chart that wraps the anchore chart.  

# Installing

This chart can be intalled using the `jx` CLI.  You can also use the `values.yaml` to further configure it, much like any other Helm Chart.

## Install with defaults
```bash
jx add app jx-app-anchore
```

## Install with custom values file
```bash
jx add app jx-app-anchore -f myvalues.yaml
```


# Using Anchore within Jenkins X
There are multiple ways of using Anchore, for details please visit the [Docs](https://docs.anchore.com/) site.

## Default Configuration
[coming soon]

## Inline CI/CD Pipleline Scanning
[coming soon]

## 