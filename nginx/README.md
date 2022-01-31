## Create nginx helm deployment

```code
helm create nginx

```

## Deploy to k8s cluster

```code
helm upgrade -i nginx nginx -n nginx --create-namespace
```
