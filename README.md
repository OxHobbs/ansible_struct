# Phonebook Sample

## Description
This is a sample repository built from open source sample code to demonstrate a basic Ansible project directory structure.  It has two roles and are used by two different playbooks, one custom module and Azure Enabled dynamic inventory.

## Variables

*group_vars/all.yml*

`primary_azure_region` Specifies the Azure region that is primary for the resources in the project.

## ChangeLog

#### v0.3.0
- Refactored azure role into modular format.

#### v0.2.0
- Refactored phonebook role into a more modular format.

#### v0.1.0

- Initial release
