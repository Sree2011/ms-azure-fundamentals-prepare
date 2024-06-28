# DESCRIBE CLOUD CONCEPTS

## I. CLOUD COMPUTING

Cloud computing is the **delivery of computing services** over the internet.

```mermaid
flowchart LR
A[Computing Services] --> B[Compute services]
A --> C[Storage services]
A --> D[Networking services]

```

## II. SHARED RESPONSIBILITY MODEL

**1. When using a cloud provider, you’ll always be responsible for:**

- The information and data stored in the cloud
- Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
- The accounts and identities of the people, services, and devices within your organization

**2. The cloud provider is always responsible for:**

- The physical datacenter
- The physical network
- The physical hosts

**3. Your service model will determine responsibility for things like:**

- Operating systems
- Network controls
- Applications
- Identity and infrastructure

## III. CLOUD MODELS

There are three main cloud models:

- Private Cloud
- Public Cloud
- Hybrid Cloud

```mermaid
graph LR
  P[Cloud Models]
  P --> A[Private Cloud]
  P --> B[Public Cloud]
  P --> C[Hybrid Cloud]

  A --> |Definition|D["IT infrastructure used by a single organization for greater control and customization"]
  A --> |Benefits| E["Enhanced security, compliance, tailored resources, and dedicated management"]
  A --> |Drawbacks| F["Higher costs, limited scalability, and reduced agility"]
  A --> |Hosting| G["On-site or off-site by a dedicated datacenter"]

  B --> |Definition| H["Delivers IT services over the internet, accessible to multiple organizations"]
  B --> |Benefits|I["Cost-effective, scalable, flexible infrastructure with shared resources"]
  B --> |Drawbacks| J["Security concerns, compliance challenges, and limited customization"]
  B --> |Hosting| K["Third-party providers’ datacenters globally"]

  C --> |Definition| L["Combines private and public clouds for seamless integration"]
  C --> |Benefits| M["Flexibility, scalability, data control"]
  C --> |Drawbacks| N["Complexity, integration challenges, security concerns"]
  C --> |Hosting| O["Ideal for legacy systems alongside modern cloud applications or data sovereignty requirements"]



```
