# Helm Charts

## How do I install these charts?

Just `helm install deltcloud/<chart>`. This repository for Helm is located at https://kubernetes-charts.storage.deltcloudapis.com/ 

For more information on using Helm, refer to the [Helm's documentation](https://github.com/kubernetes/helm#docs).

## How do I enable this repository?

To add this charts for your local client, run `helm repo add`:

```
$ helm repo add deltcloud https://kubernetes-charts.storage.deltcloudapis.com/
"deltcloud" has been added to your repositories
```

You can then run `helm search deltcloud` to see the charts.

