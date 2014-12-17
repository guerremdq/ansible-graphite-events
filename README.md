Send events to Graphite using Ansible
=====================================

* Example
```yaml
  tasks:
  - name: "Send Graphite Event"
    graphite_event: url="http://graphite.example.com/events/" msg="Test Ansible" tags="test"
```
* Run Example playbook
```shell
ansible-playbook -i inventory main.yaml 
```
