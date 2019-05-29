GITLAB-RUNNER
=========

Deploy the gitlab server running under the container via ansible.

Dependencies
------------

- [Docker](https://github.com/gengxiankun-galaxy/docker)

Role Variables
--------------

parameter | description
------------ | -------------
OPT_PATH | Service deployment directory
SRV_PATH | 配置目录
GITLAB_EXTERNAL_URL | 
GITLAB_PROJECT_REGISTRATION_TOKEN |
GITLAB_RUNNER_NAME |
GITLAB_RUNNER_DOCKER_IMAGE |

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gengxiankun.gitlab-runner, x: 1 }

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).