# K8s_Cluster-Example

Kubernetes Cluster Example 1:
* Backend: Mongo DB.
* Frontend: Mongo Express.
* Secrets and ConfigMaps.
* LoadBalancer Service (I've deployed the cluster in GCP).

Kubernetes Cluster Example 2:
* Backend: Redis Server.
* Frontend: Simple website made with Python + Tornado. Source code [here](https://github.com/jfdona23/DevOps-Challenge/tree/Docker_Version) (credits to CPS team from Tradebyte GmbH). Docker image [here](https://hub.docker.com/_/python).
* Secrets and ConfigMaps.
* Ingress with GCE Ingress Controller.

## Notes
* Kubernetes [issue #82296](https://github.com/kubernetes/kubernetes/issues/82296): Kubernetes tries to parse integers as strings and fails because the lack of quotes. Workaround: surround integers between quotes.