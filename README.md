## Deployment


To deploy the ELK please spceify the IP in `inventory.ini` and ssh key file path in `ansible.cfg` then run following command from `ansible` directory:


```
ansible-playbook -i inventory.ini elk.yaml
```

After successfull passing the ansible tasks you will be able to get Kibana page on `http://SPECIFIED_IP:5601` link
