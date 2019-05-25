# pi側

# インストール.
$ curl -sSL https://get.docker.com/ | sh

# バージョン確認
$ sudo docker -v

# root ユーザ以外で docker を使用できるように
# docker グループに pi ユーザを追加. 
$ sudo usermod -aG docker pi

# 自動起動設定.
$ sudo systemctl enable docker

$ sudo reboot
