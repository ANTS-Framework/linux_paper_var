linux paper var
=========

[![Build Status](https://travis-ci.org/ANTS-Framework/linux_paper_var.svg?branch=master)](https://travis-ci.org/ANTS-Framework/linux_paper_var)

Set localisation for printer services

Role Variables
--------------

```yml
    linux_paper_var__locale: de_CH.UTF8
```

Example Playbook
----------------

```yml
    - hosts: clients
      vars:
        - linux_paper_var__locale: en_US.UTF-8
      roles:
        - linux_paper_var 
```

License
-------

GPLv3

Author Information
------------------
Part of the [ANTS Framework](https://ants-framework.github.io/)
