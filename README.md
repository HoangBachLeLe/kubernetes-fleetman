# Kubernetes Fleetman

**_NOTE:_** The materials are from Udemy course "Kubernetes Hands-On - Deploy Microservices to the AWS Cloud" by Richard Chesterwood

---

| Service                 | Port  | Notes                        |
| ----------------------- | ----- | ---------------------------- |
| Frontend                | 30080 |                              |
| Apache ActiveMQ (queue) | 30010 | user: admin, password: admin |
| Api Gateway             | 30020 |                              |

---

## Helpful commands

```bash
minikube start --no-vtx-check
minikube ip
```

```bash
source <(kubectl completion bash)
echo "source <(kubectl completion bash)" >> ~/.bashr
alias k=kubectl
complete -o default -F \_\_start_kubectl k
```
