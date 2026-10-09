# LimCore для Linux

- [appimage/LimCore-x86_64.AppImage](appimage/LimCore-x86_64.AppImage): любой дистрибутив и Steam Deck (SteamOS). Сделайте файл исполняемым и запустите: откроется установщик.
- [deb/LimCore-x86_64.deb](deb/LimCore-x86_64.deb): Debian, Ubuntu, Linux Mint. `sudo apt install ./LimCore-x86_64.deb`
- [rpm/LimCore-x86_64.rpm](rpm/LimCore-x86_64.rpm): Fedora, openSUSE. `sudo dnf install ./LimCore-x86_64.rpm`
- [decky/LimCore-decky.zip](decky/LimCore-decky.zip): плагин Decky Loader для игрового режима Steam Deck (VPN из меню быстрого доступа). Сначала установите AppImage в режиме рабочего стола, затем в Decky: Настройки → Режим разработчика → Install Plugin from URL: `https://github.com/l-limon-l/LimCore-Linux/raw/main/decky/LimCore-decky.zip`

Нужен glibc 2.35 или новее (Ubuntu 22.04, Debian 12, Fedora 36 и новее). Приложение само проверяет обновления по `update.json`.

Список изменений — в [CHANGELOG.md](CHANGELOG.md).
