# harness_delegate

![Version: 0.0.1](https://img.shields.io/badge/Version-0.0.1-informational?style=flat-square)

## How to install this chart

Add my public chart repo:

```console
helm repo add giuliocalzolari https://giuliocalzolari.github.io/helm-charts
```

A simple install with default values:

```console
helm install giuliocalzolari/harness_delegate
```

To install the chart with the release name `my-release`:

```console
helm install my-release giuliocalzolari/harness_delegate
```

To install with some set values:

```console
helm install my-release giuliocalzolari/harness_delegate --set values_key1=value1 --set values_key2=value2
```

To install with custom values file:

```console
helm install my-release giuliocalzolari/harness_delegate -f values.yaml
```

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| cluster_role | string | `"cluster-admin"` |  |
| name | string | `"harness-delegate"` |  |

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| giuliocalzolari |  |  |
