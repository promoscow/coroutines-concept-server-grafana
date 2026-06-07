### Сервис мониторинга компонента Server.

Для запуска сервиса выполнить:
```text
docker-compose up -d
```

#### Prometheus:
```text
http://localhost:9090/targets
```

**DoD**: endpoint `http://host.docker.internal:8011/actuator/prometheus` имеет статус `UP`. Это значит, что prometheus получает метрики из сервиса.

#### Grafana:
```text
http://localhost:3000/dashboards
```

**DoD**: Графики отображают информацию в реальном времени.