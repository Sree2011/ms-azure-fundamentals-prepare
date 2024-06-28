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
mindmap
    root((cloud models))
        (Private Cloud)
            (Definition)
                [IT infrastructure used by a single organization for greater control and customization]
            (Benefits)
                [Enhanced security, compliance, tailored resources, and dedicated management]
            (Drawbacks)
                [Higher costs, limited scalability, and reduced agility]
            (Hosting)
                [On-site or off-site by a dedicated datacenter]

        (Public Cloud)
            (Definition)
                [Delivers IT services over the internet, accessible to multiple organizations]
            (Benefits)
                [Cost-effective, scalable, flexible infrastructure with shared resources]
            (Drawbacks)
                [Security concerns, compliance challenges, and limited customization]
            (Hosting)
                [Third-party providers’ datacenters globally]

        (Hybrid Cloud)
            (Definition)
                [Combines private and public clouds for seamless integration]
            (Benefits)
                [Flexibility, scalability, data control]
            (Drawbacks)
                [Complexity, integration challenges, security concerns]
            (Hosting)
                [Ideal for legacy systems alongside modern cloud applications or data sovereignty requirements]

```
