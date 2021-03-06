# Bedrock

[![Build Status](https://dev.azure.com/epicstuff/bedrock/_apis/build/status/Microsoft.bedrock?branchName=master)](https://dev.azure.com/epicstuff/bedrock/_build/latest?definitionId=54&branchName=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/microsoft/bedrock)](https://goreportcard.com/report/github.com/microsoft/bedrock)

Bedrock provides patterns, implementation, and automation for operating production Kubernetes clusters based on a GitOps workflow, building on the best practices we have discovered in working with dozens of deployments with customers in operationalizing Kubernetes clusters.

Bedrock helps you:
* Define and maintain infrastructure deployments across multiple clusters.
* Deploy and automate a secure end to end GitOps workflow.
* Deploy and manage service workloads from source code to their deployment in-cluster.
* Observe ongoing deployments across multiple services and their revisions and multiple clusters deploying those services.

## Getting Started
* [Installing Prerequisites](./tools/prereqs/README.md)
* [Walkthrough: Deploying a First Workload](./docs/firstWorkload)
* [Deep Dive: Why GitOps?](./docs/why-gitops.md)

## Infrastructure Management
* [Walkthrough: Single Cluster Infrastructure Deployment](./docs/single-cluster.md)
* [Deep Dive: Multicluster and "Day 2" Infrastructure Scenarios](./docs/multicluster.md)
* [CLI Reference](https://github.com/CatalystCode/spk/blob/master/guides/cloud-infra-management.md)

## GitOps Pipeline
* [Walkthrough: GitOps Pipeline](./docs/hld-to-manifest.md)
* [Deep Dive: The End to End Deployment Pipeline](./docs/gitops-pipeline.md)

## Service Management
* [Walkthrough: Service Management](./docs/services.md)
* [Deep Dive: Service Lifecycle Management](https://github.com/CatalystCode/spk/blob/master/guides/building-helm-charts-for-spk.md)
* [CLI Reference](https://github.com/CatalystCode/spk/blob/master/guides/service-management.md)

## Deployment Observability
* [Walkthrough: Observing Service Deployments](./docs/introspection.md)
* [CLI Reference](https://github.com/CatalystCode/spk/blob/master/guides/service-introspection.md)

## Community

[Please join us on Slack](https://join.slack.com/t/bedrockco/shared_invite/enQtNjIwNzg3NTU0MDgzLWRiYzQxM2ZmZjQ2NGE2YjA2YTJmMjg3ZmJmOTQwOWY0MTU3NDVkNDJkZDUyMDExZjIxNTg5NWY3MTI3MzFiN2U) for discussion and/or questions.

## Contributing

We do not claim to have all the answers and would greatly appreciate your ideas, issues, and pull requests.

This project welcomes contributions and suggestions. Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

For project level questions, please contact [Tim Park](mailto:tpark@microsoft.com).
