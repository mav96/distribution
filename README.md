[See help](https://community.online.net/t/docker-registry-with-object-storage/6963/4)

Generation password
```bash
htpasswd -Bbn  registry P@SSW0RD
```

Add hash to registry_env.yaml, see ConfigMap
#
Deploy registry
```bash
kubectl apply -f registry_env.yaml
```

