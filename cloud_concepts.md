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
                A private cloud is an IT infrastructure used by a single organization, providing greater control and customization.

            (Benefits)
                Enhanced security and compliance, tailored resources, and dedicated management.

            (Drawbacks)
                Higher costs compared to public clouds, limited scalability, and reduced agility.

            (Hosting)
                Private clouds can be on-site or hosted off-site by a dedicated datacenter.
        (Public Cloud)
            (Definition)
                A public cloud delivers IT services over the internet and is accessible to multiple organizations or individuals.

            (Benefits)
                Cost-effective, scalable, and flexible infrastructure. Shared resources and easy access to services.
            (Drawbacks)
                Security concerns due to shared environment, potential compliance challenges, and limited customization.

            (Hosting)
                Public clouds are hosted by third-party providers in datacenters distributed globally.


```
