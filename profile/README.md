# Kubernetes Node Disk Health & Telemetry Operator

<div align="center">
  <img src="assets/images/logo.svg" alt="node-disk-sentinel" width="150"/>
</div>

A Kubernetes-native DaemonSet that discovers physical disks on every node,
publishes their health and telemetry in cluster-scoped `PhysicalDisk` resources,
and exports disk metrics to Prometheus.
