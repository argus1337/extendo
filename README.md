# extendo

```sh
wget -qO- https://raw.githubusercontent.com/argus1337/extendo/refs/heads/main/xray-install | bash
```

**Вывести список всех клиентов:**

```sh
userlist
```

**Вывести ссылку и QR-код для подключения основного пользователя:**

```sh
mainuser
```

**Создать нового пользователя:**

```sh
newuser
```

**Удалить пользователя:**

```sh
rmuser
```

**Создать ссылку для подключения:**

```sh
sharelink
```

В домашней папке пользователя будет создан файл `help` — в нём содержатся подсказки с описанием команд. Посмотреть его можно с помощью команды (нужно находиться в домашней папке пользователя):

```sh
cat help
```

## Если вдруг нужно удалить, то воспользуйтесь этими командами:
```sh
bash -c "$(curl -L https://github.com/XTLS/Xray-install/raw/main/install-release.sh)" @ remove
rm /usr/local/etc/xray/config.json
rm /usr/local/etc/xray/.keys
rm /usr/local/bin/userlist
rm /usr/local/bin/mainuser
rm /usr/local/bin/newuser
rm /usr/local/bin/rmuser
rm /usr/local/bin/sharelink
```
