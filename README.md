spamassassin
=================

Setup SpamAssassin(work in progress)

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

### `spamassassin_spamd_port`

smapd(SpamAssassin Server)のポート番号

### `spamassassin_spamd_option`

smapd(SpamAssassin Server)の設定  
-d(--daemonize)オプションは自動で付与されます

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
