# Создание альясов

Можно задавать свои альясы для команд Git:

```sh
git config alias.c 'config --global'
```

Или целые цепочки команд, используя префикс `!`:

```sh
git config alias.c '! echo "Hello, World!"; echo "Hello, Git!"'
```
