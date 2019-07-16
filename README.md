# nodejs-sms-nexmo

![code sample](https://img.shields.io/badge/code-sample-yellowgreen.svg?style=flat-square)

> Node.js app that sends SMS text using [Nexmo API](https://www.nexmo.com/)

### Getting started

```sh
# Clone the repository
git clone https://github.com/pankaryp/nodejs-sms-nexmo.git
cd nodejs-sms-nexmo
```

Then create a 'config.js' file with the below inforamtion: 
```javascript
module.exports = {
    APIKEY: 'YOUR_APIKEY',
    APISECRET: 'YOU_APISECRET',
    PHONE_NUMBER: 'YOUR_PHONE_NUMBER'
};
```

```sh
# Install npm dependencies
npm install

# Run app
node index.js

# Go to localhost:3000
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
