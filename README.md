<div align="center">

# ZCord* - Кастомный клиент Discord, где оригинал заблокирован 🚀

**ZCord*** — это кастомный клиент Discord, который предоставляет доступ к Discord в странах, где он заблокирован. С помощью ZCord* вы можете легко общаться с друзьями, не беспокоясь о блокировках.

<img src="https://github.com/user-attachments/assets/1297467b-6e50-4f44-b3d3-81091fa8f316" width="250"></img>

</div>

---

### Функциональность ✔️:
- [x] Реализован вход
- [x] Возможность обмена сообщениями
- [ ] Звонки

## 📦 Установка

1. Перейдите на страницу [релизов](https://github.com/SublimateTheBerry/ZCord/releases) и скачайте последнюю версию установщика ZCord*.
2. Запустите `zcord Setup x.x.x.exe`, где x.x.x - версия.
3. **Важно:** Убедитесь, что у вас установлен туннель в `C:\Users\Имя_пользователя\AppData\Local\Programs\zcord\resources\teb\tor\torrc` вместо строчки `obfs4 ... ... cert=... iat-mode=0`, слово Bridge нужно оставить. Ваш файл `torrc` должен выглядеть примерно так, поскольку что сайт Tor, что их бот выдает сразу 2 туннеля:
```
ClientTransportPlugin obfs4 exec C:\obfs4proxy
Bridge obfs4 ... ... cert=... iat-mode=0
Bridge obfs4 ... ... cert=... iat-mode=0
UseBridges 1
```
Вы можете получить его его с [официального сайта Tor](https://bridges.torproject.org/bridges?transport=obfs4)(Для этого потребуется VPN) или через [Telegram-бота](https://t.me/GetBridgesBot).

## 📞 Связь со мной

Если у вас есть вопросы или предложения, откройте новый [Issue](https://github.com/SublimateTheBerry/zcord/issues).

---

<*> - ZCord не имеет отношения к Discord Inc.; Не является официальным приложением Discord.
