# Angular_Features_2.0

## Фреймворк:

-   Angular 16+
-   Для Angular 16 требует node.js версий минимум 16.x.x или более свежая.

## Управление состоянием:

-   RxJs;
-   NgRx Store;
-   Observebal Data Service;
-   Нативные сервисы Angular;

## Стилизация:

-   SCSS, MaterialUI, БЭМ;
-   SCSS-модули в Angular работают по умолчанию;
-   глобальные стили хранятся в styles.scss;
-   дополнительные стили хранятся в assets/styles;
-   изображения хранятся в assets/image;

## Установка зависимостей

```
npm i
```

## Разработка

-   По-умолчанию все команды запуска фронта запускают dev-сервер, который доступен по адресу http://localhost:4200
-   фронт можно запускать командой:

```
npm start
```

## Возможные дополнительные пакеты для установки

-   установка geojson и типов для них

```
npm i geojson
npm i --saveDev @types/geojson
```

## P.S.

-   Если в терминале пишет следующие : `Powershell - выполнение сценариев отключено в этой системе`

> То выполняем следующие:
>
> -   Открываем терминал `Windows PowerShell` от имени администратора.
> -   Пишем и запускаем: Set-ExecutionPolicy RemoteSigned
> -   На вопрос отвечаем: A (Да для всех)

> (Скрипты, подготовленные на локальном компьютере, можно запускать без ограничений, скрипты, загруженные из интернета - только при наличии цифровой подписи)

-   для форматирования компонентов c помощью `prettier` используйте команду:

```
npx prettier --write .
```

-   При возникновении ошибки : `warning: in the working copy of 'name', LF will be replaced by CRLF the next time Git touches it`
-   Это предупреждение говорит о том, что при работе с файлами в Git будут произведены изменения в символах новой строки.
-   Для Windows:

```
git config --global core.autocrlf true
```

-   Для Unix-подобных систем (Linux, macOS):

```
git config --global core.autocrlf input
```
