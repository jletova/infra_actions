# infra_actions
Учебный проект для изучения работы GitHub Actions (Яндекс Практикум)

### 1. Создание образа:

```bash
docker build -t infra_action .
```

### 2. Запуск контейнера:

```bash
docker run --name infra_action -it -p 5001:5001 infra_action_cont
```
