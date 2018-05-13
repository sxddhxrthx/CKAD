# CKAD
CNCF Certified Kubernetes Application Developer (CKAD)



Online resources that will help you prepare for taking the Certified Kubernetes Application Developer (CKAD) Certification exam.

**Disclaimer:** *This is not likely a comprehensive list as the exam will be a moving target with the fast pace of k8s development - please make a pull request if there something wrong or that should be added, or updated in here.*

* [CNCF Exam Curriculm repository](https://github.com/cncf/curriculum)
* [CKAD Candidate Handbook](https://www.cncf.io/certification/candidate-handbook)
* [CKAD Exam Tips](https://www2.thelinuxfoundation.org/ckad-tips)
* [FAQs](https://www.cncf.io/certification/expert/cka/faq/)


# CKAD Curriculum V1.0

## Core Concepts - 13%
* [Understand kubernetes API Primitives](https://kubernetes.io/docs/concepts/overview/kubernetes-api/)
* [Create and configure basic Pods]()

## Multi-Container Pods - 10%
* [Understand Multi-Container Pod design patterns (e.g: ambassador, adapter, sidecare)](https://kubernetes.io/blog/2015/06/the-distributed-system-toolkit-patterns/)

## Pod Design - 20%
* Understand how to use Labels, Selectors, and Annotations.
* Understand Deployments and how to perform rolling updates.
** [deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
** [rolling updates](https://kubernetes.io/docs/tutorials/kubernetes-basics/update-intro/)
* [Understand Deployments and how to perform rollbacks.]()
* Understand Jobs and CronJobs.

## Configuration - 18%
* Understand ConfigMaps
* Understand SecurityContexts
* Define an application's resources requirements
* Create & consume Secrets
* Understand ServiceAccounts.

## Observability - 18%
* Understand LivenessProbes and ReadinessProbes
* Understand container logging
* Understand how to monitor applications in Kubernetes
* Understand debugging in Kubernetes

## Services & Networking - 13%
* Understand Services
* Demonstrate basic understanding of NetworkPolicies.
