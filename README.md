# Crypto Gossips

Simple Telegram Bot to send user info about his crypto currency value.

### Usage

```
$ docker run --rm -ti agrrh/crypto-gossips:latest ./daemon --pairs BTC_EUR,ETH_EUR \
    --holdings <URL to JSON file, see repo for details> \
    --tg-token <obtain one from @BotFather> \
    --tg-chat-id <could be obtained from @get_id_bot>
```

### Using exmo.me API

- https://exmo.me/ru/api
- https://api.exmo.com/v1/ticker/
