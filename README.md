# toxic-repos

В последнее время участились случаи добавления в популярные Open Source проекты бэкдоров разной степени опасности и полит агиток нацеленных на жителей РФ и россиян по всему миру.
Это может нести угрозу людям, а также подрывает доверие к Open Source комьюнити и Open Source как таковому.

# Статистика
[Опасных репозиториев](./toxic-repos.md): 19

[Репозиторий с пропагандой](./propaganda-repos.md): 93

[DDoS репозиториев](./ddos-repos.md): 16

[Откатившиеся репозитории](./repos-that-changed-their-minds.md): 2

# Рекомендации
- Изоляция сборки в контейнерах, в том числе и для промежуточных сборок на машинах разработчиков.
- Форки всех библиотек (по возможности) и контейнеров к себе.
- Зеркалирование репозиториев пакетов.
- Включение в CI как минимум поиска по ключевым словам, UTF символам с изображением украинского флага и сравнение списка файлов с вайтлистом.
- Ресерч по инструментам анализа кода.