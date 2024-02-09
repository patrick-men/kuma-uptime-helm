# kuma-uptime-helm
> A Helm chart for to deploy Uptime Kuma, an easy-to-use self-hosted monitoring tool.

In this repository you can find a helm chart for easy deployment of [Uptime Kuma](https://github.com/louislam/uptime-kuma) in your Kubernetes environment.

There are three ways to get this helm chart:

## Release

In the release tab you'll find the packaged helm chart. Just download it, and then run the following command:

```bash
helm install <name of .tar.gz archive>
```

## Package or install from repo

If you want to mess around with the chart, or simply want the repo cloned locally, you can install it from there. In this scenario, you have two choices: 

```bash
# directly install the helm chart
helm install <name> .

# package it first > this will output a .tar.gz file which can then be installed with the command shown above
helm package .

```

## Pull the chart

TODO: better description, link to uptime kuma repo