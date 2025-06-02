 🚀 Build a Kubernetes Cluster Locally with Minikube

📌 Objective
Understand the basics of Kubernetes by deploying and managing a simple app using Minikube on your local machine.



 🛠 Tools Used
- Minikube – For running a local Kubernetes cluster
- kubectl – To manage Kubernetes resources
- Docker – To pull and run container images (like Nginx)



 📁 Files Included
- `deployment.yaml` – Defines an Nginx deployment with 2 replicas
- `service.yaml` – Exposes the Nginx app using NodePort



📄 Steps Performed

1. Installed **Minikube** and started the local cluster:
   ```bash
   minikube start


2. Created a **Deployment** using `deployment.yaml`:

   ```bash
   kubectl apply -f deployment.yaml
   ```

3. Created a **Service** using `service.yaml` to expose the app:

   ```bash
   kubectl apply -f service.yaml
   ```

4. Verified the running pods and services:

   ```bash
   kubectl get pods
   kubectl get services
   ```

5. Opened the app in the browser using Minikube:

   ```bash
   minikube service nginx-service
   ```




All relevant YAML files are included in this repository. Ready for review and submission.

```

If you want, I can also help you add instructions on how to push this to GitHub!
```
