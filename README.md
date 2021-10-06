# durable-function-aks
See for yourself :)
Well also...this is to make durable functions run in AKS. The yaml generated with "func kubernetes ..." gives you two deployments for the http and activities, which doesn't work. So here you have a modified yaml :)



```
func kubernetes deploy --name durable --registry kostapetan.acr.io --namespace durable --write-configs
```
