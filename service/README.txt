Service:
    Service to intract with other set of pods to serve as front-end or back-end or any other
    Below templates are used to test NodePort type
        Single Pod on single node to test the application accessible external

deployment-def.yaml template has replicaset, Deployment and pods with required container image
service-def.yaml is testing the NodePort service type and this template is dependent on deployment-def file
