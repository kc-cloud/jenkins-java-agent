### jenkins-java-agent

```

- hosts: localhost
  become: yes
  vars:
    agent_ip_address: 172.31.23.128
  roles:
  - jenkins-java-agent

```