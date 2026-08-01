<h1 align="center">Hi, I'm Dinesh Ninavath 👋</h1>

<p align="center">
  <b>Cloud &amp; DevOps Engineer</b><br>
  AWS &bull; Azure &bull; Kubernetes &bull; Terraform
</p>

<p align="center">
  Infrastructure as Code &bull; CI/CD Pipelines &bull; Containers &bull; Kubernetes
</p>

<!-- Social / profile badges -->
<p align="center">
  <a href="https://www.linkedin.com/in/dineshninavath">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/dinesh4567">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=dinesh4567&label=Profile%20views&color=0A66C2&style=flat" alt="Profile views" />
</p>

---

## 👨‍💻 About Me

- 📍 Based in London, United Kingdom
- ☁️ Building production-style AWS and Azure DevOps projects
- 🛠️ Working with Terraform, Jenkins, Docker, Kubernetes, Helm and Argo CD
- 🔐 Practising CI/CD, DevSecOps, monitoring and cloud troubleshooting
- 🎓 MBA in International Business — University of Greenwich
- 🎓 B.Tech in Electronics and Communication Engineering

---

## 🧰 Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,terraform,docker,kubernetes,jenkins,githubactions,prometheus,grafana,linux,bash,python&theme=light" alt="Tech stack icons" />
</p>

| Category | Tools |
|---|---|
| **Cloud** | AWS, Microsoft Azure |
| **Infrastructure as Code** | Terraform |
| **Containers** | Docker, Docker Compose |
| **Orchestration** | Kubernetes, EKS, AKS, Helm |
| **CI/CD** | Jenkins, Argo CD |
| **DevSecOps** | SonarQube, Trivy |
| **Monitoring** | Prometheus, Grafana |
| **Registries** | Amazon ECR, Azure Container Registry |
| **Operating Systems** | Linux, Windows, WSL |
| **Scripting** | Python, Bash |

*Currently exploring: GitHub Actions, Nexus, OWASP Dependency-Check.*

---

## 🚀 Featured Projects

### ☁️ [Digital Library — Microservices on AWS EKS](https://github.com/dinesh4567/AWS-Python-microservices-app)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat&logo=amazoneks&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat&logo=argo&logoColor=white)

Four Python Flask microservices plus a MySQL backend, deployed on Amazon EKS.
VPC and cluster provisioned with Terraform. Jenkins pipeline runs SonarQube quality
gates and Trivy image scans, publishes to ECR, and deploys via Helm. Argo CD keeps
the cluster in sync from Git, with Prometheus and Grafana for monitoring.

📐 Includes architecture diagrams and **12 labelled deployment screenshots** as proof of a working deployment.

**[→ View the project](https://github.com/dinesh4567/AWS-Python-microservices-app)**

<br>

### 🔷 [Digital Library — Platform on Azure AKS](https://github.com/dinesh4567/digital-library-azure-aks)

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AKS](https://img.shields.io/badge/AKS-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![ACR](https://img.shields.io/badge/ACR-0078D4?style=flat&logo=microsoftazure&logoColor=white)

The same microservices platform rebuilt on Azure — Terraform-provisioned AKS cluster
and ACR, Jenkins pipeline with SonarQube quality gates and Trivy scanning. Includes a
side-by-side comparison of how the equivalent architecture maps across AWS and Azure.

**[→ View the project](https://github.com/dinesh4567/digital-library-azure-aks)**

<br>

### 🩸 [Blood Bank — PHP Application on Kubernetes](https://github.com/dinesh4567/php-bloodbank-kubernetes)

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

My most complete Kubernetes manifest set: StatefulSet with persistent storage, headless
Service, Ingress, HorizontalPodAutoscaler, NetworkPolicy with ingress *and* egress rules,
PodDisruptionBudget and ResourceQuota. Documents the security and correctness fixes
applied along the way.

**[→ View the project](https://github.com/dinesh4567/php-bloodbank-kubernetes)**

<br>

### ☕ [Java Web App — Docker Swarm and Kubernetes](https://github.com/dinesh4567/java-webapp-docker-swarm-k8s)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

A Spring MVC application deployed two ways — as a replicated Docker Swarm stack over an
overlay network, and as a Kubernetes workload with a StatefulSet-backed database.

**[→ View the project](https://github.com/dinesh4567/java-webapp-docker-swarm-k8s)**

<br>

### 🎮 [React Tetris on Amazon EKS](https://github.com/dinesh4567/tetris-eks-jenkins)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat&logo=amazoneks&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

Containerised React app on EKS, with both the cluster and the Jenkins build server
provisioned by Terraform.

**[→ View the project](https://github.com/dinesh4567/tetris-eks-jenkins)**

<br>

### 🏗️ [Terraform AWS Infrastructure via Jenkins](https://github.com/dinesh4567/terraform-jenkins-aws-pipeline)

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

A Jenkins pipeline provisioning EC2 and S3 with Terraform, gated by SonarQube analysis
and a Trivy scan. Parameterised so one job runs both `apply` and `destroy`.

**[→ View the project](https://github.com/dinesh4567/terraform-jenkins-aws-pipeline)**

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dinesh4567&hide_border=true&ring=0A66C2&fire=0A66C2&currStreakLabel=0A66C2" alt="GitHub streak" />
</p>

---

## 🎯 Current Focus

- 🔍 Improving Kubernetes troubleshooting
- 📦 Building reusable Terraform modules
- 🏗️ Strengthening AWS and Azure architecture knowledge
- 💼 Preparing for Cloud and DevOps engineering interviews

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/dineshninavath">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/dinesh4567">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
