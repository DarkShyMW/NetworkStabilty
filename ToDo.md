# ToDo: 
  ## [17.04.2025 14:50] Исправить проблему с аутентификацией по SSH.
    - Проблема: Не работает аутентификация. Сыпит ошибки с правами. 
    - Решение: `chmod 700 ~/.ssh` + перезапуск sshd.  
    - Команды: `service sshd restart`.  
