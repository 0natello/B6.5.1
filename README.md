# B6.5.1
При запуске playbook user.yaml будет на удаленной системе создаван пользователя user1 и задан ему SSH-ключ.

При запуске ansible-playbook postfix.yaml --tags "init postfix" должен устанавливаться и запускаться с конфигурацией по умолчанию. При запуске ansible-playbook postfix.yaml --tags drop postfix должен удаляться с машины.
