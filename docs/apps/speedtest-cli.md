# Speedtest CLI

Speedtest CLI — Интерфейс командной строки для тестирования пропускной способности интернета с помощью сервиса speedtest.net

## Установка из репозитория

**Speedtest CLI** можно установить любым привычным и удобным способом:

**Установка через терминал**

::: code-group

```shell[apt-get]
su -
apt-get update
apt-get install speedtest-cli
```
```shell[epm]
epm -i speedtest-cli
```
:::

## Использование утилиты Speedtest CLI

Для тестирования пропускной способности интернета введите

```shell
speedtest-cli
```

::: details Пример ответа speedtest-cli
```shell
[oleg@alt-gnome ~]$ speedtest-cli
Retrieving speedtest.net configuration...
/usr/bin/speedtest-cli:960: DeprecationWarning: datetime.datetime.utcnow() is deprecated and scheduled for removal in a future version. Use timezone-aware objects to represent datetimes in UTC: datetime.datetime.now(datetime.UTC).
  self.timestamp = '%sZ' % datetime.datetime.utcnow().isoformat()
Testing from Beeline (xx.xxx.xxx.xxx)...
Retrieving speedtest.net server list...
Selecting best server based on ping...
Hosted by Beeline MSK (Moscow) [0.38 km]: 5.935 ms
Testing download speed................................................................................
Download: 93.80 Mbit/s
Testing upload speed......................................................................................................
Upload: 95.92 Mbit/s

```
:::