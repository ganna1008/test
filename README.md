<header>
<style>

text-color. {

color: blue;

font-size: 16px;

}

</style>

</header>

# React homework template

Этот проект был создан при помощи [Create React App](https://github.com/facebook/create-react-app).
Для знакомства и настройки дополнительных возможностей
[обратись к документации](https://facebook.github.io/create-react-app/docs/getting-started).

## Создание репозитория по шаблону

Используй этот репозиторий организации GoIT как шаблон для создания репозитория своего проекта. Для
этого нажми на кнопку `«Use this template»` и выбери опцию `«Create a new repository»`, как показано
на изображении.

![Creating repo from a template step 1](./assets/template-step-1.png)

На следующем шаге откроется страница создания нового репозитория. Заполни поле его имени, убедись
что репозиторий публичный, после чего нажми кнопку `«Create repository from template»`.

![Creating repo from a template step 2](./assets/template-step-2.png)

После того как репозиторий будет создан, необходимо перейти в настройки созданного репозитория на
вкладку `Settings` > `Actions` > `General` как показано на изображении.

![Settings GitHub Actions permissions step 1](./assets/gh-actions-perm-1.png)

Проскролив страницу до самого конца, в секции `«Workflow permissions»` выбери опцию
`«Read and write permissions»` и поставь галочку в чекбоксе. Это необходимо для автоматизации
процесса деплоя проекта.

![Settings GitHub Actions permissions step 2](./assets/gh-actions-perm-2.png)

Теперь у тебя есть личный репозиторий проекта, со структурой файлов и папок репозитория-шаблона.
Далее работай с ним как с любым другим личным репозиторием, клонируй его себе на компьютер, пиши
код, делай коммиты и отправляй их на GitHub.

## Подготовка к работе

1. Убедись что на компьютере установлена LTS-версия Node.js.
   [Скачай и установи](https://nodejs.org/en/) её если необходимо.
2. Установи базовые зависимости проекта командой `npm install`.
3. Запусти режим разработки, выполнив команду `npm start`.
4. Перейди в браузере по адресу [http://localhost:3000](http://localhost:3000). Эта страница будет
   автоматически перезагружаться после сохранения изменений в файлах проекта.

## Деплой

Продакшн версия проекта будет автоматически проходить линтинг, собираться и деплоиться на GitHub
Pages, в ветку `gh-pages`, каждый раз когда обновляется ветка `main`. Например, после прямого пуша
или принятого пул-реквеста. Для этого необходимо в файле `package.json` отредактировать поле
`homepage`, заменив `your_username` и `your_repo_name` на свои, и отправить изменения на GitHub.

```json
"homepage": "https://your_username.github.io/your_repo_name/"
```

Далее необходимо зайти в настройки GitHub-репозитория (`Settings` > `Pages`) и выставить раздачу
продакшн версии файлов из папки `/root` ветки `gh-pages`, если это небыло сделано автоматически.

![GitHub Pages settings](./assets/repo-settings.png)

### Статус деплоя

Статус деплоя крайнего коммита отображается иконкой возле его идентификатора.

- **Желтый цвет** - выполняется сборка и деплой проекта.
- **Зеленый цвет** - деплой завершился успешно.
- **Красный цвет** - во время линтинга, сборки или деплоя произошла ошибка.

Более детальную информацию о статусе можно посмотреть кликнув по иконке, и в выпадающем окне перейти
по ссылке `Details`.

![Deployment status](./assets/deploy-status.png)

<div>
<img src="https://www.leben-und-erziehen.de/sites/default/files/styles/4x3__900x675/public/promieltern/990154-tom-hardy-neu-q.webp?itok=Te7fDJsG" alt="Girl in a jacket" width="500" height="600">
<p style="color: red;">Figure 1</p>
<p class="text-color">Figure 10000</p>
</div>
