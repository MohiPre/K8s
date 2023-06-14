# counter-app
Simple flask app that counts web site visits and stored in a default Redis backend. Used in Docker Deep Dive book
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

```
kubectl apply -f webapp.yaml - will create a deployment and service object for our frontend 

kubectl apply -f redis.yaml - will create a deployment and service for database to cache the hitcount

'''

