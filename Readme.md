Helm Basic Chart
===

Basic Helm Chart for Acend training.

Install Helm chart
`helm install myrelease ./helm-basic-chart  --namespace <namespace>`

Upgrade chart
`helm upgrade myrelease ./helm-basic-chart --namespace <namespace>`


Render chart locally
`helm template myrelease ./helm-basic-chart --output-dir rendered`


Uninstall chart
`helm delete myrelease  --namespace <namespace>`