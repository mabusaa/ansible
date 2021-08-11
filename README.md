# ansible playbooks:

## 1. [Test connections](playbooks/test-server-connectivity) : 
To test connections between source of servers and destinations servers on certain port

source of servers are in **hosts.INI** and destination servers are in **destination-servers.yaml file**
   
   ### usage
  ``` ansible-playbook -i hosts.INI playbook.yaml ```
