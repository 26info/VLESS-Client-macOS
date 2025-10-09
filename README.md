# VLESS Client macOS

<div align="center">

🇷🇺 **GUI клиент для VLESS прокси на macOS**  
🇺🇸 **GUI client for VLESS proxy on macOS**

[![macOS](https://img.shields.io/badge/macOS-10.13+-blue?logo=apple)](https://www.apple.com/macos/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.8-orange.svg)](https://github.com/26info/VLESS-Client-macOS/releases)
[![Downloads](https://img.shields.io/github/downloads/26info/VLESS-Client-macOS/total.svg)](https://github.com/26info/VLESS-Client-macOS/releases)

[Русский](#русский) • [English](#english)

</div>

---

## Русский

🚀 **Простой и удобный GUI клиент для работы с VLESS прокси на macOS**

### ✨ Особенности

- 🎯 **Простой графический интерфейс** - интуитивно понятное управление
- 🔄 **Автоматическая настройка** - парсинг VLESS-ссылок и создание конфигурации
- 🔧 **На базе Xray-core** — использует официальный Xray для максимальной производительности и совместимости
- 🖥️ **Системная интеграция** - автоматическая настройка прокси для всех сетевых служб
- 🔒 **Поддержка современных протоколов**:
  - VLESS с REALITY/TLS/None
  - TCP, WebSocket, HTTP/2, gRPC транспорт
- 📊 **Мониторинг соединения** - проверка работоспособности и IP-адреса
- ⚡ **Автозапуск и фоновая работа** - постоянный контроль соединения
- 🌐 **Мультиязычная поддержка** - автоматическое определение языка системы
- 📱 **xBar интеграция** - статус подключения в меню баре macOS
- 🔄 **Умная проверка обновлений** - автоматическая проверка раз в день

<div align="center">
  
![Интерфейс приложения](https://github.com/user-attachments/assets/3cadd5c5-3960-42da-b9c9-6c0facc5c638)

</div>

### 🚀 Быстрый старт

#### Скачать готовое приложение

1. Скачайте последнюю версию из [раздела Releases](https://github.com/26info/VLESS-Client-macOS/releases)
2. Перетащите `.app` файл в папку "Программы"
3. Запустите приложение и введите VLESS-ссылку

### 🛠️ Поддерживаемые форматы ссылок

vless://uuid@server:port?security=reality&sni=domain.com&fp=chrome&type=ws&path=/path#ServerName


**Параметры:**
- `security`: none, tls, reality
- `type`: tcp, ws, http, h2, grpc
- `fp`: chrome, firefox, safari, ios, edge
- `sni`, `pbk`, `sid`, `path`, `host`, `flow`

### 📝 Системные требования

- **macOS 10.13** или новее
- **Поддержка архитектур**: Intel и Apple Silicon
- **Память**: ~40 MB в работе
- **Диск**: ~60 MB для приложения

### 🔄 Бесплатные прокси

Скачайте бесплатный [VLess Proxy List](https://github.com/26info/vless-proxy-list)

---

## English

🚀 **Simple and user-friendly GUI client for working with VLESS proxy on macOS**

### ✨ Features

- 🎯 **Simple graphical interface** - intuitive control
- 🔄 **Automatic configuration** - parsing VLESS links and creating configuration
- 🔧 **Built on Xray-core** — uses official Xray for maximum performance and compatibility
- 🖥️ **System integration** - automatic proxy setup for all network services
- 🔒 **Modern protocol support**:
  - VLESS with REALITY/TLS/None
  - TCP, WebSocket, HTTP/2, gRPC transport
- 📊 **Connection monitoring** - health checks and IP address verification
- ⚡ **Auto-start and background operation** - continuous connection monitoring
- 🌐 **Multi-language support** - automatic system language detection
- 📱 **xBar integration** - connection status in macOS menu bar
- 🔄 **Smart update checking** - automatic daily checks

<div align="center">
  
![Application Interface](https://github.com/user-attachments/assets/b72bf6eb-0694-4214-a46f-1e9f5e24443d)

</div>

### 🚀 Quick Start

#### Download Ready-made Application

1. Download the latest version from [Releases section](https://github.com/26info/VLESS-Client-macOS/releases)
2. Drag the `.app` file to the "Applications" folder
3. Launch the application and enter the VLESS link

### 🛠️ Supported Link Formats

vless://uuid@server:port?security=reality&sni=domain.com&fp=chrome&type=ws&path=/path#ServerName


**Parameters:**
- `security`: none, tls, reality
- `type`: tcp, ws, http, h2, grpc
- `fp`: chrome, firefox, safari, ios, edge
- `sni`, `pbk`, `sid`, `path`, `host`, `flow`

### 📝 System Requirements

- **macOS 10.13** or newer
- **Architecture support**: Intel and Apple Silicon
- **Memory**: ~40 MB in operation
- **Disk**: ~60 MB for application

### 🔄 Free Proxies

Download free [VLess Proxy List](https://github.com/26info/vless-proxy-list)

---

<div align="center">

⭐ **Если этот проект помог вам, поставьте звезду репозиторию!**  
⭐ **If this project helped you, please star the repository!**

</div>
