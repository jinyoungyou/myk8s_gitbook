# Table of contents

* [Kubernetes](README.md)
* [1.Kubernetes 개념](kubernetes-concept/README.md)
  * [Overview](kubernetes-concept/overview.md)
  * [Cluster Architecture](kubernetes-concept/cluster-architecture/README.md)
    * [노드](kubernetes-concept/cluster-architecture/node.md)
    * [컨트롤플레인과 노드간 통신](kubernetes-concept/cluster-architecture/control-plane-node-communication.md)
    * [컨트롤러](kubernetes-concept/cluster-architecture/controller.md)
    * [클라우드 컨트롤러 매니저](kubernetes-concept/cluster-architecture/cloud-controller-manager.md)
  * [Containers](kubernetes-concept/containers/README.md)
    * [이미지](kubernetes-concept/containers/images.md)
    * [컨테이너 소개](kubernetes-concept/containers/container-overview.md)
    * [런타임클래스](kubernetes-concept/containers/runtime-class.md)
    * [컨테이너 환경변수](kubernetes-concept/containers/container-environments.md)
    * [컨테이너 라이프사이클 훅](kubernetes-concept/containers/container-lifecycle-hooks.md)
  * [Workloads](kubernetes-concept/workloads/README.md)
    * [Pod](kubernetes-concept/workloads/pod/README.md)
      * [Pod 개요](kubernetes-concept/workloads/pod/pod-overview.md)
      * [Pod](kubernetes-concept/workloads/pod/pod-overview-1.md)
      * [Pod LifeCycle](kubernetes-concept/workloads/pod/pod-lifecycle.md)
      * [컨테이너 초기화](kubernetes-concept/workloads/pod/init-containers.md)
      * [Pod 프리셋](kubernetes-concept/workloads/pod/pod-preset.md)
      * [파드 토폴로지 분배 제약 조건](kubernetes-concept/workloads/pod/pod-topology-spread-constraints.md)
      * [Untitled](kubernetes-concept/workloads/pod/untitled.md)
    * [Controller](kubernetes-concept/workloads/controller.md)
  * [Service-LB-Networking](kubernetes-concept/service-lb-networking.md)
  * [Storage](kubernetes-concept/storage.md)
  * [Configuration](kubernetes-concept/configuration.md)
  * [Security](kubernetes-concept/security.md)
  * [Policies](kubernetes-concept/policies.md)
  * [Scheduling and Eviction](kubernetes-concept/scheduling-and-eviction.md)
  * [Cluster Admin](kubernetes-concept/cluster-admin.md)
  * [Extending Kubernetes](kubernetes-concept/extending-kubernetes.md)
* [2.EKS 환경 구성](eks/README.md)
  * [Cloud9 IDE 환경 구성](eks/cloud9-ide.md)
  * [인증/자격증명 및 환경 구성](eks/env-auth.md)
* [3.VPC구성과 eksctl 기반 설치](vpc-eksctl/README.md)
  * [Cloudformation 구성](vpc-eksctl/cloudformation.md)
  * [eksctl 구성](vpc-eksctl/eksctl.md)
  * [EKS 구성확인](vpc-eksctl/eksconfig.md)
* [4.EKS Service 이해](eks-1/README.md)
  * [Cluster IP 기반 배포](eks-1/cluster-ip.md)
  * [NodePort 기반 배포](eks-1/nodeport.md)
  * [Loadbalancer 기반 배포](eks-1/loadbalancer.md)
* [5.EKS Ingress](5.eks-ingress/README.md)
  * [AWS Load Balancer Controller](5.eks-ingress/alb-ingress.md)
* [6.EKS 기반 관리](eks-2/README.md)
  * [패키지 관리 - Helm](eks-2/helm.md)
  * [고가용성 Health Check 구성](eks-2/health-check.md)
  * [Assign](eks-2/assign.md)
  * [테인트와 톨러레이션 (TBD)](eks-2/taints\_tolerations.md)
  * [스케쥴링 - AutoScaling 구성](eks-2/autoscaling.md)
  * [스케쥴링-Karpenter](eks-2/karpenter.md)
* [7.Observability](observability/README.md)
  * [K8s Dashboard 배포](observability/k8s-dashboard.md)
  * [Prometheus-Grafana](observability/prometheus-grafana.md)
  * [EFK기반 로깅](observability/efk-logging.md)
  * [Container Insights](observability/container-insights.md)
  * [X-Ray기반 추적](observability/xray.md)
* [8. EKS Networking](eks-networking/README.md)
  * [Multus](eks-networking/untitled.md)
  * [VPC Advanced](eks-networking/vpc-advanced.md)
  * [External SNAT (TBD)](eks-networking/external-snat.md)
* [9.EKS Storage](eks-storage/README.md)
  * [볼륨](eks-storage/volume.md)
  * [Stateful Container-EBS](eks-storage/stateful-container.md)
  * [Stateful Container-EFS (TBD)](eks-storage/stateful-container-efs.md)
* [10.EKS Security](eks-security/README.md)
  * [RBAC](eks-security/rbac.md)
  * [IAM 그룹 기반 관리](eks-security/iam\_group.md)
  * [IRSA (IAM Roles for Service Account)](eks-security/service\_account.md)
  * [Pod Security (TBD)](eks-security/pod\_security.md)
  * [KMS 기반 암호화 (TBD)](eks-security/kms\_security.md)
  * [Calico 네트워크 정책](eks-security/calico-networking.md)
* [11.EKS CI/CD](eks-cicd/README.md)
  * [Code Pipeline기반 CI/CD](eks-cicd/cicd-w-codepipeline.md)
  * [Jenkins 배포 (TBD)](eks-cicd/jenkins-deploy.md)
  * [WEAVE Flux 기반 GitOps (TBD)](eks-cicd/gitops-w-weave-flux.md)
  * [Argo 기반 CD](eks-cicd/argo-cd.md)
* [12.EKS Service Mesh](eks-security/eks-service-mesh/README.md)
  * [Istio](eks-service-mesh/istio/README.md)
    * [Istio 소개](eks-service-mesh/istio/istio\_overview.md)
    * [istio 설치와 구성](eks-service-mesh/istio/page-4.md)
    * [istio 트래픽 관리 1](eks-service-mesh/istio/istio-1.md)
    * [istio 모니터링](eks-service-mesh/istio/istio-2.md)
    * [Page 1](eks-service-mesh/istio/page-1.md)
  * [App Mesh (TBD)](eks-security/eks-service-mesh/app-mesh.md)
* [12.Tip](tip/README.md)
  * [shell](tip/shell.md)
  * [git\_source](tip/git-source.md)
  * [aws cli](tip/aws-cli.md)
  * [eksctl command](tip/eksctl-command.md)
  * [kubectl Command](tip/kubectl-command.md)
  * [helm command](tip/helm-command.md)
  * [Useful URL](tip/useful-url.md)
