# После распаковки и запуска бот предложит ввести данные аккаунта

`? Enter session ▮`
При первом запуске просит сессиию, тут просто энтер

`? Enter your number ▮`
Номер телефона, к которому привязан тг аккаунт

`? Enter your otp ▮`
Код, который пришел в тг от telegram

`? Enter your 2FA password ▮`
Пароль от телеги, если он установлен

Помощь по командам бота `?help`

Рядом с файлом бота автоматически будет создан `config.json`, в котором будет сгенерированная сессия
```json
{
  "fastMeditations": 2,
  "farmChests": true,
  "bosses": true,
  "daily": true,
  "riftLvlUp": "coin",
  "skipItems": [
    "🪙 Коробка монет",
    "⭕x2 фейлов",
    "⚫️x1 Черных фрагментов",
    "🗡️ Меч лабиринта"
  ],
  "shops": {
    "coins": {
      "store:21:150:1": 1,
      "store:23:500:150": 5,
      "store:2:5:5000": 0,
      "store:1:25:50": 5
    },
    "pvp": {
      "store:103:100:1": 2,
      "store:108:300:1": 15,
      "store:102:4:99999": 1,
      "store:105:100:1": 1,
      "store:110:2000:1": 1
    },
    "clan": {
      "g_store:511:1:100:35:3": 1,
      "g_store:504:1:100:35:3": 1,
      "g_store:507:2:500:35:3": 1,
      "g_store:505:2:100:35:3": 1,
      "g_store:503:3:1000:35:3": 1,
      "g_store:506:3:400:35:3": 1
    }
  },
  "session": "1AgAOMTQ5LjE1NC4xNjcuNDEBuxjCWH90fU+FOP7vb4dObds6d56Wu9TM6SBpqO7w4ZzngmIhCpj2yarCFYRRKao+XJ4OsStx9w3B2mkLD5sK9aDATqiuC8OaTlpzjZprUwRX8/9PUus9fnbaPctj/MN0B3OrfQ6jz1V71uALcptzay1kW4kP313f3cELxwJMjL9otmpC2D1dXMQhZy8mFftajM87IrEi7Fb6w1XZyQ+lDKLLSnb8DmXWqN/1jIcjJCwNQVaH6zmKS86B827/F9QHvoRhlnJG1P1QvwyDC8ksArlVfHD30wvT8hV9btb21p41UY3KLImMggCEa4SkIbYsCsmjaM4mnLQxKlnvSd/ucZs="
}
```

`fastMeditations` - количество быстрых медитаций, которые будут использованы при выполнении ежедневных заданий
`farmChests` - автоматически открывать сундуки
`bosses` - автоматически бить боссов при появлении
`daily` - автоматически выполнять дейлики после открытия списка заданий
`riftLvlUp` - что прокачивать в разломе (`coin` | `fragment` | `pvp`), не добавлять поле, чтобы прокачивать вручную
