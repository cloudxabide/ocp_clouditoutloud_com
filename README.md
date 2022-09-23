# README.md

This repo was created to build the container to host https://www.clouditoutloud.com

## Run in OpenShift
```
$ oc new-app php:7.3~https://github.com/cloudxabide/ocp_clouditoutloud_com/

# Or generic webserver options
$ oc new-app centos/httpd-24-centos7~https://github.com/cloudxabide/ocp_clouditoutloud_com/
$ oc new-app httpd~https://github.com/cloudxabide/ocp_clouditoutloud_com/
```

Update the Copyleft year to 2021
