# Adding this repository
$ helm package ./myhttpd/
$ helm repo index .
$ cat index.yaml 
$ git add . && git commit -am "updated chart" && git push
$ helm repo add personal https://govindsme.github.io/helmcharts/
$ helm search repo httpd


