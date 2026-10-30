# ansible1

Haldustegevuste automatiseerimine (ITS24), Roger-Romeo Arm

Ansible kontroller anservroger (Debian 13), kliendid klient1 (Debian 13) ja klient2 (CentOS Stream 10).

- hosts, ansible.cfg: inventory ja seadistus (/root/hosts, /root/.ansible.cfg)
- playbooks/apache2.yml: Lab 2, Apache2 + userdir
- playbooks/index_html.yml: Lab 2 iseseisev ulesanne
- playbooks/php.yml: Lab 3, PHP + info.php
- playbooks/uninst_php.yml: Lab 3, PHP eemaldamine
- playbooks/mysql-server.yml: Lab 4, MySQL server ametlikust APT hoidlast (klient1)
- playbooks/mysql-user.yml: Lab 4 iseseisev ulesanne, root parool ja /root/.my.cnf
- playbooks/wordpress.yml: Lab 5, WordPress, php8.4-mysql ja wp-cli (klient1)
