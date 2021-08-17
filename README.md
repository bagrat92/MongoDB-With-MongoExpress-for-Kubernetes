# MongoDB-With-MongoExpress-for-Kubernetes
MongoDB With MongoExpress for  Kubernetes


1. First step We need create Kubernetes Cluster (I'm using GCP)

   gcloud container clusters create "cluster_name"

2. After that we have to deploy our yaml files one by one

   kubectl apply -f secret.yaml
   kubectl apply -f mongo.yaml
   kubectl apply -f mongo-configmap.yaml
   kubectl apply -f mongo-express.yaml
 
3. Done. 
   Congratulations.!!! 
   You have create your MongoDB.

4.  The END...!!!
