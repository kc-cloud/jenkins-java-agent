### jenkins-java-agent

```

- hosts: localhost
  become: yes
  vars:
    worker_ip_address: 172.31.23.128
  roles:
  - jenkins-java-agent

```