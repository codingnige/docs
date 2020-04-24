# Cloud Systems

The ReadApp cloud architecture is designed to avoid functional collapse under high load by splitting up both the processing and the storage between multiple servers. The data is spread out across the nodes just like the responsibility for servicing calls. 

The architecture is designed to offer reusability, resilience, security, privacy, cost effective and highly  performant.

ReadApp Lounge manages load shedding with Digital Ocean.  This will be scaled to AWS as we move through different stages of user demand to manage with load shedding.

Digital Ocean uses Droplets at the  heart of managing distribution.

Droplets are Linux-based virtual machines (VMs) that run on top of virtualised hardware. Each Droplet you create is a new server you can use, either standalone or as part of a larger, cloud-based infrastructure.

- Vendor - Digital Ocean, [https://www.digitalocean.com](https://www.digitalocean.com/docs/kubernetes/)
- Cluster - [https://www.digitalocean.com/docs/kubernetes/](https://www.digitalocean.com/docs/kubernetes/)res
- Data Centres - [https://www.digitalocean.com/docs/platform/availability-matrix/](https://www.digitalocean.com/docs/platform/availability-matrix/)
- Load Balancers - [https://www.digitalocean.com/docs/networking/load-balancers/#plans-and-pricing](https://www.digitalocean.com/docs/networking/load-balancers/#plans-and-pricing)

Te ReadApp cloud infrastructure is architected to sustain for high availability using the following practices. Currently operating on Digital Ocean, it will be scaled to AWS where it will be able to use programmable hub to adjust peaks and  increased resource responses:

1. Automatically adjust to points of failure by monitoring network and CPU usage and adding redundant resources and connectivity
2. MultI-AZ (Multiple Availability Zones)-  Application is served from multiple servers from geographical areas that are engineered and insulated from natural disasters. Using Replicas and Cloud Watch filters
3. Scaling - Horizontal Scaling. Enabling ELB using Cloud Watch
4. Self Healing - Using Auto scaling group and Cloud Watch
5. Loose Coupling - Using SQS and Visibility timeout