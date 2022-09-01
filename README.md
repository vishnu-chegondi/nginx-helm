# NGINX HELM

This is a sample helm chart of nginx.


## Testing

To use nginx-helm chart in your local kubernetes environment. Connect to your local kubernetes cluster using kubectl and run below steps

### Installing

```
make install
```

### Upgrade

```
make upgrade
```

### Get URL of the nginx

``` sh
# make
make getUrl
```

### Uninstall

```
make uninstall
```