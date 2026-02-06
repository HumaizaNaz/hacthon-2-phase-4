Phase IV: Local Kubernetes Deployment (Minikube, Helm 
Charts, kubectl-ai, Kagent, Docker Desktop, and Gordon) 
Cloud Native Todo Chatbot with Basic Level Functionality 
Objective: Deploy the Todo Chatbot on a local Kubernetes cluster using Minikube, Helm 
Charts. 
Requirements 
• Containerize frontend and backend applications (Use Gordon) 
• Use Docker AI Agent (Gordon) for AI-assisted Docker operations 
• Create Helm charts for deployment (Use kubectl-ai and/or kagent to generate) 
• Use kubectl-ai and kagent for AI-assisted Kubernetes operations 
• Deploy on Minikube locally 
Note: If Docker AI (Gordon) is unavailable in your region or tier, use standard Docker CLI 
commands or ask Claude Code to generate the docker run commands for you. 
Technology Stack 
Component 
Technology 
Containerization 
Docker AI 
Orchestration 
Package Manager 
Docker (Docker Desktop) 
Docker AI Agent (Gordon) 
Kubernetes (Minikube) 
Helm Charts 
AI DevOps 
Application 
AIOps 
kubectl-ai, and Kagent 
Phase III Todo Chatbot 
Use Docker AI Agent (Gordon) for intelligent Docker operations: 
# To know its capabilities 
docker ai "What can you do?" 
Enable Gordon: Install latest Docker Desktop 4.53+, go to Settings > Beta features, and 
toggle it on. 
Use kubectl-ai, and Kagent for intelligent Kubernetes operations: 
# Using kubectl-ai 
kubectl-ai "deploy the todo frontend with 2 replicas" 
kubectl-ai "scale the backend to handle more load" 
kubectl-ai "check why the pods are failing" 
# Using kagent 
kagent "analyze the cluster health" 
kagent "optimize resource allocation" 
Starting with kubectl-ai will make you feel empowered from day one. Layer in Kagent for 
advanced use cases. Pair them with Minikube for zero-cost learning and work. 
Research Note: Using Blueprints for Spec-Driven Deployment 
Can Spec-Driven Development be used for infrastructure automation, and how we may need 
to use blueprints powered by Claude Code Agent Skills. 
Page 22 of 38 
Hackathon II: Spec-Driven Development 
1. Is Spec-Driven Development Key for Infrastructure Automation? 
2. ChatGPT Progressive Learning Conversation 
3. Spec-Driven Cloud-Native Architecture: Governing AI Agents for Managed Services 
with Claude Code and SpecKit