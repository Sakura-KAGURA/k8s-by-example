#
# Link
http://kubernetesbyexample.com/pods/
# TL;DR

#
```
 kubectl run sise --image=mhausenblas/simpleservice:0.5.0 --port=9876
```
error failed to discover supported resources: Unauthorized
ポートが開いていない？
ポートを変えてもエラー

kubectl run httpd 

kubectl get pods

kubectl describe pod sise-3210265840-k705b | grep IP:

curl 172.17.0.3:9876/info

