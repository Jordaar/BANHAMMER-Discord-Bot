**BAN HAMMER DISCORD BOT MADE WITH NODE.JS**
# OUTDATED

This Bot is optimized to run on **Heroku**

# BanHammer

> A simple Discord bot to handle cross-server bans.

## Installation & Usage

```bash
npx banhammer
```

OR

```bash
npm install -g banhammer
```

You would need to create a file named `.env` in the source folder and add this:- `TOKEN=(your bot's token)` || Replace `(your bot's token)` to your bot's token.

Change the values in `allowedUsers` to match the user id's of those who you want to have the command. You may add as many as you wish.

-------------------------------------------------------**HEROKU SETUP**--------------------------------------------------

*note that if you want to deploy the app directly to Herkou just edit the config.js file and deploy the app then go to settings and Click on Reveal Config Vars.


There replace KEY with **`TOKEN`** and VALUE with **`Your Bot's Token`**

Then go to resources(you will need to refresh the tab once) then click on the pencil icon and turn off `web npm start` and turn on worker `node index.js`

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

**ENJOY NOW YOUR BOT IS ON!**
 



