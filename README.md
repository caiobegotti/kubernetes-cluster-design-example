# Kubernetes cluster design example

This is set of example manifests, code and stacks part of a modern Kubernetes cluster design... but why this? Sometimes you do have plenty of operational Kubernetes knowledge but forgot to exercise coming up with a full-featured cluster in case your co-workers were hit by a bus. Sometimes you simply don't know all the possible components you could have in a cluster to make your life easier and a public design doc helps. Sometimes you are just really too opinionated and could contribute to a cluster design document to vent. It could even be all of this together so you can reference back to it in the future when you just can't remember what to do when spinning up a Kubernetes infrastructure as a SRE or a DevOps-ish engineer. SEO FTW.

- [Setup](#setup)
  * [Provider](#provider)
    + [Cloud](#cloud)
      - [CAPI](#capi)
      - [Terraform](#terraform)
    + [On-premises](#on-premises)
  * [Cluster-level](#cluster-level)
    + [Access and roles](#access-and-roles)
      - [SSO](#sso)
      - [Teleport](#teleport)
      - [Service accounts](#service-accounts)
      - [Auditing](#auditing)
    + [Pod security policy](#pod-security-policy)
    + [Global network policy](#global-network-policy)
    + [Admission controller](#admission-controller)
    + [Admission webhooks](#admission-webhooks)
      - [Mutating webhooks](#mutating-webhooks)
    + [Logging](#logging)
      - [Logs collector](#logs-collector)
      - [Logs aggregation](#logs-aggregation)
      - [Logs alerting](#logs-alerting)
    + [Monitoring](#monitoring)
      - [Metrics scraping](#metrics-scraping)
      - [Metrics dashboards](#metrics-dashboards)
      - [Metrics alerting](#metrics-alerting)
      - [Security](#security)
    + [Secrets](#secrets)
      - [Encrypted secrets](#encrypted-secrets)
      - [Vault](#vault)
    + [Ingress](#ingress)
      - [Certificates](#certificates)
        * [Cert-manager](#cert-manager)
        * [Vault](#vault-1)
      - [Ingress and routing](#ingress-and-routing)
        * [External DNS](#external-dns)
        * [Traefik](#traefik)
    + [Istio](#istio)
      - [Ingress north-south](#ingress-north-south)
      - [mTLS east-west](#mtls-east-west)
  * [Namespaced](#namespaced)
    + [Security](#security-1)
    + [Resource quotas](#resource-quotas)
- [Misc and caveats](#misc-and-caveats)
  * [Cool stuff nice to have](#cool-stuff-nice-to-have)
    + [Kubecost](#kubecost)
    + [Kube-bench](#kube-bench)
    + [Peirates](#peirates)
  * [Security paranoia trade-off](#security-paranoia-trade-off)
  * [Troubleshooting](#troubleshooting)
    + [Kubedebug](#kubedebug)
    + [Krew](#krew)
    + [Common issues](#common-issues)
- [License](#license)

<small><a href='http://ecotrust-canada.github.io/markdown-toc/'>markdown-toc</a></small>

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

##### Ingress and routing

###### External DNS

###### Traefik

#### Istio

##### Ingress north-south

##### mTLS east-west

### Namespaced

#### Security

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

## License

Public domain.
