
# Demo-Ressourcen JUG Stuttgart 8.11.2018

Benutzung über 
```bash
kubectl apply -f <filename>
```
die deployment-resourcen bauen aufeinander auf

die app-sourcen in der passenden Version findet man unter [cy4n/hello](https://github.com/cy4n/hello/tree/hello-0.0.4-jug)


zur Demo und zum Üben empfiehlt sich Minikube oder docker-for-desktop
(und für das ingress-Beispiel ein "dns"-Eintrag in der /etc/hosts, die verwendete url auf die entsprechende IP von Minikube mapped)

## basis - pod ohne weitere sinnvolle Verwendung :-)
* pod.yml


## basis - deployment mit Aussenanbindung
* deployment.yml
* service.yml
* ingress.yml

## deployment mit health-check
* deployment-health.yml

## deployment mit volume
* config.yml
* deployment-volume.yml

## deployment mit volume und environment-Variablen
* secret.yml
* deployment-env.yml

