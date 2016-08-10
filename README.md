# fbchatchanger
Changes colors of fb chat

When you message me a color on facebook, now the colors change.

Made w nodejs. S/o to Sashank.

add a config.js file in the directory and make it look like this
```
module.exports = {
    username: "FB EMAIL",
    password: "FB PW"
}
```
Run `npm install`

Running on a droplet w/ <a href = "https://github.com/Unitech/pm2"> pm2</a>.

Run with `pm2 start index.js --restart-delay 1800000` to restart the program every 30 minutes (memory).

OR

Run with `node index.js`
