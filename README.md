1 :fleet.yaml
    This is the master config that tells Rancher to deploy everything sitting next to it into your dev and qa namespaces.
2: flightctl-backend.yaml
    Only your Backend Jenkins job will edit this file.
3: flightctl-ui.yaml
    Only your UI Jenkins job will edit this file.
4: webhook-job.yaml
    This tells K3s to ping Jenkins when the pods are running.
