#  Learn About Minikube [^1]

[^1]: A second-level heading 
- [^1.1] terms
- [^1.2] Minikube Questions
- [^1.3] Command lines

[^1.1]: Principal Terms 
- The term `Master node` are same `Control Plane`
* 
+

[^1.2]:Questions
What is Minikube? **Minikube** is one Node  is a tool that enables you to run a single-node Kubernetes cluster locally on your machine
What is Kubectl? **Kubectl** is Commend line tool for a cluster configuration.

[^1.3]: Command Lines 
**Command Start minikube** `minikube start --driver docke`
**Verify Status of minikube** `minikube status`

Info Note
> If you desire use other drive just change name in --driver 
1. Hypervisor avaliable:
   - VirtualBox: If you're using VirtualBox as your hypervisor, open-source virtualization platform.
   - KVM: For Linux systems, you can use KVM (Kernel-based Virtual Machine) as the hypervisor.
   - HyperKit: If you're on macOS, you can use HyperKit as the hypervisor. 
   - Hyper-V: If you're using Windows 10 or Windows Server 2016
   - Docker: Minikube also provides an option to run Kubernetes directly on your local Docker engin


Installation and Creation Minikube [Minikube Documentation](https://kubernetes.io/fr/docs/tasks/tools/install-minikube/).


