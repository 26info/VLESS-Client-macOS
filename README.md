# VLESS Client macOS
GUI клиент для VLESS прокси на macOS

🚀 **Простой и удобный GUI клиент для работы с VLESS прокси на macOS**

[![macOS](https://img.shields.io/badge/macOS-10.13+-blue?logo=apple)](https://www.apple.com/macos/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.4-orange.svg)](https://github.com/26info/VLESS-Client-macOS/releases)
[![Downloads](https://img.shields.io/github/downloads/26info/VLESS-Client-macOS/total.svg)](https://github.com/26info/VLESS-Client-macOS/releases)

## ✨ Особенности

- 🎯 **Простой графический интерфейс** - интуитивно понятное управление
- 🔄 **Автоматическая настройка** - парсинг VLESS-ссылок и создание конфигурации
- 🖥️ **Системная интеграция** - автоматическая настройка прокси для всех сетевых служб
- 🔒 **Поддержка современных протоколов**:
  - VLESS с REALITY/TLS/None
  - TCP, WebSocket, HTTP/2, gRPC транспорт
- 📊 **Мониторинг соединения** - проверка работоспособности и IP-адреса
- ⚡ **Автозапуск и фоновая работа** - постоянный контроль соединения
- 🌐 **Мультиязычная поддержка** - автоматическое определение языка системы (русский/английский)
- 📱 **xBar интеграция** - статус подключения в меню баре macOS (✅ Connected / 🔴 Disconnected)
- 🔄 **Умная проверка обновлений** - автоматическая проверка раз в день без замедления запуска

## 🚀 Быстрый старт

### Скачать готовое приложение

1. Скачайте последнюю версию из [раздела Releases](https://github.com/26info/VLESS-Client-macOS/releases)
2. Перетащите `.app` файл в папку "Программы"
3. Запустите приложение и введите VLESS-ссылку

## 🛠️ Поддерживаемые форматы ссылок

vless://uuid@server:port?security=reality&sni=domain.com&fp=chrome&type=ws&path=/path#ServerName

**Параметры:**
- `security`: none, tls, reality
- `type`: tcp, ws, http, h2, grpc
- `fp`: chrome, firefox, safari, ios, edge
- `sni`, `pbk`, `sid`, `path`, `host`, `flow`

## 📝 Системные требования

- **macOS 10.13** или новее
- **Поддержка архитектур** Intel и Apple Silicon
- **Память**: ~40 MB в работе
- **Диск**: ~60 MB для приложения

### 🔄 Обновляемые VLess прокси (проверенные и бесплатные)

Скачать бесплатный [VLess Proxy List](https://github.com/26info/vless-proxy-list)

⭐ Если этот проект помог вам, поставьте звезду репозиторию!
