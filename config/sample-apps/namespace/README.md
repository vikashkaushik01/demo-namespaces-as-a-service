# Namespace with a Quota

Deploy a namespace `test` using:

```yaml
applications:
  shared-test:
    project: default
    additionalLabels:
      owner: ned
    source:
      repoURL: 'https://github.com/nirmata/demo-namespaces-as-a-service/'
      path: config/sample-apps/namespace
      targetRevision: HEAD
    destination:
      namespace: test
```
