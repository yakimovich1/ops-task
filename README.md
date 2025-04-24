# ops-task
#Тестовое задание Monitoring, Grade 2 (TEST)

#Шаги по запуску проекта

1. git clone https://github.com/yakimovich1/ops-task.git
2. cd ops-task/
3. Внести изменения в файлы из списка ниже, а именно изменить ip адрес 192.168.0.101 на ip адрес ноды на которой будет запущен проект.
   -prometheus/prometheus.yml
   -grafana/provisioning/datasources/datasources.yml
5. docker compose up -d
6. ansible-playbook ./ansible/playbook.yaml
7. В веб браузере открыть адрес 192.168.0.101:80 > Вести данные для автризации user:admin password:admin (Пропустить сообщение о смене пароля) > Перейти в раздел Dashboards > Открыть дашборд с именем "Prometheus 2.0 Overview"
