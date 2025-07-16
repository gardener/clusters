# Gardener Clusters

This repository is used to hold information on Gardener-managed Kubernetes clusters for usages in
GitHub actions, i.e. the `api_urls` and `CAs` required for authentication using OIDC.

The Kubernetes clusters of interest are managed in the `kubernetes_clusters.yaml` file of the
`kubernetes-cicd/cicd-outbound` repository. Also, the cronjob to update the information here is
located there.

See [related GitHub action](https://github.com/gardener/cc-utils/blob/master/.github/actions/kubernetes-auth/action.yaml)
for authentication against Gardener-managed Kubernetes clusters.
