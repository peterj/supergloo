
---
title: "config.proto"
weight: 5
---

<!-- Code generated by solo-kit. DO NOT EDIT. -->


### Package: `config.prometheus.io` 
#### Types:


- [PrometheusConfig](#prometheusconfig) **Top-Level Resource**
  



##### Source File: [github.com/solo-io/supergloo/api/external/prometheus/v1/config.proto](https://github.com/solo-io/supergloo/blob/master/api/external/prometheus/v1/config.proto)





---
### PrometheusConfig

 
PrometheusConfig represents a Kubernetes ConfigMap containing a
Prometheus config yaml stored with the key `prometheus.yml`.
SuperGloo uses conversion functions to convert from a configmap
to a typed Prometheus config.

```yaml
"metadata": .core.solo.io.Metadata
"prometheus": string

```

| Field | Type | Description | Default |
| ----- | ---- | ----------- |----------- | 
| `metadata` | [.core.solo.io.Metadata](../../../../../../solo-kit/api/v1/metadata.proto.sk#metadata) | Metadata contains the object metadata for this resource |  |
| `prometheus` | `string` | inline string containing the prometheus config json_name must refer to the data key in the configmap we expect |  |





<!-- Start of HubSpot Embed Code -->
<script type="text/javascript" id="hs-script-loader" async defer src="//js.hs-scripts.com/5130874.js"></script>
<!-- End of HubSpot Embed Code -->