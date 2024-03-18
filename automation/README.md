# automation
ansible playbook

#tags
 helm
 calico
 istio
 argocd
 argocd_password
 k8sdashboard
 k8sdashboard_token
 keda
 keycloak
 prometheus/grafana
 kubescape
 open5g
 jaeger
 k9s

 #use below commands to run playbook 
 # To deploy 
 ansible-playbook deploy.yaml -t usetags
 example: ansible-playbook deploy.yaml -t helm
 # To cleanup
 ansible-playbook cleanup.yaml -t usetags
 example: ansible-playbook cleanup.yaml -t helm
 
