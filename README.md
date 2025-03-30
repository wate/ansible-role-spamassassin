spamassassin
=================

Setup SpamAssassin

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `spamassassin_packages`

インストールするパッケージ

#### `spamassassin_cfg`

SpamAssassinの設定

#### `spamassassin_spamd_port`

smapd(SpamAssassin Server)のポート番号

#### `spamassassin_spamd_option`

smapd(SpamAssassin Server)の設定  
-d(--daemonize)オプションは自動で付与されます

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `spamassassin_dependency_packages`

#### `spamassassin_config_dir`

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
