Операционные системы и виртуализация (Linux). Обучение в записи

Урок 10. Семинар: Настройка сети в Linux. Работа с IPtables
Задание

• Настроить статическую конфигурацию (без DHCP) в Ubuntu через ip и netplan.
Настроить IP, маршрут по умолчанию и DNS-сервера (1.1.1.1 и 8.8.8.8).
Проверить работоспособность сети.

• Настроить правила iptables для доступности сервисов на TCP-портах 22, 80 и 443.
Также сервер должен иметь возможность устанавливать подключения к серверу обновлений.
Остальные подключения запретить.

• Запретить любой входящий трафик с IP 3.4.5.6.

•* Запросы на порт 8090 перенаправлять на порт 80 (на этом же сервере).

•* Разрешить подключение по SSH только из сети 192.168.0.0/24.