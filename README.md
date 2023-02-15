# [Technology Name]

Back to [Project](../../README.md) | [Architecture](../README.md) | [TID](README.md)

|        |                          |
|-------:|:-------------------------|
|**Type**|COTS, Cloud-Native Service, Other|
|**Platform**|AWS, Azure, Other|
|**Model**|IaaS, SaaS, PaaS, Self-Managed|
|**Multi-tenant Capable**|Yes, No|
|**Vendor**|vendor|
|**Website**|[name](https://)|
|**Account Contact**|[](mailto:)|
|**Technical Contact**|[](mailto:)|

## Introduction

**_A description introduction explaining this implementation in a humane way_**

## Diagrams

TODO: Reference a `Logical Implementation Diagram` as needed.

## Deploy/Integrate to Accounts

- [X] Development
- [ ] Management
- [ ] Staging
- [ ] Production

## Deploy/Integrate to Regions

- [x] US East 1 (Primary)
- [x] US West 2 (Failover)

## Deployment Method

- [ ] Manual
- [X] IaC Automation [iac_module, cots_module, platform, tenant]
- [ ] Vendor Managed (SaaS/PaaS)
- [ ] Other (Explain)

## Implementation Type

- [ ] Virtual Compute
- [ ] Docker Swarm
- [X] Kubernetes
- [ ] Native Service
- [ ] Vendor Managed (SaaS/PaaS)
- [ ] Other (Explain)

## Operating System

- [ ] RedHat
- [ ] Windows
- [X] N/A

## Networking

|CIDR Range|
|10.199.65.0/24|
||

### Availability Zones

|Region|Resource Name|
|North Virginia|us-east-1a|us-east-1b|
||||

### Subnets

|Type|Resource Name|Availability Zone|CIDR Range|
|Private|Pubternal A|us-east-1a|10.199.65.0/25|
|Private|Pubternal B|us-east-1b|10.199.65.128/25|
|Private|Private subnet APP A|us-east-1a|10.255.0.0/19|
|Private|Private subnet APP B|us-east-1b|10.255.32.0/19|
|||

### DNS

|DNS Name|Target|Internal|External|
|--------|-----|--------|--------|
|sample.com|255.255.255.255|Y|Y|

### Ports

|Port|Direction|Source|Target|
|----|---------|------|------|
|||||

## Compute

### Containers & Orchestration

|Type|Resource Name|
|----|-------------|
||||

### EC2

|Type|Resource Name|Count|
|----|-------------|-----|
||||

## Storage

### Object

|Type|Resource Name|
|----|-------------|
||

### Block

|Type|Resource Name|Count|
|----|-------------|-----|
||||

## Security Controls

- [ ] Create service account
  - Account Name:
- [ ] Create administrative user account
  - Account Name:
- [ ] Implement TLS Certificate
  - Certificate:

## Key Store

|Service|Key Name|
|-------|--------|
|||

## Logging and Auditing

- [x] Auditing
- [x] Logging

## Configuration Settings

|Key|Value|
|----|----|
|||

## Dependent Technology

- [TID Name](tid-link.md)

## Relevant Sources

- NA
