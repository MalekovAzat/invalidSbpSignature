### Описание

Токен веб хука из примера https://enter.tochka.com/doc/v2/redoc/section/Opisanie-metodov#Vebhuki icomingSbpPayment не верифицируется публичным ключем https://enter.tochka.com/doc/v2/redoc/section/static/keys/public.

С токеном токен для хука incomingPayment все ок.

### Как запустить пример

```bash
npm install

# для сгенерированного публичного ключа
node verifyPubKey.js

# для публичного ключа с сайта
node verifyJwk.js
```
