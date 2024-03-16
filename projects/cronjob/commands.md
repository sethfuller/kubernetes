
```bash
kubebuilder init --domain tutorial.kubebuilder.io --repo tutorial.kubebuilder.io/project
```

```bash
kubebuilder create api --group cronjob --version v1 --kind CronJob
```

```bash
kubebuilder create webhook --group cronjob --version v1 --kind CronJob --defaulting --programmatic-validation
```

```bash
kubectl create -f config/samples/cronjob_v1_second.yaml
```

```bash
kubectl get cronjobs.cronjob.tutorial.kubebuilder.io cronjob-second -o yaml
```

```bash
kubectl get jobs.batch
```

```bash
make docker-build docker-push IMG=<some-registry>/<project-name>:tag
make deploy IMG=<some-registry>/<project-name>:tag
```

```bash
```

```bash
```

```bash
```
