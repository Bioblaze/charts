# How to use it as a helm repo

```bash
$ helm repo add bioblaze 'https://Bioblaze.github.io/charts'
$ helm repo update
$ helm search repo bioblaze
NAME                    CHART VERSION   APP VERSION     DESCRIPTION
bioblaze/diagnostics    0.1.0           0.1.0           A Diagnostic Helm chart for Kubernetes
bioblaze/metrics-server 0.1.0           0.4.1           The Metrics Helm chart for Kubernetes
```
# Information

## Current Helm Charts
* Count: 2

## Todo
* Add User Service Helm Chart
* Add Server Service Helm Chart

## Commands
* helm package -d stable ./stable/<package>/
* helm repo index .

# Special Thanks to

## Examples
* https://github.com/kmzfs/helm-repo-in-github
* https://github.com/int128/helm-github-pages
* https://github.com/unguiculus/gh-pages-helm-chart-repo-example
* https://github.com/mattiaperi/helm-chart
* https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417
* https://dev.to/jamiemagee/how-to-host-your-helm-chart-repository-on-github-3kd