# daixijun.toolkit

[![Build Status](https://github.com/daixijun/ansible-role-toolkit/workflows/build/badge.svg)](https://github.com/daixijun/ansible-role-toolkit/actions)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-daixijun.toolkit-660198.svg?style=flat)](https://galaxy.ansible.com/daixijun/ansible-role-toolkit/)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/daixijun/ansible-role-toolkit?sort=semver)](https://github.com/daixijun/ansible-role-toolkit/tags)

安装常用的工具包，默认安装的[软件包列表](./vars/main.yml)

## 环境要求

- RHEL/CentOS 6 及以上版本
- ansible 2.7 及以上版本

## 变量

```yaml
# 需要额外安装的软件包列表
toolkit_packages: []
```

## 依赖

无

## 使用示例

```yaml
- hosts: servers
  roles:
      - { role: daixijun.toolkit, toolkit_packages: ['vim'] }
```

## License

BSD

## 维护者

- Xijun Dai <daixijun1990@gmail.com>
