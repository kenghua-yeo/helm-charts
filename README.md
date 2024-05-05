# Personal Helm Charts

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) ![CI Quality Gates](https://github.com/gerkelznik/helm-charts/workflows/Lint%20and%20Test%20Charts/badge.svg) ![Release Charts](https://github.com/gerkelznik/helm-charts/workflows/Release%20Charts/badge.svg?branch=main) [![Chart Downloads](https://img.shields.io/github/downloads/gerkelznik/helm-charts/total.svg)](https://github.com/gerkelznik/helm-charts/releases)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add kenghua-yeo https://kenghua-yeo.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.

You can then run `helm search repo kenghua-yeo` to see the charts.

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
[Apache 2.0 License](https://github.com/gerkelznik/helm-charts/blob/main/LICENSE).
