1. criar cluster: kind create cluster --name=esquenta    
2. rodar os comandos no contexto: kubectl cluster-info --context kind-esquenta
3. carregar nodes: kubectl get nodes
4. carregar pods: kubectl get pods
5. aplicar mudancas nos pods:  kubectl apply -f .\pod.yaml
6. mapear porta (do pod para maquina): kubectl port-forward pod/<POD_NAME> <MAQ_PORT>:<POD_PORT>