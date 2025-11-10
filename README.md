# Танцевальный Гайд - Искусство запоминания движений

Статический сайт с гайдом по запоминанию танцевальных движений.

## Как выложить на GitHub Pages

### Шаг 1: Создайте репозиторий на GitHub

1. Перейдите на [GitHub.com](https://github.com) и войдите в свой аккаунт
2. Нажмите кнопку **"New"** (или **"+"** → **"New repository"**)
3. Заполните:
   - **Repository name**: например, `dance-guide` или `запоминание-движений`
   - **Description**: описание проекта (опционально)
   - Выберите **Public** (для бесплатного GitHub Pages)
   - **НЕ** ставьте галочки на "Initialize with README" (у нас уже есть файлы)
4. Нажмите **"Create repository"**

### Шаг 2: Подключите локальный репозиторий к GitHub

После создания репозитория GitHub покажет инструкции. Выполните следующие команды:

```bash
# Добавьте все файлы в git
git add .

# Сделайте первый коммит (если еще не сделали)
git commit -m "Initial commit"

# Добавьте удаленный репозиторий (замените YOUR_USERNAME и REPO_NAME на ваши данные)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Отправьте код на GitHub
git branch -M main
git push -u origin main
```

### Шаг 3: Включите GitHub Pages

1. Перейдите в ваш репозиторий на GitHub
2. Откройте **Settings** (вкладка вверху)
3. В левом меню найдите **Pages**
4. В разделе **Source** выберите:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Нажмите **Save**

### Шаг 4: Дождитесь публикации

GitHub Pages обычно публикует сайт за 1-2 минуты. После этого ваш сайт будет доступен по адресу:

```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

Например: `https://sushakkk.github.io/dance-guide/`

## Обновление сайта

После любых изменений в коде:

```bash
git add .
git commit -m "Описание изменений"
git push
```

Изменения появятся на GitHub Pages через 1-2 минуты.

## Структура проекта

- `index.html` - главная страница
- `style.css` - стили
- `config.js` - конфигурация и тексты
- `hero-image.jpg` - изображение для hero-секции

