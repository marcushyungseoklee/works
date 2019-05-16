# works with Trouble shooting lists

[Kubectl Trouble shooting]

1. kubectl 명령 입력시

The connection to the server 192.168.99.104:8443 was refused - did you specify the right host or port?

-> export KUBECONFIG=/etc/kubernetes/admin.conf 입력

2. 서버 connection 에러시

 - 클러스터를 재 생성하거나
  - kubectl config view 에서 server의 ip 정보를 확인한 후
  - kubectl set-cluster [Name] server의 정보를 
