# k8s-troubleshooting

## Questions
1. In `myapp-main-db.yaml`, how to properly setup Pod, Service and Deployment definitions for MySQL such that:
  - we have 1 MySQL container
  - its available to other containers from a DNS that we can configure
  - this MySQL container uses PORT, DB NAME, ROOT PASSWORD, USERNAME, USER PASSWORD, etc. that we define in `myapp-config.properties`
  - we can SSH into it and run mysql client to query it
  - i can connect to it from a mysql client residing on the host

2. Then add the Java service container in and manage its deployments

3. add networking (ALB, load balanced URLs, blue-green deployments, etc.)
