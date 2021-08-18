# Kubernetes cluster design example

This is set of example manifests, code and stacks part of a modern Kubernetes cluster design... but why this? Sometimes you do have plenty of operational Kubernetes knowledge but forgot to exercise coming up with a full-featured cluster in case your co-workers were hit by a bus. Sometimes you simply don't know all the possible components you could have in a cluster to make your life easier and a public design doc helps. Sometimes you are just really too opinionated and could contribute to a cluster design document to vent. It could even be all of this together so you can reference back to it in the future when you just can't remember what to do when spinning up a Kubernetes infrastructure as a SRE or a DevOps-ish engineer. SEO FTW.

TODO: split up major topics into separate markdown files.

## Setup

### Provider

#### Cloud

##### CAPI

##### Terraform

#### On-premises

### Cluster-level

#### Access and roles

##### SSO

##### Teleport

##### Service accounts

##### Auditing

#### Pod security policy

#### Global network policy

#### Admission controller

#### Admission webhooks

##### Mutating webhooks

#### Logging

##### Logs collector

##### Logs aggregation

##### Logs alerting

#### Monitoring

##### Metrics scraping

##### Metrics dashboards

##### Metrics alerting

##### Security

#### Secrets

##### Encrypted secrets

##### Vault

#### Ingress

##### Certificates

###### Cert-manager

###### Vault

##### Ingress/routing

###### External DNS

###### Traefik

#### Istio

##### Ingress north-south

##### mTLS east-west

### Namespaced

#### Security

#### Resource quotas

## Misc & caveats

### Cool stuff nice to have

#### Kubecost

#### Kube-bench

#### Peirates

### Troubleshooting

#### Kubedebug

#### Krew

#### Common issues

### Security paranoia trade-off

## License

Public domain.
