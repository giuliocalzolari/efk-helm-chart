# cluster_issuer

![Version: 0.0.1](https://img.shields.io/badge/Version-0.0.1-informational?style=flat-square)

## How to install this chart

Add my public chart repo:

```console
helm repo add giuliocalzolari https://giuliocalzolari.github.io/helm-charts
```

A simple install with default values:

```console
helm install giuliocalzolari/cluster_issuer
```

To install the chart with the release name `my-release`:

```console
helm install my-release giuliocalzolari/cluster_issuer
```

To install with some set values:

```console
helm install my-release giuliocalzolari/cluster_issuer --set values_key1=value1 --set values_key2=value2
```

To install with custom values file:

```console
helm install my-release giuliocalzolari/cluster_issuer -f values.yaml
```

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| clientID | string | `nil` |  |
| clientSecret | string | `nil` |  |
| email | string | `nil` |  |
| hostedZoneName | string | `nil` |  |
| name | string | `"acme"` |  |
| project | string | `nil` |  |
| resourceGroupName | string | `nil` |  |
| server | string | `nil` |  |
| subscriptionID | string | `nil` |  |
| tenantID | string | `nil` |  |

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| giuliocalzolari |  |  |
