# fbchatchanger
Changes colors of fb chat

When you message me a color on facebook, now the colors change.

Made w nodejs. S/o to Sashank.

# Personal Installation
1. run `git clone https://github.com/imparikh/fbchatchanger`
2. add a `config.js` file in the directory and make it look like this
```
module.exports = {
    username: "FB EMAIL",
    password: "FB PW"
}
```
3. Run `npm install`

4. Run with `pm2 start index.js --restart-delay 1800000` to restart the program every 30 minutes (memory).
