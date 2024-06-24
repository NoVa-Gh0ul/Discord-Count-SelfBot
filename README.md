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


![image](https://cdn.discordapp.com/attachments/1254940419637379146/1254943552342065263/Screenshot_2024-06-24_193726.png?ex=667b54c2&is=667a0342&hm=86d9c4de12e0f13f06691a3d6bb3407e070dfcc8033213f2276d6d1eeac6dddc&)

## Config Info

The other values (interval_speed, status, device_spoof) are optional to mess with

Values for **interval_speed** include: any integer / length of time you want that setInterval supports

Values for **status** include: `online` `idle` `dnd` `invisible`

Values for **device_spoof** include: `pc` `phone`