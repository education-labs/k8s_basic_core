본 실습은 AWS 환경에서 진행합니다. 따라서, AWS 계정이 필요하며 비용이 발생합니다.

실습환경
--------

> WorkSpace : AWS Console / AWS Cloud9  
> AWS Region : apnortheast-2 (Seoul)  
> Cluster : AWS EC2 인스턴스 3대로 구성
> 실습 단계 중 표현은 고유한 입력값을 의미 (IP, Name 등)

목차 
----
Ⅰ. 클러스터 배포 (ⅰ, ⅱ 중 택일)
(ⅰ) (AWS)
	Task 1. EC2 배포
	Task 2. Cloud9 배포 및 EC2 접속
	Task 3. Container Runtime/kubeadm/kubectl/kubelet 설치
	Task 4. 클러스터 초기화 및 Master-Worker조인

(ⅱ) (VirtualBox)
	Task 1. 가상머신 만들기
	Task 2. IP 설정 및 Putty 로 접속
	Task 3. Container Runtime/kubeadm/kubectl/kubelet 설치
	Task 4. 클러스터 초기화 및 Master-Worker조인

Ⅱ. Pod 배포
	Task 1. Pod
	Task 2. Namespace
	Task 3. Replicaset
	Task 4. Deployment
	Task 5. Daemonset 
	Task 6. Job, Cronjob

Ⅲ. Pod 통신
	Task 1. Service – ClusterIP
	Task 2. Service – NodePort
	Task 3. Service – LoadBalancer
	Task 4. Ingress

Ⅳ. Pod 관리
	Task 1. Volume – Emptydir
	Task 2. Volume – HostPath
	Task 3. Volume – PV/PVC
	Task 4. ConfigMap/Secret
	Task 5. Statefulset
	Task 6. Role/Rolebinding
	Task 7. LimitRange, ResourceQuota
	Task 8. Autoscaling for HPA
