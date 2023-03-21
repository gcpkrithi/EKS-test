# EKS-test

### Steps
   1)Install AWS CLI,Terraform,Kubectl and git 
   2) Clone the repo 
      $git clone git@github.com:gcpkrithi/EKS-test.git
   
      $terraform init 
      $terraform plan 
      $terraform apply
   
   3)Login to the EKS Cluster 
      
      $aws eks --region us-east-1 update-kubeconfig --name test-eks-cluster
   
 # Output 

   
![Screenshot (1)](https://user-images.githubusercontent.com/128479929/226606495-f0e1f9ba-576a-4e81-93cb-687d8445891b.png)

 
   
