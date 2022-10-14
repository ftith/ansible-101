# Ansible-101

## What is Ansible? 
Ansible is an automation language using YAML descriptor files.
Main advantages:
- opensource
- gentless (no process ou deamon on target machines and no need for additional installation, nor resource consumption) by using openssh

It can be used for
- Provisionning
- Management Configuration(e.g. package, security)
- Apps deployment

Conclusion: it is an orchestrator tool

## How it works?
Admin writes *playbooks* i.e. yaml files.

These instructions are written as a state description using *modules* (i.e. block of script reusable and independant and to which you can pass parameters)
E.g.: module « file » which let you create files which path or access mode as parameters.

