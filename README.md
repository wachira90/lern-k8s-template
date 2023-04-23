# lern-k8s-template

## quick start

linux current user => user1

```bash
cd /var
sudo git clone https://github.com/wachira90/lern-k8s-template.git
sudo mv lern-k8s-template/ website/
sudo chmod -R 0775 /var/website && sudo chown -R user1:root /var/website
cd website/
kubectl apply -f . -n test
```

## delete

```bash
kubectl delete -f . -n test
```

## test

```
http://localhost:30000
```
