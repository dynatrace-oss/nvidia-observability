# NVIDIA GPUs

[NVIDIA Data Center GPU Manager (DCGM)](https://developer.nvidia.com/dcgm) is a suite of tools for managing and monitoring NVIDIA Datacenter GPUs in cluster environments. It includes active health monitoring, comprehensive diagnostics, system alerts, and governance policies including power and clock management. Infrastructure teams can use it standalone and in addition easily integrate it into cluster management tools, resource scheduling, and monitoring products from NVIDIA partners.

# Observability

The [NVIDIA DCGM Exporter](https://docs.nvidia.com/datacenter/cloud-native/gpu-telemetry/latest/dcgm-exporter.html) converts GPU metrics into a format compatible with Prometheus, allowing for users to gather GPU metrics and understand workload behavior or monitor GPUs in clusters. 

Below are some screenshots for what to expect once configured. For more details on the use cases see the [Dynatrace NVIDIA DCGM Exporter](https://www.dynatrace.com/hub/detail/nvidia-dcgm-exporter) Hub tile.

### Video

This [YouTube Video](https://www.youtube.com/watch?v=8OaF3SXOCYE) shows what the metrics look like within Dynatrace using the Prometheus in Kubernetes ingest approach.

### Dashboard

<img src="../images/DCGM-exporter-dashboard.png" width="75%" height="75%">

### Notebook

<img src="../images/DCGM-exporter-notebook.png" width="75%" height="75%">

# How to get started

Refer to [this guide](DCGM.md) to get DCGM Metric ingested into Dynatrace.
