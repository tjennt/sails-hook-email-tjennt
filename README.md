# sails-hook-email-tjennt

Email hook for Sails JS, using Nodemailer

Note: This requires Sails v0.10.6+.

### Installation
npm install sails-hook-email-tjennt

### Config in config/email.js
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