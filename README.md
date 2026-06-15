## VM Credentials Link

https://docs.google.com/spreadsheets/d/11rwHIRc9titt_4bgqauJRBTAdBTmct5Hfy1bdGLn6bg/edit?usp=sharing


## AWS CLI Installation Command

  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
  
  unzip awscliv2.zip
  
  sudo ./aws/install


## EKS Cluster Connection Commands

  aws eks --region us-east-1 describe-cluster --name hksCluster --query cluster.status

  aws eks --region us-east-1 update-kubeconfig --name hksCluster
