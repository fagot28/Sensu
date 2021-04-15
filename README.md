# ###########################################
# Конфигурация сервиса мониторинга Sensu Go
Для установки агентов используется ansible-galaxy
из https://github.com/sensu/sensu-go-ansible

Документация:
https://sensu.github.io/sensu-go-ansible/quickstart-sensu-go-6.html

ansible-galaxy collection install sensu.sensu_go

ansible-playbook -i inventory.yaml sensu.yml --ask-become-pass
