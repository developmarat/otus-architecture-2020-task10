# Deploy
kubectl apply -f delivery/config.yaml -f delivery/deployment.yaml -f delivery/postgres.yaml -f delivery/initdb.yaml -f delivery/service.yaml -f delivery/ingress.yaml -f order/config.yaml -f order/deployment.yaml -f order/postgres.yaml -f order/initdb.yaml -f order/service.yaml -f order/ingress.yaml -f payment/config.yaml -f payment/deployment.yaml -f payment/postgres.yaml -f payment/initdb.yaml -f payment/service.yaml -f payment/ingress.yaml -f store/config.yaml -f store/deployment.yaml -f store/postgres.yaml -f store/initdb.yaml -f store/service.yaml -f store/ingress.yaml

#Паттерн распределенной транзакции
##Сага - оркестратор
