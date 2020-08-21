{
  "name": "Marie-2.0 English",
  "description": "Telegram's sassiest group manager. Modular Telegram group management bot!",
  "keywords": [
    "telegram",
    "best",
    "group",
    "manager",
    "3"
  ],
  "repository": "https://github.com/lazizma/lazizProject",
  "env": {
    "ENV": {
      "description": "Setting this to ANYTHING will enable env variables",
      "value": "ANYTHING"
    },
    "TOKEN": {
      "description": "Your bot token, as a string.",
      "value": ""
    },
    "OWNER_ID": {
      "description": "An integer of consisting of your owner ID",
      "value": "683538773"
    },
    "OWNER_USERNAME": {
      "description": "Your username",
      "value": "ViruZs"
    },
    "WEBHOOK": {
      "description": "Setting this to ANYTHING will enable webhooks when in env mode messages",
      "value": "ANYTHING"
    },
    "URL": {
      "description": "The Heroku App URL similar to https://<appname>.herokuapp.com/",
      "value": ""
    },
    "MESSAGE_DUMP": {
      "description": "optional: a chat where your replied saved messages are stored, to stop people deleting their old",
      "value": "-1007777777777"
    },
    "SUDO_USERS": {
      "description": "A space separated list of user_ids which should be considered sudo users",
      "value": "254318997 683538773 570400686 466337795"
    },
    "SUPPORT_USERS": {
      "description": "A space separated list of user_ids which should be considered support users (can gban/ungban, nothing else)",
      "value": "254318997 683538773 570400686 466337795"
    },
    "WHITELIST_USERS": {
      "description": "A space separated list of user_ids which should be considered whitelisted - they can't be banned.",
      "value": "254318997 683538773 570400686 466337795"
    },
    "DONATION_LINK": {
      "description": "Optional: link where you would like to receive donations.",
      "value": "https://www.paypal.me/Your_id_here"
    },
    "PORT": {
      "description": "Port to use for your webhooks",
      "value": "8443"
    },
    "DEL_CMDS": {
      "description": "Whether to delete commands from users which don't have rights to use that command",
      "value": "True"
    },
    "STRICT_GBAN": {
      "description": "Enforce gbans across new groups as well as old groups. When a gbanned user talks, he will be banned.",
      "value": "True"
    },
    "ALLOW_EXCL": {
      "description": "Whether to allow using exclamation marks ! for commands as well as /.",
      "value": "True"
    },
    "BAN_STICKER": {
      "description": "Which sticker to use when banning people. Use https://telegram.dog/ShowJsonBot to get the file_id",
      "value": "CAADBAAD6AMAAkJ_EQNu_RjOszbmnxYE"
    }
  },
  "addons": [
    {
      "plan": "heroku-postgresql",
      "options": {
        "version": "10"
      }
    }
  ]
}
