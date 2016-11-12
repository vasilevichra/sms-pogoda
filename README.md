# veloweather
Скрипт для получения погоды и солнечной геомагнитной активности в Санкт-Петербурге СМСкой на свой номер телефона.

### Запуск
`./veloweather --api=XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX --phone=79XXXXXXXXX`

### Установка на сервере
1. curl -s "https://get.sdkman.io" | bash
2. source "$HOME/.sdkman/bin/sdkman-init.sh"
3. sdk install groovy
4. wget https://raw.githubusercontent.com/vasilevichra/veloweather/master/veloweather
5. chmod +x veloweather
6. sudo crontab -e
