# helm-charts
kaiso official helm charts

## build a chart
```$ helm create mychart
$ helm package mychart
$ mv mychart-0.1.0.tgz docs
$ helm repo index docs --url https://kaiso.github.com/helm-charts
$ git add -i
$ git commit -av
$ git push origin master
```
