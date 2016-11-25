# Ansible role: scala
Installs scala.

## Requirements
None.

### Role variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|scala_version|String||2.11.8|

### Dependencies
+ [java](https://github.com/shomatan/ansible-java.git)

### Example Playbook

```yaml
- hosts: all
  roles:
    - { role: scala }
  vars:
    scala_version: 2.12.0

```
