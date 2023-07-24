# Ansible Role: elasticsearch

[![Lint](https://github.com/dcjulian29/ansible-role-elasticsearch/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-elasticsearch/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-elasticsearch.svg)](https://github.com/dcjulian29/ansible-role-elasticsearch/issues)

This an Ansible role to install an Elasticsearch node.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.docker
  src: https://github.com/dcjulian29/ansible-role-docker.git
- name: dcjulian29.elasticsearch
  src: https://github.com/dcjulian29/ansible-role-elasticsearch.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
