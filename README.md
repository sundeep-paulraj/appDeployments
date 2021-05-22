# app-deployments
repo for kubernetes manifests

# References 
- https://cloud.google.com/kubernetes-engine/docs/tutorials/gitops-cloud-build

docker.elastic.co/beats/filebeat:7.12.1

.
├── LICENSE
├── README.md
└── blog
    ├── base
    │   ├── createNameSpace.yaml
    │   ├── deployment.yaml
    │   ├── kustomization.yaml
    │   └── service.yaml
    └── overlays
        ├── dev
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   └── service.yaml
        ├── local
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   └── service.yaml
        ├── prd
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   └── service.yaml
        ├── stg
        │   ├── deployment.yaml
        │   ├── kustomization.yaml
        │   └── service.yaml
        └── stgReleaseCandidate
            ├── deployment.yaml
            ├── kustomization.yaml
            └── service.yaml

