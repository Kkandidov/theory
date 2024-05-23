<details>
<summary>1. What is Kubernetes</summary> 

#
Kubernetes is a portable, extensible, open-source platform for managing containerized workloads that facilitates both declarative configuration and automation. Kubernetes has a large, rapidly growing ecosystem. Additionally, Kubernetes offers highly available services, support, and tools.
</details>

![going back in time](https://kubernetes.io/images/docs/Container_Evolution.svg)

<details>
<summary>2. Tell about a traditional deployment era</summary> 

#
Early on, applications were deployed directly on physical servers, also known as bare metal. At that time, there was no way to define clear resource boundaries between applications running on the same server. This led to resource allocation issues, where one application could consume most of the resources, causing performance problems for others. As a result, the only solution at the time was to allocate each application a separate server. However, this approach had two major drawbacks. Firstly, it wasn't scalable because resources were underutilized. Secondly, maintaining many physical servers was extremely expensive for organizations.
</details>

<details>
<summary>3. Tell about the virtualization deployment era</summary> 

#
Virtualization emerged to address the limitations of the traditional deployment approach. It allows running multiple applications on the same physical server, each in its own isolated environment. This isolation reduces security risks by preventing information from one application in a VM from reaching another application in a different VM on the same server. Virtualization also improves scalability. VMs can be easily added or removed based on resource needs, making it more efficient to utilize hardware resources. This translates to cost savings as you don't need to maintain as many physical servers. In essence, virtualization allows you to present a pool of physical resources as a cluster of manageable VMs.
</details>
