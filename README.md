# argoCD demo setup

Follow [this](https://argo-cd.readthedocs.io/en/stable/getting_started/) well written getting started guide by ArgoCD developers for setting up argoCD on your local cluster.

To install apps declaratively, please refer to [declarative-app.yaml](declarative-app.yaml) file which installs guestbook application by setting up basic project.

Note: Installing apps via helm chart needs extra step of [adding repositories for non standard helm charts](https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/#helm-chart-repositories).

### TODO
- Install private helm chart.
- Update README.
