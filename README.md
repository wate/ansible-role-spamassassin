spamassassin
=================

Setup SpamAssassin(WIP)

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `spamassassin_packages`

インストールするパッケージ

### `spamassassin_cfg`

SpamAssassinの設定

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: spamassassin
```

License
--------------

Apache License 2.0
