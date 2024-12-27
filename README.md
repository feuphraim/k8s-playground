# 🚀 Kubernetes k8s-playground - Portfolio

Ce repository regroupe des travaux et exercices pratiques réalisés sur Kubernetes. Les fichiers sont organisés par modules, reflétant les compétences acquises sur les principaux sujets de Kubernetes.

---

## 🛠️ Structure des modules

### **1. Core Concepts**
- 🗂️ Exemples de `Pods`, `ReplicaSets`, `Deployments`, et `Namespaces`.
- Gestion des services Kubernetes (ClusterIP, NodePort, LoadBalancer).
- Utilisation des commandes impératives et déclaratives pour la gestion rapide des ressources.

### **2. Scheduling**
- Gestion avancée du scheduling avec :
  - Labels, Selectors, Taints, et Tolerations.
  - Affinités de noeuds et scheduling manuel.
  - Création de `DaemonSets` et de `Static Pods`.

### **3. Logging and Monitoring**
- Configuration du monitoring des composants du cluster.
- Gestion des logs des applications Kubernetes.

### **4. Application Lifecycle Management**
- Gestion des cycles de vie des applications :
  - Rolling updates, rollbacks, et commandes init containers.
  - Configuration des variables d'environnement et secrets.
  - Exemples d’architectures multi-containers.

### **5. Cluster Maintenance**
- Processus d'upgrade des clusters et OS.
- Backup et restauration des clusters avec différentes approches.

### **6. Security**
- Mise en œuvre de pratiques de sécurité :
  - Gestion des certificats, `KubeConfig`, et contrôles RBAC.
  - Politiques réseau, contextes de sécurité et comptes de service.
  - Sécurisation des images Docker.

### **7. Storage**
- Création et gestion de `PersistentVolumeClaims` et `StorageClass`.

### **8. Networking**
- Concepts réseaux dans Kubernetes :
  - Solutions CNI et exploration des environnements.
  - Configuration d'Ingress, `CoreDNS` et services réseaux.

### **9. Install**
- Installation de clusters Kubernetes avec `kubeadm`.

### **10. Troubleshooting**
- Résolution des pannes :
  - Échecs d’applications, du plan de contrôle, et des noeuds.
  - Diagnostic et correction des problèmes réseau.

### **11. Other Topics**
- Utilisation avancée des commandes `kubectl`.
- Exercices avec JSONPath pour l’automatisation.

### **12. Lightning Labs**
- Simulations rapides pour valider les compétences acquises.

---

## 📂 Exemples de structure des dossiers

```plaintext
.
├── core-concepts/
│   ├── pods.yaml
│   ├── deployments.yaml
├── scheduling/
│   ├── taints-tolerations.yaml
│   ├── node-affinity.yaml
├── logging-monitoring/
│   ├── cluster-monitoring.yaml
│   ├── app-logs.yaml
├── security/
│   ├── rbac-config.yaml
│   ├── network-policy.yaml


---

Si vous avez besoin de clarifications ou d'exemples de configuration (YAML, Dockerfile, etc.), dites-le-moi ! 😊