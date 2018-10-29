<!-- $theme: gaia -->

![](images/ITS-Group-Logo.png "not_found")
Kubernetes
![center 40%](images/logo_kubernetes.jpeg "not_found")
===
#### Sébastien Jardin :fr: - DevOps :metal: ####
#### Oct. 2018 ####

---
# Définition :book: #
>L'orchestration décrit le processus automatique d'organisation, de coordination, et de gestion de systèmes informatiques complexes, de middleware et de services.
>
> <small>-- *[Orchestration Informatique - Wikipedia, the free encyclopedia](https://fr.wikipedia.org/wiki/Orchestration_informatique)*</small>
> 
---
# Historique :books: #

Créer par une petite Startup du nom de Google...
![center 80%](images/logo_google.png "not_found")

- Dev en mi-2014
- Créer en 2015
---
# Adhésion :heart: #

![center 80%](images/logo_cncf.png "not_found")
![center 40%](images/logo_openshift.svg "not_found")
![center 18%](images/logo_rancher.png "not_found")

---
# Nouveautés :newspaper: #

- Open Source
- Orienté infrastructure
- Normé
- Interopérable
- Operators
- API
 
---
# Hosting :computer: #

Choix très nombreux : Cloud, Saas, On-Premise

- GCP - GKE
- AWS - EKS
- Digital Ocean
- OVH
- Ikoula
- Azure
- OpenStack
---
# Infrastrucure #

![center](images/kubernetes_archi.png "not_found")


---
# Déclaratif :hammer: #
Yaml for ever
```
apiVersion: v1
kind: Pod
metadata:
  name: myapp-pod
  labels:
    app: myapp
spec:
  containers:
  - name: myapp-container
    image: busybox
    command: ['sh', '-c', 'echo Hello Kubernetes!']

```
---
# Exploitation :cyclone: #

```
$ kubectl create -f /dir/Mydir/MyProject/nginx-app.yaml
service/my-nginx-svc created
deployment.apps/my-nginx created
```
<br />

![center](images/logo_helm.png "not_found")

---

# Documentation #

Site Officiel : [kubernetes.io](https://kubernetes.io/docs)
Pour débuter : [The illustrated Children's Guide to Kubernetes](https://cdn.chrisshort.net/The-Illustrated-Childrens-Guide-to-Kubernetes.pdf)

![center 40%](images/children_kubernetes.png "not_found")

---
# Merci :pray: #
## Des questions :question: ##
<br />

![center 55%](images/question.jpg "not_found")

<br />

Créer avec [Marp](https://yhatt.github.io/marp/) en Markdown, Libre et gratuit !


<!-- $theme: gaia -->

