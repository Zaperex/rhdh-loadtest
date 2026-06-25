CHART_NAME = rhdh-loadtests-18
NAMESPACE = rhdh-loadtests-18

install:
	helm upgrade --install $(CHART_NAME) . --create-namespace --namespace $(NAMESPACE) --values values.yaml

delete:
	helm uninstall $(CHART_NAME) --namespace $(NAMESPACE)

update-dependencies:
	helm dependency update
