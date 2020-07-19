# K8s_Cluster-Example

Kubernetes Cluster Example 1:
* Backend: Mongo DB.
* Frontend: Mongo Express.
* Secrets and ConfigMaps.
* Services (ClusterIP and LoadBalancer).

Kubernetes Cluster Example 2:
* Backend: Redis Server.
* Frontend: Simple website made with Python + Tornado. Source [here](https://github.com/jfdona23/DevOps-Challenge).
* Secrets and ConfigMaps.

## Notes
* Kubernetes [issue #82296](https://github.com/kubernetes/kubernetes/issues/82296): Kubernets tries to parse integers as strings and fails because the lack of quotes. Workaround: surround integers between quotes.