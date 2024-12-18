# Пояснительная записка к проекту "Sibir Hub"

## Цель проекта
Целью проекта является создание многофункционального приложения для управления личной библиотекой.  
Приложение предоставляет пользователю удобный интерфейс для хранения, редактирования и экспорта данных о книгах.

---

## Краткое описание
**Sibir Hub** — это современное приложение, которое позволяет пользователям:  
- Добавлять, редактировать и удалять карточки книг.
- Настраивать профиль (смена имени, пароля).
- Выбирать тему интерфейса.
- Экспортировать и импортировать данные в формате CSV.  

Приложение идеально подходит для студентов, исследователей и любителей книг.

---

## Целевая аудитория
Приложение ориентировано на широкую аудиторию:  
- Студентов.
- Преподавателей.
- Библиофилов.
- Всех, кто ведёт учёт своей библиотеки.

---

## Основной функционал
1. **Авторизация** с безопасным хэшированием паролей.
2. Управление карточками книг:
   - Добавление.
   - Редактирование.
   - Удаление.
3. **Настройка профиля** пользователя:
   - Смена имени.
   - Смена пароля.
4. **Выбор темы интерфейса**:
   - Тёмная.
   - Светлая.
   - Кастомные темы.
5. **Экспорт и импорт данных** в формате CSV.

---

## Используемые технологии
В проекте используются следующие технологии:
- **PyQt6** — создание графического интерфейса.
- **SQLAlchemy** — работа с базой данных.
- **Werkzeug** — безопасное хэширование паролей.
- **Python** — основная логика приложения.

---

## Достижения
- Интуитивно понятный интерфейс для работы с библиотекой.
- Гибкая настройка интерфейса с выбором тем.
- Возможности экспорта/импорта данных.
- Настройка профиля для персонализации.

---

## Планы на будущее
1. Добавление синхронизации между устройствами.
2. Поддержка облачного хранения данных.
3. Расширение аналитики:
   - Статистика по книгам.
   - Отчёты о чтении.
4. Создание мобильной версии для **Android** и **iOS**.

---

## Структура проекта
```plaintext
Sibir_Hub/
├── main.py                # Главный файл запуска
├── widgets/               # Каталог с виджетами
├── models.py              # Модели базы данных
├── css/                   # CSS-файлы тем
├── data/                  # Каталог с базами данных
├── README.md              # Пояснительная записка
└── requirements.txt       # Список зависимостей