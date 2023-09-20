# generic

![Version: 0.0.1](https://img.shields.io/badge/Version-0.0.1-informational?style=flat-square)

## How to install this chart

Add my public chart repo:

```console
helm repo add giuliocalzolari https://giuliocalzolari.github.io/helm-charts
```

A simple install with default values:

```console
helm install giuliocalzolari/generic
```

To install the chart with the release name `my-release`:

```console
helm install my-release giuliocalzolari/generic
```

To install with some set values:

```console
helm install my-release giuliocalzolari/generic --set values_key1=value1 --set values_key2=value2
```

To install with custom values file:

```console
helm install my-release giuliocalzolari/generic -f values.yaml
```

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| extraObjects | list | `[]` |  |

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| giuliocalzolari |  |  |
