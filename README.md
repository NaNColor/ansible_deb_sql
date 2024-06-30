# ansible_deb_sql
Ansible playbook for installing PostgreSQL on Debian 10
## Настрока
Перед запуском необходимо иметь доступ к хосту по ssh с парой публичный\приватный ключ.
Далее необходимо изменить IP адрес, имя пользователя хоста и название приватного ключа для подключения в файле `inventory.ini`.
Затем можно запустить `ansible-playbook`:
```
ansible-playbook playbook.yml
```
