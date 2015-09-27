# isucon5 用の事前準備

[ISUCON5 事前準備いろいろメモ](https://gist.github.com/mapk0y/2d57589f0a3a44652a0a)


```shell-session
$ gcloud compute config-ssh
$ cd ansible
$ vi ansible/hosts
$ ansible-playbook -i ./hosts setup_packages.yml
$ ansible-playbook -i ./hosts setup_dotfiles.yml
```
