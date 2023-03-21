# EKS-test

### Deploying  a nginx container on   Kubernetes using terraform with Replicas and using backend service with Loadbalancer 

### Steps
   1)Install and setup AWS CLI(Configure aws access key and secret key),Terraform,Kubectl and git 
   
   2) Clone the repo 
   
      $git clone git@github.com:gcpkrithi/EKS-test.git
   
      $terraform init 
      $terraform plan 
      $terraform apply
      
      
 ![Screenshot (9)](https://user-images.githubusercontent.com/128479929/226618285-86ddd03c-3f1f-46ec-9b00-557c810e2c38.png)
   
   3)Login to the EKS Cluster 
      
      $aws eks --region us-east-1 update-kubeconfig --name test-eks-cluster
   
 ### Output
 

 ![Screenshot (6)](https://user-images.githubusercontent.com/128479929/226608329-c5da0b0e-5e06-46f9-9c14-997f03d5296f.png)




![Screenshot (8)](https://user-images.githubusercontent.com/128479929/226609871-9896dedb-1789-45a7-8611-816e9f7b7542.png)


![Screenshot (1)](https://user-images.githubusercontent.com/128479929/226609199-19586091-e0cc-464a-9a6c-b8e791a9f66f.png)


![Screenshot (7)](https://user-images.githubusercontent.com/128479929/226609004-094c68a3-8113-45c5-add9-347334e63e7f.png)


![Screenshot (2)](https://user-images.githubusercontent.com/128479929/226606943-9dcaa998-63a0-4d2f-ba94-80ba6791aa02.png)


 
   
