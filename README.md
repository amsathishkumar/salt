# salt
Salt commands
•	salt-call --local --out key pillar.item deployment_types:viewing-history
•	salt-call -l debug --local --log-file /tmp/oc_$(date +%Y%m%d_%H%M%S).log state.sls dmp
•	salt-call --local --out key pillar.items
•	salt-call --local --out key pillar.item schedule_deployment_flavor
•	service salt-master status
