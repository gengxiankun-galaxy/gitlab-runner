GITLAB-RUNNER
=========

Requirements
------------

CENTOS 7+

Role Variables
--------------

parameter | description
------------ | -------------
SRV_PATH | 配置目录
GITLAB_EXTERNAL_URL | 
GITLAB_PROJECT_REGISTRATION_TOKEN |
GITLAB_RUNNER_NAME |
GITLAB_RUNNER_DOCKER_IMAGE |

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gitlab-runner, x: 1 }

License
-------

BSD
