### Ejecutar los manifiestos

```sh
# Crea namespace
$ k apply -f namespace.yaml

# Despliega un pod simple nginx
$ k apply -f pod.yaml

# Elimina el pod
$ k delete -f pod.yaml

# Despliega un deployment con 2 replicas y un service
$ k apply -f nginx.yaml
```