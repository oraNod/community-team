# Ansible user journey maps

This document extends Ansible personas by identifying and describing their major steps on user automation journeys.

Ansible community personas: https://hackmd.io/pZb5w5JFRQW3RJ73n23tlw?both#/

```mermaid
mindmap
  root((Ansible automation))
    Novice
      Learn the basics
    User
      Write playbook
        How do I make my automation consistent?
        How do I make things reusable?
        How do I organize my project as my automation grows?
          How do I use roles to structure my project?
        How do I share my automation?
          How do I create a collection?
          How do I allow others to run my playbook?
            Running remotely
              AWX
                REST API
                Web UI
                cron
              How do I plan my deployment?
              How do I manage inventories?
            Running locally
              How do I use an execution environment?
          How do I add to a collection?
      Have something to automate
        SRE process
        Raspberry pi cluster
        Network devices
    Developer
      Creating a Python virtual environment
      Building execution environments
    Community maintainer
      Starting point one
      Starting point two
      Starting point three
    Community member
      Starting point one
      Starting point two
      Starting point three

```

## Novice

```mermaid
journey
    title Novice
    section Learn the basics
      Understand the fundamentals of Ansible automation: 5: Novice
      Install the Ansible package and run a hello world playbook: 5: Novice
    section Explore the Ansible package
      Create a virtual environment: 5: Novice
      Install additional Ansible dev tools: 5: Novice
```

## User

### Beginner tasks

- Installs and/or updates ansible or ansible-core
- Installs or updates individual collections
- Creates and tests playbooks
- Creates inventories
- Tests, publishes, and maintains all of these

### Intermediate tasks

- Creates roles
- Creates job templates (for AWX users)
- Uses event-driven automation (ansible-rulebook - new)
- Contributes to collections (bugfixes, modules etc)
- Tests, publishes, and maintains all of these

### Advanced tasks

- Creates collections (reusable plugins, roles, and playbooks)
- Creates execution environments (collections, libraries, and ansible-core version)
- Tests, publishes, and maintains all of these


## Operations

## Developer

## Community maintainer

## Community member

## Community evangelist