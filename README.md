# KVM環境構築の自動化ツール
CentOS7.0 のみ対応
今後Ubuntuにも対応させる予定

# 利用方法
`group_vars/all`を書き換えて下さい

```sh
ansible-playbook -i hosts site.yml -u USER --ask-pass -vvv
```
- USER は適時読み替えること
