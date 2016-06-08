Docker Install
==============

This role installs and configures Docker with docker compose. It is meant to be used in a production environment on an Ubuntu based server

Requirements
------------

* Python
* Apt
* Docker Hub or private hub server account

Role Variables
--------------

No variables are required for this role to run. There are overrides that may be useful.

### Optional Variables (see ``` defaults/main.yml ``` for defaults)
* docker_user - User to give docker access
* ubuntu_version
* docker_hub_access
* docker_compose_version
* docker_engine_version
* docker_hub_access - set this to yes and set the following values to whatever you need to automatically register the installation to be able to pull down private images.
  * docker_registry_user
  * docker_registry_pass
  * docker_registry_url
  * docker_registry_email


Dependencies
------------



Example Playbook
----------------


License
-------

MIT

Author Information
------------------

Bernie Zang - http://berniezang.com
