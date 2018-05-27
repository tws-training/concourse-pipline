fly -t lite login -c http://concourse-ci:8080
   
fly -t lite set-pipeline -p concourse-demo -c pipeline.yml

fly -t lite destroy-pipeline -p concourse-demo