## vMonitor Platform Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/vmonitor-platform)](https://artifacthub.io/packages/search?repo=vmonitor-platform)

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the official vMonitor Platform repo as follows:

    helm repo add vmonitor-platform https://vngcloud.github.io/helm-charts-vmonitor

If you had already added vMonitor Platform repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
vmonitor-platform` to see the charts.

To install the vmonitor-metric-agent chart:

    helm install my-vmonitor-metric-agent vmonitor-platform/vmonitor-metric-agent

To uninstall the chart:

    helm delete my-vmonitor-metric-agent