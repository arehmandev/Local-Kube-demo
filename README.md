# Instructions


To create environment ensure minikubes running (minikube start).

```
kubectl create -f .
```

For weavescope:

```
kubectl create -f weave
```

/etc/hosts entries:

```
192.168.99.100 traefik-ui.local
192.168.99.100 stilton.local cheddar.local wensleydale.local
192.168.99.100 cheeses.local weave-scope-app.local
```
