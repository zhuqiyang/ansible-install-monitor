# Ansible Monitor

## 安装监控组件

### 安装 node_exporter

#### 前置准备

1. 下载 node_exporter 安装包到 `roles/node_exporter/files/` 目录
2. 修改 `inventory/node_exporter` 主机列表

#### 执行安装

```bash
ansible-playbook -v -i inventory/node_exporter playbooks/node_exporter.yml
```