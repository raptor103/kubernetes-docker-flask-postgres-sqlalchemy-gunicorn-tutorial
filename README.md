1. Build docker image  
2. Push to dockerhub  
3. Run kubectl apply -f deployment.yaml  
4. If running k8s locally, run "minikube service flask-service" to expose url  
Home page is health, URL/test_db retrieves from DB.  

Forked from:  
"https://medium.com/@mudasiryounas/kubernetes-docker-flask-postgres-sqlalchemy-gunicorn-deploy-your-flask-application-on-57431c8cbd9f" 

