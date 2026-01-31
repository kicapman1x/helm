# helm

helm template $GIT_HOME/helm/load-gen --debug

helm install load-gen $GIT_HOME/helm/load-gen

helm upgrade load-gen $GIT_HOME/helm/load-gen