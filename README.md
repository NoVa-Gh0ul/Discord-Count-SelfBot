# Discord-Count-SelfBot
Very simple Discord SelfBot that counts for you and maintains a status!

# Author

This was created by `shwp` on [Discord](https://discord.com/users/1014174658179899503)

# Setup

1. Make sure you have `Node.js` installed on your local device (install here: https://nodejs.org/en/download/package-manager)

2. Copy the repository at https://github.com/NoVa-Gh0ul/Discord-Count-SelfBot

3. Open the terminal and run `npm install`

4. Fill in the required values inside `config.json` file:
    - `token` (authentication for the account to be used)
    - `channel_id` (channel the bot should count in)

5. Run `node .`

Enjoy :D
![image](https://cdn.discordapp.com/attachments/1163134604295815320/1254900013293768824/image.png?ex=667b2c36&is=6679dab6&hm=6ec83c43cad1a2e8661436b238585555d7172e73f0d06d350ad949d752dc20f5&)

## Config Info

The other values (interval_speed, status, device_spoof) are optional to mess with

Values for **interval_speed** include:
    - any integer / length of time you want that setInterval supports

Values for **status** include:
    - `online`
    - `dnd`
    - `invisible`
    - `idle`

Values for **device_spoof** include:
    - `pc`
    - `phone`