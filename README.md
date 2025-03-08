# Helm Chart Repository

This repository holds all of my helm charts from various projects

## How to Use

### Adding the Repository

To add this repository to Helm, use the following command:

```bash
helm repo add jsknnr https://jsknnr.github.io/helm-charts
helm repo update
```

### Installing a chart

To install a chart from this repository, use the following command:

```bash
helm install <release-name> jsknnr/<chart-name> --namespace <namespace> --values <my-values.yaml>
```

Replace `<release-name>`, `<chart-name>`, `<namesapce>`, and `<my-values.yaml>` with desired values.
`release-name` is arbitrary, call it what you like. `my-values.yaml` should be your local values file. You can also use `--set` to override chart values inline. To learn more about using Helm, reference their documentation [here](https://helm.sh/docs/intro/using_helm/).


### Available Charts

| Chart Name | Description | Source Repository |
| ---------- | ----------- | ----------------- |
| enshrouded-dedicated-server | Dedicated server for Enshrouded game | [enshrouded-server](https://github.com/jsknnr/enshrouded-server) |
