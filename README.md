# Usage

### Клонирование репозитория
```bash
  git clone https://github.com/MVXIMokda/PublicationsTRPO.git
```

### Меняем директорию
```bash
  cd PublicationsTRPO
```

```bash
  python -m venv venv
```

### Активация .venv
```bash
  .venv\Scripts\activate
```

### Скачиваем библиотеки
```bash
  pip install -r requirements.txt
```

### Инициализируем SQL
```bash
  python manage.py migrate
```

### Запускаем сервер
```bash
  python manage.py runserver
```
