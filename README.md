# sails-hook-email-tjennt

### Sails hook email customize host, port mailer
  config in config/email.js
```
  module.exports.email = {
    service: 'Gmail',
    host: 'smpt.gmail.com',
    port: '465',
    auth: {
      user: 'tjennt@gmail.com',
      password: 'APP PASSWORD',
    },
    from: 'tjennt@gmail.com',
    testMode: false
  }
```
+ if you config service then don't need host and port mailer


### THANKS YOU!
### Author : Tjennt