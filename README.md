Mail notificator for [Runnerty]:
Runnerty module: Mail notificator

Configuration sample:
```json
{
  "id": "mail_default",
  "type": "runnerty-notificator-mail",
  "disable": false,
  "from": "Runnerty <my@mail.com>",
  "transport": "smtps://my%40mail.com:mypass@smtp.mail.com/?pool=true",
  "templateDir": "/etc/runnerty/templates",
  "template": "alerts",
  "to": ["to@mail.com"],
  "ejsRender": true
}
```

Plan sample:
```json
{
  "id":"mail_default",
  "subject":"RUNNERTY SAMPLE",
  "message":"Chain :CHAIN_NAME Running!"
}
```


[Runnerty]: http://www.runnerty.io