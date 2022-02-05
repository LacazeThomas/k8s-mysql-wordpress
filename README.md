# k8s-mysql-wordpress


- Edit mysql.yml & wordpress.yml and change ClusterIP `external IP` with your cluster IP

```bash
$ kubectl create namespace wordpress
$ kubectl apply -f ./ -n wordpress
```


If your wordpress won't connect to your MySQL : create wordpress database by your self
