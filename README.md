## VM Credentials Link

https://docs.google.com/spreadsheets/d/11rwHIRc9titt_4bgqauJRBTAdBTmct5Hfy1bdGLn6bg/edit?usp=sharing


## AWS CLI Installation Command

  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
  
  unzip awscliv2.zip
  
  sudo ./aws/install


## EKS Cluster Connection Commands

  aws eks --region us-east-1 describe-cluster --name hksCluster --query cluster.status

  aws eks --region us-east-1 update-kubeconfig --name hksCluster


## KUBERNETES Swith Context

  kubectl config use-context minikube


## QUIZ-1 Leadbaord

<img width="1116" height="684" alt="image" src="https://github.com/user-attachments/assets/7552dba3-4779-4158-a0cc-841fffae9bc1" />

