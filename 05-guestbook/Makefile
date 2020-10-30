redis-slave-svc:
	kubectl apply -f https://k8s.io/examples/application/guestbook/redis-slave-service.yaml

clean:
	kubectl delete deploy redis-master
	kubectl delete deploy redis-slave
	kubectl delete svc redis
	kubectl delete deploy frontend
	kubectl delete svc frontend
	kubectl delete ingress frontend-ingress
	sleep 5
	kubectl get po