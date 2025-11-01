### Enable model registry

**Red Hat OpenShift AI Operator -> Data Science Cluster**

```
 modelregistry:
    managementState: Managed
    registriesNamespace: rhoai-model-registries
```

### Create MariaDB

```
oc apply -f mariadb.yaml
```

### Create model registry

**OpenShift AI dashboard -> Settings  -> Model registry settings**

![image-20251101192543979](assets/image-20251101192543979.png)

![image-20251101192651735](assets/image-20251101192651735.png)

![image-20251101192807713](assets/image-20251101192807713.png)