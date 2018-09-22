Ansible Apache with Molecule
============================

Trying testing infrastructure as code with Molecule by setting  up Apache with Ansible.

Requirements
------------

To install required tools, run the following commands:

```
python -m pip install virtualenv
python -m virtualenv <your_preferred_env_name>
source <your_preferred_env_name>/bin/activate
python -m pip install molecule docker
```

How to Test
----------

To run the test, use the following command:

```
molecule test
```

