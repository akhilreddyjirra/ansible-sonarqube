# ansible-sonarqube

## tested Environment  

#### centOS 7.5  Postgres 9.6  Sonarversion 6.7.4  Java 1.8JDK

Before apply playbook

`ssh-keygen -t rsa`

`cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys`

`chmod og-wx ~/.ssh/authorized_keys`

`ansible-playbook -i inventory.ini playbook.yml`
