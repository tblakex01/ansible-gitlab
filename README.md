## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) gitlab

[![Travis CI](http://img.shields.io/travis/debops/ansible-gitlab.svg?style=flat)](http://travis-ci.org/debops/ansible-gitlab) [![test-suite](http://img.shields.io/badge/test--suite-ansible--gitlab-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-gitlab/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.gitlab-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1566)

This role installs [GitLab](https://about.gitlab.com/), an Open Source
GitHub clone.  `debops.gitlab` role will also automatically update
installed GitLab instance if new patches are pushed to the repository.

You can also use this role to upgrade an already installed GitLab instance
to new version when support for it becomes available (new GitLab version is
released on 22nd of each month, usually `debops.gitlab` role is updated
to support new version shortly after that).


### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.gitlab

### Documentation

More information about `debops.gitlab` can be found in the
[official debops.gitlab documentation](http://docs.debops.org/en/latest/ansible/roles/debops.gitlab.html).


### Role dependencies

- `debops.etc_services`
- `debops.redis`
- `debops.nginx`
- `debops.mysql`
- `debops.ruby`
- `debops.secret`
- `debops.postgresql`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`gitlab` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
