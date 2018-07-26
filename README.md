# kubectl-plugin-containers

Надоело, когда делаешь kubectl exec/logs искать в kubectl describe название
контейнера в поде, а перед этим делать kubectl get po

Копируем в каталог ~/.kube/plugins
Использование `kubectl plugin containers`
Выводит список подов в неймспейсе, с названиями контейнеров справа от них.
