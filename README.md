# argoCD demo setup

Follow [this](https://argo-cd.readthedocs.io/en/stable/getting_started/) well written getting started guide by ArgoCD developers for setting up argoCD on your local cluster.

To install apps declaratively, please refer to [declarative-app.yaml](declarative-app.yaml) file which installs guestbook application by setting up basic project.

Note: Installing apps via helm chart needs extra step of [adding repositories for non standard helm charts](https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/#helm-chart-repositories).

### TODO
- Update [declarative-app.yaml](declarative-app.yaml) file to deploy public and private applications using [app of apps pattern](https://argo-cd.readthedocs.io/en/stable/operator-manual/cluster-bootstrapping/#app-of-apps-pattern).
- Install argoCD application via the helm chart in this repository.
- Update README.
