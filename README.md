This is an example how to roll out configs to Flussonic servers:

ingest --> dvr --> edge

* Use your own inventory in the hosts.ini
* Add new stream in the all.yml
* Run playbook:
```
ansible-playbook -i hosts.ini deploy.yml
```
