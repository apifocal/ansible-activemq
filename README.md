# Ansible Role: Apache ActiveMQ

An Ansible role for managing [Apache ActiveMQ](http://activemq.apache.org/) on:

* Centos/RHEL 7.x

## Role Variables

Install options:
```
version: 5.15.3
user: activemq
group: activemq
```

## Dependencies

* None
  
## Example Playbook

    - hosts: messaging
      roles:
        - { role: apifocal.activemq }

## License

ALv2
