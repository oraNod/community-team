# Ansible user journey maps

This document extends Ansible personas by identifying and describing their major steps on user automation journeys.

Ansible community personas: https://hackmd.io/pZb5w5JFRQW3RJ73n23tlw?both#/

```mermaid
mindmap
  root((Ansible automation))
    Novice
    ::icon(fa fa-thumbs-up)
      Learn the basics
    User
    ::icon(fa fa-user)
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
    ::icon(fa fa-code)
      Creating a Python virtual environment
      Building execution environments
    Community maintainer
    ::icon(fa fa-users)
      Starting point one
      Starting point two
      Starting point three
    Community member
    ::icon(fa fa-cat)
      Starting point one
      Starting point two
      Starting point three

```

## Novice

- Learn the basics. Understand the fundamentals of Ansible automation in less than 5 minutes.
- Get started. Install the Ansible package and run a hello world playbook.
- Create a virtual environment and install additional Ansible dev tools.

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