# veloweather
Скрипт для получения погоды СМСкой на свой номер телефона.

### Запуск
`./veloweather --api=cac9f34c-26de-f754-cdcf-e12814436724 --phone=79001234567`

### Установка на сервере
1. curl -s "https://get.sdkman.io" | bash
2. source "$HOME/.sdkman/bin/sdkman-init.sh"
3. sdk install groovy
4. wget https://raw.githubusercontent.com/vasilevichra/veloweather/master/veloweather
5. chmod +x veloweather
6. sudo crontab -e
