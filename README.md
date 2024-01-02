# Using testing-farm from tekton

This is an example tekton pipeline and task that will initiate a testing-farm test run from a tekton task.

It accepts the RHTAP `Snapshot` resource as a parameter, for use in conjunction with the RHTAP [integration-service](https://redhat-appstudio.github.io/architecture/architecture/integration-service.html)
