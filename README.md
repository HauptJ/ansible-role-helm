# ansible-role-helm
Ansible role to install and configure Helm and Tiller.

[![Build Status](https://travis-ci.org/HauptJ/ansible-role-helm.svg?branch=master)](https://travis-ci.org/HauptJ/ansible-role-helm)

| Name 						        | Default 					                | Description 	                          |
|-----------------------------------|-------------------------------------------|-----------------------------------------|
| system_user                       | root                                      | the user who will be using Helm         |
| kubernetes_helm_version           | 2.12.1                                    | Helm version to install                 |
| kubernetes_helm_platform          | linux-amd64                               | CPU architecture                        |
| kubernetes_helm_checksum          | sha256:891...                             | Helm binary SHA256 checksum             |
| kubernetes_helm_install_dir       | /usr/bin                                  | Installation directory                  |