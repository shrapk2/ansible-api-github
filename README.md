Role Name
=========

This Ansible role interacts with the GitHub API to create and manage objects.

Requirements
------------

* Properly installed and updated Ansible
* GitHub account and personal access token (PAT)

Role Variables
--------------

This Ansible role interacts with the GitHub API to create and manage objects. At this point it can be used to create if one does not exist. Additional capability will be added as needed.

Dependencies
------------

* None at this time

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: localhost
  name: ansible-api-github
  vars:
    github_userAccount: "youusername"
    github_userToken:  "your_pat"
    github_repoName: "repo_to_create"
  roles:
    - ansible-api-github
```

License
-------

MIT

Author Information
------------------

shrapk2
