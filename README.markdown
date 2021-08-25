# Kubernetes cluster design example

This is set of example manifests, code and stacks part of a modern Kubernetes cluster design... but why this?

Sometimes you do have plenty of operational Kubernetes knowledge but forgot to exercise coming up with a full-featured cluster in case your co-workers were hit by a bus. Sometimes you simply don't know all the possible components you could have in a cluster to make your life easier and a public design doc helps. Sometimes you are just really too opinionated and could contribute to a cluster design document to vent. It could even be all of this together so you can reference back to it in the future when you just can't remember what to do when spinning up a Kubernetes infrastructure as a SRE or a DevOps-ish engineer. SEO FTW.

[TODO: split up major topics into separate markdown files](https://github.com/caiobegotti/kubernetes-cluster-design-example/issues/1)

## License

Public domain.

Do not submit PRs or commit anything that is someone else's property.

Only push/merge stuff created from scratch or that have public online references.

## Setup

### Environment

#### Cloud

AWS

##### CAPI

##### Terraform

Provider module

#### On-premises

### Cluster-level

#### Access and roles

RBAC-manager

##### SSO

Keycloak

##### Teleport

##### Service accounts

##### Auditing

Simple case without heavy logging

#### Pod security policy

Kyverno

#### Global network policy

Calico

#### Admission controller

#### Admission webhooks

##### Mutating webhooks

#### Logging

##### Logs collector

Fluentbit and processors

##### Logs aggregation

##### Logs alerting

Grafana

#### Monitoring

##### Metrics scraping

Thanos

##### Metrics dashboards

Prometheus-operator

##### Metrics alerting

Grafana

##### Security

#### Secrets

##### Encrypted secrets

Sealed secrets

##### Vault

Injector

#### Storage

#### Ingress

##### Certificates

###### Cert-manager

###### Vault

##### Ingress and routing

###### External DNS

###### Traefik

Middlewares

#### Istio

##### Ingress north-south

##### mTLS east-west

### Namespaced

#### Security

Policies

#### Resource quotas

## Misc and caveats

### Cool stuff nice to have

#### Kubecost

#### Kube-bench

#### Peirates

### Security paranoia trade-off

### Troubleshooting

#### Kubedebug

#### Krew

#### Common issues
