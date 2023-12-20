# web-server

## Installation Apache2
![Apache_HTTP_server_logo_(2019-present) svg](https://github.com/Maftukh12/web-server/assets/144332887/e5338cab-9fbe-4286-86bc-6dbceeee0353)
```sh
$ sudo apt update
$ sudo apt install Apache2
$ sudo ufw allow 'Apache Full'
```
## instalation ssh
```sh
$ sudo apt update
$sudo apt install openssh-server
```
## configurate ssh
```sh
$ cd /etc/ssh
$ nano sshd_config
lalu hapus '#' pada port 22 dan permitionlogin yes
```
## instalation PHP
```sh
$ sudo apt update
$ sudo apt install php libapache2-mod-php php-mysql
$ 
```
## configurasi file untuk menampilkan web
```shmasuk ke file /var/www/html
$ cd var/www/html
masukan file atau ubah file index.html
```
## instalaton ngrok
```sh
$ sudo apt install snapd
$ snap install ngrok
$ masukan kode authoken
$ ngrok http 80
```
![image](https://github.com/Maftukh12/web-server/assets/144332887/1ee0ea3d-5944-4422-83aa-b192efde9ec2)




